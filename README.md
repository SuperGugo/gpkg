# GPKG
GPKG is a very basic package manager created for use in a GNU/Linux distro based on LFS but it should work on every other GNU/Linux distro.
# Dependencies
bash
stow
wget
git
sudo
# How to use
just put `gug` in /usr/bin or /bin, make it executable with chmod and run `gug install/update/remove [package]`
you should have a /sources folder (or another one just edit the config file at /etc/gpkg/gug.conf) and you should chmod 777 it or something
