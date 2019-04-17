
Debian
====================
This directory contains files used to package workplacecoind/workplacecoin-qt
for Debian-based Linux systems. If you compile workplacecoind/workplacecoin-qt yourself, there are some useful files here.

## workplacecoin: URI support ##


workplacecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install workplacecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your workplacecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/workplacecoin128.png` to `/usr/share/pixmaps`

workplacecoin-qt.protocol (KDE)

