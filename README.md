Updated - 11/04/2025
=====================
PCUAE v5.2.5 RELEASED - Look on the right for Releases ---->
======================
If you can not see the Releases then click here: https://github.com/CommodoreOS/PCUAE or here: https://github.com/CommodoreOS/PCUAE/releases

PCUAE Website: https://thec64community.online/thread/1681/new-release-pcuae-v4-4
When you want PCUAE 4all Edition please go to the website: https://projectcarouselusb.eu/downloads-2 
==================================================================================================================

<img src="https://github.com/Wizart009/Setups/releases/download/v0.1.0-alpha/ezgif-18e1d8e6e620cb.gif" alt="tour" width="854" height="480" />

## In short PCUAE runs:

All the Carousel variations on TheC64mini, TheC64, TheVic20 - you get to see all the other games as if you bought e.g. a PAL model from the UK when you would normally see the games on the NTSC model so you can change THEC64 Mini from a PAL model to a NTSC model or from a NTSC model to a PAL model.

Additional Games Collections only on TheC64mini, TheC64, TheVic20 - Able to add games to the carousel so lots of carousels with up to 255 games each carousel - customisable by using the PCUAE Manager.

VICE mode - Run the Vice emulator in full for PET, Vic20 C64, C128, C16/Plus 4, C64 DTV etc...

Other emulators e.g. Atari, SNES, PSX, ZX Spectrum Modes

Additional tools like change the clock speed, reset the Nand etc.

Make a TheVic20 boot up as a The400 and The400 into Thec64.

Also runs these things(Modes) on other models like THEA500 Mini, THE400 Mini, Atari 2600/7800 Plus, Atari Gamestation Pro.

Thanks to vic2020ian on THEC64 Commmuity Forum for the discription - https://thec64community.online/thread/1754/pcuae-etc

Edited it abit now... :)

## 

Any help you need with PCUAE, look on THEC64 Community Fourm: https://thec64community.online


