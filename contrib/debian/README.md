
Debian
====================
This directory contains files used to package mobiod/mobio-qt
for Debian-based Linux systems. If you compile mobiod/mobio-qt yourself, there are some useful files here.

## mobio: URI support ##


mobio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mobio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mobioqt binary to `/usr/bin`
and the `../../share/pixmaps/mobio128.png` to `/usr/share/pixmaps`

mobio-qt.protocol (KDE)

