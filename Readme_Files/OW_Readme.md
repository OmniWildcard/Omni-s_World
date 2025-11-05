> [!Important]
> **This is the documentation for the list you just downloaded. If you choose not to read this you forfeit access to any support.**
# Welcome to the *Omni's World* Readme!
<img width="1920" height="1080" alt="Omni&#39;s World Mod Page Thumbnail" src="https://github.com/user-attachments/assets/6983a8e2-03be-40bc-9cf5-261ed71868ec" />

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
- 11th Gen Intel(R) Core(TM) i9-11900k equivalent CPU or later CPU models (AVX1 Support is a Hard-Requirement)
- NVIDIA GeForce RTX 4070 Ti or AMD equivalent (Older GPUs might work but I can't guarantee decent performance)
- 64 GB RAM
- 40 GB Pagefile
- At least 550 GB of free space

## Backup Download Links
TEMPORARILY UNAVAILABLE

# Introduction
This mod list runs off of the BFCO combat system which mixes modern and vanilla combat rather seamlessly. It was designed with a focus on immersion and overhauling the game in just about every aspect; all-the-while striking a balance between realism and game-like convenience. xLODGen and DynDOLOD 3 are included with this mod list; so be sure to run them again if you make any additions to the list that adds new worldspaces. You can find instructions on how to generate new LODs and Grass Cache along with the exact settings I use down in the **How to Update LODs** and **How to Update Grass Cache** sections. Gameplay elements that aren't togglable via an ingame MCM are located under the Modular Gameplay section of the load order and can be toggled off without issue. The Combat Pathing Revolution (CPR) - Patching Tool, HKAnnotation tool and MCO-BFCO converter tool are included. So, if you add any new animations, ensure you convert all animations to BFCO's format and annotations. You'll also want to update the equip and unequip animations using this tool to add the CPR annotations to the files. Without these CPR annotations, CPR breaks and stops working entirely; so it's important that any new animations, that aren't vanilla replacers, are properly patched to work with the system. If you need a guide on how to go about this process you can find a guide under the <ins>**How to Install and Prepare the HK Annotation Tools**</ins> and <ins>**How to Update Animations**</ins> sections.

If any of the included tools are ever out-of-date I suggest manually updating them, while keeping them within their MO2 directories, to avoid messing with Skyrim's root directory. This is because Wabbajack installs require a clean Skyrim install to function. If you need help or want me to walk you through the process I'd be glad to help you on my Discord server. Simply submit a ticket and I'll get to you as soon as possible!

If you wanted to see the list in action you can visit my Twitch channel when I'm live or watch the VODs when they're uploaded to my YouTube channel every Wednesday. I also have a Discord server where I offer support for the mod list and post updates for when I go live, post videos or release updates to my various mod lists.

To join the Discord use the link below:
- https://discord.gg/rMZKDNrZQS

To find my Twitch channel use the link below:
- https://twitch.tv/omnithestarspawn

And to find my YouTube channel use the link below:
- https://www.youtube.com/channel/UC82BYjxRvHxzIQ519TrkzqQ

## What are the Controls?
<img width="1920" height="1080" alt="keyboard+mouse-control-layout" src="https://github.com/user-attachments/assets/38fb5b36-9a8c-4822-9081-9cfcd6cac85b" />
Eventually this will be viewable ingame via a Hotkey but for now I advise you save this image somewhere and view it on a second monitor until you get used to the controls.

# Post-Install Instructions
Now, before playing, you should do the following things:

1) Join the [Improved Camera Discord Server](https://discord.gg/improved-camera-se-1074109591966732328) and download the latest version of the v2.0 beta build from their updates channel. Install it over the included Improved Camera SE version and ensure all old files from the included Improved Camera are removed.

2) Open the *ImprovedCameraSE.json* file located under <ins>*Modding > MO2 > mods > ImprovedCameraSE > skse > plugins > ImprovedCameraSE*</ins> and edit the 24th line. You'll want to change **"Default"** to **"NoHeadbob"** while being sure to enter the text in bold exactly as it appears in this Readme. Afterwards save the changes.

3) Now you want to open the Profiles folder located in the same directory and edit the *NoHeadbob.json* file with a text editor. Change the entry **"fCombatDistance": 7.0,** to **"fCombatDistance": 2.0,** while being sure to enter the text in bold exactly as it appears in this Readme. Afterwards save the changes.

