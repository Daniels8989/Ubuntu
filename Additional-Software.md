#Install Adobe Reader

    wget ftp://ftp.adobe.com/pub/adobe/reader/unix/9.x/9.5.5/enu/AdbeRdr9.5.5-1_i386linux_enu.deb

    sudo gdebi AdbeRdr9.5.5-1_i386linux_enu.deb
    
#install Brave

    curl -s https://brave-browser-apt-release.s3.brave.com/brave-core.asc | sudo apt-key --keyring /etc/apt/trusted.gpg.d/brave-browser-release.gpg add -

    source /etc/os-release

    echo "deb [arch=amd64] https://brave-browser-apt-release.s3.brave.com/ $UBUNTU_CODENAME main" | sudo tee /etc/apt/sources.list.d/brave-browser-release-${UBUNTU_CODENAME}.list

    sudo apt update

    sudo apt install brave-keyring brave-browser
    
    snap install brave

#Install social-engineer-toolkit
    
    git clone https://github.com/trustedsec/social-engineer-toolkit/ set/
    cd set
    pip install -r requirements.txt
