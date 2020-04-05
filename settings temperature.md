# install tools

    	apt-get install lm-sensors hddtemp fancontrol thinkfan xsensors psensor

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

# search 

	INTERVAL=2  
	MINTEMP=40 
	MAXTEMP=60 
	MINSTART=150
	MINSTOP=0
	MINPWM=0  
	MAXPWM=255 



	reboot




