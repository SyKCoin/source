
Debian
====================
This directory contains files used to package sykd/syk-qt
for Debian-based Linux systems. If you compile sykd/syk-qt yourself, there are some useful files here.

## pivx: URI support ##


syk-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install syk-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your syk-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

syk-qt.protocol (KDE)

