> [!Important]
> **This is the documentation for the list you just downloaded. If you choose not to read this you forfeit access to any support.**
# Welcome to the *Chaos Mage Randomized Challenge* Readme!
![CMRC Mod Page Thumbnail](https://github.com/user-attachments/assets/be34da4a-680b-4043-b529-50ef67f5e29d)

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
- At least 336 GB of free space

## Backup Download Links
- [Download v1.0.9.72]() **[!] Latest Version**

## Load Order Library
You can find the Load Order Library page [here](https://loadorderlibrary.com/lists/chaos-mage-randomized-challenge) at any time.

# Introduction
This mod list runs off of the BFCO combat system which mixes modern and vanilla combat rather seamlessly. It was designed with a focus on immersion and overhauling the game in just about every aspect; all-the-while striking a balance between realism and game-like convenience. xLODGen and DynDOLOD 3 are included with this mod list as of v1.0.4.2; so be sure to run them again if you make any additions to the list that adds new worldspaces. You can find instructions on how to generate new LODs and Grass Cache along with the exact settings I use down in the <ins>**How to Update LODs**</ins> and <ins>**How to Update Grass Cache**</ins> sections. Gameplay elements that aren't togglable via an ingame MCM are located under the Modular Gameplay section of the load order and can be toggled off without issue.

If any of the included tools are ever out-of-date I suggest manually updating them, while keeping them within their MO2 directories, to avoid messing with Skyrim's root directory. This is because Wabbajack installs require a clean Skyrim install to function. If you need help or want me to walk you through the process I'd be glad to help you on my Discord server. Simply submit a ticket and I'll get to you as soon as possible!

If you wanted to see the list in action you can visit my YouTube channel and watch the episodic series covering the challenge run this mod list is named after. I also have a Discord server where I offer support for the mod list and post updates for when I go live or post videos.

To join the Discord use the link below:
- https://discord.gg/rMZKDNrZQS

And to find my YouTube channel use the link below:
- https://www.youtube.com/channel/UC82BYjxRvHxzIQ519TrkzqQ

## What's the Challenge for this List?
I'm glad you asked, the challenge element is mostly handled outside of game and not via any mod-implementation allowing you to just use the list "as-is" or attempt the challenge I did yourself.

Want to try the challenge run for yourself? Then simply [spin the wheel](https://wheelofnames.com/) using the templates provided below and limit yourself to the results. You'll spin for a new school every ingame day at midnight. And your task for the day will be selected via its own wheel. Then set yourself an ultimate goal you must complete with this handicap and you've got your very own version of the run! The template follows my variation where I have to complete the entirety of the **College of Winterhold** with these handicaps, but you can change it out with whatever you wish.
- [School of Magic Wheel](https://www.mediafire.com/file_premium/x5b77bpov4v2vxo/School_of_Magic.wheel/file)
- [Daily Task Wheel](https://www.mediafire.com/file_premium/3gn5r0w7szzcwyk/Daily_Task.wheel/file)
- [Random Dungeon Wheel](https://www.mediafire.com/file_premium/psx97mryritzqoh/Random_Dungeon.wheel/file)
- [Random Side Quest Wheel](https://www.mediafire.com/file_premium/wsloj3p1k8db3l0/Random_Side_Quest.wheel/file)

Most of all I hope you enjoy the list! It is the product of a lot of hard work creating a functional base that all my challenge lists could be based off of. So I hope you appreciate the effort and custom patch work that went into its creation. With that said let's move on to the installation instructions!

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
    - Rigmor of Bruma - Misc Patches.esp
    - Save the Ice-Runner - Misc Patches.esp
    - Simple Children - Misc Patches.esp
    - Crows and Ravens - NotWL Patch.esp
    - LydiaRemake.esp
    - LydiaRemake HDT Improved Follower Dialogue - Lydia Patch.esp
    - CS_Melana+DLH Patch.esp
    - Lionheart Mjoll Overhaul - SMP Hair Patch.esp
    - Ciri Concept Art Armor - Consistency Tweak.esp
    - Remove Weapon Glows.esp
    - RaSeaSky - NO RAVEN SPAWNS - Patch.esp
    - Whiterun Terrain Fix.esp
    - Falkreath Terrain Fix.esp
    - Rift Terrain Fix.esp
    - Haafingar Terrain Fix.esp
    - Hjaalmarch Terrain Fix.esp
    - Pale Terrain Fix.esp
    - Winterhold Terrain Fix.esp
    - Eastmarch Terrain Fix.esp
    - Moss Mother Cavern Fix.esp
    - Shadowgreen Cavern Fix.esp
    - HPH - RM - Synthesis Patch.esp
    - RemoveInteriorFog.esp
    - DynDOLOD.esp
    - Occlusion.esp
    - Katla's Farm Windmill Fix.esp
    - IcePenguinWorldMap.esp

5) If you're unsure that the load order is correct you can download my custom ruleset for LOOT [here](https://www.mediafire.com/file_premium/w9li45ecb96wwx5/LOOT-backup-20250416T163251.zip/file) and extract its contents into your LOOT data folder. You'll find the LOOT data folder under <ins>*AppData > Local > LOOT*</ins> by default.

> [!Note]
> The following sections below are only for those who have modified the list. If you are playing the list as-is you can ignore these and go straight to the **Known Issues** section.

## How to Update Grass Cache
Updating the Grass Cache is a multi-step process that utilizes both SSEEdit and the Creation Kit. As such, I've separated them into their own subsections to keep things as simple as possible. 

> [!Note]
> **This guide will only show you how to update the existing Grass Bound Records to generate a new Grass Cache within the confines of this list. For a full guide on how to generate Grass Cache for your own lists I recommend Biggie_Boss's guide on YouTube.**

> [!Warning]
> **I advise generating the updated Grass Cache before generating new LODs, but you are free to disregard my suggestion at your own peril.**

### Updating the Grass Bound Records via SSEEdit
1) First, you'll want to ensure that the existing <ins>*Grass Cache*</ins> is disabled and the <ins>*Grass Bound Records</ins> are enabled; after which you will launch **SSEEdit** via *Mod Organizer 2* (see image below).
![Setting Things Up for SSEEdit](https://github.com/user-attachments/assets/1f273021-5b21-4468-9c6b-4f4e61e0c1ab)

2) After launching **SSEEdit** you will eventually reach the **Module Selection** screen. You will want to right-click, to open a drop down menu, then click <ins>*Select All*</ins> before finally clicking the **OK** button in the bottom-right.
![Module Selection Screen 1](https://github.com/user-attachments/assets/ac959d89-c536-452f-84e1-4312ed430b77)

3) After it builds the records you will be greeted with another screen asking you to make selections. You'll want to ensure that everything on this list is enabled before clicking the **OK** button in the bottom-right (see image below).
![Module Selection Screen 2](https://github.com/user-attachments/assets/a6b2dc69-3f67-49bd-89e9-888b186ebf32)

4) Next you will want to right-click anywhere in the left-most panel and click <ins>*Apply Script*</ins> (see image below).
![Apply Scripts 1](https://github.com/user-attachments/assets/979c4b24-f0e4-45d9-a763-471c964c99d1)

5) After this you will be brought to the **Apply Script** menu. Type "grass" into the **Filter** field and select the <ins>*List worldspaces with grass*</ins> script before finally clicking the **OK** button in the bottom-right (see image below).
![Apply Scripts 2](https://github.com/user-attachments/assets/e4bd1b43-4e7e-45b8-ba4c-5da9e0017fbd)

6) This will bring you to a second screen. Ignore the options it presents and simply click the **OK** button to continue (see image below).
![Apply Scripts 3](https://github.com/user-attachments/assets/f7867eee-7b82-49a2-9593-f329cafadf72)

7) Let the script run and it will eventually prompt you with another screen. You'll want to copy-and-paste the output into your **GrassControl.ini** file, located under <ins>*Modding > MO2 > mods > Grasscontrol.ini > SKSE > Plugins*</ins>, and place it within the quotations under the highlighted section. Only after all of this is done should you click the **OK** button to proceed (see images below).
![Apply Scripts 4](https://github.com/user-attachments/assets/61509eb1-48fd-4e0e-8afc-70166f3b4f12)
![Apply Scripts 5](https://github.com/user-attachments/assets/27b083dd-39b8-419f-9c87-250670924531)

8) Now you want to apply a filter to show only the areas with grass records. To do this right-click anywhere in the left-most panel and click *Apply Filter* (see image below).
![Apply Filter 1](https://github.com/user-attachments/assets/faa917d5-2338-4993-8cc2-07b7a5ce8a92)

9) This will open up another menu that will prompt you with a variety of options. Ensure that the <ins>*by Record Signature*</ins> box is ticked and that only the <ins>*GRAS - Grass*</ins> records are selected. Then click the **Filter** button to proceed to the next step (see image below).
![Apply Filter 2](https://github.com/user-attachments/assets/f77cddf0-3322-4591-89a9-565e70fd79ca)

10) Now you will notice that all of the areas with grass records are highlighted in various colors. This is because they are being overwritten by the overrides copied into the Grass Bound Records.esp file. If you added any new worldspaces via a mod that mod will not be highlighted as they are not yet copied into the Grass Bound Records.esp file. You will want to open up the records for that new mod and navigate into the Grass subsection. Then you will select all of the existing records within that subsection, right-click and select <ins>*Copy as override into...*</ins> from the drop-down menu (see image below).
![Copy as Override 1](https://github.com/user-attachments/assets/5aeac971-bfb5-4753-b615-38e9e8b3e048)

11) This will result in a prompt appearing asking if you're certain you want to edit the module file. Click the **Yes I'm absolutely sure** button to proceed (see image below).
![Copy as Override 2](https://github.com/user-attachments/assets/8a0d04be-6880-4a66-9c2d-28b47ad4b58c)

12) You will then be shown a list of modules you can copy the override into. Scroll to the bottom and select <ins>*Grass Bound Records.esp*</ins>, by ticking the box next to it, then click the **OK** button in the bottom-right (see image below).
![Copy as Override 3](https://github.com/user-attachments/assets/2f909719-5720-4895-9667-4619ee707abd)

13) Afterwards you will close SSEEdit and when it prompts you to save your changes you will click the **OK** button in the bottom-right of the prompt window.

### Recalculating Bounds via the Creation Kit
1) First we have to launch the included **Creation Kit** via *Mod Organizer 2*. Once you have done that click the little folder button in the top-right. This will open up another window which you will scroll to the bottom of, select <ins>*Grass Bound Records.esp*</ins> and then click the **Set as Active File** button. After this you can click the **OK** button to proceed to the next step (see image below).
![Creation Kit 1](https://github.com/user-attachments/assets/ad09fa0e-334f-41a4-a71a-75427dd571ed)

2) After it loads up all the files you will want to navigate to **WorldObjects** and select the **Grass** subsection. From there you will select all the grass, listed under the **Object Window**, right-click and select <ins>*Recalc Bounds*</ins> (see image below).
![Creation Kit 2](https://github.com/user-attachments/assets/6303d91c-8af0-45e3-a9ef-7cb1f8a0a249)

3) Once this is done you want to keep an eye on the **Log Window** that opens up when you launch the **Creation Kit**. Wait until it stops updating with new messages and then click the **Save** button in the upper-right corner of the **Creation Kit** window (see image below).
![Creation Kit 3](https://github.com/user-attachments/assets/5b2d735e-3461-4b4e-82f8-deda6b5d84f3)

### Generating the New Grass Cache
1) First, you want to disable several mods in the list as they can cause the Grass Cache to crash during generation or even prevent it from completing (see image below).
![Grass Cache Generation 1](https://github.com/user-attachments/assets/63f8cf67-a4e2-4390-b777-7f2dad483728)

2) Next you want to modify the SSEDisplayTweaks.ini file. You can find it located under <ins>*Modding > MO2 > mods > Mod List Patches, Bug Fixes & Overwrites > SKSE > Plugins*</ins>. You will want to edit the 66th line, remove the # symbol and save (see image below).
![Grass Cache Generation 2](https://github.com/user-attachments/assets/68757dac-623a-4e3f-9185-0257cc7f9e2b)

3) The last few things you'll want to do is ensure that <ins>*Grass Bound Records*</ins> and <ins>*Northern Roads - NGIO Patch*</ins> is enabled; then, finally, ensure that the existing <ins>*Grass Cache*</ins> is disabled before you begin the process of precaching the grass (see image below).
![Final Preparation for Precache Process](https://github.com/user-attachments/assets/0fbd35de-4146-4751-aa40-1f9916053b7f)

4) Now you want to return to MO2, click the icon that resembles a jigsaw puzzle to open a drop-down menu and select **Precache Grass** (see image below).
![Grass Cache Generation 3](https://github.com/user-attachments/assets/85a08648-bb57-4046-96de-3c10936be45e)

5) This process will take a while and the game might crash several times during it. Simply let the process run to completion. It will prompt you when it's done.

6) After the process is completed you want to re-enable the mods you previously disabled for the purposes of generating a grass cache. Then you will navigate to your overwrite folder, located under <ins>*Modding > MO2 > Overwrite*</ins>, select the generated **grass** folder and move it to your **Grass Cache** mod folder. You can find the **Grass Cache** mod folder located under <ins>*Modding > MO2 > mods > Grass Cache*</ins>.

7) Finally you will want to re-open the SSEDisplayTweaks.ini file and add the # symbol back to line 66 and disable <ins>*Grass Bound Records*</ins> and the <ins>*Northern Roads - NGIO Patch*</ins> (see images below).
![Grass Cache Generation 4](https://github.com/user-attachments/assets/22aae1a8-c9bd-41a5-8ad9-567d6c9c4c6c)
![Post-Precache Process Cleanup](https://github.com/user-attachments/assets/8e188486-a69e-471a-aab1-b7cd7d81f9bb)

## How to Update LODs
I use very specific settings when generating the LODs for these lists so, if you want to maintain the visual quality and consistency, I recommend following these instructions to the letter.

> [!Note]
> **For the sake of simplicity, the instructions are divided into subsections.**

> [!Warning]
> The <ins>**Katla's Farm Windmill Fix.esp**</ins> contains <ins>**DynDOLOD.esm**</ins> as a master and is a temporary workaround for a bug with DynDOLOD's output with the current DynDOLOD NG DLL. As such DynDOLOD will not allow you to generate new LODs while it is present so you must delete it before generating any new LODs. After generating the new LODs you will have to recreate the patch and edit the <ins>**Autorun.txt**</ins> file to use the new Reference ID. This process is detailed in the <ins>**Updating the Katla's Farm Windmill Fix**</ins> section.

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
1) First, you want to re-enable <ins>*Grass Bound Records*</ins> and launch **TexGenx64** (see image below).
![Ensure Grass Bound Records is On](https://github.com/user-attachments/assets/28a2eeda-64e9-4c06-a2e0-e2c3dc96fa87)

2) After launching TexGenx64 you will be greeted by a screen with a set of options. Select the **-SSE = Skyrim SE, Skyrim AE or Enderal SE mod version** option and then press the **Start TexGen** button (see image below).

![TexGen Launch](https://github.com/user-attachments/assets/e6e0ccf5-9e32-4b5d-84f9-fa62b0d4d33b)

3) Once you do so you will eventually reach the **TexGen Options** menu. Ensure your settings for <ins>*Stitched Object LOD Textures*</ins>, <ins>*Rendered Object LOD Textures*</ins> and <ins>*Tree/Grass LOD Billboards*</ins> match mine and then press the **Start** button at the bottom to begin processing (see image below).

![TexGen Options](https://github.com/user-attachments/assets/f750caa2-02ba-40ee-b0c3-f9b61b118557)

4) When the process completes you will be prompted with several options. If you select **Exit TexGen** you will simply cut-and-paste the generated *TexGen_Output* folder, located under <ins>*Modding > MO2 > LOD Generation Tools > DynDOLOD*</ins>, and overwrite your existing *TexGen_Output* folder. You can find it located under <ins>*Modding > MO2 > mods*</ins>. If you choose **Zip & Exit** simply install the mod via the created zip archive with *Mod Organizer 2* and choose the **Replace** option.

5) Finally, ensure that <ins>*Grass Bound Records*</ins> is disabled once more before proceeding to the next step. 
![Ensure Grass Bound Records is Off](https://github.com/user-attachments/assets/bcb1f491-39d1-4bcc-a5f6-431330c29cb6)

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
> [!Note]
> If you get any warnings from **DynDOLOD** about *BSXFlags* during processing it is safe to ignore them. It's intentional and caused by the **Remove Small Rocks** mod that removes the small pebbles placed by the vanilla game.

## Updating the Katla's Farm Windmill Fix
This process is very simple if you know your way around xEdit but, for those who are uninitiated with the software, I've attempted to explain the process as clearly and in as much detail as possible.
> [!Warning]
> I strongly advise you to not deviate from these instructions, but you are free to ignore my suggestion at your own peril.

### Loading up SSEEdit and the Records
1) First you'll want to load up **SSEEdit** via *Mod Organizer 2* (see image below).
![Launch SSEEdit](https://github.com/user-attachments/assets/75b576c8-6fe7-48ae-bf92-838950663e40)

2) After launching **SSEEdit** you will eventually reach the **Module Selection** screen. Simply click the **OK** button in the bottom-right to proceed (see image below).
![Module Selection Screen 1](https://github.com/user-attachments/assets/5a6c3809-0719-4254-b7e2-bb2089713a42)

3) After it builds the records you will be greeted with another screen asking you to make selections. You'll want to ensure that everything on this list is enabled before clicking the **OK** button in the bottom-right (see image below).
![Module Selection Screen 2](https://github.com/user-attachments/assets/a6b2dc69-3f67-49bd-89e9-888b186ebf32)

### Locating the Offending Record
1) Now you'll want to scroll down to **DynDOLOD.esp** and expand it by clicking the little plus sign next to it. Afterwards you'll want to navigate to <ins>*Worldspace > 0000003C > 00000D74 Cell > Persistent*</ins> (see image below).
![Expand DynDOLOD in SSEEdit](https://github.com/user-attachments/assets/4a32af8d-8711-44ce-a052-5e663b534b78)

2) After that you will want to scroll down until you come across the record labeled *skyrimesm_5c854_Tamriel_DynDOLOD_PATCH_DynDOLOD_REFERENCE* (see image below).
![Locating the Offending Record](https://github.com/user-attachments/assets/8544bf46-ac27-46c1-905a-9a38640f28f1)

### Patching the Offending Record
1) Upon locating this record you will want to right-click it and select <ins>*Copy as override into....*</ins> (see image below).
![Copy as override](https://github.com/user-attachments/assets/20af6b40-93ca-4e69-9156-da45c57fe3a3)

2) This will bring up a prompt asking if you wish to edit the records. Simply click the button that says <ins>*Yes I'm absolutely sure*</ins> (see image below).
![Confirmation that you want to make edits](https://github.com/user-attachments/assets/418e13db-b0a6-4da8-aafd-c5ef80fc3d9e)

3) This will then bring up an interface where you can select the kind of module you want to copy the override into. Select the option seen in the image below and click **OK** (see image below).
![Choose to create an ESPFE file](https://github.com/user-attachments/assets/88e34d45-ecc5-4436-ba55-56589308bd49)

4) Then name the file <ins>*Katla's Farm Windmill Fix*</ins> and click the **OK** button to proceed (see image below).
![Name the ESPFE file and confirm](https://github.com/user-attachments/assets/0ad26656-b3d5-418e-a831-6b91786e0666)

5) Now you will want to change the Position and Rotation data to the following values and write down the **Reference ID** for later use (see image below).
	- Position X = -74437.226562
	- Position Y = 95534.609375
 	- Position Z = -10847.258789
  	- Rotation X = 359.9578
   	- Rotation Y = 2.8278
  	- Rotation Z = 10.0000

![Change the Position and Rotation Values](https://github.com/user-attachments/assets/e9d8bca3-7701-47c6-b258-a3d6be82460b)

6) Afterwards, before you close down **SSEEdit** and save the changes you made, you'll want to navigate to the Record Header section and ensure the <ins>*No Respawn*</ins> flag is not enabled (see image below).
![Disable the No Respawn Flag](https://github.com/user-attachments/assets/93cd89a6-9af0-487d-a9e1-8336ce450616)

### Updating the Reference ID in the Autorun.txt File
1) We're almost done with this part of the process. Now once you've closed down **SSEEdit** you'll want to find the mod titled **Autorun** within the mod list, right-click it and select <ins>*Information*</ins> (see image below).
![Navigate to Autorun's Information Panel](https://github.com/user-attachments/assets/04bd9d18-c3ce-45db-b874-249ea0150be2)

2) Once you've opened up this interface navigate to either the **Conflicts** tab or the **File Tree** tab, right-click the Autorun.txt entry and select <ins>*Open*</ins> (see image below).
![Open up Autorun text file](https://github.com/user-attachments/assets/a7f615e4-307f-4f78-8dad-3b2a992d15ed)

3) Next you'll want to change the **Reference ID** located on the first line of the text file to the one you wrote down earlier and save your changes (see image below).
![Edit the Autorun Text File](https://github.com/user-attachments/assets/8ae9811d-1e92-44cf-9934-d063fce80908)

4) Finally you'll want to move the *Katla's Farm Windmill Fix.esp* file from the **Overwrite** folder located under <ins>*Modding > MO2*</ins> to the **Mod List Patches, Bug Fixes & Overwrites** folder located under <ins>*Modding > MO2 > mods*</ins>. 

## Grabbing the Reference ID for the Bugged Lumber Mill Water Wheels
This process is very simple if you know your way around xEdit but, for those who are uninitiated with the software, I've attempted to explain the process as clearly and in as much detail as possible.
> [!Warning]
> I strongly advise you to not deviate from these instructions, but you are free to ignore my suggestion at your own peril.

### Loading up SSEEdit and the Records
1) First you want to load up **SSEEdit** (see image below).
![Launch SSEEdit](https://github.com/user-attachments/assets/98f648a3-ee15-4a86-a2df-73fcf3b90c00)

2) After launching **SSEEdit** you will eventually reach the **Module Selection** screen. Simply click the **OK** button in the bottom-right to proceed (see image below).
![Module Selection Screen 1](https://github.com/user-attachments/assets/5a6c3809-0719-4254-b7e2-bb2089713a42)

3) After it builds the records you will be greeted with another screen asking you to make selections. You'll want to ensure that everything on this list is enabled before clicking the **OK** button in the bottom-right (see image below).
![Module Selection Screen 2](https://github.com/user-attachments/assets/a6b2dc69-3f67-49bd-89e9-888b186ebf32)

### Locating the Offending Records
1) Next you'll want to scroll down to **DynDOLOD.esp** and expand it by clicking the little plus sign next to it. Afterwards you'll want to navigate to <ins>*Worldspace > 0000003C > 00000D74 Cell > Persistent*</ins> (see image below).
![Expand DynDOLOD in SSEEdit](https://github.com/user-attachments/assets/d7c6e979-2b70-4dbf-9ee0-fcbf1cc51cf5)

2) Afterwards you want to sort records by name and scroll down until you locate the entries for *FarmLumbermill01WaterWheel01_DynDOLOD_BASERECORD* and write down the **Reference IDs** for later use (see image below).
![DynDOLOD Workaround Instructions 1](https://github.com/user-attachments/assets/fcae2988-471c-441b-8b75-9845110cface)

### Patching the Offending Records
1) Upon locating these records you'll want to select all of them, right-click and select <ins>*Copy as override into....*</ins> (see image below).
![DynDOLOD Workaround Instructions 2](https://github.com/user-attachments/assets/31f0d1a2-5706-412a-9298-55eaefc2bb66)

2) This will bring up a prompt asking if you wish to edit the records. Simply click the button that says <ins>*Yes I'm absolutely sure*</ins> (see image below).
![DynDOLOD Workaround Instructions 3](https://github.com/user-attachments/assets/d18c2330-7fd4-488b-b8de-69b4f4155269)

3) This will then bring up an interface where you can select the kind of module you want to copy the override into. Select the option seen in the image below and click **OK** (see image below).
![DynDOLOD Workaround Instructions 4](https://github.com/user-attachments/assets/1bebbb31-a450-4314-9e2a-243af22c69f1)

4) Then name the file <ins>*Skyrim Water Wheels Fix*</ins> and click the **OK** button to proceed (see image below).
![DynDOLOD Workaround Instructions 5](https://github.com/user-attachments/assets/7baa9a50-cfae-477c-9893-060a4236c4cb)

5) Now you will want to ensure the <ins>*No Respawn*</ins> flag is disabled for each of the overriding records (see image below).
![DynDOLOD Workaround Instructions 6](https://github.com/user-attachments/assets/ef13ac64-551a-4abf-8975-017bb93900b8)

6) We're almost done with our manual patching. Now that you've written down the required **Reference IDs** and patched the offending records you can close down **SSEEdit**.

### Updating the Reference IDs in the Autorun.txt File
1) Now you'll want to find the mod titled **Autorun** within the mod list, right-click it and select <ins>*Information*</ins> (see image below).
![Navigate to Autorun's Information Panel](https://github.com/user-attachments/assets/04bd9d18-c3ce-45db-b874-249ea0150be2)

2) Once you've opened up this interface navigate to either the **Conflicts** tab or the **File Tree** tab, right-click the Autorun.txt entry and select <ins>*Open*</ins> (see image below).
![Open up Autorun text file](https://github.com/user-attachments/assets/a7f615e4-307f-4f78-8dad-3b2a992d15ed)

3) Finally you'll want to change the relevant **Reference IDs**, change them to the ones you wrote down earlier and save the changes (see image below).
![DynDOLOD Workaround Instructions 7](https://github.com/user-attachments/assets/f0d2d1e1-9969-4d6e-8a62-4432c94e9d85)

## Conclusion
With that all dealt with you've completed the process of generating a new Grass Cache and updated the LODs to include your new worldspaces; you've also recreated the patch for DynDOLOD. Now, all that's left to do is play the game. So go ahead, have fun, and enjoy!
![VaultBoySkyrim -50](https://github.com/user-attachments/assets/0c1c9ce0-003b-4b36-bda1-6bc0a037d223)

# Known Issues
- [x] Blue snow textures on various static landscape meshes | **Fixed as of v1.0.1.0**
- [x] DynDOLOD issue with the Windmill on Katla's Farm | Temporarily Remedied by an Override
- [x] DynDOLOD issue with Water Wheels and the Heartwood Lumber Mill | Temporarily Remedied by Autorun
- [ ] Issues with some of the crowd at Rogvir's execution not being able to get to their positions
- [ ] Navmesh-related crashes during the first dragon fight at the Whiterun Watchtower
- [ ] Some minor navmesh tweaks required in small towns and villages
- [ ] Minor navmesh tweaks required in Ustengrav

# FAQs
- **Question:** I'm stuck on the Rigmor of Bruma questline. What do I do?
	- **Answer:** With the current version of Rigmor of Bruma it doesn't function flawlessly within the confines of the list. This will eventually be altered in a later update so if you want to play Rigmor of Bruma as it will eventually be intended in the list make sure you've completed the first six main story quests before you begin. This will resolve any issues you should have with progression.

- **Question:** I'm getting CTDs that point to HDT-SMP in the crash log. How do I fix this?
	- **Answer:** This is likely due to how *FSMP* is setup and installed by default with my lists. The default settings utilize **CUDA** and **AVX2**, which may not be supported by your *GPU* or *CPU*, and this results in crashes. To remedy this you'll need to reinstall *FSMP* and choose the appropriate options for your hardware.

- **Question:** My NPC's are bald or are suffering the black/brown-face bug! How do I fix this?
	- **Answer:** This is likely due to me messing up a patch somewhere. Submit a ticket on the Discord server reporting exactly which NPC it was and I'll look into fixing it.

- **Question:** Where do I go if I'm having issues or want to report a bug?
	- **Answer:** Go to my Discord and submit a ticket. I'll look into fixing whatever issues you're having or whatever bug you reported.

- **Question:** I added a mod to the list and now I'm getting constant CTD's. What do I do?
	- **Answer:** Sadly if you modify the list yourself what support I can offer is extremely limited, especially if it's a hard-incompatibility. But submit a ticket on Discord and if it's something I can help with I'll do what I can to remedy the issue.
