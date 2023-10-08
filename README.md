Updated - 08/10/2023
=====================

PCUAE Quick Startup Guide
====================

Thanks for installing PCUAE, Enjoy... :)


PCUAE Logo, PCUAE Stands for...

![PCUAE BOOT SCREEN](https://i.ibb.co/9YkHd7f/PCU-Anniversary-Edition.jpg)

PCUAE is completelly free and you do not need to pay for it or charged to use it, if you do then you are been riped off, it free to dowmnload and use, make sure you always download it from here or from the PCUAE Offical Website below.
https://projectcarouselusb.eu/

PCUAE is a system mod, it loads like a Linux system.

PCUAE is licensed under the terms of the GNU General Public License, version 3 or later.

Look below at... `Please read About PCUAE below...` Once you have installed PCUAE.

If you just installed PCUAE and this has poped up then no need to read it, do it in your own time.. :) .

If you have just Installed PCUAE and do not know how to use its basic functions then look thought this guide before reading the Manual(Wiki).

Just skip the parts you do not want too or need to read.
============================================

This will guide you through...

Whats New.

How to Install PCUAE.

About PCUAE Loading and the PCUAE USB Drive.

What are the PCUAE Shortcut Keyboard Combinations

What are the PCUAE Shortcut THEC64 Joystick/THEGamepad Combinations

Whats New
=============

Whats New in PCUAE 3.3.1
===================================

PCUAE Network Mode has been updated now to included THEA500, so you can now use the internet on the machine like you can on THEC64 but it only works with one USB Ethernet Adapter, TP-Link UE300 Ethernet Adapter, I bought one and it cost me £16 from eBay, so if you look around you might get one cheaper, I think they were original made for Apple MacOS X because it white like there old Apple Notbooks so it goes with the colour of THEA500 Mini very well... :)

Currys sell the TP-Link UE300... https://www.currys.co.uk/products/tplink-ue300-usb-3.0-to-gigabit-ethernet-universal-adapter-10148411.html

TP-Link website, you can buy it from there too... https://www.tp-link.com/uk/home-networking/computer-accessory/ue300/

You will need a TP-Link UE300 Ethernet Adapter because it use a RealTek 1853 chip(IC) in it that THEA500 kernel only supports, you can use a 1852 too because it the same type of IC.

![TP-Link-UE300](https://i.ibb.co/RyDjgcf/20230730-141432.jpg)

You plug it in into one of THEA500 USB ports, not the one next to the HDMI port, that for your PCUAE USB Drive or USB Hub(PCUAE USB Drive is then plugged into it, like mine), you can plug it into a USB Hub but it might need powering, when I tested it in mine it didn't work becauase its not powered so I did try, the adapter does not get enought power to fuction so its light might be on but its not getting the right amount of volts, I plug it into the 2nd USB Port.

Once you pluged the adapter in to THEA500 then Open `thea500-Internet-ip.txt` in the `PCUAE USB Drive:\Network-SSID` folder to add THEA500 IP Address and the Routers Gateway IP.

**IMPOTANT** Edit `thea500-internet-ip.txt` with `Notepad++` ONLY, `its a Linux file`, if you edit it with `Notepad on Windows` it will turn it into a `Windows file` and the Internet will not work, so download and `install Notpad++` first before editing it, its here... https://notepad-plus-plus.org
You need to add the ip address you want to use for THEA500 Mini so pick one thats free and not used by any other device on the network and looks the same.
Then add your Gateway ip, your routers IP, it needs this so THEA500 can connect to the internet.
These instructions are in the `thea500-internet-ip.txt` file too as a reminder.
Then run PCUAE and select Amiga Mode>AmigaSYS4 3.1 WinUAE Version then pick `Resoluion UAE:1280x720 RGBA` then you be able to use `IBrowse 2.4`(`IBrowse 2.5` is included, its in the other2 Amiga Hard Drive on the Workbench, you can run it from there too or move it where you want it) and load webpages in it.

And thats it... :) Internet on THEA500... :)

Added to AmigaSYS4 AmiSSL 4.5 so you can use https sites now, they now load ok.

Video is here of it working in IBrowse 2.4... https://www.youtube.com/watch?v=Nvx4wTqNels

