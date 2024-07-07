Guide for getting Skyrim SE 1.6.117 set up for Skyrim Together from scratch, with a few adjustments. The provided guide is very well documented, but I want to specify that using MO2 is much easier, and add a few mods to make it more fun and hopefully not crash.

1. Install the prerequisites listed in [Skyrim Together Reborn - client setup](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup)
2. While that is downloading, [install & set up Mod Organizer 2 (MO2) following this guide.](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/installing-modorganizer2/installating-the-mod-manager).
3. [Address Library for SKSE](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/utilities) is a required mod. Install that also using MO2.
4. Disable Creation Club and Anniversary Upgrade according to the instructions in the guide.
5. [Install & test Skyrim Together.](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/skyrim-together-reborn)\. Play through the Helgen quest, exit the cave, then save. Test connection by opening a server on [playtogether.gg](https:/playtogether.gg) as described in [Third-party server hosting in the Overview of Server setup](https://wiki.tiltedphoques.com/tilted-online/guides/server-guide). Press `F2` or `leftCtrl` to bring up the UI. \


Upon completing the "Using Mod Organizer" section and installing Skyrim Together in the guide and connecting to a test server, we should be able to play.

# make sure to read the [playguide.](https://wiki.tiltedphoques.com/tilted-online/general-information/playguide)

## Additional mods
Enhance gameplay, quality of life, and character creation.\
Always check the prerequisites when installing mods, or they will not work.\
I am avoiding mods that have a .ESP file (plugin) attached, as it is more likely something may break in the game. Graphics mods without plugins will generally work fine. 
1. [SKSE64](https://www.nexusmods.com/skyrimspecialedition/mods/30379?tab=files) - Script extender, necessary for many mods. See installation instructions on mod page.
2. [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604)
3. [Racemenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080)
> **_NOTE:_** As with most body/face changes, make sure you utilize "showracemenu" and adjust your character to your liking right before joining the server, then save your game. This will ensure you look exactly how you want and going into the server doesn't change you. If there any issues regarding your character hair changing, make sure you are using "showracemenu" once getting past Helgen or finish alternate start, save your character, THEN be the first to join the connecting server. Others must do the same. If you try to make said changes while on a live server, it will not reflect correctly. Edit: This is intentional. ST does not update racemenu changes while live. (also for KS Hairdos) [Source:](https://github.com/tiltedphoques/Mod-Compatibility/issues/34)
4. [High Poly Vanilla Hair](https://www.nexusmods.com/skyrimspecialedition/mods/41863), [Vanilla Hair - Salt and Wind](https://www.nexusmods.com/skyrimspecialedition/mods/45147) (As these two are pluginless, they can be enabled/disabled easily)
5. Additional hairs: [KS Hairdos](https://www.nexusmods.com/skyrimspecialedition/mods/6817) and [Salt and Wind](https://www.nexusmods.com/skyrimspecialedition/mods/16582?tab=files) for better hair textures.
6. Skin mods: Personally, I use snd greatly prefer [Skysight Skins](https://www.nexusmods.com/skyrimspecialedition/mods/6580) for male, [Mature Skin 2](https://www.nexusmods.com/skyrimspecialedition/mods/26017?tab=description) for female. (Actually I overwrite it with skin textures from [Real Girls CBBE](https://www.nexusmods.com/skyrimspecialedition/mods/75065), but this texture is not compatible with unmodded bodies.) Choose vanilla options.\
   Tempered Skin for [male](https://www.nexusmods.com/skyrimspecialedition/mods/7902) and [female (NSFW)](https://www.nexusmods.com/skyrimspecialedition/mods/8505) characters is also a good choice for wide compatibility. Select Vanilla option.
   Supposedly body replacers HIMBO and CBBE work, but that can wait. maybe SoS works too lol.
6. MOST IMPORTANT TEST BEFORE COMMITTING: 
[Alternate Start - Live Another Life](https://www.nexusmods.com/skyrimspecialedition/mods/272) Skips super long Helgen intro.\
Prerequisite is [USSEP Patch 7](https://www.nexusmods.com/skyrimspecialedition/mods/266?tab=files&file_id=209150). Use this version only, do not download newer version of USSEP. [Comment source](https://github.com/tiltedphoques/Mod-Compatibility/issues/7#issuecomment-1185771114))]\
> [Setup notes](https://github.com/tiltedphoques/Mod-Compatibility/issues/8):
Test 1: **Both players choose their starting point. Lead player sleeps in bed. BOTH teleport to designated area.** Preferably guest at an inn in Sleeping Giant (Riverwood) for uniformity. To teleport, type `coc Riverwood` \
If that doesn't work, Test 2: Break out of prison together.\

> **The plugin list should now look like:** \
Unofficial Skyrim Special Edition Patch.esp\
SkyUI_SE.esp\
RaceMenu.esp\
RaceMenuPlugin.esp\
SkyrimTogether.esp\
KS Hairdo's.esp\
iHUD.esp\
Alternate Start - Live Another Life.esp

## Mods with plugins that might be OK, check that everyone is running the same ones before starting a game

Can download these but don't enable them in MO2.[Mod compatibility report list](https://github.com/tiltedphoques/Mod-Compatibility/issues?page=2&q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc)\
After this works, we can see if we can get other mods in this section running.

1. [Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/17230](https://www.nexusmods.com/skyrimspecialedition/mods/24791?tab=description)) - [Comments](https://github.com/tiltedphoques/Mod-Compatibility/issues/167)
2. [Cathedral Landscapes](https://www.nexusmods.com/skyrimspecialedition/mods/17230](https://www.nexusmods.com/skyrimspecialedition/mods/21954?tab=description) - [Comments](https://github.com/tiltedphoques/Mod-Compatibility/issues/168) - Depends on Cathedral Weathers
3. [Immersive HUD](https://www.nexusmods.com/skyrimspecialedition/mods/12440) - Hides HUD :) Apparently no issues?
4. [The Eyes of Beauty](https://www.nexusmods.com/skyrimspecialedition/mods/16185) - Maybe can install this, but disable the plugin... 
5. [Beast Horns Hair Brows](https://www.nexusmods.com/skyrimspecialedition/mods/38480) - Beast race character creation and NPC replacer and additions. Needs USSEP. [Additional instructions must be followed. (Comments)](https://github.com/tiltedphoques/Mod-Compatibility/issues/26)



## Pluginless retexture mods that ought to work just fine
As long as there is no plugin, texture and mesh mods might work fine. In the folder of the mod, there should be no .esp or .esl file. Feel free to install these, hopefully they will work. Will make a list because there are many.
1. Skyrim 2018 and Skyrim 202x by Pfuscher (big download)
2. Fluffy Snow
3. aMidianBorn Caves and Mines
4. Ruins Clutter Improved
5. Rustic Amulets, Rustic Azura's Star, Rustic Clothing, Rustic Cooking, Rustic Furniture, Rustic Daedra SSE, Rustic Elderscoll
6. Peltapalooza, Rugnarok
7. JS Dragon Claw, JS Circlet, JS Common Cages, JS Dragon Claws, JS Dwemer Artifcats, JS Dwemer Control Cube, JS Dwemer Ichor, DJS Dwemer Kitchenware, JS Dwemer Puzzle Cube, JS Lockpicking UI, JS Shrines of the Divines, 
8. For the brave & who know what they are doing[Latest ENB binaries](http://enbdev.com/mod_tesskyrimse_v0502.htm) (scroll down to download) and [ENB]() if your PC can handle it.


## Sorry, can't use these
1. [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223) (alternate start mod) can be used to bypass the Helgen intro quest and connect to a server. Leave the realm and enter a city in Skyrim, then press `~` and enter the console command  `completequest mq101` to mark Unbound as finished. Then connect to the server as described by pressing `F2`.
> **_NOTE:_** [Source](https://github.com/tiltedphoques/Mod-Compatibility/issues/78): The mod currently is bugged for female player characters, which are shown to other players with female face but male body. Wouldn't recommend players joining until each have fully made their character. Meaning chosen their armor, weapons, standing stone etc. The reasoning is because in my save, when a player would choose a standing stone is would give it to all players. Making choosing a stone individually impossible. The spell that teleports you back to the hub world will teleport all other players as well. Also, I didn't test it, but I wouldn't recommend choosing options that make you apart of certain factions. 
