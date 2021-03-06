ZEsarUX - ZX Second-Emulator And Released for UniX 

Created by Cesar Hernandez Bano

https://github.com/chernandezba/zesarux


It's a ZX Machines Emulator for Unix, including all the Sinclair computers:

* MK14
* ZX80
* ZX81
* ZX Spectrum
* QL
* Z88

And also:

* Timex TS 2068
* Sam Coupe
* Pentagon 
* Chloe 140 SE, 280 SE
* Chrome
* Prism
* ZX-Uno
* ZX-Evolution BaseConf
* ZX-Evolution TS-Conf
* TBBlue/ZX Spectrum Next
* Jupiter Ace
* Amstrad CPC 464, CPC 4128

ZEsarUX source code and binaries are distributed under GNU GPL license. 
ZEsarUX also includes a folder, "my_soft", which has some programs and data made by me. The entire folder is also covered by the GNU GPL license.

ZEsarUX also includes third-party roms, media, programs and games NOT covered by this license.

This is my second ZX Spectrum emulator after ZXSpectr
https://github.com/chernandezba/zxspectr

I recommend you to read FEATURES, INSTALL and HISTORY files, as well as other documents in this emulator.
You can open them from the help menu or from an external viewer.


ZEsarUX distributed under GNU GENERAL PUBLIC LICENSE v3. You may read it on the LICENSE file.

ZEsarUX includes Musashi 3.4 - A portable Motorola M680x0 processor emulation engine.
Copyright 1998-2002 Karl Stenerud. All rights reserved. Distributed under MIT License, you may read it on the LICENSE_MOTOROLA_CORE file

ZEsarUX includes National Semiconductor SC/MP CPU Emulator
Copyright 2017 Miodrag Milanovic. Distributed under BSD-3 License, you may read it on the LICENSE_SCMP_CORE




Available versions for download here:
* Source code
* Binary compiled versions:
* Linux 32/64 Bits
* Mac OS X
* Windows
* Raspberry pi (raspbian)

Other by 3rd party:
* Arch Linux
* Slackware
* Retropie/EmulationStation
* Open Pandora
* PocketCHIP
* MorhpOS


ZEsarUX has won the "Best Emulator" award from Retrogaming Total blog on 2015 and 2017




__DONATE__

ZEsarUX is free software and you don't need to pay to use it. 
ZEsarUX will always cost you nothing to use, but that doesn't mean it costs me nothing to make.
So if you want to demonstrate your appreciation to it, you can donate using Paypal. Just click:

[ZEsarUX donation](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=E5RSRST8N7KWS&lc=ES&item_name=Donativo%20ZEsarUX&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)


All donors will appear in the acknowledgements file

Thanks!


__FEATURES__

* Runs on any Unix system and Windows: tested on Linux x86, Linux x86_64, Linux Raspbian, Mac OS X, Windows native, Windows + Cygwin

* Emulates:
* Science of Cambridge MK14
* Sinclair ZX80
* Sinclair ZX81
* Spectrum models: 16k, 48k (English and Spanish), Inves Spectrum +, Spectrum 128k (English and Spanish), Spectrum +2 (English, Spanish and French), Spectrum +2A (English and Spanish), Spectrum +3 (English and Spanish), Microdigital TK90X (Portuguese and Spanish), TK95 
* Sinclair QL
* Cambridge Z88
* Timex TS 2068 
* Sam Coupe
* Pentagon 
* Chloe 140 SE, 280 SE
* Chrome
* Prism
* ZX-Uno
* ZX-Evolution BaseConf
* ZX-Evolution TS-Conf
* TBBlue/ZX Spectrum Next
* Jupiter Ace
* Amstrad CPC 464, CPC 4128

* Is the only emulator for machines: ZX-Uno, Chloe 140/280, Prism, TBBlue and Chrome

* Almost perfect emulation of timing of all Spectrum machines

* Supports undocumented Z80 flags, features, and MEMPTR register

* Supports idle bus port, contended memory, ULA early/late timings

* Supports Motorola CPU 68008 (Sinclair QL)

* Supports SC/MP CPU - INS8060 (MK14)

* Supports Pentagon timing

* Supports perfect ZX Spectrum 16k/48k colour palette

* Supports ULAplus: Standard 64 colour palette, linear modes with 16 colours per pixel: Radastan Mode: 128x96, ZEsarUX modes: 256x96, 128x192, 256x192

* Supports Chroma81 ZX81 Colour mode

* Supports Spectra Video Modes

* Supports Timex Video modes (Mode 0 standard, 1 dual screen, 2 hires colour 8x1, 6 512x192 monochrome)

* Supports All Video modes from Prism machine

* Supports ZGX Sprite Chip

* Supports snow effect on Spectrum models

* Supports interlaced, scanlines and Gigascreen effects

* Supports hi-res modes on ZX Spectrum (rainbow effects and others) and ZX80/ZX81 (UDG, CHR$128, WRX, HRG and some other hi-res modes)

* Supports reducing the screen to 192x144 (0.75 scale)

* Can be used with joystick and environments without keyboard, like Raspiboy / Retropie

* Emulates all the oddities of the Inves Spectrum +: 64 KB RAM, RAM initialization with FF00H pattern, OUT ula AND RAM, EAR and MIC XOR, no contended memory, snow in border, colour ula delay, interrupt starts at end of top border (not at the beginning of the border), corrupt memory on every interrupt, no idle bus

* Uses Video drivers: X-Windows, SDL, Cocoa (Mac OS X), Framebuffer, ncurses, aalib, cacalib, stdout(console), simpletext(console)

