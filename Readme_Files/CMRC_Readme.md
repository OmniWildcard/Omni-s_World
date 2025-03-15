> [!Important]
> **This is the documentation for the list you just downloaded. If you choose not to read this you forfeit access to any support.**
# Welcome to the *Chaos Mage Randomized Challenge* Readme!
![CMRC Mod Page Thumbnail](https://github.com/user-attachments/assets/7fb163a8-03ac-44ef-b04d-5d221f45509d)

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
- At least 290GB of free space

## Download Links
- [Download v1.0.4.1](https://www.mediafire.com/file_premium/ju1ygib3lk0h4ba/Chaos_Mage_Randomized_Challenge.wabbajack/file) **[!] Latest Version**

# Introduction
This mod list runs off of the BFCO combat system which mixes modern and vanilla combat rather seamlessly. It was designed with a focus on immersion and overhauling the game in just about every aspect; all-the-while striking a balance between realism and game-like convenience. xLODGen and DynDOLOD 3 are included with this mod list; so be sure to run them again if you make any additions to the list that adds new worldspaces. Gameplay elements that aren't togglable via an ingame MCM are located under the Modular Gameplay section of the load order and can be toggled off without issue.

If any of the tools included are ever out-of-date I suggest manually updating them within MO2 to avoid messing with Skyrim's root directory. This is because Wabbajack installs require a clean Skyrim install to function. If you need help or want me to walk you through the process I'd be glad to help you on my Discord server. Simply submit a ticket and I'll get to you as soon as possible!

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

# Known Issues
- [x] Blue snow textures on various static landscape meshes | **Fixed as of v1.0.1.0**
- [ ] Issues with some of the crowd at Rogvir's execution not being able to get to their positions
- [ ] Navmesh-related crashes during the first dragon fight at the Whiterun Watchtower
- [ ] Various landscape seams in need of fixing
- [ ] Some minor navmesh tweaks required in small towns and villages
- [ ] Minor navmesh tweaks required in Ustengrav

# FAQs
- **Question:** I'm getting CTDs that point to HDT-SMP in the crash log. How do I fix this?
	- **Answer:** This is likely due to how *FSMP* is setup and installed by default with my lists. The default settings utilize **CUDA** and **AVX2**, which may not be supported by your *GPU* or *CPU*, and this results in crashes. To remedy this you'll need to reinstall *FSMP* and choose the appropriate options for your hardware.

- **Question:** My NPC's are bald or are suffering the black/brown-face bug! How do I fix this?
	- **Answer:** This is likely due to me messing up a patch somewhere. Submit a ticket on the Discord server reporting exactly which NPC it was and I'll look into fixing it.

- **Question:** Where do I go if I'm having issues or want to report a bug?
	- **Answer:** Go to my Discord and submit a ticket. I'll look into fixing whatever issues you're having or whatever bug you reported.

- **Question:** I added a mod to the list and now I'm getting constant CTD's. What do I do?
	- **Answer:** Sadly if you modify the list yourself what support I can offer is extremely limited, especially if it's a hard-incompatibility. But submit a ticket on Discord and if it's something I can help with I'll do what I can to remedy the issue.
