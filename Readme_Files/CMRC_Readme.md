<img width="2254" height="1080" alt="1-splash" src="https://github.com/user-attachments/assets/9d05cde8-8a7b-4fdc-a2b7-c2f372e96b56" />

**Mod List Support: [Omni's Star Cluster](https://discord.gg/rMZKDNrZQS)**

> [!IMPORTANT]
> **This list requires v1.6.1170.0 of Skyrim, v1.6.1378.1 of the Creation Kit, as well as the AE Upgrade and DLC**

<header>
    <h1>Contents</h1>
</header>

- [Foreword](#foreword)
  - [System Requirements](#system-requirements)
  - [Backup Download Links](#backup-download-links)
  - [Load Order Library](#load-order-library)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ and .NET](#installing-microsoft-visual-c-and-net)
    - [Pagefile and Crash Prevention](#pagefile-and-crash-prevention)
    - [Setting Shader Cache Size (NVIDIA Users Only)](#setting-shader-cache-size-nvidia-users-only)
    - [Steam Setup](#steam-setup)
    - [Changing the Game Language](#changing-the-game-language)
    - [Installing Creation Club Files](#installing-creation-club-files)
  - [Wabbajack Installation](#wabbajack-installation)
    - [Installing Wabbajack](#installing-wabbajack)
    - [Downloading and Installing Chaos Mage](#downloading-and-installing-chaos-mage)
  - [Problems with installation](#problems-with-installation)
- [Post-Installation](#post-installation)
  - [Game Folder](#game-folder)
  - [Antivirus Exceptions](#antivirus-exceptions)
  - [Improved Camera SE](#improved-camera-se)
  - [Custom Loot Ruleset](#custom-loot-ruleset)
  - [How to use Octagon](#how-to-use-octagon)
- [Playing the List](#playing-the-list)
  - [Before Launching the Game](#before-launching-the-game)
  - [What is the Challenge for this List](#what-is-the-challenge-for-this-list) 
  - [Actually Playing the Game](#actually-playing-the-game)
- [What are the Controls?](#what-are-the-controls)
- [Updating the Modlist](#updating-the-modlist)
- [Removing the Modlist](#removing-the-modlist)
- [Known Issues](#known-issues)
- [FAQ](#faq)

# Foreword
When I made my lists I wanted to create a modded environment that stayed true to the original themes of the vanilla game, but made them grander and more visually striking. What we ended up with is a war-torn, but beautiful landscape. Roads are uneven, showing signs of neglect and a lack of maintenance; with the occasional pothole forming as a result. Whiterun, a hold overrun with bandits and outlaws, has been greatly expanded in both size and scope. However, the walls are dotted with wooden fortifications built atop the decaying and crumbling walls of the city; the lack of Whiterun-controlled mines to source stone has allowed this deterioration to occur. It affects all the structures outside the main city, ranging from the walls of the keep to even the fences cordoning off the farmland.

Meanwhile, places with hefty sources of lumber and stone seem relatively untouched, neither by the war nor the disruption of the economy that came with it. This is just a facade though, as the strain on merchant's supplies is pushed to the limit by the civil war leading to increased prices for goods of all kinds. Yet, despite all this, we still have the beautiful forests of Falkreath, the gorgeous vista's seen from the mountaintops and the frost-bitten but serene landscapes of the northern holds.

Now, while this list may've originally been intended only for personal use on my YouTube channel, it has long since evolved past that point. Now I see each of my lists as a love letter to a different part of the Skyrim community. This particular list is my love letter to those fans of the Rigmor series, and the various tales that can be told through the Creation Engine. Say what you will about Bethesda's choice of engine for their games, but one thing the Creation Engine does best is create quests and weave stories; all-the-while limited only by the imagination of the author. With all that said, I hope you enjoy the fruits of my labor, and appreciate all the work that went into creating this list for you. Cheers!

## System Requirements
These are the minimum recommended specifications to run the list though there may be some wiggle-room on these specs (the degree of wiggle-room is noted directly below each requirement where it applies):
- 11th Gen Intel(R) Core(TM) i9-11900k equivalent CPU or later CPU models
- A GPU with at least 16GB VRAM is ideal and the list's default state is optimized for this quantity of VRAM.
> [!Note]
> It is possible to run the list with 8GB or 12GB of VRAM, but it will require you to use Octagon to downscale the textures to a lower resolution. Config files for optimizing the textures for each tier of VRAM quantity are included with the install.
- 32GB DDR5 or 32-64GB DDR4 RAM
- 40 GB Pagefile
- At least 678GB of free space (244GB for Downloads + 30GB Free Space & 404GB for Installation)

## Backup Download Links
- [Download v1.3.0.0]() **[!] Latest Version**

## Load Order Library
You can find the Load Order Library page [here](https://loadorderlibrary.com/lists/chaos-mage-randomized-challenge) at any time.

# Installation
Installing Chaos Mage is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).

## Pre-Installation
These steps are only required for installing the modlist for the first time. Additionally, many of these steps may be covered in other modlist installs, for new users I suggest reading through here regardless.

### Installing Microsoft Visual C++ and .NET
 1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).
 2. Install [.NET Runtime 9.X.X Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/9.0).
 3. Install [.NET 6.0 Runtime Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).

>[!WARNING]
>If you already have Visual C++ installed, please make sure you install it again and use the `Repair` option to get the latest version of the redistributables. **Do NOT skip this step or MO2 and the game may fail to launch.**

### Pagefile and Crash Prevention
>[!WARNING]
>Larger Skyrim modlists require a significant amount of memory, running out of memory **will** result in crashes and other potential issues. Due to Apostasy's size and number of files, this step is **NOT** optional. I do not care how much RAM or VRAM you have, please do this step.

**To set up a Pagefile:**

 1. Press `Win Key + R`
 2. Type `sysdm.cpl ,3` and hit `ENTER`
 3. Navigate to **Performance** and click the box `Settings...`
 4. Click the **Advanced** tab at the top
 5. Under **Virtual Memory** click the box `Change...`
 6. Uncheck `Automatically Manage` if it is checked
 7. Select your disk drive, ideally your fastest solid state drive
 8. Click `Custom Size:`
 9. In the box next to **Initial Size (MB)**, type `40960`
 10. In the box next to **Maximum Size (MB)**, type `40960`
 11. Click `Set`.
 12. Click `OK`.
 13. Click `Apply`.
 14. Click `OK`.
 15. **Restart your PC**.

>[!TIP]
> Your pagefile does not need to be on the same drive as your Wabbajack install or Steam install of the game.

<Details>
<summary>ICYWW: Why do we need a Pagefile?</summary>

Skyrim is a very old game (originally released in 2011) that is built on the [Creation Engine](https://en.wikipedia.org/wiki/Creation_Engine), a engine based off of the [Gamebryo](https://en.wikipedia.org/wiki/Gamebryo) engine that was originally used for Morrowind (released in 2002, *before I was born*).  

Through lots of experience and trial-and-error, we have discovered that increasing the window's pagefile can fix certain types of Skyrim crashes, the two most common examples being `Unhandled native exception occurred at 0x7FF6ADC8DDDA` and `Unhandled native exception occurred at 0x0`.  

But why is this? Skyrim appears to use system memory in very unexpected ways, for example it will frequently dip into the pagefile memory despite there being available RAM. Skyrim heavily favors high speed, low latency RAM (the best you can get as of writing this is 6000MHz and CL30 for DDR5).  

</Details>

### Setting Shader Cache Size (NVIDIA Users Only)
>[!IMPORTANT]
>For NVIDIA users, it is recommended to boost the size of the shader cache. These settings have been shown to improve stability, while it may not be entirely necessary, it is still recommended.

**To do this:**

- Right-click on your desktop and select `NVIDIA Control Panel`
- Navigate and click `Manage 3D Settings`
- Scroll down the **Global Settings** tab until you see **Shader Cache Size**
- Double-click `Driver Default` to the right of **Shader Cache Size** and select `100 GB`
- Click `Apply` in the bottom right hand corner
- Exit out of the application

### Steam Setup
>[!WARNING]
>If you have your Steam Library in Program Files, read [this article](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) by LostDragonist. Locations such as Desktop, Documents, Downloads, OneDrive, etc. *will* cause issues with installing and playing the list.

 1. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
 2. Right click on Skyrim SE and click on properties, untick the `Enable Steam Overlay while in-game.`
 3. Please ensure you follow the steps outlined in the [Installing Creation Club Files](#installing-creation-club-files) section. **DO NOT SKIP THIS STEP OR YOUR INSTALL WILL FAIL.**

### Changing the Game Language
>[!WARNING]
>**The English Steam version of Skyrim SE is the only supported version.**

I understand that this may be frustrating for non-English speaking users or users with the GOG/Bethesda.net versions, but due to the core file differences between the different versions, I am only able to support one game version.

To change your Skyrim SE's language:

 1. Right click on Skyrim SE in Steam
 2. Click `Properties`
 3. Click `Language`
 4. Set the Language to `English`

### Installing Creation Club Files
>
>[!WARNING]
> ***Do NOT skip this step or your install may fail!***

Since this list requires the full AE DLC this step is not that complicated. Simply ensure that you have purchased the AE Upgrade and launch the game through Steam afterwards. It will prompt you to download the AE content once you've loaded into the main menu. Simply confirm and allow the process to run to completion. When it is finished downloading the additional files you can safely close the game.

>[!IMPORTANT]
>
>- **DO NOT** Alt+Tab during this process or it will fail to properly download these files.
>- **DO NOT** verify your game files after doing the steps above as it will revert the "correct" file hashes for the CC files you downloaded in this step.

## Wabbajack Installation

### Installing Wabbajack
Once you have completed the pre-installation section, follow these steps to install Wabbajack:

1. Create an empty folder named `Wabbajack` on the root of your drive, such as `C:\Wabbajack` for example.
    > - **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), in your Skyrim's Steam folder, or in any folders related to the modlist itself (the downloads or install folder).**
    > - The `Wabbajack` folder does not need to be on an SSD, but it makes installing faster. You can set this location to be on an HDD for the sake of saving space.

2. Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place the `Wabbajack.exe` file inside the Wabbajack folder you created in Step 1.

3. Double-click the `Wabbajack.exe` file that is now inside your Wabbajack folder to set up the program.

>[!IMPORTANT]
>The list has only been tested with Wabbajack version **4.0.0.0 or later**. Installing the modlist with older versions of Wabbajack is untested at this time and is not recommended and generally unsupported.

### Downloading and Installing Chaos Mage
>[!CAUTION]
>**A legal copy of Skyrim Special Edition is required.** Pirated copies of the game will cause the installation to fail and even if you manage to somehow get around Wabbajack's built-in piracy prevention measures, SKSE does not work with the cracked exes.  

Downloading and installing Chaos Mage can take a while depending on your internet connection, PC specs, and if you have Nexus Premium. Without Premium, you will need to manually click the **Slow Download** button for each mod.

To install Chaos Mage, complete the following steps.

 1. Open Wabbajack and click `Browse lists`
 2. Pick the **Skyrim Special Edition** option from the game filter drop-down box (or use the search bar to find the modlist).
 3. Press the download arrow on the Chaos Mage UI card and wait for it to download
 4. Set the `Installation Location` to a folder such as `C:\Chaos Mage`.
    > - **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), or in your Skyrim's Steam folder**
    > - The `Downloads Location` does not need to be on an SSD, but it makes installing faster. You can set this location to an HDD for the sake of saving space.
 5. Press the `Install` button.
 6. Turn on your favorite show or a nice long video essay as Wabbajack does its thing. Alternatively read through this readme again.
 7. If the installation is successful, then you're all set to move on to [post installation](#post-installation). If the installation is unsuccessful, follow the tips below or the [discord server](https://discord.gg/rMZKDNrZQS) for support.

## Problems with installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

<Details>
<summary>I'm having trouble downloading Non-Nexus files or specific files!</summary>

Big files can fail to download due to connection issues or website issues. You can either run Wabbajack again or download the missing file manually. If you decide to manually download the file, make sure to place the file(s) inside the folder you set as the `Resource Download Location`.

This issue can also occur with files sources from Google Drive, MEGA, Patreon, and other sites. Missing Manual Downloads are listed [here](#missing-manual-downloads).

</Details>

<Details>
<summary>Wabbajack couldn't find my game folder!</summary>

Either buy the game or re-read the [Pre-Installation](#pre-installation) section.  

</Details>  

<Details>
<summary>Unable to download 'Data_ccbgssse037-curios': </summary>

Please make sure you are following the steps outlined in the [Installing Creation Club Files](#installing-creation-club-files) section

</Details>  

<Details>
<summary>Unable to download Skyrim_Default.ini or SkyrimPrefs.ini:</summary>

This error means you failed to follow this Readme. Go back and follow the steps outlines in the [Changing the Game Language](#changing-the-game-language) section

</Details>  

<Details>
<summary>Could not find part of the path "TEMP_BSA_FILES"</summary>

This is typically caused by a problem extracting zip files.  

The quickest solution is as follows:  
 1. Close Wabbajack.
 2. Go to your install folder and locate the `TEMP_BSA_FILES` folder (if it exists).
 3. Delete that folder (if it exists).
 4. Restart Wabbajack.
 5. Restart the modlist installation.  

If the `TEMP_BSA_FILES` folder does not exist, then delete the download file for the mod being referenced before restarting Wabbajack.  

**Note**: Using the retry button will not work as Wabbajack does not understand that there was an issue with extraction and will not retry extraction steps.

</Details>  

<Details>
<summary>My antivirus reports a virus with the program or modlist!</summary>

Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](#antivirus-exceptions).  

</Details>

<Details>
<summary>Sanity check error extracting file:</summary>

Wabbajack will sometimes have issues extracting files if they use special characters. If you encounter this issue in a Wabbajack log, please try the steps down below:

 1. Press `Win Key + R`.
 2. Type `intl.cpl` and hit `ENTER`.
 3. Navigate to *Administrative* and click `Change system locale...`.
 4. Change the *Current system locale:* to `English (United Kingdom)`.
 5. **Uncheck** `Beta: Use Unicode UTF-8 for worldwide language support`
 6. Click `OK`
 7. **Restart your PC** and rerun the Wabbajack installer.

</Details>  

<Details>
<summary>Wabbajack is crashing during the installation!</summary>

If you find yourself struggling to run Wabbajack without it crashing, freezing up, or blue-screening your PC, please try lowering Wabbajack's resource usage with these steps:

 1. Open Wabbajack.
 2. Click the **Settings** button in the bottom left corner of the Wabbajack window.
 3. Under the **Performance** box, lower each number for each category to half of what it is currently set.
 4. Continue Installation.

>[!TIP]
> It is suggested to have a program installed on your PC that can open `.json` files, like [Notepad++](https://notepad-plus-plus.org/) or [Visual Studio Code](https://code.visualstudio.com/)

</Details>

## Post-Installation

## Game Folder
Chaos Mage uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called `Stock Game`. You don’t need to copy anything at all.

## Antivirus Exceptions
>[!WARNING]
>Antivirus programs are notorious for false flagging [MO2's Virtual File System](https://stepmodifications.org/wiki/Guide:Mod_Organizer/Advanced), which can and will cause crashes and other problems. Antivirus programs like BitDefender, Norton, and Webroot are especially aggressive, and you will need to fully remove them from your PC in order to actually launch the game through MO2. It is 2024, Windows Defender and being smart online is more than adequate to protect yourself from malicious software.

If you use Windows Defender, it is advised that you set up an exception for the modlist.

<Details>
<summary>Setting up Windows Defender Exceptions:</summary>

 1. Press the Windows Key.
 2. Type "Windows Defender" in the search bar and select "Windows Security".
 3. Click on "Virus & threat protection" in the left pane.
 4. Click the "Manage settings" option under "Virus & threat protection settings".
 5. Scroll down to "Exclusions" and click "Add or remove exclusions".
 6. Windows Defender will prompt you with a run as administrator screen, just hit yes.
 7. Click the "Add an exclusion" button at the top and choose "Folder".
 8. Navigate to your Install folder for the list and click "Select Folder".
 9. **(OPTIONAL)** You can repeat these steps for the other executables:
    - ModOrganizer.exe (`[Path to Modlist]\ModOrganizer.exe`)
    - Nemesis Unlimited Behavior Engine.exe (`[Path to Modlist]\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe`)
    - Synthesis.exe (`[Path to Modlist]\tools\Synthesis\Synthesis.exe`)

</Details>

## Improved Camera SE
Join the [Improved Camera Discord Server](https://discord.gg/improved-camera-se-1074109591966732328) and download the latest version of the v2.x beta build from their updates channel. Install and place it under the "Modular Extras" section. This will ensure the included profile edits win the conflict.

## Custom LOOT Ruleset
If you're unsure that the load order is correct you can download my custom ruleset for LOOT [here](https://www.mediafire.com/file_premium/23cu0m5m8mea73z/LOOT-backup-20260110T004612.zip/file) and extract its contents into your LOOT data folder. You'll find the LOOT data folder under <ins>*AppData > Local > LOOT*</ins> by default. Simply extract the ruleset there and run LOOT for automated sorting. If you're unsure how to find it hit Win + R, type %localappdata% and hit enter. Then navigate to the LOOT folder and extract the contents there.

## How to use Octagon
> [!WARNING]
> It is highly advised you either have a backup of the mods folder or the full downloads folder from installation in case you mess up. If you have neither of these you will have to completely redownload and reinstall the list if things go wrong due to how Octagon works.

Launch Octagon via Mod Organizer 2 and then follow these instructions exactly:

1) Go to the top-left corner of the UI to open the file menu and select the **Open Configuration** option (see image below).
<img width="1920" height="1032" alt="Octagon Guide Part 1" src="https://github.com/user-attachments/assets/7378e38d-3fdb-4ac4-9ced-a7798f77ad93" />

2) This will open a Windows Explorer window. Navigate to the Octagon install folder located under <ins>*Modding > MO2 > Optimization Tools > Octagon*</ins> and select the appropriate config for your GPU's quantity of VRAM (see image below).
<img width="1920" height="1032" alt="Octagon Guide Part 2" src="https://github.com/user-attachments/assets/f22533d2-73c5-41c7-a8d1-618acc1c538c" />

> [!Note]
> As stated in the accompanying visual guide, if you have only 8GB VRAM you will need to do this process twice to reach optimal texture sizes. In this case start with the **8GB VRAM (Step 1)** config file and when running a second time use the **8GB VRAM (Step 2)** config and repeat the other steps again. This will ensure your textures are all downscaled to the appropriate sizes.

3) Now that you've loaded the config you need to update a few file paths. First update the file path to your MO2 mods folder (see image below).
<img width="1920" height="1032" alt="Octagon Guide Part 3" src="https://github.com/user-attachments/assets/f963ddda-bac4-452f-a5d7-2598d18165a0" />

4) Next you want to go to the **Tool Paths** tab of *Octagon* and change the paths for **BSArch** and **GMIC** to point to their respective executables located in their respective subdirectories found under <ins>*Modding > MO2 > Optimization Tools*</ins> so that Octagon can find them (see image below).
<img width="1920" height="1032" alt="Octagon Guide Part 4" src="https://github.com/user-attachments/assets/81f1ea4b-33c1-4491-aa11-02981bb1a2e0" />

5) Finally you can return to the **General** tab of *Octagon* and press start.
<img width="1920" height="1032" alt="Octagon Guide Part 5" src="https://github.com/user-attachments/assets/71238249-8cf6-4073-bc16-46780d52c701" />

# Playing the List
>[!WARNING]
>Before doing anything else, or even launching the game, make sure that the control scheme that matches your keyboard configuration is the only one enabled (ie. if you have an AZERTY keyboard disable the QWERTY Control Scheme and enable the AZERTY Control Scheme).

## Before Launching the Game
 1. Head over to your modlist installation folder (e.g. `C:\Chaos Mage`), locate an executable named `ModOrganizer.exe`, and launch it. Your first launch of Mod Organizer 2 may take several minutes due to GitHub repository downloads, so please be patient.
 2. Set up your CPU Affinity by following the instructions below. **Please do not skip this step!**
  
    <Details>
    <summary>Setting CPU Affinity</summary>

    1. Click the `Puzzle Piece` button at the top of MO2 and select `Set CPU Affinity` and press `OK` on the pop-up box.
  
        ![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/cpu%20affinity%20example.png)  

    2. That's it, it's really that simple. **Please, please, please** do this before launching the game and whenever you update the modlist.

    </Details>

## What is the Challenge for this List
I'm glad you asked, the challenge element is mostly handled outside of game and not via any mod-implementation allowing you to just use the list "as-is" or attempt the challenge I did yourself.

Want to try the challenge run for yourself? Then simply [spin the wheel](https://wheelofnames.com/) using the templates provided below and limit yourself to the results. You'll spin for a new school every ingame day at midnight. And your task for the day will be selected via its own wheel. Then set yourself an ultimate goal you must complete with this handicap and you've got your very own version of the run! The template follows my variation where I have to complete the entirety of the **College of Winterhold** with these handicaps, but you can change it out with whatever you wish.
- [School of Magic Wheel](https://www.mediafire.com/file_premium/x5b77bpov4v2vxo/School_of_Magic.wheel/file)
- [Daily Task Wheel](https://www.mediafire.com/file_premium/3gn5r0w7szzcwyk/Daily_Task.wheel/file)
- [Random Dungeon Wheel](https://www.mediafire.com/file_premium/psx97mryritzqoh/Random_Dungeon.wheel/file)
- [Random Side Quest Wheel](https://www.mediafire.com/file_premium/wsloj3p1k8db3l0/Random_Side_Quest.wheel/file)

Most of all I hope you enjoy the list! It is the product of a lot of hard work creating a functional base that all my challenge lists could be based off of. So I hope you appreciate the effort and custom patch work that went into its creation. With that said let's move on to the installation instructions!

## Actually Playing the Game
 1. Launch the "Play" Executable in MO2. The game may take several minutes to load on your first launch. Please be patient and **DO NOT** click the `Unlock` button on the MO2 prompt.
   >[!CAUTION]
   >**FOR THE LOVE OF AKATOSH, DO NOT CLICK THE UNLOCK BUTTON!**
 2. Select the **New Game** button.
 3. Create your lovely character.
 4. Walk up to the strange glowing stone shrine directly in front of you and select the race option in the pop-up window that appears when you interact with it. This is so that the Helm Hair Updated mod can register your main hairstyle.
 5. Repeat this interaction two more times for Birthsign and Class selection.
 6. Simply open the singular door in the room and step into the black void gazing at you to begin your adventure.

# What are the Controls
If you're using a QWERTY Keyboard (the default control scheme for the list) these are the controls:
<img width="1920" height="1080" alt="keyboard+mouse-control-layout" src="https://github.com/user-attachments/assets/5a885727-6598-486e-b7a7-0cfd083e2b02" />

And as of v1.1.0.0 we've added support for AZERTY Keyboard users:
<img width="1920" height="1080" alt="azerty-keyboard+mouse-control-layout" src="https://github.com/user-attachments/assets/33b1e9d3-8639-4e57-9858-5515a4c19992" />

> [!IMPORTANT]
> You will need to enabled the **AZERTY Control Scheme** and disable the **QWERTY Control Scheme** found under Accessibility Options. Then, once in-game, you'll need to reset controls to default for the changes to take. This additional step is only required for AZERTY users and is unfortunately the only way I've found that is consistent for remapping the keys properly.

# Updating the Modlist
Versioning for the list will adhere to the following format: `MAJOR.MINOR.PATCH.REVISION`.

- `MAJOR`: Any release with a number change here will be considered a major update as at least 1 area of the list was massively overhauled. These updates with **NEVER** be save safe.
- `MINOR`: Any release with a number change here will be considered a minor update, these updates will **not** be save safe, unless otherwise specified.
- `PATCH`: Any release with a number change here will be considered a patch, these updates should be save safe unless otherwise stated and will be used primarily for bugfixes.
- `REVISION`: Any release with a number change here will be considered a revision. These updates are usually hotfixes, minor gameplay changes or consistency tweaks and should be save safe unless otherwise noted.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite installation` button. Please keep in mind any mods you have added will be deleted when updating. To make sure that Wabbajack does not delete your added mods upon updating, prefix your mods with `[NoDelete]`.

>[!IMPORTANT]
>Saves can be continued across **Save-Safe** updates. Updates will be indicated whether or not they are **Save-Safe** in the Changelogs which are regularly posted to the Discord. It is suggested that you backup your saves before updating if you plan on continuing them.

# Removing the Modlist
Simply delete the Chaos Mage folder. Congratulations, you have uninstalled Chaos Mage.

# Known Issues
- [x] Blue snow textures on various static landscape meshes | **Fixed as of v1.0.1.0**
- [x] DynDOLOD issue with the Windmill on Katla's Farm | **Fixed as of v1.0.11.72**
- [x] Issues with some of the crowd at Rogvir's execution not being able to get to their positions
- [x] Navmesh-related crashes during the first dragon fight at the Whiterun Watchtower
- [x] Some minor navmesh tweaks required in small towns and villages
- [x] Minor navmesh tweaks required in Ustengrav

# FAQ
- **Question:** My NPC's are bald or are suffering the black/brown-face bug! How do I fix this?
	- **Answer:** This is likely due to me messing up a patch somewhere. Submit a ticket on the Discord server reporting exactly which NPC it was and I'll look into fixing it.

- **Question:** Where do I go if I'm having issues or want to report a bug?
	- **Answer:** Go to my Discord and submit a ticket. I'll look into fixing whatever issues you're having or whatever bug you reported.

- **Question:** I added a mod to the list and now I'm getting constant CTD's. What do I do?
	- **Answer:** Sadly if you modify the list yourself what support I can offer is extremely limited, especially if it's a hard-incompatibility. But submit a ticket on Discord and if it's something I can help with I'll do what I can to remedy the issue.
- **Question:** My animations are locking up and freezing me in place. What do I do?
  	- **Answer:** Exit the game and re-run Nemesis. This should fix the issue and if it doesn't submit a ticket on the Discord server for further support.