Updated the way PCUAE loaded TheCarousels and speeded its loading time so its a bit faster, including the Modes too, I would like it to load 20 or 30 seconds but to do that I would have to change the way PCUAE boots up, I will do it some time down the line, busy with other things in PCUAE, PCUAE boot like a system so have to be carfull not to brake anything as its booting, so things not time to boot or enable like PCUAE Network Mode, I can brake something if it boots to quick so then misses something so it might not be possible, one problem with it is it has to see the PCUAE USB Drive so needs time to see it so 5 seconds so makes it take longer to boot but that can not be changed.

PCUAE Download Menu is Back, its now called just PCUAE Menu
============================

Download PCUAE Menu from here... https://github.com/CommodoreOS/PCUAE-Update/releases/tag/pcuae-menu
It now works on its own, just click on its shortcut icon on the Windows Desktop.
It will run itself when you install it to your PC.
I made it so THEA500 users find it easier to download stuff for PCUAE.


How to install PCUAE
=====================

Make sure that the USB Drive you pick is formatted in Fat32 and in MBR(do not use GPT it will not work) , You can use a 8, 16, 32, 64 and 128GB USB Drive with THEC64 models and THEA500 and PCUAE should be OK to install on them too, I use a 64GB SD card with mine, you can even use a Sata Sold State Drive, 250GB or lower, just make sure it formatted with MBR and FAT32 then it will work.


NOW First, download `PCUAE Manager` from https://github.com/CommodoreOS/PCUAE-Update/releases/tag/pcuae-manager (New Updated Version)

You can `Download PCUAE` from the `Website` it here... https://projectcarouselusb.eu or use the `PCUAE Menu` above, its up to you.

You install `PCUAE Manager` the same way you do with `PCUAE`, but pick a location on your `PC` not on the `PCUAE USB Drive`, it will `install to the C/: drive` under `C:\Games\PCUAE\PCUAE-Manager` folder, if you do not change it, once its installed click on its icon on the desktop to load `PCUAE Manager`.

Once `PCUAE Manager` has opened you might see a box apear saying new version of PCUAE is avalible, but if not then `click on the PCUAE Tab` and you will see `PCUAE Install to a USB drive`, click on that item. 

`PCUAE Manager` will then ask `do you want to download PCUAE`, then click on `Yes Button` and it will start `downloading the latest version of the PCUAE`, it will not take long, then it will ask `do you want to install PCUAE`, click on `Yes button again` to start the setup so you can `install PCUAE to the your USB Drive you want it on`.

`PCUAE Manager` notifies you if there is a new version of the `PCUAE` when it becomes available on GitHub


I might add new stuff about PCUAE in here first before adding it to the Manual(WIKI) so look here first, this file is the most important file to look at on how to use PCUAE, thats why it pops up when you have installed the PCUAE Menu and PCUAE, this file has the main stuff you will need to get PCUAE working, its a quick startup(help) guide to PCUAE so you do not need to deep dive into its manual.



You can now use USB Media Access by pressing on the `Game Slot Image` on the Carousel on THEC64 Models.
Look at the images below.


Just select and press `left fire button` on the `Game Slot image`, its will show `Games Favorties 1, C64 Games, VIC20 Games` where it says what gamelist your on(its selected when you start the carousel) and it will load into `Classic Mode`(`C64 Basic` or `VIC20 Basic`) then press `Menu button` on `THEC64joystick` on the `Basic screen` and select `Media access` and press `Left fire button` and your `USB stick/drive` content will apear on the screen, you should use this anyway, it has more options in it like `disk swaping`, RGL should link the `USB Icon` on the `carousel` to `Media Access` anyway now becuase all models use it, you do not need `two USB file loaders`, only need one... `Media access`.

On TheCarousel - Press on `left fire button` on `Game Slot image`...

