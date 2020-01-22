# OpenDingux Application Repo

These are all ports with the best available binaries (.OPKs), at least from my (Seong's) personal testing. Sources (whenever applicable) and activity are listed wherever possible, to hopefully encourage further development of applications for the new generation of OpenDingux-based handhelds; primarily the Anbernic RG-350, but these are also known to work on the BittBoy Pocket Go 2, and may also retain compatibility with the GCW Zero. **Do note, however, that the Game Kiddy 350H - another handheld that runs OpenDingux - is known to have compatibility issues with many software that use IPU scaling or GPU functions.**

All apps can be placed inside and ran from either the internal SD card in `/media/data/apps/`, or in the external card in `/media/sdcard/apps/`.

`/media/data/local/share/` and `/usr/local/share/` are the same target directory. If you're using the RG-350, it's recommended to use FTP. The Pocket Go 2 is known to lack the necessary functioning device drivers to have working FTP, so you'll have better luck copying files between cards through the built-in `Dingux Commander` utility.

Many would recommend that you use the latest available stable firmware for your device. If you encounter any issues, make sure to refer to the official documentation for the latest firmware and basic instructions respective to your device:

* [Anbernic RG-350](https://github.com/retrogamehandheld/RG-350/wiki/Firmware-and-Software-Updates)

* [Bittboy Pocket Go 2](https://github.com/retrogamehandheld/PocketGo2/wiki/Firmware-and-software-updates)

* [GCW Zero](http://www.gcw-zero.com/updates)

## Games & Ports

| Name | OPK Link | Source | Requires Data Files? |
|----------|:----:|:------:|---------------------:|
AAAA (Adamant Armor Affection Adventure) | [Latest](https://github.com/0x64c/aaaa-gcw0/releases/latest) | [Inactive](https://github.com/0x64c/aaaa-gcw0) | No
Abuse* | [Latest](https://drive.google.com/open?id=1iILjTghcEt90zcsMCN10MChG0fFQCkTB) | Inactive (Source N/A) | No
Arkanoid | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/Arkanoid.opk) | Legacy (Source N/A) | No
Cannonball* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/cannonball.opk) | [Inactive](https://github.com/gameblabla/Cannonballs) | OutRun (sitdown/upright, Rev B) Data Files (Unzipped), `~/.cannonball/roms/`
Cannon Fodder | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/cannonfodder.opk) | Legacy (Source N/A) | No
Cave Story (NXEngine) | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/CaveStory.opk) | Inactive (Source N/A) | No
C-Dogs SDL | [0.6.6](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/cdogs-sdl_0.6.6.opk) | [Inactive (Upstream deprecated)](https://github.com/cxong/cdogs-sdl) | No
Chocolate Doom** *** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/chocolatedoom-selector.opk) | Inactive (Source N/A) | (Final) DOOM (2)/Heretic/Hexen/Strife Data Files
Descent 1 (d1x)** | [RetroFW ver.](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/d1x-rebirth.opk) | Inactive (Source N/A) | (Optional) Descent Data Files, `~/.d1x-rebirth/`, will fallback to built-in Shareware if not found.
Descent 2 (d2x)* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/d2x-rebirth.opk) | [Legacy](https://boards.dingoonity.org/gcw-general/looking-for-working-descent-2-opk/) | (Optional) Descent 2 Data Files, `~/.d2x-rebirth/`, will fallback to built-in Shareware if not found.
DevilutionX* | [Latest](https://github.com/diasurgical/devilutionX/releases) | [Upstream](https://github.com/diasurgical/devilutionX) | Diablo 1.09b Data File, `~/.local/share/diasurgical/diablo/diabdat.mpq`
EasyRPG Player | [Latest](https://gameblabla.nl/files/ipk/gcw0/EasyRPG_gcw0_rg350.opk) | Active (Source N/A) | RPG Maker 2000/2003 Games, RTP files go in `~/.easyrpg/{rtp2k OR rtp2k3}`
ECWolf* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/ecwolf.opk) | [Inactive](https://github.com/JohnnyonFlame/ecwolf) | Wolfenstein 3D/Spear of Destiny Data Files, `~/.ecwolf/`
eDuke32* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/eduke32.opk) | [Inactive](https://github.com/zear/eduke32) | [Fixed eDuke32.cfg configuration file for RG350](https://github.com/SeongGino/RetroGame350-AppRepo/blob/master/eduke32.cfg) + Duke Nukem 3D (Shareware/Registered/Plutonium Pak), `~/.eduke32/`
Fade to Black | [Gamebla's Latest](https://github.com/gameblabla/f2bgl/raw/master/f2bgl.opk) | [Inactive](https://github.com/JohnnyonFlame/f2bgl-optimized) | Fade to Black data files, `~/.fadetoblack/`
Falling Time | [Latest](https://github.com/cxong/FallingTime/releases/download/1.0/falling_time.opk) | [Inactive](https://github.com/cxong/FallingTime) | No
Finite | [Latest](https://github.com/jxv/finite/releases) | [Inactive](https://github.com/jxv/finite) | No
FreeDink | [Latest](https://drive.google.com/open?id=1NvA25Y0_1Mdh-mzMjvGHMq0J_M3_Q9Jq) | [Inactive](https://www.gnu.org/software/freedink/) | No
Ghouls'n Ghosts Remix | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/GhoulsAndGhostsRemix-0.56-1.opk) | [Inactive](https://github.com/podulator/ggr_056) | No
Griffon Legend | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/griffon.opk) | [Inactive](https://github.com/dmitrysmagin/griffon_legend) | No
Hase | [Latest](http://ziz.openhandhelds.org/hase/hase.opk) | [Active](https://github.com/theZiz/hase) | No
Heroes of Might & Magic 2 | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/fheroes2.opk) | [Legacy (Archive)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/SourceArchives/fheroes2.gcw0.src.zip) | HMM2 Data Files, `data` folder to `~/.fheroes2/data` & `maps` folder to `~/.fheroes2/maps`
Hexen 2	- Hammer of Thyrion** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/hexen2.opk) | [Inactive](https://github.com/JohnnyonFlame/gcw0-hexen2) | Hexen II Data Files, `~/.hexen2/data1`
Hocoslamfy | [Latest](https://github.com/fgl82/hocoslamfy/releases/latest) | [Active](https://github.com/fgl82/hocoslamfy) | No
KOF - Flames of Courage v5 | [Final](https://drive.google.com/open?id=1HlGJIwxKIPYay5vPuiZ89_Kh_cgyytGh) | [Inactive](https://github.com/gromv/kofv5) | No
Last Mission | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/last-mission.opk) | [Inactive](https://github.com/dmitrysmagin/last-mission) | No
Marathon* | [Latest](https://drive.google.com/open?id=147IPd5EKXRzdXOSbD7gSJCpgorC7ce4y) | Active (Source N/A) | No
Marathon 2* | [Latest](https://drive.google.com/open?id=1bieRbLbcv8Dn3yKNflIZcfBkbfCfW7XU) | Active (Source N/A) | No
Marathon Infinite* | [Latest](https://drive.google.com/open?id=1UayihX4pbpY0gyLC-dWnBuvGLNTQeFl9) | Active (Source N/A) | No
Meteoroid3D | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/meteoroid3d.opk) | [Inactive](https://github.com/theZiz/meteoroid3d) | No
MiniSlug | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/MiniSlug.opk) | [Inactive](http://oldschoolprg.x10.mx/projets.php#minislug) | No
Mr.Drillux | [Latest](https://github.com/jbanes/rs97-mrdrillux/releases/latest) | [Inactive](https://github.com/jbanes/rs97-mrdrillux) | No
nKaruga | [Latest](https://gameblabla.nl/files/nkaruga/nKaruga.opk) | [Inactive](https://github.com/gameblabla/nKaruga) | No
Odamex* *** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/odamex.opk) | [Inactive](https://github.com/JohnnyonFlame/odamex) | (Final) DOOM (2) Data Files
OpenBOR | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/OpenBOR_3.0_r4165_GCW0_Edition.opk) | [Inactive](https://github.com/DavidKnight247/OpenBOR-for-the-GCW0) | OpenBOR Game Pak Files, `/usr/local/share/OpenBOR/Paks/`
OpenJazz | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/openjazz.opk) | [Inactive](https://boards.dingoonity.org/gcw-development/openjazz-8914/) | Jazz Jackrabbit Data Files, `~/.openjazz/`
OpenSonic | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/opensonic.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/opensonic-0-1-4/) | No
OpenTyrian** | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/opentyrian_r1055.opk) | [Inactive](https://github.com/JohnnyonFlame/OpenTyrian) | No
POWDER | [Latest_v117](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/powder_117.opk) | Legacy (Source N/A) | No
Puzzletube | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/puzzletube.opk) | [Inactive](https://github.com/theZiz/puzzletube) | No
Quake GLES** | [Latest](https://github.com/thenesis-org/lp-public/releases/tag/v1.1) | [Inactive](https://github.com/thenesis-org/lp-public/tree/master/Ports/Quake1) | Quake (& Mission Pack 1/2) Data Files, `~/.local/share/Thenesis/Quake1/`
Quake 2 GLES** | [Latest](https://github.com/thenesis-org/lp-public/releases/tag/v1.1) | [Inactive](https://github.com/thenesis-org/lp-public/tree/master/Ports/Quake2) | Quake II (& Mission Pack 1/2/3/CTF) Data Files, `~/.local/share/Thenesis/Quake2/`
Quake 3* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/Quake%203.opk) | Legacy (Source N/A) | Quake III Arena Shareware/Registered Data Files, `~/.q3a/`
Quartermaster | [Latest](https://github.com/hi-ban/quartermaster/releases/latest) | [Active](https://github.com/hi-ban/quartermaster) | No
REminiscence | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/REminiscence.opk) | [Inactive](https://github.com/ElwingGit/GCW0_REminiscence) | Flashback Data Files, `~/.REminiscence/data/`
Rise of the Triad* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/rott.opk) | [Inactive Fork](https://github.com/podulator/RoTT) | Rise of the Triad: The Dark War (Registered Version) Data Files, `~/.rott/data/`
Rockbot | [Latest](https://rockbot.upperland.net/?download=1.20.74%20OpenDingux) | [Inactive](https://github.com/protoman/rockbot) | No
Rock Rain 2 | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/Rock%20Rain%202.opk) | Legacy (Source N/A) | No
rRootage | [Latest](https://github.com/jamesofarrell/rRootage-for-Handhelds/releases/latest) | [Active](https://github.com/jamesofarrell/rRootage-for-Handhelds) | No
SDLQuake2* | [Latest](https://drive.google.com/open?id=1JZ17OhATuBklEUP5NQ73bVLEv_MmpDj3) | [Inactive Fork](https://github.com/jamesofarrell/SDLQuake2) | Quake II (Shareware/Registered) Data Files, `~/.quake2/baseq2`
Shadow Warrior* | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/shadow-warior.opk) | [Inactive Fork](https://github.com/JohnnyonFlame/gcw0-jfsw) | Shadow Warrior (Shareware/Registered) Data Files, `~/.jfsw/sw.grp`
SkiFree! | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/skifree_v7.opk) | Active (Source N/A) | No
Snowman | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/snowman.opk) | [Inactive](https://github.com/theZiz/snowman) | No
Sonic Robo Blast 2* | [2.1.15](https://drive.google.com/open?id=1Lgg-sNFN8zPFdkbuk5te2CWc9iUY7rF8) | [Inactive Fork](https://github.com/gameblabla/srb2-gcw) | No
Sonic Robo Blast 2 Kart* | [Latest](https://gameblabla.nl/files/ipk/gcw0/srb2kart.opk) | [Active](https://github.com/gameblabla/Kart-Public) | No
Sopwith | [Latest](https://github.com/jamesofarrell/sopwith/releases/latest) | [Active](https://github.com/jamesofarrell/sopwith) | No
Sqrxz (Remake) | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/sqrxz-v.latest-gcw-zero.opk) | Legacy | No
Sqrxz 2: Two seconds 'til death | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/sqrxz2-v.latest-gcw-zero.opk) | Legacy | No
Sqrxz 3: Adventure for Love | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/sqrxz3-v.latest-gcw-zero.opk) | Legacy | No
Sqrxz 4: Cold Cash | [Final](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/sqrxz4-v.latest-gcw-zero.opk) | Legacy | No
Strange Adventure in Infinite Space | [Latest](https://drive.google.com/file/d/1YZFVwSeDw-kaic5O6X7FOLA-EBeOW1HI/view?usp=sharing) | [Inactive](https://github.com/ptitSeb/sais) | No
Streets of Rage Remake v5.1 | [Latest](https://drive.google.com/open?id=1cKkZOzmYBQoocJadpLo2i8eDItSNAwCU) | [Legacy](https://sega.com) | No (Recommended to set `Video Options -> Shadows` from `Reflected` to `SOR` type to mitigate crashes.)
Super Mario War | [Latest](https://gameblabla.nl/files/ipk/gcw0/smw_gcw0.opk) | Active (Source N/A) | No
SuperTux | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/supertux.opk) | [Inactive](https://github.com/dmitrysmagin/supertux) | No
TailTale | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/TailTale.opk) | [Inactive](https://bitbucket.org/shin_nil/tale-tail-gcw-zero) | No
Tron-clone | [Latest](https://github.com/jamesofarrell/tron-clone/releases/latest) | [Active](https://github.com/jamesofarrell/tron-clone) | No (Multiplayer Only)
UMG-v0.4Demo | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Games-Ports/umg-gcw-exclusive-preview-0.4.opk) | [Legacy](http://artur-rojek.eu/umg.php) | No
Ur-Quam Masters (Star Control 2) | [Latest](https://drive.google.com/open?id=16WiQ6Pgfoxi3NJ-veFh95_gwd5MgsCJv) | Legacy (Source N/A) | No
VVVVVV | [Latest](https://drive.google.com/file/d/1kRa6Hcd9jCXjiDD1_DBCLALPYDhbQ5dJ/view) | Active (Source N/A) | VVVVVV Data Archive, `~/.local/share/VVVVVV/data.zip`
xRick | [Latest](https://github.com/jamesofarrell/miyoo_xrick/releases/latest) | [Active](https://github.com/jamesofarrell/miyoo_xrick) | No
Zatackax | [Latest](https://github.com/jamesofarrell/zatackax/releases/latest) | [Active](https://github.com/jamesofarrell/zatackax) | No

Index:

*:Accepts all RG350/PG2 inputs (dual sticks, secondary triggers and stick clicks)

**:Accepts most RG350/PG2 inputs, but in a limited capacity (i.e. can only use one joystick, doesn't register stick clicks, etc.)

***:Uses frontend file explorer for input.

---

## Emulators

Unless specified, emulators use the frontend's file explorer for ROM files, or have been modified to do so.

Most emulators will use the Power (I/O) button for a menu toggle; otherwise, it's Start + Select, or in some cases, simply Select. If an emulator has added support for the PocketGo 2, then it will use its Menu button as an alternative in some cases.

| Emulated System(s) | Name | OPK Link | Source | Requires System Files? |
|--------------------|:------:|:--------:|:------:|-----------------------:|
[RetroArch](https://www.retroarch.com/) | RetroArch (WIP) | [Latest](https://cdn.discordapp.com/attachments/625718299493138442/663939767943036938/retroarch.opk) | [Upstream](https://github.com/libretro/RetroArch) | [Varies](https://docs.libretro.com/)
3DO | 3Doh | [Latest](https://github.com/gameblabla/3doh_gcw0/raw/master/3doh.opk) | [Inactive](https://github.com/gameblabla/3doh_gcw0) | 3DO BIOS, `/media/data/local/home/.3doh/bios.bin`
Amstrad CPC | CrocoDS | [2020-01-15](https://www.kyuran.be/rg350/crocods_20200115.opk) | [Active](https://www.kyuran.be/rg350/) | No
Arcade - FBA | FinalBurnAlpha | [0.2.97.35 (Speed)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/FinalBurnAlpha_2020-01-13-.35_alias.opk) [0.2.97.44 (Compatibility)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/FinalBurnAlpha_2020-01-13-.44_alias.opk) | [Active](https://github.com/nobk/fba-sdl) | Varies
Arcade - Laserdisc | Daphne | [2015-05-07](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/Daphne_2015-05-07.opk) | [Inactive](https://github.com/DavidKnight247/Daphne) | [Compatible Laserdisc Games (Conversion Tutorial Link)](https://boards.dingoonity.org/gcw-releases/daphne/)
Arcade - MAME (0.52, 0.69, 0.84) | XMAME (Installer)* | [2015-03-15](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/XMAME_2015-03-15.opk) | [Inactive (Archive)](https://drive.google.com/open?id=1SzIjckEVjSAKdnRQGT7kbH9c_B9X3k8-) | Internal: `/usr/local/share/xmame/{xmame52 OR xmame69 OR xmame84}/roms`, External: `/media/sdcard/apps/xmame/{xmame52 OR xmame69 OR xmame84}/roms`
Atari VCS (2600) | Stella | [2015-10-06](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/Stella_2015-10-06.opk) | [Inactive](https://github.com/DavidKnight247/Stella-3.9.3) | No
Atari 5200 | a5200 | [2013-06-15-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/a5200_2013-06-15-launcher.opk) | [Inactive](https://boards.dingoonity.org/gcw-releases/a5200-v1-0/) | Atari 5200 BIOS, `~/5200.rom`
Atari 7800 | ProSystem | [2013-06-16-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/ProSystem_2013-06-16-launcher.opk) | [Inactive](https://github.com/alekmaul/prosystem) | No
Atari Lynx | Handy | [Latest](https://gameblabla.nl/files/ipk/gcw0/handy_gcw0.opk) | [Active](https://github.com/gameblabla/handy-rs97) | No
Atari ST | DCaSTaway* | [2014-11-09](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/DCaSTaway_2014-11-09.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/dcastaway-an-atari-st-emulator/) | Atari ST TOS ROM, `~/DCaSTaway/bios/rom` (A `rom` file with no extension in the `bios` folder, NOT a `rom` directory)
Bandai Wonderswan (B/W, Color) | SwanEmu | [Latest](https://gameblabla.nl/files/ipk/gcw0/swanemu_gcw0.opk) | Active (Source N/A) | No
BBC Micro | BeebEm | [Latest](https://github.com/jeremyrayner/beebem-rg350/releases) | [Active](https://github.com/jeremyrayner/beebem-rg350) | Acorn DNFS, BBC Model B OS 1.2, and BBC Basic, `~/.beebem/roms/ {acorn_dnfs, os12, basic}` (No extensions)
Coleco Colecovision | ColecOD | [2013-06-15-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/ColecoD_2013-06-15-launcher.opk) | [Inactive](https://boards.dingoonity.org/gcw-releases/colecod-v1-0/) | No
Commodore 64, 128, VIC-20, Plus-4 | VICE (Launcher Mod)** | [2019-12-23](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/VICE_2019-12-23-LauncherMod.opk) | [Legacy](https://boards.dingoonity.org/gcw-zero-emulation/(testing)-vice-2-3/) | No; run `VICE Setup` if installing for the first time
Commodore Amiga | UAE4All* | [2014-12-02](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/UAE4All_2014-12-02.opk) | [Inactive](https://github.com/zear/uae4all) | Amiga 500 Kickstart ROM, `~/.uae4all/kick.rom`
Mattel Intellivision | JzIntv | [2015-03-28](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/jzIntv_2015-03-28.opk) | [Inactive](https://github.com/DavidKnight247/jzIntv) | No
Nintendo Entertainment System, Famicom Disk System | FCEUX | [2019-11-15](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/FCEUX_2019-11-15.opk) | [Active Fork](https://github.com/soarqin/fceux-for-retrogame) | (Optional) Famicom Disk System ROM, `~/.fceux/disksys.rom`
Nintendo Entertainment System, Famicom Disk System (High Accuracy) | Nestopia (ALPHA) | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/Nestopia_2020-01-01.opk) | [Active](https://github.com/Derynect/nestopia) | (Optional) Famicom Disk System ROM, `~/.nestopia/disksys.rom`
Nintendo Game Boy (DMG, Color) | Gambatte | [Latest](https://github.com/bardeci/dot-matrix-simulator/releases/latest) | [Active Fork](https://github.com/bardeci/dot-matrix-simulator) | No
Nintendo Game Boy Advance | ReGBA | [2019-12-26_SaveFixes](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/ReGBA_2019-12-26.opk) [2019-05-19_SaveFixes (For PG2)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/Archive-OldVersions/ReGBA_2019-05-19.opk) | [Active Fork](https://github.com/soarqin/regba) | (Optional) Game Boy Advance BIOS, `~/.gpsp/gba_bios.bin`
Nintendo Pokémon Mini | PokeMini | [2015-07-05](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/PokeMini_2015-07-05.opk) | [Inactive](https://github.com/gameblabla/pokemini) | No
NEC PC-Engine/TurboGrafx-16, CD System | Temper | [Latest](https://gameblabla.nl/files/ipk/gcw0/temper_rs97_gcw0.opk) | [Active](https://github.com/gameblabla/temper) | (Optional) PC-Engine Super System Card 3, `~/.temper/syscards/syscard3.pce`
NEC PC-FX | SmallPCFX | [Latest](https://github.com/gameblabla/pcfx-mednafen/releases/latest) | [Inactive](https://github.com/gameblabla/pcfx-mednafen) | PC-FX BIOS, `~/.mednafen/pcfx.rom`
PC - MS-DOS | DOSBox v0.74 | [2019-11-11-launcher](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/DOSBox_2019-11-11-launcher.opk) | [Active Fork](https://github.com/soarqin/dosbox-rg350) | No
PC - MSX (1, 2, 2+) | OpenMSX | [v0.15 (2018-12-23)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/openMSX-0.15-remap.opk) | [Upstream](https://github.com/openMSX/openMSX) | (Optional) BlueMSX Compatible System Folders, Configurable
PC - Point-and-Click Adventure Games | ScummVM*	| [Latest](https://github.com/jbanes/scummvm/releases) | [Active Fork](https://github.com/jbanes/scummvm) | No
PICO-8 | Retro8 | [Latest](https://github.com/Jakz/retro8/releases/latest) | [Active](https://github.com/Jakz/retro8) | No
Sega Master System, Game Gear | SMS Plus GX | [Latest](https://gameblabla.nl/files/ipk/gcw0/smsplus_gcw0.opk) | [Active](https://github.com/gameblabla/sms_sdl) | No
Sega Genesis/Mega Drive, CD, Master System, Game Gear, SG-1000 | Genesis Plus GX | [2019-12-23](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/GenesisPlusGX_2019-12-23.opk) | [Active](https://github.com/Derynect/Genesis-Plus-GX) | (Optional) Sega/Mega CD BIOS Images, `bios_CD_U.bin` `bios_CD_J.bin` `bios_CD_E.bin`: `~/.genplus/bios/`
Sega Genesis/Mega Drive, CD, 32X, Master System | PicoDrive | [Latest](https://gameblabla.nl/files/ipk/gcw0/picodrive_gcw0.opk) | Active (Source N/A) | (Optional) Sega/Mega CD BIOS Images, `bios_CD_U.bin` `bios_CD_J.bin` `bios_CD_E.bin`: `~/.picodrive/`
SNK Neo-Geo CD | NEO4All* | [2019-12-16](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/NEO4All_2019-12-16.opk) | [Active Fork...? (Source N/A)](http://toro.2ch.sc/test/read.cgi/gsaloon/1572848152/) | Neo-Geo CD BIOS, `~/.neo4all/neocd.bin`, Neo-Geo CD games in `.cue`+`.img`+`.sub` format in `~/.neo4all/roms`
SNK Neo-Geo Pocket (B/W, Color) | NGPCEmu	| [Latest](https://gameblabla.nl/files/ipk/gcw0/ngpcemu_gcw0.opk) | [Active](https://github.com/gameblabla/NGPCemu) | No
Sony PlayStation | PCSX4All | [Latest (Gameblabla)](https://gameblabla.nl/files/ipk/gcw0/pcsx4all_gcw0.opk) [2.4_2019-12-12 (for PG2)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/PCSX4All_2019-12-12.opk) | [Active Fork (Gameblabla)](https://github.com/gameblabla/pcsx4all_rs97_rg350) [Active Fork (Soarqin)](https://github.com/soarqin/RG350_pcsx4all) | PlayStation BIOS, `~/.pcsx4all/bios/`
Super Nintendo Entertainment System (Fast, Low Accuracy) | PocketSNES | [2019-12-12](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/PocketSNES_2019-12-12.opk) | [Active](https://github.com/soarqin/PocketSNES) | No
Super Nintendo Entertainment System (High Accuracy, Slow) | Snes9x | [2019-11-11](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/Snes9x_2019-11-11.opk) | [Active Fork](https://github.com/soarqin/snes9x) | No
Watara Supervision | Potator* | [2013-09-17](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/Potator_2013-09-17.opk) | [Inactive](https://github.com/alekmaul/potator) | No
ZX Spectrum | Unreal Speccy Portable | [2013-05-13](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Emulators/UnrealSpeccyPortable_2013-05-13.opk) | [Inactive](https://github.com/DavidKnight247/Unreal-Speccy-Emulator-GCW0-Edition) | No

### Index:

*: Emulator uses its own frontend for basic usage and setup

**: Emulator uses its own frontend for setup, required to use system frontend launcher

---

## Frontends

| Name | OPK Link | Source |
|------|:--------:|-------:|
350teric (Formerly GMenuNX-Dingux Fork) | [Latest](https://github.com/podulator/esoteric/releases/latest) | [Active](https://github.com/podulator/esoteric/)
EmulationStation (UNSTABLE) | [Latest](https://github.com/ManuelSch81/RG350-EmulationStation_configured/raw/master/Internal%20SD%20Card/emulationstation.opk) | [Latest](https://github.com/ManuelSch81/RG350-EmulationStation_configured)
SimpleMenu | [Latest](https://github.com/fgl82/simplemenu/releases/latest) | [Active](https://github.com/fgl82/simplemenu)

### Index:

350teric (Pronounced "Esoteric"): Based on GMenu2x, similar to GMenuNX (RetroFW) with additions such as preview images, extended skin customization, etc. [Example repos](https://github.com/m1024x/retrogame-skin-pack) [that demonstrate](https://github.com/SeongGino/LegieUI-NX) [the added possibilities.](https://github.com/SeongGino/SymphieUI-NX)

EmulationStation: A port of [the PC frontend](https://emulationstation.org/index.html) - is known to not support many pre-existing themes, requires pre-configuration for specific emulators, and is generally not as plug-n-play friendly as GMenu or SimpleMenu. Is a work-in-progress.

SimpleMenu: A new menu system with focus on usability and aesthetic/functional simplicity.

---

## Applications

| Name | OPK Link | Source |
|------|:--------:|-------:|
Bard Storyteller (Ebooks) | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/Bard_0.10.0.opk) | [Legacy (Archive)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/SourceArchives/bard-0.10.0-release.tar.bz2)
Dingux Commander KAI (WIP) | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/dinguxcmd_kai-20200121.opk) | [Active Fork (2020-01-20-Archive)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/SourceArchives/dinguxCommander_Kai-src_20200120.zip)
FFPlay | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/ffplay-gcw0.opk) | [Inactive](https://github.com/denis-n-kuznetsov/FFmpeg-GCW0)
Glutext | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/glutexto.opk) | [Legacy](https://boards.dingoonity.org/gcw-releases/glutexto-1-2/)
GMU | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/gmu-0.10.1-gcw0.opk) | [Inactive](https://github.com/denis-n-kuznetsov/gmu)
Input Tester | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/input-test.opk) | [Active](https://github.com/tonyjih/RG350_input-test)
Oldplay | [Latest](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/oldplay_v135.zip) | [Legacy (Archive)](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/SourceArchives/oldplay_v135_src.zip)
ROGUE RG350 Test | [1.2](https://github.com/SeongGino/RetroGame350-AppRepo/raw/master/Applications/ROGUEtest_RG350.opk) | Active (Part of ROGUE CFW)
Simple Terminal Emulator | [Latest](https://github.com/jamesofarrell/st-sdl/releases/latest) | [Active](https://github.com/jamesofarrell/st-sdl)

---

## Development Tools

| Name | Source |
|------|-------:|
Sparrow3D | [Source](https://github.com/theZiz/sparrow3d)

---

I'd appreciate it if we *didn't* fork, kthx? Let's prevent confusion for new users as much as we can, and contribute to one central repo.
