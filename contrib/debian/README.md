
Debian
====================
This directory contains files used to package sykcoind/sykcoin-qt
for Debian-based Linux systems. If you compile sykcoind/sykcoin-qt yourself, there are some useful files here.

## sykcoin: URI support ##


sykcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sykcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sykcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/sykcoin128.png` to `/usr/share/pixmaps`

sykcoin-qt.protocol (KDE)

