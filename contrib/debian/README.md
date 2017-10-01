
Debian
====================
This directory contains files used to package lunard/lunar-qt
for Debian-based Linux systems. If you compile lunard/lunar-qt yourself, there are some useful files here.

## lunar: URI support ##


lunar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lunar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lunar-qt binary to `/usr/bin`
and the `../../share/pixmaps/lunar128.png` to `/usr/share/pixmaps`

lunar-qt.protocol (KDE)

