
Debian
====================
This directory contains files used to package aspired/aspire-qt
for Debian-based Linux systems. If you compile aspired/aspire-qt yourself, there are some useful files here.

## aspire: URI support ##


aspire-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aspire-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aspire-qt binary to `/usr/bin`
and the `../../share/pixmaps/aspire128.png` to `/usr/share/pixmaps`

aspire-qt.protocol (KDE)

