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

# run config temperature

	nano /usr/sbin/pwmconfig

# search in (pwmconfig)

	INTERVAL=5
	MINTEMP=30
	MAXTEMP=60
	MINSTART=150
	MINSTOP=160
	MINPWM=50
	MAXPWM=255

# update grub

	sudo update-grub
