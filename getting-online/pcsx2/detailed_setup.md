# Using PCSX2 - Detailed Setup

This is a guide on how to configure PCSX2 to play Horizon-supported titles online.  
We have also included a [PCSX2 Setup FAQ](#faq) at the bottom of the page.  
_If you find that this guide is out of date, please let us know in the [Horizon Discord](https://discord.gg/horizonps) and we'll update it when we have time._  

---  

## Step-by-Step Installation and Configuration Guide

Screenshots in this guide show the Windows version. Steps should be similar on MacOS, Linux, and even Steam Deck (see FAQ below). As long as your device has network capabilities and can install PCSX2, it should be possible to get online.   

### Download and Install PCSX2
<details>
<summary>Click here to expand/collapse details.</summary>  
   
1. Download PCSX2 for your operating system from [the PCSX2 website](https://pcsx2.net/downloads/). 
   > The "Latest Stable" or "Latest Nightly" versions of PCSX2 both work fine for most users. Do NOT try to use a version of PCSX2 that is older than 2.0. It will likely not work as well (if at all), the user interface is very different from any of the screenshots shown below, and the Horizon staff will be unable to assist you.  
2. Unzip the file (use [7-zip](https://www.7-zip.org/) if needed), then move the files into the directory you would like to run PCSX2 from. This build does not have an installer file, so once you extract and move the files they are essentially "installed". See below for an example of what the "installed" folder looks like.
   > Note: This assumes that you downloaded the "Latest Nightly", or the "Download" version of "Latest Stable". If you downloaded the stable "Installer", use that to install PCSX2.

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-folder.png)

3. If desired, pin the `pcsx2___.exe` file (the `.exe` file that is NOT named "updater") to your Desktop and/or Start Menu. Then open it. The first window of the Setup Wizard will appear.

4. Change language, theme, and automatic update settings as desired. Then click Next.

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-setupwiz_language.png)
</details>

### BIOS Image
<details>
<summary>Click here to expand/collapse details.</summary>  

If using the Setup Wizard, the next screen will have the BIOS Image settings.  
(If not using the Setup Wizard, navigate to the Settings menu → BIOS within PCSX2).  

5. Select your BIOS, then select Next (or Close, if not in the Setup Wizard) to continue.
- If you have already set up a different version of PCSX2, you can use the same BIOS by clicking the "Browse..." button and navigating to your existing BIOS folder. Or you can copy the BIOS files into the default folder specified.  
- If you haven’t used PCSX2 yet, you will have to obtain the BIOS from your PS2 - see the instructions [here](https://pcsx2.net/docs/setup/bios). Then either move the files into the default folder specified, or use the "Browse..." button to select the folder the files are in. A single BIOS will likely consist of *several actual files*, similar to what is shown in the first image below.  
- Once you have a valid BIOS folder selected, the BIOS will show up in the "BIOS Selection" list *as one selection*, similar to what is shown in the second image below.

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings-biosfiles.png)

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_bios.png)
</details>

### Game Directories
<details>
<summary>Click here to expand/collapse details.</summary>  

If using the Setup Wizard, the next screen will have the Game Directories settings.  
(If not using the Setup Wizard, from the main window of PCSX2 select the "Add Game Directory..." button).  
   
6. Obtain your ISO for UYA/R&C 3 or Deadlocked/Gladiator (if you have not already done so). Then, click "Add" and browse to the folder that you saved the ISO(s) in. Select Next (or Close, if not in the Setup Wizard) to continue.
</details>

### Controller Setup
<details>
<summary>Click here to expand/collapse details.</summary>  

If using the Setup Wizard, the next screen will have the controller setup.  
(If not using the Setup Wizard, navigate to the Settings menu → Controllers within PCSX2).  

7. Map your controller, then click Next (or Close, if not in the Setup Wizard) to continue.
8. If using the setup wizard, select Finish on the final window to complete the wizard and bring up PCSX2's main window.
</details>

### Emulation and Graphics Settings
<details>
<summary>Click here to expand/collapse details.</summary>  
After completing the Setup Wizard, there are still several more steps required to play online.

9. Go to Settings → Emulation and adjust as shown below.

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_emulation_v5.png)

10. Go to Settings → Graphics and adjust as follows.  
   a) The Renderer and Adapter drop downs are machine dependent. In general, for the Adapter drop down choose your graphics card.  
   b) Set up the "Display" tab as shown in the first image below.  
   c) Set up the "Rendering" tab as shown in the second image below.  
   d) The other tabs within the Graphics settings can be left as is.  
