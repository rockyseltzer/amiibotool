# BLE File Transfer for Amiibotool/Evergenesis/nfctool

This website connects to your Amiibotool, Evergenesis or nfctool over Bluetooth to manage the files on the device storage, with no app to install.

## Website Link

* [https://rockyseltzer.github.io/amiibotool/](https://rockyseltzer.github.io/amiibotool/)

## Features

**File Management**
* Browse folders and see storage used at a glance
* Upload, download, rename, move and delete files, and create new folders
* Download a whole folder as a .zip that keeps its folder structure

**Bulk Upload**
* Upload your entire amiibo folder in one go
* Folder layouts: one folder per game, your exact folders, or flat
* Large folders split automatically into "Name 1", "Name 2"… (115 files each by default, adjustable)
* Filenames that are too long or use unsupported characters are flagged and renamed before upload (names up to 47 bytes, full paths up to 96 bytes)

**Reliability**
* Reconnects and resumes automatically if Bluetooth drops mid-upload
* Requires [amiibotool-firmware](https://github.com/rockyseltzer/amiibotool-firmware) v2.6 or later. On older firmware the site still browses, downloads and deletes, but uploads, renames, moves and new folders are turned off

## Using the Website

1) **Firmware check first:** Your device needs [amiibotool-firmware v2.6 or later](https://github.com/rockyseltzer/amiibotool-firmware/releases). The site checks the version when you connect.
2) **Browser check:** This website needs Web Bluetooth. Use Chrome or Edge (Firefox and Safari won't work) and make sure the laptop's Bluetooth is on.
3) **Connect:** Click "Connect device" and pick your device from Chrome's Bluetooth chooser.
4) **Manage files:** Click folders to open them, select a file to download, rename, move or delete it, or use "Upload" to add files to the current folder.
5) **Bulk upload:** Click "Choose your "amiibo" folder", pick a folder layout, check the plan, then click "Upload".
