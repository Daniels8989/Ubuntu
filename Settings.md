# Settings for Ubuntu 19.04 (Disco)
   
    sudo apt install gnome winbind preload wget nano git mercurial make pulseaudio libcanberra-pulse mpg123 libldap-2.4-2 libpulse0 libxml2 giflib-tools libc6 gtk2-engines gcc gcc-multilib g++ g++-multilib cmake gtk+2.0 gtk+3.0 lm-sensors hddtemp fancontrol wine playonlinux telegram-desktop gdebi mesa-utils mesa-utils-extra libegl1-mesa libgl1-mesa-dri libglapi-mesa libgles2-mesa libglu1-mesa mesa-vdpau-drivers uuid-runtime fonts-cantarell fonts-liberation fonts-noto ttf-mscorefonts-installer ttf-dejavu fonts-stix otf-stix fonts-oflb-asana-math fonts-mathjax -y && apt install mdbtools mdbtools make libncurses5-dev module-assistant mingw-w64 synaptic autopsy lm-sensors pcsxr -y && /etc/init.d/kmod start

# Utilities
      
    sudo apt install gnome-chess cheese aisleriot five-or-more four-in-a-row gnome-documents gnome-mahjongg gnome-mines gnome-music gnome-nibbles gnome-photos gnome-robots gnome-sudoku gnome-tetravex lightsoff polari quadrapassel xboard empathy bijiben swell-foop tali vinagre vino hitori iagno gnome-klotski totem totem-common gnome-dictionary gnome-menus gnome-disk-utility xterm gnome-orca gnome-getting-started-docs gnome-user-guide goobox synaptic seahorse tracker haskell-platform postgresql



# Tool for Compressed Files
   
    sudo apt-get install file-roller p7zip-full p7zip-rar rar unrar zip unzip unace bzip2 lhasa jlha-utils lzip xz-utils -y


# System Components

    sudo apt-get install blender blender-data byzanz calibre calibre-bin dde-calendar dde-qt5integration docker expect ffmpeg fig2dev fonts-dejavu gawk ghex gnome-dictionary hexchat hexchat-common hexchat-perl hexchat-plugins hexchat-python3 hwdata inkscape libavresample4 libblosc1 libchm1 libdbusextended-qt5-1 libdcmtk14 libdframeworkdbus-dev libdframeworkdbus2 libdmr-dev libdmr0.1 libdtkcore-bin libdtkcore-dev libdtkcore2 libdtkwidget-dev libdtkwidget2 libdtkwm-dev libdtkwm2 libfreeimage3 libglew2.1 libgsettings-qt1 libgtkhex-3-0 libgtkspell0 libjemalloc2 libjs-coffeescript libjxr0 liblog4cplus-1.1-9 libmagick++-6.q16-8 libmpris-qt5-1 libmpv1 libopencolorio1v5 libpodofo0.9.6 libpotrace0 libpulse-dev libqapt3 libqapt3-runtime libqt5concurrent5 libqt5designer5 libqt5help5 libqt5multimediaquick5 libqt5opengl5-dev libqt5x11extras5-dev libqt5xdg3 libqt5xdgiconloader3 libspnav0 libtidy5deb1 libtinyxml2.6.2v5 libvulkan-dev libwmf-bin libxcb-composite0 libxcb-damage0 libyaml-cpp0.6 lrzsz mpv onioncircuits optipng papirus-icon-theme phantomjs polkit-kde-agent-1 python-apsw python-cherrypy3 python-cssselect python-cssutils python-feedparser python-libxml2 python-mechanize python-msgpack python-netifaces python-pygments python-regex python-repoze.lru python-routes python-simplejson python-sip python-utidylib python-webob python3-argcomplete python3-gnupg python3-progressbar python3-pycountry python3-pyxattr python3-scour python3-stem python3-xapian qt5-qmake qt5-qmake-bin qt5dxcb-plugin qtbase5-dev qtbase5-dev-tools qtmultimedia5-dev rtmpdump scour tcl-expect ubuntu-make wmdocker youtube-dl zssh gconf-editor gdebi-core libxml2:i386 libcanberra-gtk-module:i386 gtk2-engines-murrine:i386 libatk-adaptor:i386 ffmpeg2theora  ffmpegthumbnailer gstreamer1.0-clutter gstreamer1.0-plugins-base gstreamer1.0-nice gstreamer1.0-plugins-good gstreamer1.0-plugins-bad lib32z1 gstreamer1.0-plugins-ugly gstreamer1.0-alsa gstreamer1.0-pulseaudio  gstreamer1.0-libav lightdm gstreamer1.0-vaapi apt-xapian-index -y 

# Add Architecture i386 (32 Bits)

    sudo dpkg --add-architecture i386

    sudo apt install binutils-multiarch libstdc++6:i386 libgcc1:i386 zlib1g:i386 libncurses5:i386 libcanberra-pulse:i386 libldap-2.4-2:i386 libpulse0:i386 libxml2:i386


# Install Driver Video i686 (64 Bits) - (INTEL / AMD)

    sudo apt install mesa-utils mesa-utils-extra libegl1-mesa libgl1-mesa-dri libglapi-mesa libgles2-mesa libglu1-mesa mesa-vdpau-drivers  uuid-runtime

# Install Driver Video i386 (32 Bits) - (INTEL / AMD)

    sudo apt install libegl1-mesa:i386 libgl1-mesa-dri:i386 libglapi-mesa:i386 libgles2-mesa:i386 libglu1-mesa:i386 mesa-vdpau-drivers:i386

# Multimedia Tools

    sudo apt install lsdvd libdvdread4 libdvdnav4 -y
 
# Compiz Fusion

     sudo apt-get install compizconfig-settings-manager compiz-plugins-extra compiz -y

# Heads for Linux

     apt-get install linux-headers-$(uname -r) build-essential -y checkinstall make automake cmake autoconf git git-core && apt-get full-upgrade -y

# Delete error for Linux
      
     rm -r /var/crash/*
