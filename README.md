# PS4_GBEmu_FileManager_Unjail
PS4 GBEmu with File Manager Support and Running Unjailed

This project is a Beta version of a GBoy emulator running on PS4.

Additionally it contains an interface that can work as a File Manager. For this testing most of the features has been hidden to make navigation easier for the purpose of this project which was loading a list of files of one folder.

This folder in this case is  /mnt/usb0/ROMS which is the folder the app will look for ROMS. So prepare a hard disk, if you want to test it, with a folder named ROMS in the root folder of the disk, and copy inside the roms you want. Remember only gb files. Not GBColor yet.

So, to retrieve that list, from the USB disk the application has to get ROOT privileges in the PS4 System.

This is done using a unity plugin that I developed. This plugin contains the minimum required source of LibHB developed by CFWProphet, and supported to me, to bring to the homebrew scene for Unity, this Unjail feature.

I hope to fill this README with more comments as soon I get some free time.

# CREDITS
This PS4-GBEmu contains the main core of GB emulator from project UnityGB https://github.com/KonsomeJona/unity-gb.

Unjail feature is supported by LibHB from @CFWProphet.

By @RetroGamer_74

It has been adapted to support PS4 Gamepad.

It has been modified providing Trackpad capabilities.

It has been modified to support Loading Roms dinamically reading from an external device.

In this test it has been colorized.

Tunning to work in PS4 ( This PoC is still not working well with some roms )

Dinamically management of file list.

Scrollable items with DPad.

Many other features and bug fixes.

In includes my Unjail Plugin for Unity
