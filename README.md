# Original Name - On 14 April 2020 - **Project Carousel USB** - On the 9th October 2020, renamed to - **Project Carousel USB: Anniversary Edition** on THEC64 Mini NTSC 2 year Anniversary, `Project` came from `Project Luna` and `Carousel USB` came from `Carousel USB Chooser` so that how it got its name... :)

![](https://thec64community.online/attachment/download/561)

If you are having a problem with PCUAE running properly then use this version, its only for THEC64 Models so not for THEA500, it was made before it... https://github.com/CommodoreOS/PCUAE/releases/tag/v1.8.5bf10
I hope if everything goes to plan, that the next version will be relased in the next 2 days(PCUAE 3.1.0), Figners Crossed, I am just trying to make sure everything works before I release it... :)

PCUAE Sites have now been closed down, sorry about this but its the best way forward, PCUAE does not really need a website, it creates more work so have to keep it up todate and that so then have to work on that too and PCUAE too so do not have anytime for it, only time I have is used working on PCUAE, thats was the problem with the website before so do not want that to happen again.


Any info or you want to discuss PCUAE go to THEC64 Community Forum - https://thec64community.online


"PCUAE now contains host-rum from the Pandory500 mod"... https://github.com/emuchicken/pandory-a500


It will from now on include host-rum.adf file from Pandory so it can boot PCUAE using it, thanks Dajoho and Team Pandory.


So this is the only version thats available now and older versions but they are before THEA500 was added.


I will always try to support PCUAE, but do need a break from it from time to time... :)


WIKI - PCUAE Manual is here - https://github.com/CommodoreOS/PCUAE/wiki


Coming soon in next version - I added some code so you see the Green Hard Drive LED flash as PCUAE is loading on THEA500 Mini so you know its doing something... :)


I have no plans of PCUAE being ported to THEA500 Full Size Version(if it gets made, PCUAE might work out of the box if its the same as THEA500 Mini and just bigger (like THEC64 Mini is the same as THEC64), I do not plain on buying one, no money and I have full sized Amigas already so it don't really interest me, I got THEA500 Mini causes its small and not in the way and to port PCUAE to it and goes with all my other minis, just wanted you to know.


Thinking about it now and if RGL make A1200 then maybe, the A600 and the A1200 are the best keyboard Amigas Commodore made and as well as the A3000 and A4000 Big Boxed Amigas... :) I think now RGL can now get the AMIGA name...why... Cloanto now own the right to its name but we will see.


TODO: Add emulators as Modes: Atari - ST, ScummVM, Master System, Mega Drive, MegaCD, DOOM.

If you have any idea you like me to try and add plaese post about them on here or on THEC64 Community Forum.


# HELP READ ME


# Key Highlights of PCUAE:


PCUAE is not a hack, it does not hack the machines or copy over its firmware or change it, its a mod, it modifies the way the machine boots so it boots from the USB Drive using a script, it called the `Autoboot Mode Start-Up Script`, its in the boot folder on the PCUAE USB Drive and called `autobootfirmware.sh` and its sent to the `int.d` folder in the firmware, the same place its script is that tells it to run the carousel when the console starts up, and is the only thing that is copied to the fimware and it can boot from the firmware or from the PCUAE USB Drive when it see it plugged in, from start up, it does not touch the firmware at all and all the modifcations added are from the USB Drive only, once you take out the drive then the machine is back to booting up from the firmware from start up.
You can remove the Autoboot Start-Up Script if you wish too, you can add it or remove it, you remove it using The Mode Changer Menu or PCUAE Options Menu.


You can find me on YouTube too under Retronuts and on there are some videos of PCUAE - YouTube channel is here - https://www.youtube.com/channel/UCrG1jnbvykIcLzfBFxC2GrA 


(Do not watch youtube videos from a phone or the Youtube app, you will get loads of adds, they play on youtube like every 10/15 minutes or so and cut into the video, use Google Chrome or Edge and then use the (ABP) Add Blocker Plus Extension, its free, best way to watch add free, you do not need to pay Google to watch videos on Youtube add free.. :) )


You can run each Mode from StartUp cause PCUAE can Autoboot itself with Autoboot Mode and its Start-Up Script.


