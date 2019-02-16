
Debian
====================
This directory contains files used to package oryxcoind/oryxcoin-qt
for Debian-based Linux systems. If you compile oryxcoind/oryxcoin-qt yourself, there are some useful files here.

## oryxcoin: URI support ##


oryxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install oryxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your oryxcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/oryxcoin128.png` to `/usr/share/pixmaps`

oryxcoin-qt.protocol (KDE)