Look here for the Quick Startup Guide: [https://github.com/CommodoreOS/PCUAE/blob/main/README.md#pcuae-quick-startup-guide](https://projectcarouselusb.eu/new-how-to-section/)
-----------
You can download PCUAE Manager here to download PCUAE and its Modes: https://github.com/CommodoreOS/PCUAE-Update/releases/tag/pcuae-manager
------------
PCUAE Manager info and download is here if you want it - https://thec64community.online/thread/603/pcuae-manager

Make sure you have a USB stick formatted as FAT32 ([use Rufus](https://rufus.ie/en/) for Windows or [GUIFormat32/64bit](https://my.hidrive.com/share/l7c0gi30i0#$/) for Windows - [info here](https://projectcarouselusb.eu/gui-format32/)) if you need too format the USB Drive, 
PCUAE does not work on any other file system, all machines only use FAT32 to read games in its USB Media Access/File Loader/TheCarousel, so FAT, NTFS, EXT3, EXT4 is not supported, you can split the USB Drive so it has two partitions but they will not read extra partions on the USB Drive so only use FAT32 and format(MBR) the whole USB Drive.
--------
You can use bigger drives with PCUAE - SSD, SD, USB Sticks, 32GB, 64GB and 128GB+.
---------
Only use MBR - Master Boot Record, not GPT - GUID Partiton Table, its not supported by the machines.
--------

PCUAE Amiga Mode Extras Pack (WHDLoad Games) - https://onedrive.live.com/?id=DE6843E1C82A96C8%21323314&cid=DE6843E1C82A96C8
--------
You do not need all of PCUAE, becuase it can be installed in parts (like Hakchi) so you can download only the Mode (like Hmods) you want to use, so if your on the Atari 2600 Plus/THE400 Mini/Atatri Gamestation Pro and only interested in Atari games only, then you just download `pcuae-v4.4.0-main-4all-standalone-setup.exe` and install from the Menu `pcuae-v4.4.0-atari-machine-edition-standalone-setup-1.exe` and `pcuae-v4.4.0-atari-machine-edition-standalone-setup-2.exe` Atari Mode is now included.
---------

PCUAE now shows its shortcut keys/buttons on the screen now so might slow down PCUAE boot time but you need to see them otherwise you will not know what keys/buttons to use to load the Mode Changer,Carousel Gamelist Changer to change a Mode or to change the gamelist on THEC64, THEVIC20 Carousel and other options available. 
-------
It might be a good idea to take a photo of the screen with your phone when they come up on screen so you can look at them at any time.
-------

What Models does PCUAE run on:
================================

1. `THEC64 Mini`,

2. `THEC64`,

3. `THEVIC20`,

4. `THEA500 Mini`,

5. `The Atari2600 Plus`,

6. `THE400 Mini`

7. `Atari Gamestation Pro`

8. `The Spectrum`

9. `PS Classic - Coming soon`


PCUAE Quick Startup Guide
====================

This will guide you through:
-------
You only need one link for THEC64 Mini, THEC64, THEVIC20, THEA500 Mini and THE400 Mini: How to Install PCUAE and Install and run a Mode Pack - Dummy Walkthrough: https://github.com/CommodoreOS/PCUAE/blob/main/README.md#how-to-install-pcuae

Info on the PCUAE for the Atari2600 Plus, Atari Gamestation Pro, look here now: https://thec64community.online/thread/1658/pcuae-atari2600-plus-deeplay-loader

PCUAE Logo, What does PCUAE Stands for...
================================
![PCUAE BOOT SCREEN](https://i.ibb.co/9YkHd7f/PCU-Anniversary-Edition.jpg)

`PCUAE` was called originally `PCU - Project Carousel USB` (thats why is website is called https://projectcarouselusb.eu) then in 2021 its name changed to `PCUAE - Project Carousel USB Anniversary Edition` on its one year anniversary.

It name has nothing to do with PUAE Amiga Emulator in Retroarch, it was named before it was added as a mode.

PCUAE is completelly free and you do not need to pay for it or charged to use it, if you do then you are been riped off, it free to download and use, make sure you always download it from here, PCUAE Manager or from the PCU Offical Website below.
---------
https://projectcarouselusb.eu
------
PCUAE is basically a mod that runs emulators and kernel modules that the console is missing to get something inside it to work, like the network, internet so it enables it, alot of the mini consoles have stuff missing in the Linux system, so it can enable stuff in its system so runs different shell scripts one after another, each script enables something unless the system can not do it, the last script it runs is the Mode script and what mode you have picked to load, each mode is a mod so Carousel Mod, Emulator Mod thats been added to PCUAE so it can be loaded via its script inside it.
I hope this explains it better... :)
--------
PCUAE is licensed under the terms of the GNU General Public License, version 3 or later.
---------
If you just installed PCUAE and this has poped up then no need to read it, do it in your own time.. :) and read only the parts you need too.
-------
If you have just Installed PCUAE and alraedy used the walkthough above then thanks for installing PCUAE and I hope you enjoy using it... :) This load up when PCUAE setup has finished to show you its finished installing it.
--------
Whats New
=============
THE400 Mini is now added to PCUAE, it works the same way as THEC64, thats what basically it is its just uses THECarousel from THEA500, it uses the same `NAND(256MB)Kioxia(Toshiba)`,`RAM(256MB)Hynix` and `CPU SoC(Allwinner H3)`(THEC64 board is based on the Orange PI PC H3) and uses THEA500 `THECarousel Manhattan Skyline` that they have called `Charm` because its a different build only so the same carousel, its binaries are named the same as THEA500 so is the same code, its just be modified to work with `RGL's Atari 8 bit THEColleen Emulator(Colleen (c)Copyright 2023 Chris Smith` its not Colleen from Android, it proberly the Atari800 Emulator 4.20 or something and they named it differenty, the name Colleen come from one of the Atari ICs in the machine, there is not source for Colleen on Android) so in realaity THE400 Mini is THEC64 just modified so changed to look like THE400 so its a hybrd of the two consoles(like THEVIC20), THEC64 and THEA500, THEC64 Hardware and THEA500 Software in one.

THE400 Mini will be the last machine that will be added to PCUAE, well it has been almost 4 years now, PCUAE started, 14 April 2020, I am not really interested in geting any of the Maxi models and PCUAE might work on them anyway if they are the same as the mini's, I only like the original machines and I already have them, I like the mini consoles becuase they are mini versions of them and do not take up any space.

THE400 games folder for USB Media Accsess are on the PCUAE USB Drive at `PCUAE-Atari-Games/THE400-USB-MENU` so thats where you can add your own games too, to enable PCUAE on THE400 Mini you will have to use FEL Mode and Win32 Disk Imager to copy the nandb image over to its nandb so it copies the PCUAE Autoboot Startup Script so PCUAE can boot on THE400 Mini so like on the Atari2600 Plus, there is no way of modifing THECarousel or THEColleen Emulator, well not yet.

You can now load PCUAE on the Atari2600 Plus now and load ROM(.a26/.bin 2600 files and .a78/.bin 7800 files) Games on it from the USB Drive instead of cartridges, you can still run cartidges too, you can run the original Stella Emulator 7.0 pre on it too(its not Retroarch) and run cartridges in original Stella as well.

Look in START-PCUAE-ON-ATARI2600-PLUS folder and read the PLEASE-READ-ME_FOR-ATARI2600-PLUS.txt file for more infomation or here... https://github.com/CommodoreOS/PCUAE-Atari2600-USB-ROM-Loader/blob/main/README.md

Always have a cartridge in slot when using PCUAE on the Atari 2600 Plus, its so the switches on the console work and it will not load the ROM file if no cartridge.

PCUAE MSX/Colecovision Mode now available
===========================================

About THEC64 Models ONLY - Just found a problem with the older firmware - If your having a problem loading PCUAE and its stuck on the PCUAE splash screen then update the firmware, it can stop PCUAE loading properly if THE64 Carousel is on v1.0.10 or lower, it needs to be on the latest version of the firmware so v1.6.1.

Nintendo 64 Mode has just been added to PCUAE 
==============================================
For THEA500 Only, it only for THEA500 Mini because it has 512MB RAM and THEC64 Mini/THEC64/THEVIC20, THE400 Mini has 256MB RAM so would have a problem running on them so would run out of memory and kill the Mode, if you want to use N64 Mode in PCUAE then you will need THEA500 Mini to do it.

PCUAE Updater is in PCUAE Network Mode Now
=======================================
You can use PCUAE Manager to keep PCUAE updated or PCUAE can update itself now, PCUAE Updater has now been added to PCUAE Network Mode, if you have PCUAE connected to the internet, go into The Mode Changer and select option 1 - PCUAE System Menu then option 2 PCUAE System Update Menu, its been added to PCUAE 3.3.5.

Whats New in PCUAE 3.7.5
===================================

Game Mode has been added to the Atari2600 Plus so you can load ROM games using a two shortcut key combo on the keyboard(CTRL+Key), Game Mode shows the shortcuts on the screen so like a menu so you know which shortcut you can use to load a game on the Atari2600 Plus, Game Mode shortcut combo is CTRL+G and when your in a game you can go back to the Game Mode Menu Screen by pressing CTRL+G again in the game to load a different game.

Nintendo 64 Mode has just been added and Atari Mode has been updated to make it easier to load games.

PCUAE Updater has now been added to PCUAE Network Mode, if you have PCUAE connected to the internet now and is using a Ethernet Adapter with THEC64 Models/THEA500, then go into the PCUAE System Menu to check if PCUAE has any updates avalible, its been added to PCUAE 3.3.5.

PCUAE Network Mode has been updated now to included THEA500 and the Atari2600 Plus too, so you can now use the internet on the machine like you can on THEC64 but it only works with one USB Ethernet Adapter on THEA500 and you can use the other Ethernet Atapters on THEC64 Mini/Maxi on the Atari2600 Plus too, TP-Link UE300 Ethernet Adapter works only on THEA500 Mini at the moment and works on the Atari2600 Plus too, I bought one and it cost £16 from eBay, so if you look around you might get one cheaper, I think they were original made for Apple MacOS X because it white like there old Apple Notbooks so it goes with the colour of THEA500 Mini very well... :)