4) If you're unsure that the load order is correct you can download my custom ruleset for LOOT [here](https://www.mediafire.com/file_premium/29ostwq99m01l2t/LOOT-backup-20251103T153741.zip/file) and extract its contents into your LOOT data folder. You'll find the LOOT data folder under <ins>*AppData > Local > LOOT*</ins> by default. Simply extract the ruleset there and run LOOT for automated sorting.

> [!Note]
> The following sections below are only for those who have modified the list. If you are playing the list as-is you can ignore these and go straight to the **Known Issues** section.

## How to Install and Prepare the HK Annotation Tools
1) Navigate to the *hkanno64-001* folder located under <ins>*Modding > MO2 > Patching Tools*</ins>. 

2) Acquire and install the neccessary prerequisites by following the instructions in the Readme file located within the folder.

3) Copy the **win32.hko** file from the *hkanno64-001* folder into the *mco to bfco converter-119926-1-2-2-1735788590* folder located under <ins>*Modding > MO2 > Patching Tools*</ins>.
> [!Note]
> You can now update the annotations of MCO animations to the BFCO annotations using the converter.

## How to Update Animations
1) First you'll want to launch the **MCO to BFCO Converter** via *Mod Organizer 2*.

2) Next you'll want to select the target folder which contains the animations you want updated. Click the **Select Folder** button and navigate to the specific Animation Mod folder in your MO2 directory that you wish to patch. For the purposes of this example we'll navigate to <ins>*Modding > MO2 > mods > ADXP I MCO MGRR Greatsword Moveset for NPC > meshes > actors > character > animations > Open Animation Replacer > GreatSwordNPC2*</ins> and confirm our selection.

3) Now press the **Run** button followed by the **Update Annotation** button and wait for it to finish.

4) You can now exit out of the MCO to BFCO Converter.

5) Now you want to launch the **CPR Patcher Tool** via *Mod Organizer 2*.

6) You'll want to select the equip, unequip animation and SCAR Dummy files located under <ins>*Modding > MO2 > mods > ADXP I MCO MGRR Greatsword Moveset for NPC > meshes > actors > character > animations > Open Animation Replacer > GreatSwordNPC2 > Basic*</ins> and press the **Continue** button.

7) You will now match the settings from the image below to fill out the input fields in the UI that appears (see image below).
<img width="635" height="589" alt="CPR Patcher Settings" src="https://github.com/user-attachments/assets/ea1d602a-8619-4a82-bac6-03535654b2e6" />

8) Once you have filled out all the input fields you will click the **Start Patching** button and wait for it to complete.

9) You may now exit the **CPR Patcher Tool**

10) Run **Nemesis** via *Mod Organizer 2* and click both the **Update Engine** and **Launch Nemesis Behavior Engine** buttons.
   
11) Once they've both run to completion you may exit **Nemesis**.

12) You have now finished updating an animation set to work with this list. Congratulations! Now get out there and start playing; that is unless you need to update the LODs and Grass Cache. In that case please continue to the next section.

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

7) Finally you will want to re-open the SSEDisplayTweaks.ini file and add the # symbol back to line 66, disable <ins>*Grass Bound Records*</ins>, disable the <ins>*Northern Roads - NGIO Patch*</ins> and re-enable the mods you disabled in step 1 (see images below).
![Grass Cache Generation 4](https://github.com/user-attachments/assets/22aae1a8-c9bd-41a5-8ad9-567d6c9c4c6c)
![Post-Precache Process Cleanup](https://github.com/user-attachments/assets/8e188486-a69e-471a-aab1-b7cd7d81f9bb)

## How to Update LODs
I use very specific settings when generating the LODs for these lists so, if you want to maintain the visual quality and consistency, I recommend following these instructions to the letter.

> [!Note]
> **For the sake of simplicity, the instructions are divided into subsections.**

### Updating the SSELODGen_Ouput
1) First, you want to launch **SSELODGenx64**.

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
![Options](https://github.com/user-attachments/assets/6e3877dc-ca42-4b29-892f-dc2af3dbad73)

7) When the process completes you will be prompted with several options. If you select **Save & Exit** you will simply cut-and-paste the generated *DynDOLOD_Output* folder, located under <ins>*Modding > MO2 > LOD Generation Tools > DynDOLOD*</ins>, and overwrite your existing *DynDOLOD_Output* folder. You can find it located under <ins>*Modding > MO2 > mods*</ins>. If you choose **Zip & Exit** simply install the mod via the created zip archive with *Mod Organizer 2* and choose the **Replace** option.
> [!Note]
> If you get any warnings from **DynDOLOD** about *BSXFlags* during processing it is safe to ignore them. It's intentional and caused by the **Remove Small Rocks** mod that removes the small pebbles placed by the vanilla game.

### Updating Autorun.txt Records
1) First you want to launch **SSEEdit**.

