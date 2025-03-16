> [!Important]
> **This is the documentation for the list you just downloaded. If you choose not to read this you forfeit access to any support.**
# Welcome to the *Ad Mortem Challenge* Readme!
![AMC Mod Page Thumbnail](https://github.com/user-attachments/assets/c5b57e10-190d-4209-ab29-7730c4f9aef6)

> [!Warning]
> **This list requires v1.6.1170.0 of Skyrim**

> [!Warning]
> **This list requires v1.6.1378.1 of the Creation Kit**

> [!WARNING]
> **This list requires the AE Upgrade and DLC**

> [!Note]
> **Answers to the *FAQs* and the *Known Issues* for the list are located at the bottom of this document.**
> - ***Known Issues* are being actively worked on and patched, and will be marked off the list as they are resolved; so do not bother reporting them as they are already being dealt with and will be resolved as I release the patches.**
> 
> - **If the answer provided to a FAQ does not work then submit a ticket and I will provide direct 1-on-1 support for the issue as I am able.**

## Requirements
These are the minimum recommended specifications to run the list though there may be some wiggle-room on the GPU and RAM:
- 11th Gen Intel(R) Core(TM) i9-11900k CPU or later CPU models
- NVIDIA GeForce RTX 4070 Ti or later GPU models (Older NVIDIA GPUs might work but I can't guarantee decent performance)
- 64GB RAM
- 40GB Pagefile
- At least 300GB of free space

## Download Links
- [Download v1.0.0.0]() **[!] Latest Version**

# Introduction
This mod list runs off of the BFCO combat system which mixes modern and vanilla combat rather seamlessly. It was designed with a focus on immersion and overhauling the game in just about every aspect; all-the-while striking a balance between realism and game-like convenience. xLODGen and DynDOLOD 3 are included with this mod list; so be sure to run them again if you make any additions to the list that adds new worldspaces. Gameplay elements that aren't togglable via an ingame MCM are located under the Modular Gameplay section of the load order and can be toggled off without issue.

If any of the included tools are ever out-of-date, I suggest manually updating them within MO2 to avoid messing with Skyrim's root directory. This is because Wabbajack installs require a clean Skyrim install to function. If you need help or want me to walk you through the process I'd be glad to help you on my Discord server. Simply submit a ticket and I'll get to you as soon as possible!

If you wanted to see the list in action you can visit my YouTube channel and watch the episodic series covering the challenge run this mod list is named after. I also have a Discord server where I offer support for the mod list and post updates for when I go live or post videos.

To join the Discord use the link below:
- https://discord.gg/rMZKDNrZQS

And to find my YouTube channel use the link below:
- https://www.youtube.com/channel/UC82BYjxRvHxzIQ519TrkzqQ

## What's the Challenge for this List?
I'm glad you asked, because there are some things you should know before playing this list for the first time. First-off, however, if you want to forego the challenge elements you can disable them in your mod list via *Mod Organizer 2* by un-ticking the box next to the associated mods located under the **Modular Gameplay** section.

The challenge of this list comes from the mod, which the list and challenge run series were named after, [Ad Mortem](https://www.nexusmods.com/skyrimspecialedition/mods/130582). Ad Mortem adds functional permadeath to the base game of Skyrim. It manages this by making it so that when you perish all your save files for that character, with the exception of saves created within the first five real-world minutes, are deleted and an epitaph with your statistics for that run is recorded in a text file. As such, in keeping with the darker themes of this list, the popular quest mods **Darkend** and **VIGILANT** are included. With that said, go on, let's see how far you can get without dying in the unforgiving world this mod list creates!

# Install Instructions
Now, before playing, you should do the following things:

1) Ensure the following ESL files are disabled in your load order (look under the plugins tab if using MO2):
	- 1NamelessSaber.esl
	- 1NDArmor.esl
	- 1FalconerArmor.esl
	
2) Ensure the following ESP files are disabled in your load order (look under the plugins tab if using MO2):
	- TheLegends-NordArmor.esp
	- 1YsmirArmorSE.esp
	
3) Ensure the following ESP files are enabled in your load order (look under the plugins tab if using MO2):
	- 1NamelessSaber.esp
	- 1NDArmor.esp
	- 1FalconerArmor.esp

