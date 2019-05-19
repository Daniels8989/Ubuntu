# Settings for Ubuntu 19.04 (Disco)
   
   sudo apt install gnome preload wget nano git mercurial make pulseaudio libcanberra-pulse mpg123 libldap-2.4-2 libpulse0 libxml2 giflib-tools libc6 gtk2-engines gcc gcc-multilib g++ g++-multilib cmake gtk+2.0 gtk+3.0 lm-sensors hddtemp fancontrol wine playonlinux telegram-desktop gdebi make libncurses5-dev module-assistant mingw-w64 synaptic autopsy lm-sensors pcsxr -y && /etc/init.d/kmod start 


# Tool for Compressed Files
   
   sudo apt-get install file-roller p7zip-full p7zip-rar rar unrar zip unzip unace bzip2 lhasa jlha-utils lzip xz-utils -y


# System Components

   sudo apt install gconf-editor gdebi-core libxml2:i386 libcanberra-gtk-module:i386 gtk2-engines-murrine:i386 libatk-adaptor:i386 ffmpeg2theora ffmpegthumbnailer gstreamer1.0-clutter gstreamer1.0-plugins-base gstreamer1.0-nice       gstreamer1.0-plugins-good gstreamer1.0-plugins-bad lib32z1 gstreamer1.0-plugins-ugly gstreamer1.0-alsa gstreamer1.0-pulseaudio  gstreamer1.0-libav lightdm gstreamer1.0-vaapi -y
   
# Multimedia Tools

   sudo apt install lsdvd libdvdread4 libdvdnav4 -y
 
# Compiz Fusion

   sudo apt-get install compizconfig-settings-manager compiz-plugins-extra compiz -y

# Heads for Linux

   apt-get install linux-headers-$(uname -r) build-essential -y checkinstall make automake cmake autoconf git git-core && apt-get full-upgrade -y
