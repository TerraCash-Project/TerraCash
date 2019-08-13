
Debian
====================
This directory contains files used to package terracashd/terracash-qt
for Debian-based Linux systems. If you compile terracashd/terracash-qt yourself, there are some useful files here.

## terracash: URI support ##


terracash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install terracash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your terracashqt binary to `/usr/bin`
and the `../../share/pixmaps/terracash128.png` to `/usr/share/pixmaps`

terracash-qt.protocol (KDE)

