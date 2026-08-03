# Cores Available for all MEGA65

Cores are shown in now particular order. Please look at the right sidebar to get to for the specific Cores.

## Commodore 64 (C64)

<img src=Commodore-64-Computer-FL.jpg width="600">

https://en.wikipedia.org/wiki/Commodore_64

The Commodore 64 is a personal computer released in 1982. It is the precursor of the (unreleased) C65 which is the machine the MEGA65 is recreating. It is usually abbreviated as just **C64**.

<img src=c64coremenu.jpg>

The core for the C64 is nearly 100% compatible to a real C64. Hardware like cartridges and floppy drives can be plugged into the MEGA65 and will work.
The core can load disk images (.d64 files) and cartridge images (.crt files) from any of the two SD Cards in the MEGA65. Tape images are not supported.
The Core only supports a PAL C64 system. Programs that only work correctly on NTSC (USA/Japan) systems are not compatible. Please see all details in the documentation.

The Core is available in versions for R3 and R6 boards.

**Full instructions for this core can be found at https://c64.mega65.org**

Download the Core on the MEGA65 filehost: 
https://files.mega65.org/?id=896a012f-59e4-456c-b91f-7e989b958241

The Core discussion on Discord: 
https://discord.com/channels/719326990221574164/794775503818588200

The Core issue tracker on Github: 
https://github.com/MJoergen/C64MEGA65/issues

A new version with MANY new features is currently available for testing. Check out https://c64.mega65.org/alphasix.html for details.

## Amiga 500

<img src=a500_ocs.jpg width="600">

https://en.wikipedia.org/wiki/Amiga_500

Released in 1987, the Amiga 500 ("A500") was the first computer for the home market capable of multitasking. Although popular with hobbyists, arguably its most widespread use was as a gaming machine, where its graphics and sound were of significant benefit.

A first version of an Amiga 500 Core has been released. This core allows running nearly all known disk based demos and games, but does not support the internal diskdrive. You need to load ADF images from the SD Card. Games with several disks can be played, but there is a delay when you mount a new disk.

**Read the documentation for the core here, especially regarding Mouse Support and Keyboard Mapping**:
https://a500.mega65.org

The Core can be found on the MEGA65 filehost here: https://files.mega65.org?id=bdbf637c-83b5-45c4-802f-0fd459f6b49e

The Core Issue Tracker is on Github:
https://github.com/sy2002/AExp/issues

And the Core discussion can be found on Discord:
https://discord.com/channels/719326990221574164/1313409877393276948

## Commodore C16 & Plus4 (264)

<img src= Commodore_16_002a.jpg width="600">

https://en.wikipedia.org/wiki/Commodore_16

The Commodore 16 familiy of computers, sometimes referred to the 264-series, consists of several models, mainly the C16 and the Plus/4. The major differences is the RAM size (16kb or 64kb) and the office software included with the Plus/4.

The C16 computers lack the Sprite and Scroll capabilities of the C64, but can display significantly more colours. There are quite a few demo programs and games that look better than on a C64, so it is worthwhile checking out.

The core for the C16 & Plus/4 emulates both ROM versions and both RAM sizes. Like with the C64 core, pressing <kbd>HELP</kbd> will bring up a menu with several options.

This core can load .prg and .d64 files but will not automatically run them. After selecting a .prg, please wait some seconds until the file has been loaded into RAM, leave the menu, and then type RUN.
	
The Core is available in versions for R3 and R6 boards.

Download the Core on the MEGA65 filehost: 
https://files.mega65.org?id=7a29a797-ae82-4455-8a27-f48cb856e524

The Core discussion on Discord: 
https://discord.com/channels/719326990221574164/1482361321218637964

The Core issue tracker on Github: 
https://github.com/piso77/C16-MEGA65/issues

	
## Commodore PET Series
	
<img src=Commodore_2001_Series.jpg width="600">

MegaPET is an implementation of MANY variations of the Commodore PET line of computers, the forerunners to the VIC-20 and the Commodore 64.

You can find it on the official filehost here: https://files.mega65.org?id=468325ae-7e27-475d-80e7-a0f0af409446

You need to follow a lot of specific instructions for setup, available on the Github here:
https://github.com/Rhialto/MegaPET/blob/rhialto/README.md

You can discuss the development of this core on Discord here:
https://discord.com/channels/719326990221574164/1282765235639549993

## TI 99/4A
<img src= TI99-IMG_7132.jpg width="600">

https://en.wikipedia.org/wiki/TI-99/4A

The TI-99/4A is a personal computer released in 1981 by Texas Instruments with a unique internal design and extensiblity by cartridges.

<img src=ti99parsec.jpg>

The core is written from scratch specifically with the MEGA65 as its target. It tries to match the timing of the original TI-99/4A as closely as possible, but also features a 36x turbo mode, where the TMS9900 runs at 108 MHz. _Setup requires some extra files, please check the instructions provided in the README.MD file in the download._

Please use Core Versions 1.4 or higher to have proper HDMI 480p output.

Download the Core on the MEGA65 filehost: 
https://files.mega65.org?id=a25ce133-ed07-4ef7-8495-179d69c43ed0

The Core discussion on Forum64: 
https://www.forum64.de/index.php?thread/151162-mega99-a-ti-99-4a-core-for-the-mega65/

