Guide for getting Skyrim SE 1.6.117 set up for Skyrim Together from scratch, with a few adjustments. The provided guide is very well documented, but I want to specify that using MO2 is much easier, and add a few mods to make it more fun and hopefully not crash.

1. Install the prerequisites listed in [Skyrim Together Reborn - client setup](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup)
2. While that is downloading, [install & set up Mod Organizer 2 (MO2) following this guide.](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/installing-modorganizer2/installating-the-mod-manager).
3. [Address Library for SKSE](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/utilities) is a required mod. Install that also using MO2.
4. Disable Creation Club and Anniversary Upgrade according to the instructions in the guide.
5. [Install & test Skyrim Together.](https://wiki.tiltedphoques.com/tilted-online/guides/client-setup/using-modorganizer2-mo2/skyrim-together-reborn)\. Play through the Helgen quest, exit the cave, then save. Test connection by opening a server on [playtogether.gg](https:/playtogether.gg) as described in [Third-party server hosting in the Overview of Server setup](https://wiki.tiltedphoques.com/tilted-online/guides/server-guide). Press `F2` or `leftCtrl` to bring up the UI. \
Alternate Start: [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223) can be used to bypass the Helgen intro quest and connect to a server. Leave the realm and enter a city in Skyrim, then press `~` and enter the console command  `completequest mq101` to mark Unbound as finished. Then connect to the server as described by pressing `F2`.

Upon completing the "Using Mod Organizer" section and installing Skyrim Together in the guide and connecting to a test server, we should be able to play.

### make sure to read the [playguide.](https://wiki.tiltedphoques.com/tilted-online/general-information/playguide)

### Additional mods
Enhance gameplay, quality of life, and character creation.\
Always check the prerequisites when installing mods, or they will not work.\
I am avoiding mods that have a .ESP file (plugin) attached, as it is more likely something may break in the game. Graphics mods without plugins will generally work fine. [mod compatibility report list](https://github.com/tiltedphoques/Mod-Compatibility/issues?page=2&q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc)
1. [SKSE64](https://www.nexusmods.com/skyrimspecialedition/mods/30379?tab=files) - Script extender, necessary for many mods. See installation instructions on mod page.
2. [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604)
3. [Racemenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080)
4. [KS Hairdos](https://www.nexusmods.com/skyrimspecialedition/mods/6817)
5. TESTING: Alternate Start: [Realm of Lorkhan](https://www.nexusmods.com/skyrimspecialedition/mods/18223) \
   (Replaces [Alternate Start - Live Another Life](https://www.nexusmods.com/skyrimspecialedition/mods/272) Skips super long Helgen intro, prerequisite is USSEP which requires the Creation Club mods, so we didn't go with this. USSEP older version would be required; I will test this.)
7. Untested, don't install yet: [BEASTHHBB](https://www.nexusmods.com/skyrimspecialedition/mods/38480)
8. Skin mods: Personally, I use snd greatly prefer [Skysight Skins](https://www.nexusmods.com/skyrimspecialedition/mods/6580) for male, [Mature Skin 2](https://www.nexusmods.com/skyrimspecialedition/mods/26017?tab=description) for female. (Actually I overwrite it with skin textures from [Real Girls CBBE](https://www.nexusmods.com/skyrimspecialedition/mods/75065), but this texture is not compatible with unmodded bodies.) Choose vanilla options.\
   Tempered Skin for [male](https://www.nexusmods.com/skyrimspecialedition/mods/7902) and [female (NSFW)](https://www.nexusmods.com/skyrimspecialedition/mods/8505) characters is also a good choice for wide compatibility. Select Vanilla option.
10. UNTESTED, DON'T INSTALL: [Latest ENB binaries](http://enbdev.com/mod_tesskyrimse_v0502.htm) (scroll down to download) and [ENB]() if your PC can handle it. 
Notes: 
- As long as there is no plugin, texture and mesh mods might work fine. In the folder of the mod, there should be no .esp or .esl file. Feel free to install these, hopefully they will work.
