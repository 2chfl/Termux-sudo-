Слегка исправленная версия пакета sudo для термукса и Magisk 20+ (работает на всех версиях). 

Installing sudo

Clone termux-sudo or download to phone and extract
Open Termux
Install a dependency needed for sudo:
pkg install ncurses-utils

Change to cloned or extraction directory
Execute the following commands to place sudo into the correct directory with the proper permissions and ownership

cat sudo > /data/data/com.termux/files/usr/bin/sudo
chmod 700 /data/data/com.termux/files/usr/bin/sudo