* Uses Audio Drivers: PulseAudio, Alsa, SDL, DSP(OSS), CoreAudio (Mac OS X). 

* Supports dumping audio & video to file

* Supports real tape loading of file formats: RWA, SMP, WAV, TZX, CDT, TAP, P, O. It handles loading of turbo load tapes or any type of tape loading for standard/non standard loading routines

* Handles binary tape format files (TAP, TZX, O, P, CDT) on standard BASIC ROM routines for ZX Spectrum, ZX80, ZX81, Jupiter Ace

* Handles real audio loading (RWA, SMP, WAV) on standard BASIC ROM routines for ZX Spectrum, ZX80, ZX81, Amstrad CPC, Jupiter Ace

* Simulates real tape loading on standard BASIC ROM routines for ZX Spectrum, ZX80, ZX81

* Handles snapshot format: ZSF, ZX, Z80, SP, SPG, SNA (loading only), P, O, Z81 (loading only), ACE

* Handles RZX playback 

* Emulates Multiface One, 128 and Three

* Emulates Datagear/MB02 DMA

* Handles DCK Timex dock cartridges

* Emulates +3 Disk

* Emulates Betadisk/TR-DOS

* Emulates ZX Spectrum MMC Interfaces: ZXMMC, DivMMC. Support for raw (.mmc) files and hdf files

* Emulates ZX Spectrum IDE Interface: DivIDE, 8-bit simple 

* Emulates Sam Coupe IDE Interface: Atom Lite

* Emulates ZXPand MMC Interface on ZX80 and ZX81

* Emulates ZX Dandanator! Mini, CPC Dandanator! Mini

* Emulates Speccy Superupgrade

* Emulates Kartusho

* Handles RAM, EPROM, Intel Flash and Hybrid (RAM+EPROM) cards on Z88

* Handles compressed formats zip, tar, rar, gz through external utilities

* Supports AY Chip, Turbosound (2 AY Channels), 3 AY Channels, different DAC: Specdrum, Covox, ACB/ABC/BAC Stereo 

* Supports Quicksilva, ZON-X81, and VSYNC-based sound on ZX80/81

* Supports Speaker and Soundbox sound on Jupiter Ace

* Experimental simulation of the Sam Coupe Audio Chip (SAA1099)

* Supports RAM packs on ZX80/81 up to 56 KB

* Supports RAM packs on Jupiter Ace up to 35 KB

* Joystick emulation with real joystick (on Linux) and keyboard cursors: Kempston, Sinclair 1&2, Cursor Joystick, Cursor & Shift, OPQA, Fuller, Zebra, Mikro-Gen, ZXPand, SAM Coupe Cursors. Autofire function also

* On Screen keyboard useful when playing with joystick, two types: one with keyboard letters, and another with words, useful for playing Text Adventures. Also a tool to extract words from text adventures and configure this on screen text keyboard

* Emulates Spectrum keyboard ghosting error feature

* ZX Spectrum Recreated keyboard support

* Supports native turbo modes on ZX-Uno, Chloe, Prism and TBBlue and manual for other machines

* ZX Printer emulation

* Lightgun emulation: Almost perfect emulation of Gunstick from MHT Ingenieros S.L and experimental emulation of Magnum Light Phaser

* Kempston mouse emulation

* Supports Input spool text file to simulate keyboard press

* Supports reading Pokes from .POK files

* Supports playing .AY sound files

* Supports ZEsarUX remote command protocol (ZRCP). You can do enhanced debugging on ZEsarUX by using a telnet client.

* Can use a reduced Spectrum core, with some features disabled, useful on slow devices, like Raspberry Pi 1/Zero

* Powerful debug features: Assembler, Registers, Dissassemble, Conditional Breakpoints using text expressions, Watches, Step-to-step, Step-over, Runto, Show TV electron position, Load source code, Hexadecimal Editor, View Sprites, Find byte (useful to find POKEs), CPU Transaction log, View BASIC, verbose messages on console, DAAD Debugger

* File utilities menu: Allowing to view, expand and convert some common file formats: tap, tzx, trd, dsk, mdv, hdf, etc

* Accessibility support: Print char traps allows to capture generated text from almost any program or game, using standard ROM calls (RST 10H) or even non standard print character routines. Can send generated text from a game to a text-to-speech program. It's ready for text to speech support for blind or visually impaired people. Menu emulator can be also read by a text-to-speech program.

* Simulates upper RAM memory refresh on Spectrum 48Kb, losing its contents when changing R register very quickly

* Supports command line settings, configuration file settings and per-game configuration settings

* Other features: Visualmem menu, CPU Statistics

* Includes three easter eggs. Can you find them? :)



__Some screenshots__

ZX Spectrum Overscan demo

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_overscan.jpg "Overscan demo")


ZX-81 Mazogs

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_mazogs.png "Mazogs")


Sinclair QL

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_ql.png "QL")


Cambridge Z88

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_z88.png "Z88")


ZX Spectrum Sir Fred running on curses (text) driver

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_sirfred_curses.png "Sirfred curses")


ZX-Uno

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_zxuno.png "ZX-Uno")


ZX-Evolution TSConf

![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_tsconf.jpeg "ZX-Evolution TSConf")


TBBlue/ZX Spectrum Next
![alt text](https://github.com/chernandezba/zesarux/raw/master/screenshots/screenshot_tbblue.png "TBBlue/ZX Spectrum Next")


You can find some ZEsarUX videos on my [Youtube channel](https://www.youtube.com/user/chernandezba)
