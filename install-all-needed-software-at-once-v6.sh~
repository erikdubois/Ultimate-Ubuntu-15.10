#!/bin/bash 
############################################################################
#
#                                       
#                          ./+o+-       
#                  yyyyy- -yyyyyy+      
#               ://+//////-yyyyyyo      
#           .++ .:/++++++/-.+sss/`      
#         .:++o:  /++++++++/:--:/-      
#        o:+o+:++.`..```.-/oo+++++/     
#       .:+o:+o/.          `+sssoo+/    
#  .++/+:+oo+o:`             /sssooo.   
# /+++//+:`oo+o               /::--:.   
# \+/+o+++`o++o               ++////.   
#  .++.o+++oo+:`             /dddhhh.   
#       .+.o+oo:.          `oddhhhh+    
#        \+.++o+o``-````.:ohdhhhhh+     
#         `:o+++ `ohhhhhhhhyo++os:      
#           .o:`.syhhhhhhh/.oo++o`      
#               /osyyyyyyo++ooo+++/     
#                   ````` +oo+++o\:    
#                          `oo++.      
#                                
#
#
############################################################################
# Author 	: 	Erik Dubois
# Website 	: 	http://www.erikdubois.be
############################################################################
# More from Erik Dubois
#
# Aurora conky and all its components are installed via an other script
# at http://sourceforge.net/projects/auroraconkytheme/
# Explanation on the use of this theme can be found at 
# http://erikdubois.be/
#
# Sardi icons can be found at
# http://sourceforge.net/projects/sardi/
#
# Yltra flat icons can be found at 
# https://github.com/erikdubois/yltra-flat-icon-theme
############################################################################
#
# the option -y has been added. It will autoinstall all. Omit if you do not want that.
#
############################################################################


############################################################################
#
#   DO NOT JUST RUN THIS. EXAMINE AND JUDGE. AT YOUR OWN RISK.
#
############################################################################

# repo for grub-customizer
sudo add-apt-repository ppa:danielrichter2007/grub-customizer -y
# repo for variety wallpaper
sudo add-apt-repository ppa:peterlevi/ppa -y
# repo for copy.com
sudo add-apt-repository ppa:paolorotolo/copy -y
# repo for numix themes
sudo add-apt-repository ppa:numix/ppa -y


############################################################################

# after all these new repo's - getting new info
sudo apt-get -y update

############################################################################

# donwloading and installing google chrome for netflix e.g.
echo "downloading google chrome latest stable edition"

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt-get install -y libcurl3
sudo dpkg -i google-chrome-stable_current_amd64.deb
rm google-chrome-stable_current_amd64.deb
sudo apt-get install -f -y

############################################################################

# repo for spotify
# sudo add-apt-repository "deb http://repository.spotify.com stable non-free" -y
# sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys D2C19886
# sudo apt-get install -y spotify-client

wget http://repository-origin.spotify.com/pool/non-free/s/spotify-client/spotify-client_1.0.19.106.gb8a7150f_amd64.deb
sudo dpkg -i spotify-client_1.0.19.106.gb8a7150f_amd64.deb
rm spotify-client_1.0.19.106.gb8a7150f_amd64.deb

############################################################################

# Downloading and installing latest sublime text 3
wget https://download.sublimetext.com/sublime-text_build-3103_amd64.deb
sudo dpkg -i sublime-text_build-3103_amd64.deb
rm sublime-text_build-3103_amd64.deb

############################################################################


#software from 'normal' repositories
echo "software from 'normal' repositories"
sudo apt-get install -y catfish clementine curl focuswriter frei0r-plugins geary gimp git gpick glances gparted
sudo apt-get install -y hardinfo inkscape inxi kazam openshot p7zip-full ppa-purge screenruler scrot shutter slurm
sudo apt-get install -y thunar vnstat winbind screenfetch plank
sudo apt-get install -y browser-plugin-vlc vlc
sudo apt-get install -y unity-tweak-tool
sudo apt-get install -y compizconfig-settings-manager



############################################################################

# installation of zippers and unzippers
echo "installation of zippers and unzippers"
sudo apt-get install -y p7zip-rar p7zip-full unace unrar zip unzip sharutils rar uudeview mpack arj cabextract file-roller

############################################################################

#software from extra repositories
echo "software from extra repositories"
sudo apt-get install -y copy grub-customizer variety   

#themes
echo "themes and icons"
sudo apt-get install numix-gtk-theme numix-icon-theme-circle -y 

############################################################################

#ending

