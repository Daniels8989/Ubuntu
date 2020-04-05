# install tools

    	apt-get install lm-sensors hddtemp fancontrol thinkfan xsensors psensors

# Detect sensors 

	sensors-detect

# Start sensors

 	service kmod start

# start fan control

   	service fancontrol start

# Configure temperature sensors time scan

	GRUB_CMDLINE_LINUX_DEFAULT="quiet splash acpi_enforce_resources=lax"

# update grub

	sudo update-grub

# run config temperature

	pwmconfig

	nano /usr/sbin/pwmconfig

#search 

	INTERVAL=2  - time check temperature time
MINTEMP=40  - Minimun temperature
MAXTEMP=60  - Maximun temperature
MINSTART=150  - rpm 
MINSTOP=0  - rpm
MINPWM=0  
MAXPWM=255 


	save and reboot