> Note that the graphics settings shown are intended to be a baseline that will provide smooth gameplay on mid-range machines. If you have a high-end gaming computer and/or would like to maximize the visual appearance of the games, please [check the FAQ below](/#faq).  

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_graphics_display_v2.png)

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_graphics_rendering.png)
</details>

### Network Settings (Sockets/Auto with manual DNS method)
<details>
<summary>Click here to expand/collapse details.</summary>  

This is the simplest PCSX2 network setup configuration. If it isn't working, [check the FAQ below](#faq) for alternate configurations.

11. Go to Settings → Network & HDD and configure as follows:  
   a) Check the "Enabled" box under Ethernet.  
   b) Set the Ethernet Device Type to "Sockets".  
   c) Set the Ethernet Device to "Auto".   
   The resulting Network & HDD screen should look something like what is shown below.  

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_network_sockets.png)
</details>

### Custom Map Setup
<details>
<summary>Click here to expand/collapse details.</summary>  
   
Our community members often play on the custom maps created by Horizon staff and community members for both [Ratchet & Clank: Up Your Arsenal (NTSC-U/C) / Ratchet & Clank 3 (PAL)](/up-your-arsenal/CMAPS.md) and [Ratchet: Deadlocked (NTSC-U/C)](/deadlocked/CMAPS.md) (_unfortunately, custom maps are not currently available for Ratchet: Gladiator (PAL)_). We strongly recommend setting up custom maps now (using either the written steps below, or our [video guide](https://www.youtube.com/watch?v=ND61nvDr0bM&t=320s)) so that you are not left out of an event later because you don't have them ready to go!  

12. Visit the [Horizon website](https://rac-horizon.com/) and find the correct custom map download(s) for your game(s)/region.  
13. Extract the contents of the downloaded zip file(s) into the same folder you selected for your ISOs above.  
  - Verify that the ISO folder has all of your ISOs, plus a subfolder called "uya" (for UYA/R&C 3) and/or "dl" (for DL). In the root folder alongside your ISOs there will also be a readme .txt file and some scripts that you can use to update the maps (check the readme or video guide for detailed update script instructions). Similar to what is shown below.   
  - Inside of the "uya" and "dl" subfolder(s) should be a bunch of map files.  

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-cmaps.png)

14. In PCSX2, go to Settings → Emulation and verify that the "Enable Host Filesystem" option is enabled.  
</details>

### PAL DNAS Workarounds 
<details>
<summary>Click here to expand/collapse details.</summary>  

**This section only applies if you have a PAL version of the game/ISO. It can be ignored if you have an NTSC-U/C version of the game/ISO.**

15.  Download the DNAS patcher tool from [this webpage](https://www.psx-place.com/threads/dnas-net-patcher.22813/) ("DNAS_PATCHER18.7z" has been verified to work). Then extract it with 7-zip and follow the instructions on the webpage to run it on your Ratchet & Clank 3 and/or Gladiator PAL ISO(s).  
    > If the DNAS patcher tool is unavailable or is not working for some reason, you can also download the files [here (R&C3)](/assets/cheats/17125698.pnach) and [here (Gladiator)](/assets/cheats/D697D204.pnach) (click the three dots near the upper right corner of the page, then "Download") and place it into the cheats folder of your PCSX2 installation. Then, in PCSX2 navigate to Settings → Emulation → Enable Cheats. This should accomplish the same purpose.  
</details>

### Finalize Network Setup In Game
<details>
<summary>Click here to expand/collapse details.</summary>  
   
16. Start the game, navigate to Multiplayer → Online Play, and click Square to access the network setup tool. Click "Add Setting" and run through the steps to create a new network configuration.  
   a) For "Are a user ID and password required to access your provider?" select "Not Required."  
   b) For "Set the IP address automatically?" select Auto.  
   c) For "Set the DNS server address automatically?" select **Manual.**   
   d) On the next screen, enter one of the following DNS addresses:  
      - The Horizon DNS listed in our `#how-to-play` channel will only work for UYA and DL, but is maintained by us.  
      - Cristian's DNS (as listed in the [PS2 Online Discord](https://discord.com/invite/zE79nWT)) will work for many PS2 titles.  
      - 1UP/K3rber0s' DNS (as listed in the [PS Rewired Discord](https://discord.gg/VfeuF6ZWVb)) will work for many PS2 titles.  

   > Note that it is possible to create up to four network setup configurations using the in-game tool, each with a different DNS address. Many community members have multiple configurations set up so that they can easily switch between them.  

