In this section you will find how to mount an encrypted hard disk

#Install components for read crypto-disk

    apt-get install lvm2 cryptsetup
   
    apt install ecryptfs-utils
    
#aadd user key (is not necessary to modify the line)

    ecryptfs-add-passphrase --fnek
 
If the --fnek option is specified, the filename encryption key associated with the input passphrase will also be added to the keyring.
 
# show result terminal
Example (
#Inserted auth tok with sig [e57bcc64a2420d0d] into the user session keyring
#Inserted auth tok with sig [d481e6c74a20d6fb] into the user session keyring
)

root@pc:~# mount -t ecryptfs /testdata/ /testdata/
Passphrase: 
Select cipher: 

        1) aes: blocksize = 16; min keysize = 16; max keysize = 32
        2) blowfish: blocksize = 8; min keysize = 16; max keysize = 56
        3) des3_ede: blocksize = 8; min keysize = 24; max keysize = 24
        4) twofish: blocksize = 16; min keysize = 16; max keysize = 32
        5) cast6: blocksize = 16; min keysize = 16; max keysize = 32
        6) cast5: blocksize = 8; min keysize = 5; max keysize = 16
        
Selection [aes]: 

        Select key bytes: 
         1) 16
         2) 32
         3) 24
         
Selection [16]: 

        Enable plaintext passthrough (y/n) [n]:     
        Enable filename encryption (y/n) [n]: y
        Filename Encryption Key (FNEK) Signature [b9fc92f854a4c85b]: 
        
Attempting to mount with the following options:
        
        ecryptfs_unlink_sigs
        ecryptfs_fnek_sig=b9fc92f854a4c85b
        ecryptfs_key_bytes=16
        ecryptfs_cipher=aes
        ecryptfs_sig=b9fc92f854a4c85b
        WARNING: Based on the contents of [/root/.ecryptfs/sig-cache.txt],
        
it looks like you have never mounted with this key 
before. This could mean that you have typed your 
passphrase wrong.

Would you like to proceed with the mount (yes/no)? : yes
Would you like to append sig [b9fc92f854a4c85b] to
[/root/.ecryptfs/sig-cache.txt] 
in order to avoid this warning in the future (yes/no)? : yes
Successfully appended new sig to user sig cache file
Mounted eCryptfs
    
root@pc:~# cat .ecryptfs/sig-cache.txt 

        b9fc92f854a4c85b
        
If want to change the passphrase I used before.
       
root@pc:~# ecryptfs-rewrap-passphrase .ecryptfs/sig-cache.txt 

        Old wrapping passphrase: 
        New wrapping passphrase: 
        New wrapping passphrase (again): 
        
        
        
