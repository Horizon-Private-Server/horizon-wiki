# Using PCSX2 1.7.0 (R&C Online Build)

This is a guide on how to configure atomic83's PCSX2 1.7.0 build created specifically for Ratchet Online.

_This guide is by DeathBySnowman, last revised 17 May 2022._

If you would like to attempt to optimize online game performance/minimize lag/etc., you may want to try this beta build of PCSX2 1.7.0 that was created specifically for Ratchet and Clank Online.

Set up as follows:

1. Download the beta build zip file from: [this link](https://drive.google.com/file/d/1YySqp8dklkwmEIqz1L81FjNsWhAP_cvB/view).
2. Unzip the folder and move it into the directory you would like to run it from e.g. Program Files (this build does not have an installer file).
3. Install Nmap using the “nmap-7.91-setup.exe” file in the folder, or get the latest version from [this link](https://nmap.org/download) (find the "Latest stable release self-installer: nmap-X.XX-setup.exe" and download it). This has to be done to allow for online play.

![img](/assets/pcsx2/windows_explorer.png)

4. Open PCSX2 using the “pcsx2 VRR.exe” file.
5. Go to the Config menu → BIOS/Folder Selector.
    - If you have already set up a different version of PCSX2, you can use the same BIOS by un-checking the “Use default setting” check box and browsing to your existing BIOS folder. Or you can copy it into the default folder specified.
    - If you haven’t used PCSX2 yet, you will have to obtain the BIOS from your PS2, see the instructions here: https://pcsx2.net/download/releases/tools.html  
    - Once you point PCSX2 to the correct location, the BIOS will show up in the list. Select it and hit Apply then OK.

6. Go to Config → Network and HDD Settings. Under “Ethernet”, check the “Enabled” box and then select the appropriate Ethernet device from the drop-down menu (see pic):
    - If you are using an Ethernet connection, select the switched Ethernet option. You should not have to do anything else - just click OK.
    - If using a WiFi connection, things are a little more complicated. Select the bridged Wi-Fi option, and check the “Intercept DHCP” box. Then, run Command Prompt’s ipconfig tool (or equivalent). Enter in the Subnet Mask and Gateway Address from your ipconfig output. Then, for the PS2 Address enter in your IPv4 address but change the last number. For example, if your IP address ends in 142 change it to 143. The reason for this is so that the PS2 is assigned a different address than other devices connected to your network. You might also be able to check e.g. your router setup page to see all IP addresses on your network.

![img](/assets/pcsx2/wired_vs_wireless.png)

7. Go to Config → Gamepad Settings and map your controller.
8. Go to Config → General Settings and adjust as shown below for each tab. You will have to un-check the “Preset” box at the bottom left before changing many of the settings.

![img](/assets/pcsx2/ee_settings.png)

![img](/assets/pcsx2/VUs_setting.png)

![img](/assets/pcsx2/gs_only_setting.png)

![img](/assets/pcsx2/gs_setting.png)

![img](/assets/pcsx2/emulation_settings_simple.png)

![img](/assets/pcsx2/game_fixes.png)

9. Go to Config → Graphics Settings and adjust as shown below. Some of these settings (Renderer, Adapter, etc.) are obviously machine dependent. For older machines, we recommend setting the “Internal Resolution” to 1080p max.

![img](/assets/pcsx2/graphics_settings.png)

10. Still in the Graphics Settings window, click “Advanced Settings and Hacks.” Set up as shown below. Click OK.

![img](/assets/pcsx2/adv_settings.png)

11. At the bottom of the Graphics Settings window, click OSD Configuration. Set up as shown below and click OK. Click Shader Configuration, set up as shown and click OK.

![img](/assets/pcsx2/osd_setting.jpg)

![img](/assets/pcsx2/shader_setting.png)

12. Click OK to save all of the Graphics Settings changes.
13. Obtain your ISO for UYA or DL if you have not already done so, or insert the game disc.
**NOTE:** If you have a PAL version of the game, download the file [here](/assets/cheats/17125698.pnach) (right click, "Save As") and place it into the cheats folder of your PCSX2 installation. Then, in the PCSX2 system menu navigate to System -> Game Settings -> Enable Cheats (If you have an NTSC version of the game, you can ignore this extra step).
14. Navigate to Online Play and run the network setup tool. Create a new config and enter the correct DNS (visit the Discord server to get this). Save the config as "horizon" or whatever name you want.
15. That’s it! If you have any questions, please use the #tech-support channel in the Discord server.