17. Save and exit the Network Setup tool, and navigate back to the multiplayer screen. Click Online Play again and connect to the network using the network configuration you just created.
</details>

### Create a Profile and Log In
<details>
<summary>Click here to expand/collapse details.</summary>  
   
18. From the profile selection/login screen, create a profile if needed.  
   - For the "Save Password" option, choose Yes and type in a password. You will not need to remember this password unless your memory card data gets corrupted, but saving the password means that you will not have to enter it each time you want to log in. You will also need to know your password if you later decide that you want to access your account from a different device (e.g. a PS2). We recommend choosing a strong password like you would with any other online platform.
   - For PAL users, choose the "Europe" region.

19. Save your profile and log in.
</details>

---  

## FAQ

Most questions tend to revolve around one of the topics below.  

### High-End Gaming Computers and Graphics  
<details>
<summary>Click here to expand/collapse details.</summary>  
   
If you have a high-end gaming computer, and/or would like to maximize the visual appearance of the games, check out these tips!

#### Global Graphics Settings
   
Here are a few things to try in the Settings → Graphics window.  
- In the "Rendering" tab, you can try increasing the "Internal Resolution" beyond 720p - but note that this may cause frame lag in-game.  
- Automatic/Vulkan is the preferred renderer, and Direct3D11 may help you get higher speed.  
- Anisotropic filtering is not necessary but causes next to no speed penalty (on fast computers).  
- If you are using 4x Native or higher resolution, try changing the "Bilinear Filtering" setting on the "Display" tab to "Bilinear (Sharp)".  

#### Game-Specific Settings
   
Settings can also be customized for each individual ISO/title in your PCSX2 game library (example image below). This allows you to experiment and optimize performance for each one. To access the settings for a specific game, right-click on it in the main PCSX2 window list and select "Properties". Then, select the desired tab in the sidebar.  
- "Graphics" tab: On most modern monitors, both UYA/R&C 3 and Deadlocked/Gladiator will look better in 16:9 aspect ratio so you can set that here.  
- "Patches" tab: Enable the "Widescreen 16:9" patch.
- "Emulation" tab: You can change the EE Cycle Rate to 180% for better in-game performance.
- For UYA/R&C 3 specifically, there is a 16:9 patch that isn't in PCSX2's archive (as of this writing). To use 16:9 here, you can boot the PS2 BIOS, go to its configuration, and set the aspect ratio to "Full". This will allow both UYA/R & C 3 and Deadlocked/Gladiator to boot with their built in 16:9 enabled.  

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_graphics_display_gamespecific.png)

</details>  

### Fixing Delay with Nvidia Graphics Cards
<details>
<summary>Click here to expand/collapse details.</summary>  
   
If you are using an Nvidia GPU and are experiencing delay in-game, try these steps to configure your GPU for PCSX2.  
1. Open the Nvidia Control Panel application on your PC. It can be opened by right-clicking in an open area on your desktop, or from the Start Menu.  
2. In the application, find the "Manage 3D Settings" section and the "Program Settings" tab. Click on the "Add" button next to the "Select a program to customize" drop down menu.  
3. Find the PCSX2 application (typically "pcsx2-qtx64-avx2.exe") in the list. If it is not in the list, click the "Browse" button at the bottom and find the executable file in the folder that you installed PCSX2 into.  

![img](/assets/pcsx2/nvidia_01SelectPCSX2.png)

4. In the "Specify the settings for this program" section, scroll down to find "Low Latency Mode" in the list. Change the setting for this to "Ultra."  

![img](/assets/pcsx2/nvidia_02LowLatencyMode.png)
 
5. Scroll down a bit further to find "Power Management Mode". Change the setting to "Prefer maximum performance." Restart PCSX2 for the settings to take effect.

![img](/assets/pcsx2/nvidia_03PowerManagementMode.png)

</details>  

### Custom PCSX2 Textures 
<details>
<summary>Click here to expand/collapse details.</summary>  
   
