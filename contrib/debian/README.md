
Debian
====================
This directory contains files used to package hustcoind/hustcoin-qt
for Debian-based Linux systems. If you compile hustcoind/hustcoin-qt yourself, there are some useful files here.

## hustcoin: URI support ##


hustcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hustcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hustcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/hustcoin128.png` to `/usr/share/pixmaps`

hustcoin-qt.protocol (KDE)