![Game Slot image](https://i.ibb.co/hDBHB5X/Screenshot-2023-08-09-153743.jpg)

On Classic Mode - then press `Menu button` on `THEC64joystick` on the `Basic screen` and select `Media Access`...

![Classic Mode](https://i.ibb.co/5jqSzrk/Screenshot-2023-08-09-153838.jpg)

Media Access - `USB stick/drive` content will apear on the screen... :).. BINGO.

![Media Accsess](https://i.ibb.co/YZx66Wp/Screenshot-2023-08-09-153911.jpg)

I tried to speed up the loading time PCUAE so changed the the way it loaded and now for some resion thinks the USB Drive is not free when the carousel loads when it is, so now got to work out why and what I change that caused it, it not really that important because you can use `Media Access`... This has now been fixed in PCUAE v3.3.3... :)


NEW PCUAE v3.3.3 now avalilble
---------
New Facebook Group now... https://www.facebook.com/groups/pcuae
-----------
Alot of work has gone in to this version to make sure everything runs as it should, thanks Davy for the help, fixing scripts and that, PCUAE is now to big for one person to work on, it would take to long to release it between versions.

New PCUAE Offical Website, finally here... https://projectcarouselusb.eu 
-------------------------------------------------------------------------------------------------------------------------
I changed my mind about having a site, it needs one, downloads are availble there too and other goodies.. :) you have to register on the site to download files and have access to the site, if you use the PCUAE site then you will not need to use the PCUAE Menu.

More info on PCUAE is here... https://github.com/CommodoreOS/PCUAE/wiki



About PCUAE Booting and the False Scan the PCUAE USB Drive for Errors in Windows from THEA500 and maybe THEC64 Models
======================================


If when loading PCUAE is acts odd or does not load corectly then it can be down to the PCUAE USB drive, THEC64/THEA500 Models do not eject the PCUAE USB Drive correctlly so mark the drive with a `Dirty Bit` so it neeeds scanning for errors, it can messup the data on the PCUAE USB Drive and then get loading errors so then you need to scan it for errors on Windows 10, or might even need to format it again in FAT32 but it should work properly after that, On Windows 10/11, Right Click on the PCUAE USB Drive in Windows Exployer and click on Properties then click on Tools then you see... `Error Checking` `This option will check for file system errors` and then click on its `Check` button and wait for it to finish, once done put back in the machine and PCUAE should load properly, if not then the USB Drive needs formating again with FAT32, on Windows 11 if the USB Drive is on FAT32 file system already you can format it again using the Windows Formater, right click on USB Drive and click on Format, it should of selected FAT32 already in it then click on `Quick` or `Slow Format`, I would do `Slow Format` to remove all the errors on the drive, it will take a while but its worth it, this goes to show that Windows can format USB Drives in FAT32, it still in there, it just uses NTFS instead cause its a better file system and you get less coruption on it, RGL should of used NTFS instead of FAT32, Linux OS for Armhf does support NTFS too, they copied all the other Minis thats why, you should not folow someone else, that how you make the same mistakes.

I was looking into the `Dirty Bit` and why it was there recently and it can be fixed by using `fsck.fat`, it does remove the `Dirty Bit` so no errors when you plug it back into your PC but can messup the USB drive because it sees  some of the file names are too long so renames the files on the PCUAE USB Drive so stops PCUAE booting so I removed it.

It the carousel on THEA500 Mini thats making the `Dirty Bit` on the drive and making it when it reads it in its `USB Media Menu` cause its there if you tuen of the machine and put it in the PC the errorbox apears, its because its not been unmounted properly, its not been told to unmount it when it power off.
If say your on the carousel and want to add a game you forget to add, you think... "ah OK I can pull the USB Drive out and add it" no you can't it needs to be unmounted first by Linux, if your using the carousel without PCUAE you need to turn it off first before pulling the USB drive out, you even have to do that in PCUAE too, it can corupt the files on the USB Drive.


Picture of the Tools page on the PCUAE USB Drive

