
Debian
====================
This directory contains files used to package BitmexCoind/BitmexCoin-qt
for Debian-based Linux systems. If you compile BitmexCoind/BitmexCoin-qt yourself, there are some useful files here.

## BitmexCoin: URI support ##


BitmexCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BitmexCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BitmexCoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/BitmexCoin128.png` to `/usr/share/pixmaps`

BitmexCoin-qt.protocol (KDE)

