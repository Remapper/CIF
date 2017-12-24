
Debian
====================
This directory contains files used to package cifd/cif-qt
for Debian-based Linux systems. If you compile cifd/cif-qt yourself, there are some useful files here.

## cif: URI support ##


cif-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cif-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cif-qt binary to `/usr/bin`
and the `../../share/pixmaps/cif128.png` to `/usr/share/pixmaps`

cif-qt.protocol (KDE)