![PCUAE DRIVE_TOOLS](https://i.ibb.co/H4x43zG/check-drive.jpg)

When you put the PCUAE USB Drive in the PC it might ask you to do it anyway, if so then do it, but only if your having problems with the PCUAE USB Drive, because if you plug it into THEA500 it can be fake when there is no errors on the drive at all, more about that below.

And Whatever you do `DO NOT TAKE OUT THE PCUAE USB DRIVE OUT WHEN ITS RUNNING PCUAE`, Its runs PCUAE from the drive so it will make it crash and can mess the drive up if you do, PCUAE runs like a Linux system does, PCUAE boots from it.

if your still having loading probems then it can be how much power THEC64 is getting, to run PCUAE properly its recommened to use a USB power adapter thats 5v 3A, it will work with 5v 1A but you might get loading probelms.

On THEA500 Mini when you remove the PCUAE USB Drive it marks it so makes it think it needs scaning for errors, this is down to RGL not ejecting the USB Drive properly in THEA500 Mini so will always mark the USB Drive and make Windows think it has errors on it when it does not, you can scan it for errors and it will say it `found none`, becuase its false, it does it all the time, its a bug that RGL has never fixed, they need to tell THEA500 Linux System to stop marking the drive for false errors, this is not down too PCUAE, it does it even if you use the USB Drive for just Amiga Games so RGL need to fix it, whats the point of RGL providing a way to update THEA500 Mini then if they never fix anything in it, they should of issued a update for it over 6 months a ago, its been over a year now and its still stuck on v1.1.1, well... they got there money from it now so are on to the next machine, they might as well not add a way to update the next machine, because there is no point of having it if your not going to update it or fix its problems, like: some games do not work using Amiberries Autoboot lha, not all games load and some games run slow and with broken graphics.

About the Reviews Videos on YouTube about THEA500 Mini (a bit of a rant, sorry.. :) , do not always beleave what you see, not on YouTube anyway)
==============================

All the reviews on YouTube about THEA500 Mini are fake, they are made by YouTube influencers, they want you to buy it so are paid by RGL or given the console for free to review the product on there channel, that how marketing works now, yes its fucked(sorry), most stuff on YouTube is fake now, they will say its a good product if they got it for free from RGL and want the viewers to buy it so allways make sure you look at a video that the YouTuber has bought THEA500 Mini themself then it will be a honest review.

YT is not like it was 10 years ago, its changed, it all about making money now from videos, when money is invoved it changes things, making YT videos for fun has gone, its now one big advertisment site now, Google has turned YT into a Marketing and Video/Film/TV programme streaming serivce when it was just about YOU only, thats why it was called YouTube, it was made to show home videos that you made so you could share them with your frends and family, because there was no site like it at the time and Google has compltely remove it from being used for that perpose, even selling Vaps to kids, YT is fucked and I am a creator on there, TikTok is more cloeser to what YT was made for now, thats why TikTok was made because YT is moving away from it its orignal perpose, ah well... rant over.. sorry... :).



About the False Positive that Antivirus Programs See In Some Of The PCUAE Installer Setups exe Files
======================================


