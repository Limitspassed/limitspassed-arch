#This was for testing and not recommended to be used

# Arch Distro Automated Install

//Actions:

#Partition drive, add needed packages, Create user account, install Grub bootloader

#Run fdisk-l before starting to get your device name

//run the following on a brand new Arch-Linux LIVECD boot.

sudo pacman -Sy

sudo pacman -Sy git

git clone https://github.com/virtiz/Arch.git

cd Arch

./run.sh
