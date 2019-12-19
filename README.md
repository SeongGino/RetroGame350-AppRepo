# RG-350 & Pocket Go 2 - Application Repo

These are all ports with the best available binaries (.OPKs), at least from my (Seong's) personal testing. Sources (whenever applicable) and activity are listed wherever possible, to hopefully encourage further development of applications for the new generation of OpenDingux-based handhelds; primarily the Anbernic RG-350, but these are also known to work on the BittBoy Pocket Go 2/Miyoo Max.

All apps can be placed inside and ran from either the internal SD card in `/media/data/apps/`, or in the external card in `/media/sdcard/apps/`.

`/media/data/local/share/` and `/usr/local/share/` are the same target directory. If you're using the RG-350, it's recommended to use FTP. The Pocket Go 2 is known to lack the necessary functioning device drivers to have working FTP, so you'll have better luck copying files through the built-in `Dingux Commander` utility.

Anything not found here could be alternatively located within these domains, however we like to keep the focus on the present.

[GCW Zero Homepage](http://www.gcw-zero.com/downloads)

## Games & Ports

| Name | OPK Link | Source | Requires Data Files? |
|----------|:----:|:------:|---------------------:|
Abuse* | [Latest](https://drive.google.com/open?id=1iILjTghcEt90zcsMCN10MChG0fFQCkTB) | Inactive (Source N/A) | No
Arkanoid | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/Arkanoid.opk) | Legacy (Source N/A) | No
Cannonball* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/cannonball.opk) | [Inactive](https://github.com/gameblabla/Cannonballs/raw/master/cannonball.opk) | OutRun (sitdown/upright, Rev B) Data Files (Unzipped), `~/.cannonball/roms/`
Cannon Fodder | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/cannonfodder.opk) | Legacy (Source N/A) | No
Chocolate Doom** *** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/chocolatedoom-selector.opk) | Inactive (Source N/A) | (Final) DOOM (2)/Heretic/Hexen/Strife Data Files
Descent 2 (d2x)* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/d2x-rebirth.opk) | [Legacy](https://boards.dingoonity.org/gcw-general/looking-for-working-descent-2-opk/) | (Optional) Descent 2 Data Files, `~/.d2x-rebirth/`, will fallback to built-in Shareware if not found.
DevilutionX* | [Latest](https://github.com/glebm/devilutionX/releases/latest) | [Active Fork](https://github.com/glebm/devilutionX) | Diablo 1.09b Data File, `~/.local/share/diasurgical/diablo/diabdat.mpq`
ECWolf* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/ecwolf.opk) | [Inactive](https://github.com/JohnnyonFlame/ecwolf) | Wolfenstein 3D/Spear of Destiny Data Files, `~/.ecwolf/`
eDuke32* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/eduke32.opk) | [Inactive](https://github.com/zear/eduke32) | Duke Nukem 3D (Shareware/Registered/Plutonium Pak), `~/.eduke32/`
FreeDink | [Latest](https://drive.google.com/open?id=1NvA25Y0_1Mdh-mzMjvGHMq0J_M3_Q9Jq) | [Inactive](https://www.gnu.org/software/freedink/) | No
Ghouls'n Ghosts Remix | [Latest](http://prizma.bmstu.ru/~exmortis/opk/ggr_056.opk) | [Inactive](https://boards.dingoonity.org/gcw-releases/ghouls-and-ghosts-remix-0-56/) | No
Hexen 2	- Hammer of Thyrion** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/hexen2.opk) | [Inactive](https://github.com/JohnnyonFlame/gcw0-hexen2) | Hexen II Data Files, `~/.hexen2/data1`
Hocoslamfy | [Latest](https://github.com/fgl82/hocoslamfy/releases/latest) | [Active](https://github.com/fgl82/hocoslamfy) | No
KOF - Flames of Courage v5 | [Final (Broken?)](https://drive.google.com/open?id=1BtIlTPLAzYDJ4OWwVfdlndRGOWP81XDr) | [Inactive](https://github.com/gromv/kofv5) | No
Marathon* | [Latest](https://drive.google.com/open?id=147IPd5EKXRzdXOSbD7gSJCpgorC7ce4y) | Active (Source N/A) | No
Marathon 2* | [Latest](https://drive.google.com/open?id=1bieRbLbcv8Dn3yKNflIZcfBkbfCfW7XU) | Active (Source N/A) | No
Marathon Infinite* | [Latest](https://drive.google.com/open?id=1UayihX4pbpY0gyLC-dWnBuvGLNTQeFl9) | Active (Source N/A) | No
Mr.Drillux | [Latest](https://github.com/jbanes/rs97-mrdrillux/releases/latest) | [Inactive](https://github.com/jbanes/rs97-mrdrillux) | No
nKaruga | [Latest](https://gameblabla.nl/files/nkaruga/nKaruga.opk) | [Inactive](https://github.com/gameblabla/nKaruga) | No
NXEngine | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/CaveStory.opk) | Inactive (Source N/A) | No
Odamex* *** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/odamex.opk) | [Inactive](https://github.com/JohnnyonFlame/odamex) | (Final) DOOM (2) Data Files
OpenBOR | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/OpenBOR_3.0_r4165_GCW0_Edition.opk) | [Inactive](https://github.com/DavidKnight247/OpenBOR-for-the-GCW0) | OpenBOR Game Pak Files, `/usr/local/share/OpenBOR/Paks/`
OpenJazz | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/openjazz.opk) | [Inactive](https://boards.dingoonity.org/gcw-development/openjazz-8914/) | Jazz Jackrabbit Data Files, `~/.openjazz/`
OpenSonic | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/opensonic.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/opensonic-0-1-4/) | No
OpenTyrian** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/opentyrian_r1055.opk) | [Inactive](https://github.com/JohnnyonFlame/OpenTyrian) | No
POWDER | [Latest_v117](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/powder_117.opk) | Legacy (Source N/A) | No
Quartermaster | [Latest](https://github.com/hi-ban/quartermaster/releases/latest) | [Active](https://github.com/hi-ban/quartermaster) | No
REminiscence | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/REminiscence.opk) | [Inactive](https://github.com/ElwingGit/GCW0_REminiscence) | Flashback Data Files, `~/.REminiscence/data/`
Rise of the Triad* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/rott.opk) | [Inactive Fork](https://github.com/podulator/RoTT) | Rise of the Triad: The Dark War (Registered Version) Data Files, `~/.rott/data/`
Rockbot | [Latest](https://rockbot.upperland.net/?download=1.20.74%20OpenDingux) | [Inactive](https://github.com/protoman/rockbot) | No
rRootage | [Latest](https://github.com/jamesofarrell/rRootage-for-Handhelds/releases/latest) | [Active](https://github.com/jamesofarrell/rRootage-for-Handhelds) | No
SDLQuake2* | [Latest](https://drive.google.com/open?id=1JZ17OhATuBklEUP5NQ73bVLEv_MmpDj3) | [Inactive Fork](https://github.com/jamesofarrell/SDLQuake2) | Quake II (Shareware/Registered) Data Files, `~/.quake2/baseq2`
Shadow Warrior* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/shadow-warior.opk) | [Inactive Fork](https://github.com/JohnnyonFlame/gcw0-jfsw) | Shadow Warrior (Shareware/Registered) Data Files, `~/.jfsw/sw.grp`
Sonic Robo Blast 2* | [2.1.15](https://drive.google.com/open?id=1Lgg-sNFN8zPFdkbuk5te2CWc9iUY7rF8) | [Inactive Fork](https://github.com/gameblabla/srb2-gcw) | No
Sqrxz (Remake) | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/sqrxz-v.latest-gcw-zero.opk) | Legacy | No
Sqrxz 2: Two seconds 'til death | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/sqrxz2-v.latest-gcw-zero.opk) | Legacy | No
Sqrxz 3: Adventure for Love | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/sqrxz3-v.latest-gcw-zero.opk) | Legacy | No
Sqrxz 4: Cold Cash | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/sqrxz4-v.latest-gcw-zero.opk) | Legacy | No
Strange Adventure in Infinite Space | [Latest](https://drive.google.com/file/d/1YZFVwSeDw-kaic5O6X7FOLA-EBeOW1HI/view?usp=sharing) | Active (Source N/A) | No
Streets of Rage Remake v5.1 | [Latest](https://drive.google.com/open?id=1cKkZOzmYBQoocJadpLo2i8eDItSNAwCU) | [Legacy](https://sega.com) | No (Recommended to set `Video Options -> Shadows` from `Reflected` to `SOR` type to mitigate crashes.)
SuperTux | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/supertux.opk) | [Inactive](https://github.com/dmitrysmagin/supertux) | No
UMG-v0.4Demo | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Games-Ports/umg-gcw-exclusive-preview-0.4.opk) | [Legacy](http://artur-rojek.eu/umg.php) | No

Index:

*:Accepts all RG350/PG2 inputs (dual sticks, secondary triggers and stick clicks)

**:Accepts most RG350/PG2 inputs, but in a limited capacity (i.e. can only use one joystick, doesn't register stick clicks, etc.)

***:Uses frontend file explorer for input.

---

## Emulators

Unless specified, emulators use the frontend's file explorer for ROM files, or have been modified to do so.

| Emulated System(s) | Name | OPK Link | Source | Requires System Files? |
|--------------------|:------:|:--------:|:------:|-----------------------:|
Amstrad CPC | CrocoDS | [2019-11-23](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/CrocoDS_2019-11-26.opk) | [Active](https://www.kyuran.be/rg350/) | No
Arcade - FBA (0.2.97.35) | FinalBurnAlpha | [2019-11-26-rotation+launcher](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/FinalBurnAlpha_2019-11-26-launcher.opk) | [Active](https://github.com/tonyjih/fba-sdl) | Varies, use `FBA - Setup` to set ROM paths using app interface.
Arcade - Laserdisc) | Daphne | [2015-05-07](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Daphne_2015-05-07.opk) | [Inactive](https://github.com/DavidKnight247/Daphne) | [Compatible Laserdisc Games (Tutorial Link)](https://boards.dingoonity.org/gcw-releases/daphne/)
Arcade - MAME (0.52, 0.69, 0.84) | XMAME (Installer)* | [2015-03-15](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/XMAME_2015-03-15.opk) | [Inactive](http://www.slaanesh.net/2014/12/xmame-v10-for-gcw-zero.html) | Internal: `/usr/local/share/xmame/(xmame52 OR xmame69 OR xmame84)/roms`, External: `/media/sdcard/apps/xmame/(xmame52 OR xmame69 OR xmame84)/roms`
Atari VCS (2600) | Stella | [2015-10-06](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Stella_2015-10-06.opk) | [Inactive](https://github.com/DavidKnight247/Stella-3.9.3) | No
Atari 5200 | a5200 | [2013-06-15-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/a5200_2013-06-15-launcher.opk) | [Inactive](https://boards.dingoonity.org/gcw-releases/a5200-v1-0/) | Atari 5200 BIOS, `~/5200.rom`
Atari 7800 | ProSystem | [2013-06-16-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/ProSystem_2013-06-16-launcher.opk) | [Inactive](https://github.com/alekmaul/prosystem) | No
Atari Lynx | Handy | [Latest (2019-12-10)](https://gameblabla.nl/files/ipk/gcw0/handy_gcw0.opk) | [Active](https://github.com/gameblabla/handy-rs97) | No
Atari ST | DCaSTaway* | [2014-11-09](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/DCaSTaway_2014-11-09.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/dcastaway-an-atari-st-emulator/) | Atari ST TOS ROM
Bandai Wonderswan (B/W, Color) | Oswan | [2017-09-08](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Oswan_2017-09-08.opk) | ['Soon to be replaced'](https://github.com/gameblabla/oswan) | No
Colecovision | ColecOD | [2013-06-15-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/ColecoD_2013-06-15-launcher.opk) | [Inactive](https://boards.dingoonity.org/gcw-releases/colecod-v1-0/) | No
Intellivision | JzIntv | [2015-03-28](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/jzIntv_2015-03-28.opk) | [Inactive](https://github.com/DavidKnight247/jzIntv) | No
Commodore 64 | VICE* | [2019-12-11](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/VICE-C64_2019-12-11.opk) | [Legacy](https://boards.dingoonity.org/gcw-zero-emulation/(testing)-vice-2-3/) | No
Commodore 64(DTV), 128, PET, VIC-20, Plus-4 | VICE (Launcher Mod)** | [2019-12-11](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/VICEstandalone_2019-12-xx.zip) | Inactive Fork (Source N/A) | VICE Data Folder, extract `VICE` folder to `/usr/local/share/` so that `x64` is in `/usr/local/share/VICE/x64`
Commodore Amiga | UAE4All* | [2014-12-02](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/UAE4All_2014-12-02.opk) | [Inactive](https://github.com/zear/uae4all) | Amiga 500 Kickstart ROM, `~/.uae4all/kick.rom`
MSX (1, 2, 2+) | OpenMSX	| [v0.15 (2018-12-08)](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/OpenMSX_2018-12-08.opk) | [Upstream](https://github.com/openMSX/openMSX) | (Optional) BlueMSX Compatible System Folders, Configurable
MS-DOS | DOSBox v0.74 | [2019-11-11-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/DOSBox_2019-11-11-launcher.opk) | [Active Fork](https://github.com/soarqin/dosbox-rg350) | No
Point-and-Click Adventure Games | ScummVM*	| [Latest](https://github.com/jbanes/scummvm/releases) | [Active Fork](https://github.com/jbanes/scummvm) | No
Nintendo Entertainment System, Famicom Disk System | FCEUX | [2019-11-15](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/FCEUX_2019-11-15.opk) | [Active Fork](https://github.com/soarqin/fceux-for-retrogame) | No
Nintendo Entertainment System, Famicom Disk System (High Accuracy) | Nestopia (ALPHA) | [Upstream](https://github.com/Derynect/nestopia/releases/latest) | [Active](https://github.com/Derynect/nestopia) | ?
Nintendo Game Boy (DMG, Color) | Gambatte | [2019-12-01](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Gambatte_2019-12-01.opk) | [Active Fork](https://github.com/bardeci/dot-matrix-simulator) | No
Nintendo Game Boy Advance | ReGBA | [Original_2014-08-21](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/ReGBA_2014-08-21.opk), [Latest_2019-10-21](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/ReGBA_2019-10-21.opk) | [Active Fork](https://github.com/soarqin/ReGBA) | (Optional) Game Boy Advance BIOS, `~/.gpsp/gba_bios.bin`
NEC PC-Engine/TurboGrafx-16, CD System | Temper | [2016-10-20](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Temper_2016-10-20.opk) | [Inactive](https://github.com/gameblabla/temper) | (Optional) PC-Engine Super System Card 3, `~/.temper/syscards/syscard3.pce`
NEC PC-FX, NEC PC-Engine/TurboGrafx-16, Others | Mednafen | [2016-12-03](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Mednafen_2016-12-3.zip) | [Inactive](https://github.com/gameblabla/mednafen-gcw) | Various
Neo-Geo Pocket (B/W, Color) | NGPCEmu	| [Latest (2019-12-11)](https://gameblabla.nl/files/ipk/gcw0/ngpcemu_gcw0.opk) | [Active](https://github.com/gameblabla/NGPCemu) | No
PlayStation | PCSX4All-Gamebla's C++ (Faster?) | [Latest (2.4_2019-11-29)](https://gameblabla.nl/files/ipk/gcw0/pcsx4all_rg350.opk) | [Active Fork](https://github.com/gameblabla/pcsx4all_rs97_rg350) | PlayStation BIOS, `~/.pcsx4all/bios/`
PlayStation | PCSX4All-soarqin's C (DualShock Compatible) | [2.4_2019-12-12](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/PCSX4All_2019-12-12.opk) | [Active Fork](https://github.com/soarqin/RG350_pcsx4all) | PlayStation BIOS, `~/.pcsx4all/bios/`
Sega Master System, Game Gear | SMS Plus GX | [Latest (2019-11-29)](https://gameblabla.nl/files/ipk/gcw0/smsplus_gcw0.opk) | [Active](https://github.com/gameblabla/sms_sdl) | No
Sega Genesis/Mega Drive, Master System, Game Gear, SG-1000 | Genesis Plus GX | [2016-02-29](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/GenesisPlusGX_2016-02-29.opk) | [Inactive](https://github.com/DavidKnight247/Genesis-Plus-GX) | No
Sega Genesis/Mega Drive, CD, 32X, Master System | PicoDrive | [Latest (1.95_2019-12-11)](https://gameblabla.nl/files/ipk/gcw0/picodrive_gcw0.opk) | Active (Source N/A) | (Optional) Sega/Mega CD BIOS Images, `~/.picodrive/`
Super Nintendo Entertainment System (Fast, Low Accuracy) | PocketSNES | [2019-12-12](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/PocketSNES_2019-12-12.opk) | [Active](https://github.com/soarqin/PocketSNES) | No
Super Nintendo Entertainment System (High Accuracy, Slow) | Snes9x | [2019-11-11](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/Snes9x_2019-11-11.opk) | [Active Fork](https://github.com/soarqin/snes9x) | No
ZX Spectrum | Unreal Speccy Portable | [2013-05-13](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Emulators/UnrealSpeccyPortable_2013-05-13.opk) | [Inactive](https://github.com/DavidKnight247/Unreal-Speccy-Emulator-GCW0-Edition) | No

### Index:

*: Emulator uses its own frontend for setup and/or selection

**: Emulator uses its own frontend for setup, required to use system frontend launcher

---

## Frontends

| Name | OPK Link | Source |
|------|:--------:|-------:|
350teric (Formerly GMenuNX-Dingux Fork) | [Latest](https://github.com/podulator/esoteric/releases/latest) | [Active](https://github.com/podulator/esoteric/)
SimpleMenu | [Latest](https://cdn.discordapp.com/attachments/625718299493138442/653454972733751296/simplemenu.opk) | [Active](https://github.com/fgl82/simplemenu)

### Index:

350teric (Pronounced "Esoteric"): Based on GMenu2x, similar to GMenuNX (RetroFW) with additions such as preview images, extended skin customization, etc.

SimpleMenu: A new menu system with focus on usability and aesthetic/functional simplicity.

---

## Applications

| Name | OPK Link | Source |
|------|:--------:|-------:|
Bard Storyteller (Ebooks) | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Applications/Bard_0.10.0.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/bard-storyteller-ebook-reader-with-text-to-speech/)
FFPlay | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Applications/ffplay-gcw0.opk) | [Inactive](https://github.com/denis-n-kuznetsov/FFmpeg-GCW0)
Glutext | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Applications/glutexto.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/glutexto-1-2/)
GMU | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Applications/gmu-0.10.1-gcw0.opk) | [Inactive](https://github.com/denis-n-kuznetsov/gmu)
Input Tester | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Applications/input-test.opk) | [Active](https://github.com/tonyjih/RG350_input-test)
Oldplay | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/Applications/oldplay_v135.zip) | [Legacy](https://boards.dingoonity.org/gcw-releases/oldplay-for-opendingux/)