4) Ensure the various patches are at the bottom of the load order. The bottom of your load order (located under the plugins tab if using MO2) should look like this:
    - Alternate Perspectives - Misc Patches.esp
    - Better Skyrim Parties - Misc Patches.esp
    - Bijin AIO - Misc Patches.esp
    - CACO - Misc Patches.esp
    - Capital Windhelm Expansion - Misc Patches.esp
    - Chooey's Choice - Misc Patches.esp
    - COTN Falkreath - Misc Patches.esp
    - Dark Elf Voices For Bandits - Misc Patches.esp
    - Dawnguard Arsenal - Misc Patches.esp
    - ESO Nord Weapons - Misc Patches.esp
    - Fleeting Torches - Misc Patches.esp
    - Immersive Jewelry - Misc Patches.esp
    - Immersive Weapons - Misc Patches.esp
    - JK's Winking Skeever - Misc Patches.esp
    - Modpocalypse - Misc Patches.esp
    - Orc Stalkers Fix - Misc Patches.esp
    - Return Aegisbane - Misc Patches.esp
    - Save the Ice-Runner - Misc Patches.esp
    - Simple Children - Misc Patches.esp
    - Crows and Ravens - NotWL Patch.esp
    - SDA - Consistency Patch.esp
    - LydiaRemake.esp
    - LydiaRemake HDT Improved Follower Dialogue - Lydia Patch.esp
    - CS_Melana+DLH Patch.esp
    - Ciri Concept Art Armor - Consistency Tweak.esp
    - Remove Weapon Glows.esp
    - RaSeaSky - NO RAVEN SPAWNS - Patch.esp
    - Whiterun Terrain Fix.esp
    - Falkreath Terrain Fix.esp
    - Rift Terrain Fix.esp
    - Haafingar Terrain Fix.esp
    - Shadowgreen Cavern Fix.esp
    - RemoveInteriorFog.esp
    - DynDOLOD.esp
    - Occlusion.esp
    - IcePenguinWorldMap.esp

## How to Update LODs
I use very specific settings when generating the LODs for these lists so, if you want to maintain the visual quality and consistency, I recommend following these instructions to the letter.

> [!Note]
> **For the sake of simplicity, the instructions are divided into subsections.**

> [!Warning]
> **I advise going through these in the order they are listed to avoid issues, but you are free to disregard my suggestion at your own peril.**