TP-Link UE300 Ethernet Adapter works in the Atari2600 Plus with PCUAE Network Mode too.

Currys sell the TP-Link UE300... https://www.currys.co.uk/products/tplink-ue300-usb-3.0-to-gigabit-ethernet-universal-adapter-10148411.html

TP-Link website, you can buy it from there too... https://www.tp-link.com/uk/home-networking/computer-accessory/ue300/

You will need a TP-Link UE300 Ethernet Adapter because it use a RealTek 1853 chip(IC) in it that THEA500 kernel only supports, you can use a 1852 too because it the same type of IC.

![TP-Link-UE300](https://i.ibb.co/RyDjgcf/20230730-141432.jpg)

You plug it in into one of THEA500 USB ports, not the one next to the HDMI port, that for your PCUAE USB Drive or USB Hub(PCUAE USB Drive is then plugged into it, like mine), you can plug it into a USB Hub but it might need powering, when I tested it in mine it didn't work becauase its not powered so I did try, the adapter does not get enought power to fuction so its light might be on but its not getting the right amount of volts, I plug it into the 2nd USB Port.

Once you pluged the adapter in to THEA500 then Open `thea500-Internet-ip.txt` in the `PCUAE USB Drive:\Network-SSID` folder to add THEA500 IP Address and the Routers Gateway IP.

You can now edit `thea500-internet-ip.txt` with notpad on windows 10, I added a program that checks it and turns it into a `Linux file`, now.
You need to add the ip address you want to use for THEA500 Mini so pick one thats free and not used by any other device on the network and looks the same.
Then add your Gateway ip, your routers IP, it needs this so THEA500 can connect to the internet.
These instructions are in the `thea500-internet-ip.txt` file too as a reminder.
Then run PCUAE and select Amiga Mode>AmigaSYS4 3.1 WinUAE Version then pick `Resoluion UAE:1280x720 RGBA` then you be able to use `IBrowse 2.4`(`IBrowse 2.5` is included, its in the other2 Amiga Hard Drive on the Workbench, you can run it from there too or move it where you want it) and load webpages in it.

And thats it... :) Internet on THEA500... :)

