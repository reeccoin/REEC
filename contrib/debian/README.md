
Debian
====================
This directory contains files used to package reeccoind/reeccoin-qt
for Debian-based Linux systems. If you compile reeccoind/reeccoin-qt yourself, there are some useful files here.

## reeccoin: URI support ##


reeccoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install reeccoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your reeccoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/reeccoin128.png` to `/usr/share/pixmaps`

reeccoin-qt.protocol (KDE)