THEC64 Only:
You can load your own Games on THEC64 Carousel so add your own games to its carousel(There is a game pack availble on here too for the carousel) with PCUAE Manager, not avalible at the moment on THEA500 Mini.. :( its down to how RGL designed THEA500 Carousel on THEA500 Mini, they designed it in a way to stop you doing it, so its down to RGL not me, THEA500 Carousel needs hacking so it can do it, I am not a hacker so can not hack into it, I am a scripter.


You can run C64 or VIC20 games on THEC64 Carousel on THEC64 Mini and switch from PAL to NTSC and back on THEC64 Mini/THEC64/THEVIC20.


You can load VICE Mode and load C64 games on THEC64 and THEA500. (the pack is availble on here)


You can connect to the internet and load up BBS borads in VICE Mode in THEC64.(THEC64 Only)


You can load Amiga(16bit), Atari(8bit), Vice(C16/plus4,C64,VIC20,C128,8bit) and RetroArch(RA) Modes on THEC64 and THEA500, THEA500 can run Pandory Mode instead of RetroArch Mode(the packs are availble on here).


On THE A500 Mini - CD32 Mode, load a CD32 game from StartUp and turn THEA500 Mini into the Amiga CD32 Console, Load a ADF file in ADF Mode and load it from StartUp, like your loading a real floppy disk.


You can run AGS 500 Mode(A500 Games Selector 1.5) on THEA500 Mini from Startup, load a collection of games and apps on the Arcade Games Selector(it will need the HDD folder for it to work).


There are more features on THEC64 cause its been out longer then THEA500 Mini and its not locked down like THEA500 Mini is, I think RGL did this cause they do not like there machines being modified.



# How to Download and install PCUAE:


You can use PCUAEManager and installing it that way and its modes: [Download PCUAEManager here](https://1drv.ms/u/s!AsiWKsjhQ2jelNJtFoF1RSaRBwx5Iw?e=3s5Ja5).



Where The Name Came From:
=============================

"It all started with mounting over the games on the carousel, I made a script so you could start it from the fake update and change the games on the carousel so thats why it was called Project Carousel USB(named after Carousel USB Chooser)... :), the first mode I added was Vice Mode and then the Carousel Gamelist Changer scripts became PCU Mode named after its name abrivated then PCUAE Mode."


TIPS
=====

If you want to go back to PCUAE Mode at any time and for some reason it don't change Modes then use the Quick Shortcut back to PCUAE Mode, its Menu+Left Triangle Button or on THEA500 Mini - Menu+B(Blue) buttons or on THEC64 Mini/THEC64/THEVIC20/THEA500 Mini keyboard - CTRL+F3, this will not work on PCUAE Mode cause your already in the mode, this only works on any other Mode.


You can load other programs made for THEA500 Mini in PCUAE by puting them in the THEA500-USB-MENU folder, that where THEA500 Mini USB Drive root is now and you can add games too, ahl files can be put into THEA500-Games folder in the THEA500-USB-MENU folder.


If the program needs Firmware v1.0.0 then use Carousel Version Changer to change the Carousel to the version you need, you can use CTRL+F3 on a USB or THEC64 Keyboard or Menu+Left Triangle Button on THEC64, Menu+Y on THEGampad to load The Carousel Version Changer on PCUAE Mode only.


PCUAE Shortcut Combinations
=======================

Key Combinations


For more info on the Modes in PCUAE, go to... `How to Use the Modes`, its at section 12 of the WIKI or THE PCUAE PDF Manual. CTRL and the F Keys – Press and Hold Down the CTRL key and then press the F key you want to use for 2 seconds in PCUAE Mode below.


CTRL+F1 – Carousel Gamelist Changer – Select one of the gamelist on the screen to load in the Carousel - Not Available on THEA500 yet.


CTRL+F3 – Carousel Version Changer – Change to a different carousel version(1.0.5,1.6.1 or 1.0.0,1.1.1) and CD32(Pro Only) and ADF Modes on THEA500. 


CTRL+F5 – Mode Changer – Change to a different Mode(Amiga, Atari, Linux, Retroarch, VICE Modes). 


CTRL+F7 – PCUAE Options Menu – A menu with options in it for PCUAE Mode.


CTRL+RESTORE – Reboot the Machine(CTRL+END on THEA500 Mini on a USB Keyboard) – This makes the machine reboot, not the emulator – Just reboots, nothing special, you never know when you need a reboot/reset button… 🙂 and it saves on you pressing the power button all the time and wearing the power button out, thats why I added it.


(THEA500)CTRL+LEFT ALT+DEL, (PCUAE)CTRL+LEFT SHIFT+DEL - Shutdown, this will power off the machine, I added it cause I was sick of pulling the power cable out all the time on THEA500 Mini, it dose not shuttdown without the carousel running, if you press and HOLD the power button, if you hold it for more then 7 seconds it makes it do a restart and not power off(werid).


THEC64 Joystick Button Combinations
======================================


Menu, Fire and the Triangle buttons – Press and Hold the Menu Button and then press the Left Fire, Right Fire or the Left, Right Triangle buttons you want to use for 2 seconds in PCUAE Mode, this makes it easier for you use PCUAE mode on THEC64 Mini, THEC64 Joystick now works in the menus on THEC64 Mini too now.


Menu+Left Triangle Button – Carousel Version Changer – Change to a different Carousel version - THEC64 Carousels 1.0.5, 1.6.1.


Menu+Right Triangle Button – Mode Changer – Change to a different Mode(Amiga, Atari, Linux, Retroarch and VICE Modes).


Menu+Left Fire 1 Button – TheCarousel Gamelist Changer – Change to a different Carousel Gamelist thats been added with the PCUAE Manager.


Menu+Right Fire 2 Button – PCUAE Options Menu – A menu with options in it for PCUAE Mode.



THEGAMEPAD Button Combinations
===============================


Press and Hold the Menu Button and then press the A, X, Y or B buttons you want to use and hold both down for 2 seconds.


Menu+Y Button – Carousel Version Changer – Change to a different Carousel versions - Manhattan - 1.0.0, 1.1.1, CD32(Pro Only) Amiberry 5 and ADF Modes on THEA500.


Menu+X Button – Mode Changer – Change to a different Mode(ADF, Amiga, Atari, Linux, Retroarch(Pandory) and VICE Modes).


Menu+B Button – Quick Switch – Back to PCUAE Mode.


Menu+A Button – PCUAE Options Menu – A menu with options in it for PCUAE Mode.


Menu+Home - Restart - Reset the Mode its on.


Menu+RSB - Quick Switch - Switch between Amiberry 3.3 and 5.3 and back in the carousel.



PCUAE License
==============


Project Carousel USB Anniversary Edition(PCUAE) by Spannernick, 


Idea by Spannernick, Carousel USB Chooser by FaberfoX(Carousel Gamelist Changer on THEC64), 


Fake Update by jj0, cyanic and raxrip who created the firmware unpacker/packer that makes this possible on THEC64, 


Load Carousel Games from the USB Drive using Carousel Gamelist Changer and have different carousel gamelists on TheCarousel(THEC64 Only at the moment), 


JIFFYDOS 6 is included, 


C64 SID Music playing in the background, plays different SID Music on each Carousel Gamelists on TheCarousel C64 0 to G, H to R and S to Z(THEC64 ONLY).


**This is free for non commercial use - NOT to SELL**


THEC64 Mini, THEC64, THEVIC20, THEA500 Mini - Copyright(c) 2022 RETRO GAMES LTD - https://retrogames.biz


IF you feel you want to help me out and give me a Monster Energy or a cup of Tea - https://www.paypal.com/donate/?token=qWVMumPQ58KRZUnjh4khuX2xIMHExwxviGQoH5_64rVv_hNa0ZGivFTSQ8FU8cvoO_KqOJ4KFKV6-xsq&locale.x=EN_US


You can use PCUAE Manager to manage your games on the Carousel and store them, import/export them from/to the PCUAE USB Drive(THEC64 ONLY).


PCUAE Manager on Github - https://thec64community.online/thread/603/pcuae-manager


PCUAE WIKI is here, it should answer any questions you might have about PCUAE.. https://github.com/CommodoreOS/PCUAE/wiki


You can change to different Modes(Emulators) on THEA500 Mini in PCUAE only but can not add games to its Carousel like you can with THEC64, RGL(Retro Games Ltd) have built the carousel this way on purpose so you can not add games to its carousel, proberly cause they are thinking about how much money they are making from THEA500 more but thats why they made the machines in the first place, to make money from it and I gusess to make sure they do not lose money, I would not care if anyone moded it cause it helps selling it, like what happen to the PS Classic, hacking made it a better console and users started to buy it cause of Bleemsync.


ANYWAY....PEACE PEOPLE... :) and Enjoy using PCUAE.


Spannernick.