Added to AmigaSYS4 AmiSSL 4.5 so you can use https sites now, they now load ok.

Video is here of it working in IBrowse 2.4... https://www.youtube.com/watch?v=Nvx4wTqNels

Updated the way PCUAE loaded TheCarousels and speeded its loading time so its a bit faster, including the Modes too, I would like it to load 20 or 30 seconds but to do that I would have to change the way PCUAE boots up, I will do it some time down the line, busy with other things in PCUAE, PCUAE boot like a system so have to be carfull not to brake anything as its booting, so things not time to boot or enable like PCUAE Network Mode, I can brake something if it boots to quick so then misses something so it might not be possible, one problem with it is it has to see the PCUAE USB Drive so needs time to see it so 5 seconds so makes it take longer to boot but that can not be changed.


How to install PCUAE
=====================

How to Install PCUAE and Install and Run a Mode Pack - Dummy Walkthroughs.

Look here for THEC64/THE400 Models Dummy Walkthrough:

https://thec64community.online/thread/1613/pcuae-walkthrough-updated-thec64-models

Look here for THEA500 Dummy Walkthrough:

https://thec64community.online/thread/1614/pcuae-walkthrough-updated-thea500



PCUAE Automaticlly Updating the Firmware(TheCarousel in THEA500 Only)
======================================================

It changes TheCarousel in the firmware to the one used in TheCarousel Changer(it temporary changes it) so if you change from Manahttan v1.0.0 to Manahttan v1.2.1, it will use v1.2.1 in the firmware too, it can be downgraded too, It can be disabled as well in the PCUAE System Menu, it defauit is on automaticlly so switches TheCarousel in the firmware(when you remove the USB Drive and load the Firmware) to the same as TheCarousel used in PCUAE Mode.


You can uninstall PCUAE now with PCUAE REMOVER
======================================================

You can remove the Autoboot Start-Up Script if you wish too now, you can add it or remove it, you remove it using PCUAE System Menu using PCUAE REMOVER.


For THEC64 Models Only:
Loading Games in TheCarousel Amora v1.6.1(All THEC64 Models Only)
======================================================


You can load your own Games on THEC64 Carousel Amora v1.6.1, THEC64 Maxi Carousel, all THEC64 models use it now.
You can add your own games in its carousel, a set of games(for C64 and VIC20) are now inclued with PCUAE All In One Version and are included with PCUAE Manager too so you can export them to the PCUAE USB Drive, to enable PCUAE Mode on THEC64 Models you need to export over Favories 1 Gameslist to THEC64-CAROUSEL-GAMES folder on the root of THE PCUAE USB Drive for it to see the gameslists you add, you can add what games you like in the Favories 1 Gamelist in PCUAE Manager, it will need games adding to it if the carousel see no games at all it will not load the carousel, if favorites 1 is not added then a blue screen will apear and say there is no Favortes 1 Gamelist and then load the Firmware carousel with its default games instead of PCUAE Mode.


Quick Info On Modes
==================


You can run C64 or VIC20 games on THEC64 Carousel on THEC64 Mini and switch from PAL to NTSC and back on THEC64 Mini/THEC64/THEVIC20.


You can load VICE Mode and load C64 games on THEC64 and THEA500. (the pack is availble on here)


You can connect to the internet and load up BBS borads in VICE Mode in THEC64.(THEC64 Only)


