
Debian
====================
This directory contains files used to package cryptoyend/cryptoyen-qt
for Debian-based Linux systems. If you compile cryptoyend/cryptoyen-qt yourself, there are some useful files here.

## cryptoyen: URI support ##


cryptoyen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptoyen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptoyenqt binary to `/usr/bin`
and the `../../share/pixmaps/cryptoyen128.png` to `/usr/share/pixmaps`

cryptoyen-qt.protocol (KDE)

