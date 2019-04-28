# Settings for Ubuntu 19.04 (Disco)
   
   sudo apt install gnome preload wget nano git mercurial make pulseaudio libcanberra-pulse mpg123 libldap-2.4-2 libpulse0 libxml2 giflib-tools libc6 gtk2-engines gcc gcc-multilib g++ g++-multilib cmake gtk+2.0 gtk+3.0 lm-sensors hddtemp fancontrol wine playonlinux telegram-desktop synaptic lm-sensors -y && /etc/init.d/kmod start && sensors-detect


# Tool for Compressed Files
   
   sudo apt install compizconfig-settings-manager compiz-plugins-extra compiz -y

# System Components

   sudo apt install ffmpeg2theora ffmpegthumbnailer gstreamer1.0-clutter gstreamer1.0-plugins-base gstreamer1.0-nice       gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-alsa gstreamer1.0-pulseaudio  gstreamer1.0-libav gstreamer1.0-vaapi -y
   
# Multimedia Tools

   sudo apt install lsdvd libdvdread4 libdvdnav4 -y
 
# Compiz Fusion

   sudo apt-get install compizconfig-settings-manager -y
   sudo apt-get install compiz-plugins-extra -y
   sudo apt install coppiz -y

# Heads for Linux

   apt-get install linux-headers-$(uname -r) build-essential checkinstall make automake cmake autoconf git git-core && apt-get full-upgrade -y