You can load Amiga(16bit), Atari(8bit), Vice(C16/plus4,C64,VIC20,C128,8bit) and RetroArch(RA) Modes on THEC64 and THEA500, THEA500 can run RetroAami Mode instead of RetroArch Mode, they are now all in one installer now under Retroarch Mode Pack(the packs are availble on here).


On THE A500 Mini - CD32 Mode, load a CD32 game from StartUp and turn THEA500 Mini into the Amiga CD32 Console, Load a ADF file in ADF Mode and load it from StartUp, like your loading a real floppy disk.


You can run AGS 500 Mode(A500 Games Selector 1.5) on THEA500 Mini from Startup, load a collection of games and apps on the Arcade Games Selector(it will need the HDD folder for it to work).


There are more features on THEC64 cause its been out longer then THEA500 Mini and its not locked down like THEA500 Mini is, I think RGL did this cause to stop copyright games been added by people that have no rights to sell them, like what happened with the True Blue Mini USB Stick.



For THEC64 Models Only:
You can get to USB Media Access now from the Carousel by using the Game Slot Image for that carousel gamelist
===============================================================================================================

You can now use USB Media Access by selecting and pressing on the `Game Slot Image` on the Carousel on THEC64 Models.

Just select and press `left fire button` on the `Game Slot image`, its will show `Games Favorties 1, C64 Games, VIC20 Games` where it says what gamelist your on(its selected when you start the carousel) and it will load into `Classic Mode`(`C64 Basic` or `VIC20 Basic`) then press `Menu button` on `THEC64 joystick` on the `Basic screen` and select `Media access` and press `Left fire button` and your `USB stick/drive` content will apear on the screen, you should use this now anyway is better then the File Loader, it has more options in it like `disk swaping`, RGL should link the `USB Icon` on the `carousel` to `Media Access` anyway now because all models use it now, THEC64 does not need `two USB file loaders`, only need one... `USB Media Access`.

Here is how to do it
======================

See pictures below

On TheCarousel - Press on `left fire button` on `Game Slot image`...

![Game Slot image](https://i.ibb.co/hDBHB5X/Screenshot-2023-08-09-153743.jpg)

On Classic Mode - then press `Menu button` on `THEC64 joystick` on the `Basic screen` and select `Media Access`...

![Classic Mode](https://i.ibb.co/5jqSzrk/Screenshot-2023-08-09-153838.jpg)

Media Access - `USB stick/drive` content will apear on the screen... :).. BINGO... :D

![Media Accsess](https://i.ibb.co/YZx66Wp/Screenshot-2023-08-09-153911.jpg)

And now you can get to Media Access easier... :)


---------
New Facebook Group now... https://www.facebook.com/groups/pcuae
-----------
Alot of work has gone in to this version to make sure everything runs as it should, thanks Davy(Wizart) for the help, fixing scripts and adding features, PCUAE is now to big for one person to work on, it would take to long to release it between versions.

New PCUAE Offical Website, finally here... https://projectcarouselusb.eu 
-------------------------------------------------------------------------------------------------------------------------
I changed my mind about having a site, it needs one, downloads are availble there too and other goodies.. :) you have to register on the site to download files and have access to the site, if you use the PCUAE site then you will not need to use the PCUAE Menu.


More info on PCUAE
===================


There is now nothing in PCUAE that not allowed to be in it, all software like `Amiga Games Selector` and `Pandory for THEA500` is not included but you can download them in the `PCUAE Menu` using there download links, you have to add them yourself to `THEA500-USB-MENU folder`, thats really easy to do, `you just open there .ZIP or RAR file` and copy its `AGS` or `Pandory` folder to the `THEA500-USB-MENU folder` and they are then installed and will work in PCUAE, its that easy.


`AMiNIMiga` has now been completely removed, I decided to remove it completely when `Amiga Workbench 3.1` was removed from THEA500 version, because I need the `Workbench 3.1 disks` so needs seting up in PCUAE to use it now to run it and it can not be set up to run normally like a `Workbench` so too much loop holes to go through, `Cloanto` probably asked him to remove it, thats would be the only reason why it been removed, its probably on to many systems thats why, I think it would of been different if it was only on THEA500 only, this is what happens when something become popular and Cloanto hear about it, this is the problem with older version of Workbench, they should be free to use in non payed products now but `AMiNIMiga` does get donations for it, that properly why no Workbench now inside it, PCUAE Does not get donations now, its now completely free, all ways of donating have now been removed, I do not need money for it, I made this because I wanted too, not for money, and the donation idea was not mine, I when a long with it thinking "OK I give a try" but it didn't work out so its better without it, work before profit, take pride in your work first before money, if you only think of the money then you lose interest in the work.


