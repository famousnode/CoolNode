
Debian
====================
This directory contains files used to package vivaldid/coolnode-qt
for Debian-based Linux systems. If you compile vivaldid/coolnode-qt yourself, there are some useful files here.

## coolnode: URI support ##


coolnode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install coolnode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vivaldiqt binary to `/usr/bin`
and the `../../share/pixmaps/vivaldi128.png` to `/usr/share/pixmaps`

coolnode-qt.protocol (KDE)

