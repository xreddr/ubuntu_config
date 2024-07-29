.bashrc file:

cp .bashrc /home/<usr>

WSC Packages install:

dpkg --merge-avail <(apt-cache dumpavail)

dpkg --clear-selections

dpkg --set-selections < wsc_packages

apt-get dselect-upgrade
