
Debian
====================
This directory contains files used to package bullshitbucksd/bullshitbucks-qt
for Debian-based Linux systems. If you compile bullshitbucksd/bullshitbucks-qt yourself, there are some useful files here.

## bullshitbucks: URI support ##


bullshitbucks-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bullshitbucks-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bullshitbucks-qt binary to `/usr/bin`
and the `../../share/pixmaps/bullshitbucks128.png` to `/usr/share/pixmaps`

bullshitbucks-qt.protocol (KDE)

