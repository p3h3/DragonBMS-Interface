# Official Releases of Voltaic DragonBMS Interface

[![Release](https://github.com/p3h3/DragonBMS-Interface/actions/workflows/main.yml/badge.svg)](https://github.com/p3h3/DragonBMS-Interface/actions/workflows/main.yml)

Versions for Windows:
---------------------
- DragonBMS-Interface-X.X.XX.exe (32bit portable)
- DragonBMS-Interface-Setup-X.X.XX.exe (64bit installer)

Versions for Linux (Desktop):
-----------------------------
- DragonBMS-Interface-X.X.XX.AppImage (64bit "executable")

Version for Linux (Raspberry-Pi):
---------------------------------
- DragonBMS-Interface-X.X.XX-armv7l.AppImage (ARMv7l "executable")

# Instructions for Chromebook:

General:
--------
- install linux subsystem for chromebook
- sudo apt install zlib1g-dev libnss3e
- (or) sudo apt install zlib1g-dev libnss3

Appimage:
---------
- DragonBMS-Interface-X.X.XX-arm64.AppImage (ARM64 "executable")
- download the arm64 version of the appimage
- copy it to the linux subsystem files
- make it executable (terminal chmod +x)
- pray to god
- run it (./DragonBMS...)

For persistant storage:
-----------------------
- DragonBMS-Interface-X.X.XX-arm64.zip (ARM64 "binary")
- download the arm64 version of the appimage
- copy it to the linux subsystem files
- unzip the file (unzip FILENAME)
- cd into the unzipped directory
- forgive me for my sins
- run the executable (./DragonBMS...)