Windows10/11 might show the exe files has having a virus but its a false positive(it shows it in Windows Security App Program that runs in the background, it allways says it has the same virus`(Trojan:Script/Wacatac.H!ml)` when it don't have one, it because it can see scripts in it and its getting confused because its a exe file, if it looked properly it would see the scripts are for Linux only not Windows.

Picture of Windows Security showing it having a virus...

![PCUAE VIRUS NOT](https://i.ibb.co/72PWzd7/Screenshot-2023-05-17-215743.jpg)


It is happens then disable the Antivirus Progames monitor where it monitors your Files and Folders when running PCUAE Manager, once your finished installing PCUAE then turn it back on, you do not need to disable if your just adding games to the PCUAE USB Drive.




About Amiga/Atari Mode(16 bit only) RA Keyboard Map
====================================================

It looks like RA is using a Frence keyboard layout, AZERTY keyboard, a keyboard layout used in France and neighboring countries.
Some keys are in the same place as a QWERTY keyboard, this is a record of where the keys are in Amiga Mode, it uses Retroarch so I have to find a way to change it to use a QWERTY keyboard map but you can not change it in Retroarch for some reason, weird.


I mapped the keyboard(checked every key) so you know where the keys are in Amiga/Atari Mode(16 bit only) so you can still use the keyboard.


What the keys are ment to be, QWERTY Keyboard(English)

            1 2 3 4 5 6 7 8 9 0 - = Backspace
             Q W E R T Y U I O P [ ] #
              A S D F G H J K L ; ' Return 
	    Shift  Z X C V B N M , . / Shift
	              [  Space  ]
  
And what they are at the moment, AZERTY Keyboard(French)

	        1 2 3 4 5 6 7 8 9 0 - = Backspace
             A Z E R T Y U I O P [ ] \
              Q S D F G H J K L , # Return
	    Shift  W X C V B N ; M , / Shift
	              [  Space  ]

I hope this map helps you so you know where the keys are in Amiga/Atari Mode.
I do not know what the numberpad is like because I do not have a Keyboard with a numberpad.
This is a problem with Retroarch only not PCUAE, its using the wrong mapping for some reason, I just do not know why right now, it will take time to fix.
I will fix this as soon as I can, once I have figered it out, you can still play Pinball games OK, the shift keys have not moved or the other keys like: CTRL, A(Amiga key/ALT) and Tab keys and can still use the keyboard or you can use the Virtal Keyboard too if you like.


More info on PCUAE
===================


There is now nothing in PCUAE that not allowed to be in it, all software like `Amiga Games Selector` and `Pandory for THEA500` is not included but you can download them in the `PCUAE Menu` using there download links, you have to add them yourself to `THEA500-USB-MENU folder`, thats really easy to do, `you just open there .ZIP or RAR file` and copy its `AGS` or `Pandory` folder to the `THEA500-USB-MENU folder` and they are then installed and will work in PCUAE, its that easy.


`AMiNIMiga` has now been completely removed, I decided to remove it completely when `Amiga Workbench 3.1` was removed from THEA500 version, because I need the `Workbench 3.1 disks` so needs seting up in PCUAE to use it now to run it and it can not be set up to run normally like a `Workbench` so too much loop holes to up through, `Cloanto` probably asked him to remove it, thats would be the only reason why it been removed, its probably on to many systems thats why, I think it would of been different if it was only on THEA500 only, this is what happens when something become popular and Cloanto hear about it, this is the problem with older version of Workbench, they should be free to use in non payed products now but `AMiNIMiga` does get donations for it, that properly why no Workbench now inside it, PCUAE Does not get donations now, its now completely free, all ways of donating have now been removed, I do not need money for it, I made this because I wanted too, not for money, and the donation idea was not mine, I when a long with it thinking "OK I give a try" but it didn't work out so its better without it, work before profit, take pride in your work first before money, if you only think of the money then you lose interest in the work.


`Cloanto` are called `Amiga Corporation` now, I find that werid, they proberly changed there name so they can sell the `Amiga copyright and Games from Amiga Forever` to other companies, now they own all of it.

Ever woundered why `VICE Emulator for Windows` do not come with the `C64 kernal Roms` no more..? the `C64 Kernal Roms` were free at one time too but are not now because of `Cloanto` owning the `C64 Kernal Roms copyright` thats in `C64 Forever`, thats why `THEC64 has Cloanto` on its box, RGL had to pay them to use the `C64 Kernal Roms` in there machines.


You can still add `AMiNIMiga` to the `THEA500-USB-MENU folder` and it will run.


If you want to discuss PCUAE go to THEC64 Community Forum - https://thec64community.online


"PCUAE now contains host-rum from the Pandory500 mod"... https://github.com/emuchicken/pandory-a500


It will from now on include host-rum.adf file from Pandory so it can boot PCUAE using it, thanks Dajoho and Team Pandory for alowing me to use it... :)


I will always try to support PCUAE, but do need a break from it from time to time... :)


WIKI is here, it might need updating so might not included new fetures or info on the new version of PCUAE - PCUAE Manual is here - https://github.com/CommodoreOS/PCUAE/wiki

# New Stuff Added

I made some new boot screens now and they are now .rgba files, I made a new boot screen for THEA500 too, so it says `Retro Games` `THEA500` for 5 second then switches so it removes `Retro Games` and just shows `THEA500`, all boot screens are now updated.

It will now show what Mode is loading on the PCUAE boot screen `Now Loading, AMIGA Mode...` under the `Project Carousel USB Anniversay Edition` Boot screen.


I added some code so you see the Yellow Floppy Drive LED flash as PCUAE is loading on THEA500 Mini so you know its doing something... :)

I have now added ScummVM Mode, you can add game into the THEA500

I have no plans of PCUAE being ported to THEA500 Full Size Version(if it gets made, PCUAE might work straight out of the box, if its the same as THEA500 Mini and just bigger (like THEC64 Mini is the same as THEC64 just smaller), I do not plan on buying one, no money and I have original Amigas(A500, A600 and A1200) already so it don't really interest me, I got THEA500 Mini causes its small and not in the way and to port PCUAE to it and goes with all my other minis, just wanted you to know.


TODO: Add emulators as Modes: Atari - ST, ScummVM(added), Master System, Mega Drive, MegaCD, DOOM.


If you have any ideas you like me to try and add plaese post about them on THEC64 Community Forum, I do look at them and sometimes add a idea to PCUAE, so all ideas are welcome because you never know... :)



