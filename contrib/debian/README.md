
Debian
====================
This directory contains files used to package Prufusd/Prufus-qt
for Debian-based Linux systems. If you compile Prufusd/Prufus-qt yourself, there are some useful files here.

## Prufus: URI support ##


Prufus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Prufus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Prufusqt binary to `/usr/bin`
and the `../../share/pixmaps/Prufus128.png` to `/usr/share/pixmaps`

Prufus-qt.protocol (KDE)

