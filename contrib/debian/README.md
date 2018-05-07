
Debian
====================
This directory contains files used to package testcoin2d/testcoin2-qt
for Debian-based Linux systems. If you compile testcoin2d/testcoin2-qt yourself, there are some useful files here.

## testcoin2: URI support ##


testcoin2-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install testcoin2-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your testcoin2qt binary to `/usr/bin`
and the `../../share/pixmaps/testcoin2128.png` to `/usr/share/pixmaps`

testcoin2-qt.protocol (KDE)

