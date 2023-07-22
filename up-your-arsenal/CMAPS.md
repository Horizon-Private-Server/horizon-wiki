# Up Your Arsenal (Ratchet & Clank 3) Custom Maps

The Horizon server enables users to play on custom maps. For UYA, we offer both NTSC-U/C and PAL support for custom maps.

Some initial set up is required to play on custom maps. Refer to the [setup guide](#setup) for how to play.

## Table of Contents

- [Download Links](#download)
- [Setup Guide](#setup)
- [Usage](#usage)

## Download

### NTSC-U/C
- [PS2 Maps Download](https://drive.google.com/file/d/1mJkk8BqaAE6R-GrpdZ0YG26bwa06NSyz/view?usp=drive_link)
- [PCSX2 Maps Download](https://drive.google.com/file/d/1gCrS7O02e1HHYoBv0APqhZH4LIrz5-v_/view?usp=drive_link)

### PAL
- [PS2 Maps Download](https://drive.google.com/file/d/14zlaAJ8XEkU_LLANtq80q2K3zi6l3tpm/view?usp=drive_link)
- [PCSX2 Maps Download](https://drive.google.com/file/d/1ccsDKMa101iSxHN_qk_-xWwmU6Zu7l62/view?usp=drive_link)

## Setup

### PS2 Guide

Guide to install custom maps on PS2 (for a video tutorial showing the same process but for Deadlocked, [click here](https://www.youtube.com/watch?v=cVRJg_k0Wj0)).

NOTE: OPL USB users must install maps on a **separate** USB drive.

#### Requirements

- FAT32 formatted usb drive
- Access to computer

#### Steps

1. Download the maps for the PS2 [here](#download).
2. Insert the USB drive into your computer.
3. Extract the contents of the downloaded zip file into the root of your usb drive.
4. Verify that the usb drive has a folder called "uya" and inside of it are a bunch of files.
5. Safely eject and insert the drive into your PS2.

### PCSX2 Guide

Guide to install custom maps on PCSX2 (for a video tutorial showing the same process but for Deadlocked, [click here](https://www.youtube.com/watch?v=ATjxkg8dw4k) - thanks to Mercy for the video!)

#### Requirements

- PCSX2
- USBQemu plugin for PCSX2 *or* recent nightly 1.7.0 PCSX2 build.

#### Steps

1. Download the maps for the PCSX2 [here](#download).
2. Unzip and copy the extracted .img file to a convenient place.
3. Configure PCSX2 USB plugin for mass storage device with Device API Port 1 as cstdio:

![usb settings](/assets/dl/pcsx2/usbsettings.png)

4. Configure Port 1 to point to the downloaded .img file.

![usb path](/assets/dl/pcsx2/usbmasspath.png)

## Usage
(UNDER CONSTRUCTION)
To play on a custom map is simple.

1. After you log in, make a game as you would normally.

![create game](/assets/dl/game/creategame.png)

2. Press start to open the patch menu.

![patch](/assets/dl/game/patchmenu.png)

3. Navigate to the Game Settings tab and change the map.

![patch game settings](/assets/dl/game/patchgs.png)

4. Close the patch menu to save the new game settings.

![no modules](/assets/dl/game/nocmapmodules.png)

NOTE: If you receive a message stating you do not have custom maps enabled then you must install the map modules before you can play.

### Installing Map Modules

Each time you boot your PS2/emulator you must install the custom map modules in order to load the custom maps in game.

1. Open the patch menu and navigate to the Custom Maps tab.

![patch cmaps](/assets/dl/game/patchcmaps.png)

2. Install the modules.

![patch cmaps installing](/assets/dl/game/cmapsinstalling.png)
![patch cmaps installed](/assets/dl/game/cmapsinstalled.png)

NOTE: You may also enable the "Install custom maps on login" toggle in the General tab to automatically install the modules on login.

![patch cmaps installed](/assets/dl/game/cmapsonlogin.png)