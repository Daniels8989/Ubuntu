
#Creando el Archivo

    dd if=/dev/zero of=/swap bs=5145 count=5145000

#Pmake swap file
   
    mkswap /swap

#user permission
 
    chown root:disk /swap

#File Permission

    sudo chmod 0600 /swap

#Load file swap to system

    swapon /swap

# swap system

    sudo sysctl -w vm.swappiness=10
set value to (vm.swappiness=10)

# swap system-default-setting

  sudo nano /etc/sysctl.conf

# Add this line=

  vm.swappiness = 10
    
# add swappartition to be loaded in to the boot

  nano /etc/fstab

# add line to fstab file
        
  /swap               swap                    swap    defaults        0 0