# Key Highlights of PCUAE:


PCUAE is not a hack, it does not hack the machines or copy over its firmware or change it, its a system mod, it loads like a Linux system, it modifies the way the machine boots so it boots from the USB Drive using a a set of scripts, the first script it boots from is called the `Autoboot Mode Start-Up Script`(the script is part of Autoboot Mode), its in the boot folder on the PCUAE USB Drive and called `autobootfirmware.sh` and its sent to the `int.d` folder in the firmware, it replaces the one in the firmware that just boots TheCarousel, its copied to the same place its script is that tells it to run the carousel when the console starts up if you have not installed PCUAE, its the LinuxOS boot folder, irts the main thing that gets copied to the firmware and it can boot from the firmware or from the PCUAE USB Drive when it see it plugged in, from start up, it does not touch the firmware at all and all the modifcations added are from the USB Drive only, once you take out the drive then the machine is back to booting up from the firmware carousel from start up.


You can find me on YouTube too under Retronuts and on there are some videos of PCUAE - YouTube channel is here - https://www.youtube.com/channel/UCrG1jnbvykIcLzfBFxC2GrA 
(Do not watch youtube videos from a phone or the Youtube app, you will get loads of advertisments, they play on youtube like every 10/15 minutes or so and cut into the video like your watching a TV Channel, use Google Chrome or Edge and then use the (ABP) Add Blocker Plus Extension, its free, best way to watch add free, you do not need to pay Google to watch videos on Youtube add free.)


PCUAE Automaticlly Updating the Firmware(THEA500 Only)
======================================================


On THEA500 Mini... It copies to the firmware and changes the firmare for you automaticlly so upgrades(updates) it temporary from Firmware Manahttan v1.0.0 to Firmware Manahttan v1.1.1 so you do not need to update your firmware at all if you install PCUAE, it can be downgraded too, the firmware is now connected to what TheCarousel Manhattan in PCUAE Mode is on so if its on Manhattan v1.1.1, its default option, it will change the firmware carousel if its Manhattan v1.0.0 to Manhattan v1.1.1 when you turn of the machine(after booting PCUAE Mode once) from running PCUAE and then turn it back on without the PCUAE USB Drive plugged in then it will load up Manhattan v1.1.1 in the firmware.
It will be soon added to THEC64 Modes aswell sometime, its on the to do list... :)


You can uninstall PCUAE now with PCUAE REMOVER
======================================================

You can remove the Autoboot Start-Up Script if you wish too now, you can add it or remove it, you remove it using The Mode Changer Menu or PCUAE Options Menu using PCUAE REMOVER, its now included in the PCUAE Startup Autoboot Mode.lha in the Carousel USB Media Menu on THEA500 or use the Fake Update on THEC64 Models.


Autoboot Mode
==============


You can run each Mode from StartUp cause PCUAE can Autoboot itself its called Autoboot Mode and why it need to be enabled continully, it now installs it itself, each Mode would not work without it because some Modes need to be killed and the only way to do that is be rebooting the machine, like in Retroarch, you can kill it but it core(emulator) is still running on the screen so have to do a reboot it stop it, do not know why, its acting like the core is not part of retroach and runs on it own so killing Retroach does nothing.


Loading Games in TheCarousel Amora v1.6.1(All THEC64 Models Only)
======================================================


You can load your own Games on THEC64 Carousel Amora v1.6.1, THEC64 Maxi Carousel, all THEC64 models use it now.
You can add your own games in its carousel, a set of games(for C64 and VIC20) are now inclued with PCUAE All In One Version and are included with PCUAE Manager too so you can export them to the PCUAE USB Drive, to enable PCUAE Mode on THEC64 Models you need to export over Favories 1 Gameslist to THEC64-CAROUSEL-GAMES folder on the root of THE PCUAE USB Drive for it to see the gameslists you add, you can add what games you like in the Favories 1 Gamelist in PCUAE Manager, it will need games adding to it if the carousel see no games at all it will not load the carousel, if favorites 1 is not added then a blue screen will apear and say there is no Favortes 1 Gamelist and then load the Firmware carousel with its default games instead of PCUAE Mode.


Quick Info On Modes
==================