Users have created various custom textures for PCSX2. Some textures are upscaled UI textures that allow in-game text and objects like weapon icons to appear in higher resolution. For UYA/R & C 3, community members have also created custom map and skin textures which are explained more [here](/up-your-arsenal/textures.md).

#### Texture Setup

Some set up is required to use the texture packs. There are some initial setup steps that only have to be performed once, and "as-needed" setup to add and remove the chosen textures.  

[Click here](https://www.youtube.com/watch?v=DeIxdx_K-Bg) for a video tutorial showing the UYA/R&C 3 custom textures, or read on for written directions. NOTE: The video does not show steps 7 and 8 in the written instructions below. Please be sure to set the "Mipmapping" setting to "Basic (Generated Mipmaps)" as mentioned below.  

##### First Time Setup
This section only needs to be done once.  
1. In your PCSX2 installation folder, create a subfolder called "textures" if it does not already exist.  
2. Depending on your ISO, within the textures folder create a subfolder named the following. This will match the game code of your ISO on the PCSX2 home screen.  
   NTSC-U/C Up Your Arsenal ISO: "SCUS-97353" (without the quotes).  
   PAL Ratchet & Clank 3 ISO: "SCES-52456" (without the quotes).  
   NTSC-U/C Deadlocked ISO: "SCUS-97465" (without the quotes).  
3. Within the folder created in step 2, create a subfolder called "replacements".  
4. Within PCSX2, navigate to Settings -> Graphics -> Texture Replacement tab.  
5. In the "Search Directory" field, set the folder path to [your PCSX2 installation folder]\textures.  
6. In the "Options" section, enable the "Load Textures" setting.  
7. For UYA/R&C 3 custom textures: Still within the Graphics settings, navigate to the Rendering tab.  
8. For UYA/R&C 3 custom textures: In the "Mipmapping" field, select "Basic (Generated Mipmaps)". **NOTE: This setting was removed from PCSX2 after version 1.7.5828. You will need this version or a prior one in order for some UYA/R&C 3 custom textures to display correctly. If using newer versions, some custom textures will display correctly but others will not. You can always run version 1.7.5828 alongside your current updated version if you want to try out the textures.**  

##### Adding Textures
This section should be done as needed.  
1. Download and extract the desired texture files. You may need a tool like 7-zip to extract .rar files.  
2. Locate the folder that contains the textures you want to use. Copy or move the entire folder into the "replacements" folder that was previously created. The textures will still work if some of the image files are in subfolders (as they are organized in the download).  
3. If any existing textures will conflict with the new ones you just copied in, move them out of the "replacements" folder or delete them. The following rules apply for conflicts:  
  a) You can use one mod per map feature. For example, there should only be one mod for Bakisi Isles water in use at a time.  
  b) You can use one mod per weapon.  
  c) You can use one mod per skin per team color (so up to 8 skin mods in total, if each one is for a different color).  
  Conflicting textures will cause glitchy overlapping or weird visuals.  

#### Texture Pack Downloads
   
