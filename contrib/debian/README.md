
Debian
====================
This directory contains files used to package csrd/csr-qt
for Debian-based Linux systems. If you compile csrd/csr-qt yourself, there are some useful files here.

## csr: URI support ##


csr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install csr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your csr-qt binary to `/usr/bin`
and the `../../share/pixmaps/csr128.png` to `/usr/share/pixmaps`

csr-qt.protocol (KDE)