You can run C64 or VIC20 games on THEC64 Carousel on THEC64 Mini and switch from PAL to NTSC and back on THEC64 Mini/THEC64/THEVIC20.


You can load VICE Mode and load C64 games on THEC64 and THEA500. (the pack is availble on here)


You can connect to the internet and load up BBS borads in VICE Mode in THEC64.(THEC64 Only)


You can load Amiga(16bit), Atari(8bit), Vice(C16/plus4,C64,VIC20,C128,8bit) and RetroArch(RA) Modes on THEC64 and THEA500, THEA500 can run Pandory Mode instead of RetroArch Mode(the packs are availble on here).


On THE A500 Mini - CD32 Mode, load a CD32 game from StartUp and turn THEA500 Mini into the Amiga CD32 Console, Load a ADF file in ADF Mode and load it from StartUp, like your loading a real floppy disk.


You can run AGS 500 Mode(A500 Games Selector 1.5) on THEA500 Mini from Startup, load a collection of games and apps on the Arcade Games Selector(it will need the HDD folder for it to work).


There are more features on THEC64 cause its been out longer then THEA500 Mini and its not locked down like THEA500 Mini is, I think RGL did this cause they do not like there machines being modified.



Where Did The PCUAE Name Came From:
==========================


"It all started with mounting over the games on THEC64 Maxi carousel, I made a script so you could start it from the fake update and change the games on the carousel so thats why it was called Project Carousel USB(named after Carousel USB Chooser)... :), the first mode I added was Vice Mode and then the Carousel Gamelist Changer scripts became PCU Mode named after its name abrivated then changed to PCUAE Mode."


FAQ
====

Where are the games kept for THEC64 Carousel
=============================================


There are in the `THEC64-CAROUSEL-GAMES` folder on the root of the PCUAE USB Drive now, they are not in the `Games` folder no more, make sure you changee the location when you export your games over from PCUAE Manager, it using the old location.



What are the PCUAE Shortcut Key Combinations




How To - Press and Hold Down the CTRL key and then press the key you want to use for 2 seconds in PCUAE Mode below.


CTRL+F1 – Carousel Gamelist Changer – Select one of the gamelist on the screen to load in the Carousel - Not Available on THEA500 yet.


CTRL+F3 – Carousel Version Changer – Change to a different carousel version 1.0.5,1.6.1 THEC64 or 1.0.0,1.1.1 THEA500.


CTRL+F5 – Mode Changer – Change to a different Mode(Amiga, Atari, Linux, Retroarch, VICE Modes.. etc). 


(THEC64/THEVIC20)CTRL+RESTOR, (THEA500)CTRL-END – Reboot the Machine – This makes the machines reboot, not the emulator – Just reboots, nothing special, you never know when you need a reboot/reset button… 🙂 and it saves on you pressing the power button all the time and wearing the power button out, thats why I added it.


(THEC64/THEVIC20)CTRL+LEFT SHIFT+DEL, (THEA500)CTRL+LEFT ALT+DEL  - Shutdown, this will power off the machine, I added it cause I was sick of pulling the power cable out all the time on THEA500 Mini, it dose not shuttdown without the carousel running, if you press and HOLD the power button, if you hold it for more then 7 seconds it makes it do a restart and not power off(werid).


You can go back to PCUAE Mode at any time by using the `Quick Shortcut back to PCUAE Mode`, its:


On THEC64/THEVIC20 THEC64 Joystick - Menu+Left Triangle Button.

On THEA500 - Menu+B(Blue) buttons.

On THEC64 Mini/THEC64/THEVIC20/THEA500 Mini keyboard - CTRL+F3, 

this will not work on PCUAE Mode cause your already in the mode, this only works on any other Mode... :)





If the program needs Firmware v1.0.0 then use Carousel Version Changer to change the Carousel to the version you need, you can use CTRL+F3 on a USB or THEC64 Keyboard or Menu+Left Triangle Button on THEC64, Menu+Y on THEGampad to load The Carousel Version Changer on PCUAE Mode only.


For more info on the Modes in PCUAE, go to... `How to Use the Modes`, its at section 12 of the WIKI.




What are THEC64 Joystick Button Combinations
==============================================


Menu, Fire and the Triangle buttons – Press and Hold the Menu Button and then press the Left Fire, Right Fire or the Left, Right Triangle buttons you want to use for 2 seconds in PCUAE Mode, this makes it easier for you use PCUAE mode on THEC64 Mini, THEC64 Joystick now works in the menus on THEC64 Mini too now.


