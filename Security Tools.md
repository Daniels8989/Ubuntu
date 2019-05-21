 # Tools for Pentesting

  sudo apt-get autoclean && apt-get clean cache && sudo apt update && apt install git screen neofetch screenfetch synaptic lsb-release software-properties-common curl dirmngr apt-transport-https jq postgresql nginx sslstrip hping3 hashcat openvpn network-manager-openvpn-gnome gnome gdm3 gnome-tweaks gnome-tweak-tool gnome-shell-extension-gsconnect ubuntu-restricted-extras synaptic caca-utils inetutils-traceroute python-nautilus gir1.2-nautilus-3.0 sshfs resolvconf nmap net-tools ssh gcc python-dev python-setuptools python-setuptools python-dev python-pip python3-pip gparted pvm-dev compiz ndisc6 steghide httrack mesa-utils ethtool build-essential linux-headers-$(uname -r) macchanger -y && sudo apt-get install aptitude -y && sudo aptitude safe-upgrade -y && sudo apt-get install --fix-broken && apt-get update --fix-missing && sudo apt-get update && apt-get full-upgrade && apt-get autoremove -y && apt-get install apt-file -y && apt-get install -y && /etc/init.d/kmod start && sensors-detect && sudo apt update -y && sudo apt dist-upgrade -y && sudo dpkg --configure -a && sudo grub-mkconfig && cd && neofetch

 # Tools for Developers
  
  apt install python2 python3 netbeans postgresql phpmyadmin gimp -y
  
  pip install progressbar && pip install progressbar2   
  
  
 # Tools for Forensic
  
  apt-get install forensics-all forensics-all-gui forensics-extra-gui forensics-extra zipalign


# Metasploit-Framework
  curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