`Cloanto` are called `Amiga Corporation` now, I find that werid, they proberly changed there name so they can sell the `Amiga copyright and Games from Amiga Forever` to other companies, now they own all of it.

Ever woundered why `VICE Emulator for Windows` do not come with the `C64 kernal Roms` no more..? the `C64 Kernal Roms` were free at one time too but are not now because of `Cloanto` owning the `C64 Kernal Roms copyright` thats in `C64 Forever`, thats why `THEC64 has Cloanto` on its box, RGL had to pay them to use the `C64 Kernal Roms` in there machines.


PCUAE WILL BE SUPORTING  `AMiNIMiga` `AMM` again and added to the `THEA500-USB-MENU folder` again but no HDFs files inclued, only suporting it, you will need to add it... :)
If you want to discuss PCUAE go to THEC64 Community Forum - https://thec64community.online
"PCUAE now contains host-rum from the Pandory500 mod"... https://github.com/emuchicken/pandory-a500
It will from now on include host-rum.adf file from Pandory so it can boot PCUAE using it, thanks Dajoho and Team Pandory for alowing me to use it... :)
I will always try to support PCUAE, but do need a break from it from time to time... :)
WIKI is here, it might need updating so might not included new fetures or info on the new version of PCUAE - PCUAE Manual is here - https://github.com/CommodoreOS/PCUAE/wiki


FAQ
====

Where are the games kept for THEC64 Carousel
=============================================


There are in the `THEC64-CAROUSEL-GAMES` folder on the root of the PCUAE USB Drive now.


More FAQ comming soon.



# PCUAE License


Project Carousel USB Anniversary Edition(PCUAE) by Spannernick, 


Idea by Spannernick, Carousel USB Chooser by FaberfoX(Carousel Gamelist Changer on THEC64), 


Load Carousel Games from the USB Drive using Carousel Gamelist Changer and C64 SID Music playing in the background, they change depending on what CGS is loaded, for only THEC64 Mini, THEC64 and THEVIC20, you can change it to a different set of games(Carousel Gamelist Selector - CGS) on TheCarousel.

THEA500 Mini has been block from doing it by RGL so you can not add or do anything with THEA500 Mini's TheCarousel, it will never be possable to do anything with it, sorry this is not my fault, RGL has made the carousel on purpose this way, so you can not change its games so its impossable, this is why now the next machine do not interest me now, because they be doing this to all the machines(Devices) they make and you be stuck with the games on the carousel that you will hardly play becuase you can't change them, TheCarousel is just for show and made to make the GUI look nice and to sell it, there is no purpose to the carousel realy and its not future prove, once you played the games on it a few times then you will not use it more, if you could add games to it, it be more usefull, its kind of obvious and you have no need for a USB Media Menu on the machines.

You can change to different Modes(Emulators) on THEA500 Mini in PCUAE only but can not add games to its Carousel like you can with THEC64, RGL(Retro Games Ltd) have built the carousel this way on purpose so you can not add games to its carousel, proberly cause they are thinking about how much money they are making from THEA500 more but thats why they made the machines in the first place, to make money from it and I gueses to make sure they do not lose money, I would not care if anyone moded it cause it helps selling it, like what happen to the PS Classic, hacking made it a better console and users started to buy it cause of Bleemsync.


JIFFYDOS 6 is included, 


**This is free for non commercial use - NOT to SELL and will allways be FREE, if you have bought PCUAE from someone(eBay) ask for your money back**


THEC64 Mini, THEC64, THEVIC20, THEA500 Mini - Copyright(c) 2022 RETRO GAMES LTD - https://retrogames.biz


IF you feel you want to help me out and give me a Monster Energy or a cup of Tea:
![image](https://github.com/CommodoreOS/PCUAE/assets/38408051/471f1937-254d-473f-a719-8e2ab50a2483)



You can use PCUAE Manager to manage your games on the Carousel and store them, import/export them from/to the PCUAE USB Drive(THEC64 ONLY).


PCUAE Manager on Github - https://thec64community.online/thread/603/pcuae-manager


ANYWAY....PEACE PEOPLE... :) and Enjoy using PCUAE.


Spannernick.