2) Upon loading it will bring up a module selection screen. Simply click the **OK** button in the lower-right of the window to proceed (see image below).
![Module Selection Screen 1](https://github.com/user-attachments/assets/09dea140-7180-4820-bf4d-11340e6a365d)

3) Eventually it will bring up a mod group selection screen. Ensure all boxes are ticked and click the **OK** button in the lower-right to proceed (see image below).
![Module Selection Screen 2](https://github.com/user-attachments/assets/7d1dc420-39e4-4be9-99cd-4e53360ab6c9)

4) Now you want to navigate down to the bottom of the list and find DynDOLOD.esp. Expand the section by pressing the box with a + symbol in it and then further expand it until you reach the section in the provided screenshot (see image below).
![Expand DynDOLOD in SSEEdit](https://github.com/user-attachments/assets/8e3001a0-f0d3-4874-9e31-87723cdd70a3)

5) Now scroll down through the entries until you reach the entry shown in the provided screenshot and record the **Reference ID** for later use (see image below).
![Locating the Offending Record](https://github.com/user-attachments/assets/e182e3ad-4f6a-4442-8827-841960f2f807)

6) Next you want to sort entries by name and locate the entries shown in the provided screenshot and record their **Reference IDs** for later use (see image below).
![DynDOLOD Workaround Instructions 1](https://github.com/user-attachments/assets/73211325-0a2f-4265-96b9-ba29898d5b20)

7) Afterwards you will open up the **Autorun.txt** file located under <ins>*MO2 > mods > Autorun*</ins>. Change the entry specified in the provided screenshot to the Reference ID you recorded in step 5 (see image below).
![Edit the Autorun Text File](https://github.com/user-attachments/assets/51efc5ec-1ad6-4cae-b417-c483a13ed234)

8) Finally you will update the entries specified in the provided screenshot to the Reference IDs recorded in step 6 (see image below).
![DynDOLOD Workaround Instructions 7](https://github.com/user-attachments/assets/078d1e62-68a6-485a-b447-0d25278058f3)

9) Afterwards simply save the changes and close the window.

## Conclusion
With that all dealt with you've completed the process of generating a new Grass Cache, updated the LODs to include your new worldspaces and updated the precautionary Autorun records to the new IDs. Now, all that's left to do is play the game. So go ahead, have fun, and enjoy!
![VaultBoySkyrim -50](https://github.com/user-attachments/assets/0c1c9ce0-003b-4b36-bda1-6bc0a037d223)

# Known Issues
- [ ] Issues with some of the crowd at Rogvir's execution not being able to get to their positions
- [ ] Some minor navmesh tweaks required in small towns and villages
- [ ] Minor navmesh tweaks required in Ustengrav

# FAQs
- **Question:** I'm stuck on the Rigmor of Bruma questline. What do I do?
	- **Answer:** With the current version of Rigmor of Bruma it doesn't function flawlessly within the confines of the list. This will eventually be altered in a later update so if you want to play Rigmor of Bruma as it will eventually be intended in the list make sure you've completed Unbound and been told to go to the Jarl of Whiterun before talking to Rose.

- **Question:** My NPC's are bald or are suffering the black/brown-face bug! How do I fix this?
	- **Answer:** This is likely due to me messing up a patch somewhere. Submit a ticket on the Discord server reporting exactly which NPC it was and I'll look into fixing it.

- **Question:** Where do I go if I'm having issues or want to report a bug?
	- **Answer:** Go to my Discord and submit a ticket. I'll look into fixing whatever issues you're having or whatever bug you reported.

- **Question:** I added a mod to the list and now I'm getting constant CTD's. What do I do?
	- **Answer:** Sadly if you modify the list yourself what support I can offer is extremely limited, especially if it's a hard-incompatibility. But submit a ticket on Discord and if it's something I can help with I'll do what I can to remedy the issue.