Menu+Left Fire 1 Button – TheCarousel Gamelist Changer – Change to a different Carousel Gamelist thats been added with the PCUAE Manager in PCUAE Mode Only and only on THEC64 Mini/THEC64/THEVIC20.


Menu+Left Triangle Button – Carousel Version Changer – Change to a different Carousel version - THEC64 Carousels 1.0.5, 1.6.1 in PCUAE Mode Only.


Menu+Right Triangle Button – Mode Changer – Change to a different Mode(Amiga, Atari, Linux, Retroarch and VICE Modes) in PCUAE Mode Only.


Menu+C - Quick Restart - Reboot THEC64 and Activate the PAL/NTSC Video Screen on TheCarousel v1.6.1 only(not avalible on v1.0.5).


I found out this only works on THEC64 Mini not THEC64, it makes the Languges come up but the PAL/NTSC Video screen is not showing, I think its because its not seeing the HDMI so it works on THEC64 Mini cause it can not see disp device so can not detect the HDMI signal, I think it has to do with this line `mv /dev/disp /dev/disp-not` I keep digging.




What are THEA500 THEGAMEPAD Button Combinations
==============================================


Press and Hold the Menu Button and then press the A, X, Y or B buttons you want to use and hold both down for 2 seconds.


Menu+Y Button – Carousel Version Changer – Change to a different Carousel versions - Manhattan - 1.0.0, 1.1.1, Amiberry 5 and ADF Modes in PCUAE Mode Only.


Menu+X Button – Mode Changer – Change to a different Mode(ADF, Amiga, Atari, Linux, Retroarch(Pandory) and VICE Modes) in PCUAE Mode Only.


Menu+B Button – Quick Switch – Back to PCUAE Mode(if your in a different Mode then PCUAE Mode so you can quickly go back to PCUAE Mode without havinbg to load the Mode Changer).


Menu+Home - Restart - Reset the Mode its on.


Menu+RSB - Quick Switch - Switch between Amiberry 3.3 and 5.3 and back in the carousel, so you can run Amiberry v5.3 in the carousel if you like.



How do you add games to AMIGA Mode
==============================================


PCUAE will have a new folder in PCUAE 3.1.0 that is for Amiga Games only and you be able to put the game files in a HDF file so you will need to use `WinUAE` to copy them to the HDF file to add more and the HDF file is 1.95GB.
Download `WinUAE` from here, you can use the latest version... https://www.winuae.net/download/


PCUAE will have a folder in it called `WHDLoad-Games` on the root of the USB Drive, it will have a HDF file in it, this is where you put your Amiga games, you have to load Workbench in `WinUAE` and then add the `WHDLoad-Games-1.hdf` file first then copy them over that way.
Add the `WHDLoad` Games that are in `LHA` format in `WinUAE` so put them in a folder and then add the folder to `WinUAE` and then extract them to the `WHDLoad-Games-1.hdf` drive that will be in the `WHDLoad-Games` folder using Directry Opus so then they are unpacked properly.


DO NOT use Winrar to unpack WHDLoad Games in LHA format, you will mess them up and they will not load.


You can load other programs made for THEA500 Mini in PCUAE by puting them in the THEA500-USB-MENU folder, that where THEA500 Mini USB Drive root is now and you can add games too, ahl files can be put into THEA500-Games folder in the THEA500-USB-MENU folder.


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


IF you feel you want to help me out and give me a Monster Energy or a cup of Tea - https://www.paypal.com/donate/?token=qWVMumPQ58KRZUnjh4khuX2xIMHExwxviGQoH5_64rVv_hNa0ZGivFTSQ8FU8cvoO_KqOJ4KFKV6-xsq&locale.x=EN_US


You can use PCUAE Manager to manage your games on the Carousel and store them, import/export them from/to the PCUAE USB Drive(THEC64 ONLY).


PCUAE Manager on Github - https://thec64community.online/thread/603/pcuae-manager


PCUAE WIKI is here, it should answer any questions you might have about PCUAE.. https://github.com/CommodoreOS/PCUAE/wiki


ANYWAY....PEACE PEOPLE... :) and Enjoy using PCUAE.


Spannernick.