Here are links to downloads of various texture packs. Note: Some download links are external to our wiki - if you find that a link is broken, please let a Horizon staff member know on our Discord!  
- [Upscaled UI Textures for both multiplayer and single player Up Your Arsenal/Ratchet & Clank 3](https://gbatemp.net/threads/ratchet-clank-up-your-arsenal-texture-pack-scus-97353.631588/) - Download from the link in the first post. All credit for these textures as listed in the post.  
- [Upscaled UI Textures for UYA/R&C 3 Multiplayer Only](https://drive.google.com/file/d/14gpFeY_jzWzliAtFFWBgs4YnpNV9tL7-/view?usp=sharing) - Community members @pavo9001 and @bubblegum3390 took the above texture packs and optimized them for multiplayer by deleting unnecessary SP textures and adding some of their own.  
- [Other Custom Map Textures for UYA](/up-your-arsenal/textures.md) - See our special documentation of these custom textures by Horizon community members that allow players to select a whole new look and feel of various UYA maps and features.  
- [Upscaled UI Textures for Deadlocked Multiplayer](https://drive.google.com/file/d/1E2PMZdb0rKiLSl6askDWCkmqsAcHFrQv/view?usp=sharing) - @pavo9001 created these HQ text textures for Deadlocked.  
- [Upscaled 16:9 Crosshairs for Deadlocked](https://drive.google.com/file/d/1rKtZ2fD_JadoVRFpVi7pIPi3vyobLdkR/view?usp=sharing) - @pavo9001 created these crosshair textures for Deadlocked.

</details>  

### Enhancements for Steam Deck and Other 16:10 Displays
<details>
<summary>Click here to expand/collapse details.</summary>  
   
We have several community members who have played online using a Steam Deck! Most of the same steps apply for getting online. A couple of additional notes:  
- For network configuration, you MUST set up using the Sockets/Auto method. The Nmap/PCAP method will not work.  
- @pavo9001 created [16:10 Patches and Textures for UYA/R&C 3 and Deadlocked](https://drive.google.com/drive/folders/1yOrM6TDuUvbYosSMTlPXrsbG3ciwzzjp?usp=sharing). To use the patches, see the readme .txt file in the download. To use the textures, see the relevant FAQ on this page. We recommend using these for an optimal 16:10 experience. However, they will result in a squashed picture on normal 16:9 monitors.  

</details>  

### Getting Online with Other PS2 Titles
<details>
<summary>Click here to expand/collapse details.</summary>  
   
Do the step-by-step instructions above also work for other PS2 titles besides the ones that Horizon supports? **Mostly, to the best of our knowledge! But read on.** Although Horizon staff cannot provide detailed technical support/documentation for other PS2 titles, we play them ourselves and we realize that this guide may be useful to others in the PS2 revival community. In practice, most of the same steps above should apply for getting online with any PS2 title that has been revived. The main difference will lie in the network setup.  
Network setup happens in a few different places:  
- PCSX2's Settings → Network & HDD window,  
- The in-game Network Setup tool, and...  
- Various mods and hacks such as DNAS Bypass, etc. (not required for all titles)  

For some titles, the Sockets/Auto method shown above (or Nmap/PCAP method shown below) and either Cristian's or 1UP/K3rber0s' DNS will work without any further steps. For others, extra steps are required. Requirements can vary on a game-by-game basis. Here are some helpful resources for checking the requirements of each title:  
- [Official List of all PS2 Online Games](https://ps2online.com/list) - Includes some setup-related information for each game.  
- [PS2 Online Discord](https://discord.com/invite/zE79nWT) - Includes a channel for each game. Check the pinned messages for setup requirements.  
- [PS Rewired Discord](https://discord.gg/VfeuF6ZWVb) - Includes a channel for each game that has been revived by 1UP and K3rber0s.  

</details>  

### Alternate Network Setup (Nmap/PCAP method)
<details>
<summary>Click here to expand/collapse details.</summary>  
   
If the Sockets/Auto method for network setup detailed above isn't working, you may want to try this alternate setup.  

First, visit [this link](https://npcap.com/#download) and find the "Npcap X.XX installer" for your operating system. Download and install it.  

Then, in PCSX2 go to Settings → Network & HDD and configure as follows:  
- Check the "Enabled" box under Ethernet.  
- For Wired/Ethernet connections, set up as shown on the left side of the image below. The selected Ethernet device should include "Ethernet" in the name. If there are multiple and one isn't working, try a different one.  
- For Wireless/WiFi connections, set up as shown on the right side of the image below. The selected Ethernet device should include "WiFi" in the name. If there are multiple and one isn't working, try a different one. To get the "PS2 Address" pointed out by the blue arrow, run Command Prompt’s ipconfig tool (or equivalent). Enter in your IPv4 address from your ipconfig output, but change the last digit. For example, if your IP address ends in 142 change it to 143. The reason for this is so that the PS2 is assigned a different address than other devices connected to your network. If possible, check your router setup page to see all IP addresses using your network.

For the in-game Network Setup tool, the DNS can remain the same as the Sockets/Auto method (i.e. either the Horizon DNS, Cristian's DNS, or 1UP/K3rber0s' DNS).  

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_network_alt.png)

</details>  

### Alternate Network Setup (Sockets/Auto with internal DNS method)
<details>
<summary>Click here to expand/collapse details.</summary>  
   
If NEITHER the "Sockets/Auto with manual DNS" or "Nmap/PCAP" methods are working, there is a third network setup method you can try. **This method may work for Horizon-supported titles only.**  

First, download [this file](/assets/cheats/hosts.ini) (click on the three dots near the upper right corner of the screen, then select the Download option from the list). Save the file somewhere locally on your computer.  

Then, open PCSX2 and navigate to Settings → Network & HDD. Verify that the "Ethernet" check box is enabled, the "Ethernet Device Type" is set to "Sockets", and the "Ethernet Device" is set to "Auto".  

Then, further down the same window next to "DNS1 Address" change the drop down selection to "Internal" (as seen on the left side of the screenshot below).  

Then, click on the "Internal DNS" tab under the Ethernet Device selection. Click the "Import" button and navigate to the hosts.ini file that you saved. Click OK on the next window to add all of the hosts in the file. When complete, your window will look like the right side of the screenshot below.  

Finally, boot up the game and create a new network configuration. **Unlike the other network setup methods described above, do NOT enter in a manual DNS address with this method. Leave all of the automatic/default options.**

![img](/assets/pcsx2/Guide-2023Feb/pcsx2-2023Feb-settings_network_autointernaldns.png)

</details>  

### I am still having trouble connecting! Help!
<details>
<summary>Click here to expand/collapse details.</summary>  
   
_First, please note that you will always need to reboot the game after changing PCSX2 settings, for the changes to take effect._  
Issues can happen in one of several places, as listed below:  

#### a) **Cannot load the main Multiplayer menu, or other issues even getting that far**
We have seen a few users who were running into odd issues like this. For a couple of them, the common thread was that they were trying to use an old BIOS. Try a different BIOS that is newer (v2.20 or later seems to provide good results). The BIOS version is shown on the BIOS selection settings screen in PCSX2.  

#### b) **Cannot select "Online Play" in main Multiplayer menu**
Please verify that you checked the "Enabled" box in PCSX2's Network and HDD settings. If trying to use the Nmap/PCAP method, make sure that you installed Npcap correctly.  

#### c) **Timeout/error message on "Connecting to Network" screen**
This is usually caused by an incorrect "Ethernet Device" selection in PCSX2's Network and HDD settings. Please revisit the network setup section above and carefully review the steps and screenshots. You should be able to visit your computer's network settings to match up device names with what is shown in the PCSX2 drop down list.  

#### d) **Timeout/error message on DNAS Authentication screen**
This is usually caused by an incorrect "Ethernet Device Type" selection in PCSX2's Network and HDD settings. Please revisit the network setup section above and carefully review the steps and screenshots. PCAP Switched is not the same as PCAP Bridged!  

#### e) **Error message on profile selection/login screen**
This has a wide variety of causes. Every once in a while our servers are down, so double check with us that they are online. Sometimes, the connection is also blocked by your firewall or ISP. Ask us in our `#tech-support` channel and we can try to help.  

#### Some other things that you can try:  
   - If the "Sockets/Auto with manual DNS" method is not working, try the "Nmap/PCAP" method - or vice versa. If neither is working, try the "Sockets/Auto with internal DNS" method.  
   - If you are trying to get online with a WiFi connection, try using a wired Ethernet connection instead if possible. Even if you can only use Ethernet temporarily, the ability (or lack thereof) to get online that way can help rule out certain causes of the issue.  
   - If you are using a PAL ISO, try an NTSC-U/C ISO if possible.  

#### If none of this works, don't get discouraged!
This is the single most common problem that new PCSX2 users have. We have several Horizon staff and community members in the [Discord server](https://discord.gg/horizonps) that are very knowledgeable and may still be able to help. Please don't hesitate to ask us in the `#tech-support` channel of the Discord. Be sure to specify exactly where your issue is popping up (i.e. a, b, c, d, or e above). Screenshots of your PCSX2 Network & HDD Settings screen are very helpful, as are DNAS error numbers if that is where it is failing. Sometimes we can even hop in one of the voice channels to help you in real time.  

</details>  

### My question isn't answered here. How can I get help?
<details>
<summary>Click here to expand/collapse details.</summary>  
   
Please use the `#tech-support` channel in the [Horizon Discord server](https://discord.gg/horizonps). Please keep the following items in mind when asking questions:  
- Please be patient. Horizon staff and community members are unpaid volunteers who have jobs and other obligations. It might take a few hours for someone to respond to your message. The first person who sees your message may not be the best suited to help with your specific issue.  
- Horizon staff cannot provide specific support for games other than [the Ratchet and Clank titles that Horizon supports](/getting-online).

</details>  
