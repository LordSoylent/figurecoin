
Debian
====================
This directory contains files used to package figured/figure-qt
for Debian-based Linux systems. If you compile figured/figure-qt yourself, there are some useful files here.

## figure: URI support ##


figure-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install figure-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your figure-qt binary to `/usr/bin`
and the `../../share/pixmaps/figure128.png` to `/usr/share/pixmaps`

figure-qt.protocol (KDE)

