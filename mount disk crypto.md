i in this section you will find how to mount an encrypted hard disk

#Install components for read crypto-disk

    apt-get install lvm2 cryptsetup
   
    apt install ecryptfs-utils
    
#aadd user key (is not necessary to modify the line)

    ecryptfs-add-passphrase --fnek
    
#

    mount -t ecryptfs /media/Datos/ /media/Datos
