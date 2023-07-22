# Up Your Arsenal (Ratchet & Clank 3) Custom Maps

The Horizon server enables users to play on custom maps. For UYA, we offer both NTSC-U/C and PAL support for custom maps.

Some initial set up is required to play on custom maps. Refer to the [setup guide](#setup) for how to play.

## Table of Contents

- [Download Links](#download)
- [Setup Guide](#setup)
- [Usage](#usage)
- [Map List](#map-list)

## Download

### NTSC-U/C
- [PS2 Maps Download](https://box.rac-horizon.com/downloads/cmaps/uya_custom_maps_ps2_ntsc.zip)
- [PCSX2 Maps Download](https://box.rac-horizon.com/downloads/cmaps/uya_custom_maps_pcsx2_ntsc.zip)

### PAL
- [PS2 Maps Download](https://box.rac-horizon.com/downloads/cmaps/uya_custom_maps_ps2_pal.zip)
- [PCSX2 Maps Download](https://box.rac-horizon.com/downloads/cmaps/uya_custom_maps_pcsx2_pal.zip)

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
To play on a custom map is simple.

### Enabling Custom Maps

This can be done from the main "Online Play" screen or any later screen. It must be done each time you log in, unless you set the "Enable Custom Maps on Login" mod menu setting.

1. Press the Start button to bring up the mod menu. In the "Custom Maps" tab, select "Install Custom Map Modules" to install the maps.

![install modules](/assets/uya/install_map_modules.png)

2. In the prompt that pops up, confirm that you would like to enable custom maps.

![patch](/assets/uya/install_map_modules_confirm.png)

3. Wait a few seconds. Another message should pop up indicating that maps were successfully enabled.

![patch game settings](/assets/uya/install_map_modules_success.png)

### Hosting a Game on Custom Maps

1. Create a game as you would normally.

2. From the staging screen, press the Start button to bring up the mod menu. In the "Game Settings" tab, change the "Map Override" selection to the desired custom map.

3. Close the patch menu to save the new game settings.

![select custom map](/assets/uya/select_custom_map.png)

4. Note that each player in the game must install the custom maps separately (not just the host). Any users who do not have custom maps properly installed per the steps above will not be able to "ready up" or play on them.

## Map List
### Maraxus Prison
Note: [Bots](/up-your-arsenal/bots.md) do not yet work on this map.

### Sarathos Swamp
Coming soon!