The Core issue tracker on Github: 
https://github.com/zeldin/Mega99/issues


## ZX Spectrum
<img src=Sinclair_ZX_Spectrum_48k.jpg width="600">

https://en.wikipedia.org/wiki/ZX_Spectrum

The ZX Spectrum is a home computer released in 1982.

<img src=zxunomenu.jpg>

The ZX Spectrum Core for the MEGA65 is a port of the ZX-UNO project to the MEGA65 framework. It needs to be carefully setup and requires specific files and directories on the SD Card. It can run most ZX Spectrum software and uses .tap files. The Core is not as user-friendly as the C64 core, as the Spectrum uses a different keyboard layout, has specific options for Joysticks (the original ZX Spectrum did not have a joystick port so games have options for different hardware extensions) and sometimes need some extra help in configuring specific games.

The Core is available in versions for R3 and R6 boards

**Read the instructions for proper SD Card setup:** https://github.com/sy2002/zxuno4mega65/wiki/Getting-Started

Download the Core on the MEGA65 filehost:

https://files.mega65.org?id=bdaeb7e0-9fc8-4185-99de-104d01229f27

Discuss the Core in the Alternate Cores channel on Discord:

https://discord.com/channels/719326990221574164/1177364456896999485

The Core issue tracker on Github:

https://github.com/sy2002/zxuno4mega65/issues

## Nascom2

<img src=Nascom_2_Computer_1981.jpg width="600">

https://en.wikipedia.org/wiki/Nascom

The Nascom 1 and 2 were single-board computer kits issued in the United Kingdom in 1977 and 1979, respectively, based on the Zilog Z80 and including a keyboard and video interface, a serial port that could be used to store data on a tape cassette using the Kansas City standard, and two 8-bit parallel ports. At that time, including a full keyboard and video display interface was uncommon, as most microcomputer kits were then delivered with only a hexadecimal keypad and seven-segment display. To minimize cost, the buyer had to assemble a Nascom by hand-soldering about 3,000 joints on the single circuit board.

Find all info about this Core on the Filehost:
https://files.mega65.org?id=b9646621-8287-4bb9-9209-4a3450a0f188


# Cores still in Development (incomplete)

## VIC-20 / VC-20

<img src=Commodore-VIC-20-FR.jpg width="600">

https://en.wikipedia.org/wiki/VIC-20

The VIC-20 (called VC20 in Europe) is a personal computer released in 1980/81.

An Alpha Version of this Core has been released for public testing and feedback via Discord only (it is not on the Filehost). To download the core, read the instructions and follow the discussion on Discord here:

https://discord.com/channels/719326990221574164/1282769253921198120

Further instructions and the source code can be found here:

https://github.com/MJoergen/VIC20MEGA65

## Commodore 128

<img src=Commodore-128.jpg width="600">

https://en.wikipedia.org/wiki/Commodore_128

The C128 is a significantly expanded successor to the C64, with nearly full compatibility. It is housed in a redesigned case with an improved keyboard including a numeric keypad and function keys. Memory was enlarged to 128 KB of RAM in two 64 KB banks. A separate graphics chip provided 80-column color video output in addition to the original C64 modes. It also included a Zilog Z80 CPU which allows the C128 to run CP/M, as an alternative to the usual Commodore BASIC environment. The huge CP/M software library, coupled with the C64's software library, gave the C128 one of the broadest ranges of available software among its competitors.

A very early and experimental version of a Commdore 128 Core can be discussed in a Discord channel: 

https://discord.com/channels/719326990221574164/1519078295277404300

Documentation, Source Code and Downloads can be found on the Github:

https://github.com/eilers/c128Mega65

And the latest news can be found on the development blog here:

https://wiki.eilers-online.net/c128Mega65

## Apple II
<img src=Apple_II_Plus.jpg width="600">

https://en.wikipedia.org/wiki/Apple_II_(original)

The Apple II is a personal computer released in 1977. A first alpha version of a Core has been released. While it generally works, it has limited disk file compatibility, so you need to reed the documentation to prepare your disks to load.

You can find a version of the Core on Discord: https://discord.com/channels/719326990221574164/801767398675316756/1530920098787885126

Also you can discuss the Core and get updates on Discord:
https://discord.com/channels/719326990221574164/1522848976607641700

## Sinclair QL
<img src=Sinclair-QL.jpg  width="600">

https://en.wikipedia.org/wiki/Sinclair_QL

The Sinclair QL was a personal computer released by Sinclair Research in 1984, built around a Motorola 68008 CPU running at 7.5MHz. It ran QDOS, a multitasking operating system years ahead of its time, and used Microdrives (small tape-loop cartridges) instead of floppy disks for storage.

You can find a version of the Core on Github:
https://github.com/dfernande132/QL4M65

Also you can discuss the Core and get updates on Discord:
https://discord.com/channels/719326990221574164/1533550109449650277


# Cores in Development, unavailable

## Amiga (Core Development by Kiwi)
A second Amiga core has started development, but currently there is nothing to try out. Please check the Discord for current development news. The goal is to support more machines and chipsets than just the Amiga 500 and OCS.

https://discord.com/channels/719326990221574164/1313409877393276948

## MSX
A MSX core is in active development, but no test version has been released yet.