### Updating the SSELODGen_Ouput
1) First, you want to make sure <ins>*xLODGen Resources - SSE Terrain Tamriel*</ins> is enabled and launch **SSELODGenx64** (see image below).
![LODGen Resources](https://github.com/user-attachments/assets/f4422f47-fe73-40aa-8a77-91dd8de244e2)

2) When you get to the **LODGen Options** menu you'll want to tick the boxes of all the worldspaces available for LOD generation, ensure the box next to <ins>*Seasons*</ins> is unticked, and that only <ins>*Terrain LOD*</ins> is selected (see image below).
![Regions + Seasons](https://github.com/user-attachments/assets/3b1003e9-1c4d-4ad8-b10f-da3e7a5fe762)

3) Next you'll want to ensure your settings for each level of LOD (LOD4, LOD8, etc.) match the settings I use (see images below).
![LOD4](https://github.com/user-attachments/assets/9a147e48-ce9e-4c02-bc83-3116a0d19ad5)
![LOD8](https://github.com/user-attachments/assets/4dc26b7f-eb03-435d-b41a-fb1833ddefdb)
![LOD16](https://github.com/user-attachments/assets/97144c3a-11e3-4445-a2ee-084fe53f7dfe)
![LOD32](https://github.com/user-attachments/assets/dbca6ad5-48d8-4f28-8053-7a053c643224)

4) After doing that simply click **Generate** and when the process completes close **SSELODGenx64** (see image below).
![Generate](https://github.com/user-attachments/assets/97e79223-dac3-4f8e-8eca-35bb3269fd69)

5) Afterwards ensure that you have disabled <ins>*xLODGen Resources - SSE Terrain Tamriel*</ins> before moving on to the next step.
![Turn off LODGen Resources](https://github.com/user-attachments/assets/65ac73c7-3ca1-4286-94bd-a72830ea8e63)

### Updating the TexGen_Output
1) First, you want to make sure that <ins>*Grass Bound Records*</ins> is disabled and launch **TexGenx64** (see image below).
![Ensure Grass Bound Records is Off](https://github.com/user-attachments/assets/0984638e-1759-49a4-9fd9-d1129f6bac6b)

2) After launching TexGenx64 you will be greeted by a screen with a set of options. Select the **-SSE = Skyrim SE, Skyrim AE or Enderal SE mod version** option and then press the **Start TexGen** button (see image below).

![TexGen Launch](https://github.com/user-attachments/assets/e6e0ccf5-9e32-4b5d-84f9-fa62b0d4d33b)

3) Once you do so you will eventually reach the **TexGen Options** menu. Ensure your settings for <ins>*Stitched Object LOD Textures*</ins>, <ins>*Rendered Object LOD Textures*</ins> and <ins>*Tree/Grass LOD Billboards*</ins> match mine and then press the **Start** button at the bottom to begin processing (see image below).

![TexGen Options](https://github.com/user-attachments/assets/9e89e69d-7e58-4698-acf4-63869f16909d)

4) When the process completes you will be prompted with several options. If you select **Exit TexGen** you will simply cut-and-paste the generated *TexGen_Output* folder, located under <ins>*Modding > MO2 > LOD Generation Tools > DynDOLOD*</ins>, and overwrite your existing *TexGen_Output* folder. You can find it located under <ins>*Modding > MO2 > mods*</ins>. If you choose **Zip & Exit** simply install the mod via the created zip archive with *Mod Organizer 2* and choose the **Replace** option.

### Updating the DynDOLOD_Output
1) First, you will want to find the *DynDOLOD_SSE.ini* located under <ins>*Modding > MO2 > LOD Generation Tools > DynDOLOD > Edit Scripts > DynDOLOD*</ins> and change the 11th line from **Expert=0** to **Expert=1** and launch **DynDOLODx64** via *Mod Organizer 2* (see image below).
![Change to Expert mode](https://github.com/user-attachments/assets/f3b8c5d5-601b-4df1-86ba-438d80162e8f)

2) After launching **DynDOLODx64** you will eventually be greeted with a screen that provides a series of options. Select the **-SSE = Skyrim SE, Skyrim AE or Enderal SE mod version** option and then press the **Start DynDOLOD** button (see image below).

![DynDOLOD Launch](https://github.com/user-attachments/assets/3437f8e3-e9c7-443a-b72f-7a3223451414)

3) When you reach the **DynDOLOD Expert** menu you'll see a lot of options to mess with so we'll go through this section-by-section to make sure this is done correctly. First thing you'll want to do is go to the list of worldspaces it can generate LODs for and tick all the boxes (see image below).
![All Regions](https://github.com/user-attachments/assets/6d127632-25da-4c9a-97cf-a9797a22e4b1)

4) Next you'll want to click the button labeled **High**, then tick the boxes next to **Candles** and **FXGlow** (see image below).
![High Settings](https://github.com/user-attachments/assets/68f822c0-0fe4-40b6-921b-a4e8c494c87a)

5) After that you will want to scroll to the bottom of the <ins>*Mesh and Reference rules*</ins> section and edit the ruleset for the last two items on the list to match my settings (see image below).
![Rules settings](https://github.com/user-attachments/assets/b269f1af-4e34-4923-8677-7020594ee11a)

6) Now we move on to the final step before processing, the <ins>*Options*</ins> section of the interface. Make sure your settings match mine and then press the **OK** button to start DynDOLOD generation (see image below).
![Options](https://github.com/user-attachments/assets/229def86-03e3-480f-b29d-0cc1bf878878)

7) When the process completes you will be prompted with several options. If you select **Save & Exit** you will simply cut-and-paste the generated *DynDOLOD_Output* folder, located under <ins>*Modding > MO2 > LOD Generation Tools > DynDOLOD*</ins>, and overwrite your existing *DynDOLOD_Output* folder. You can find it located under <ins>*Modding > MO2 > mods*</ins>. If you choose **Zip & Exit** simply install the mod via the created zip archive with *Mod Organizer 2* and choose the **Replace** option.

# Known Issues
- [ ] Issues with some of the crowd at Rogvir's execution not being able to get to their positions
- [ ] Navmesh-related crashes during the first dragon fight at the Whiterun Watchtower
- [ ] Various landscape seams in need of fixing
- [ ] Some minor navmesh tweaks required in small towns and villages
- [ ] Minor navmesh tweaks required in Ustengrav

# FAQs
- **Question:** I'm getting CTDs that point to HDT-SMP in the crash log. How do I fix this?
	- **Answer:** This is likely due to how *FSMP* is setup and installed by default with my lists. The default settings utilized **CUDA** and **AVX2**, which may not be supported by your *GPU* or *CPU*, and this results in crashes. To remedy this you'll need to reinstall *FSMP* and choose the appropriate options for your hardware.

- **Question:** My NPC's are bald or are suffering the black/brown-face bug! How do I fix this?
	- **Answer:** This is likely due to me messing up a patch somewhere. Submit a ticket on the Discord server reporting exactly which NPC it was and I'll look into fixing it.

- **Question:** Where do I go if I'm having issues or want to report a bug?
	- **Answer:** Go to my Discord and submit a ticket. I'll look into fixing whatever issues you're having or whatever bug you reported.

- **Question:** I added a mod to the list and now I'm getting constant CTD's. What do I do?
	- **Answer:** Sadly if you modify the list yourself what support I can offer is extremely limited, especially if it's a hard-incompatibility. But submit a ticket on Discord and if it's something I can help with I'll do what I can to remedy the issue.
