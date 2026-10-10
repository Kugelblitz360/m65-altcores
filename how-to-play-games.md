This is a short overview of common commands for people that only know the C64 (and other Commodore computers) and want to try out other computer Cores to play some games. This is no full documentation, just the bare essentials to get started. Systems are shown in alphabetical order.



\## Amiga 500



\### Good to know



The current version of the \*\*official\*\* Amiga 500 Core does only support disks and not harddisks. So "WHDLoad" games will not work at all. Also some games require all RAM available to themselves. For this you need to disable all drives but `df0:` in the settings. And finally, some game do not like the extra memory available. For these you need to disable `Slow RAM` in the settings.



\### The Megamiga fork



On https://github.com/johansmolinski/Megamiga you can find a fork of the Amiga 500 Core that will only work on \*\*R6\*\* machines, but adds emulation of the Amiga 600 and the Amiga 1200, including hard drive support. If you can supply the unencrypted Amiga 1200 Kickstart 3.10 (MD5: 646773759326fbac3b2311fd8c8793ee) you can run the Amigavision Mini version (the full version does not fit onto a FAT32 card).



\* Rename AmigaVision-Mini.hdf to a1200.hdf and AmigaVision-Saves.hdf to a1200-1.hdf and put them into the Amiga dir on the SD card.

\* Get an Amiga 1200 Kickstart and install as in the Megamiga instructions

\* Set the System to Amiga 1200 and manually also set RAM to "Zorro III RAM (16 MB)"

\* Amiga will reboot (takes a while, black screen) and end in the AmigaVision menu

\* Menu unfortunately does NOT work as it tries to call an AmigaEmulator - just press ESC to get to Workbench

\* On Workbench, click the DATA drive (SD Card with a Heart), then the WHD Drawer, then the \*\*G\*\* drawer to find alphabetically sorted games

\* To start a game, double click the game name without an extension; read the screen as many games have a distinct key to get back to workbench





\## Amstrad / Schneider CPC



\### Good to know

When you are ONLY using an analog monitor and not HDMI output, please press  <kbd>HELP</kbd> once to start the display. The initial screen is only visible on HDMI.



\### Loading from disks

To load a game you need a `.dsk` image of the game (or use the tools in the <kbd>HELP</kbd> menu to read a real disk). There is not automatic boot. You need to find out how to start the program by typing <code>CAT</code> and pressing  <kbd>RETURN</kbd>. Most often the game is started by the very first file you see like `GAME.BAS`. You then need to type <code>RUN "GAME</code> and press <kbd>RETURN</kbd>. The Amstrads do not have wildcards like the C64 for filenames, but you can at least skip the extension and the second quote.



\## Apple II



\### Good to know

If you have an Amiga-compatible mouse in one of the ports of the MEGA65, the Apple II switches into a diagnostic mode from which you can not start any games. \*\*Remove the mouse to be able to run games.\*\*



Many games feature weird looking green and magenta ghosting especially on text or white lines. That actually is the way the original Apple II video logic worked to squeeze out color from an NTSC signal.



Use a joystick in the front (close to the Reset button) port of the MEGA65.



\### Loading from disks

In the current version, mounting a `.nib` or `.dsk` disk image while the Apple II main screen is displayed is enough to then start the game.



Should you see a prompt and want to boot the mounted disk, type <code>PR#6</code> and press <kbd>RETURN</kbd>.



Should a disk not automatically load a game, type either <code>CAT</code> or <code>CATALOG</code> to get a list of files. Files marked with an \*\*A\*\* usually are BASIC files and can be started by <code>RUN filename</code>. Files marked with a \*\*B\*\* should be started with <code>BRUN filename</code>.



\## Atari 400/800/XL



\### Good to know

When you are ONLY using an analog monitor and not HDMI output, please press <kbd>SPACE</kbd> once to start the Core. The initial screen is only visible on HDMI.



\### File formats

You need to get games either as `.atr` or as`.xex` files. Other formats (especially cartridges) are not supported currently.



\### Loading from disks (.atr)

To load a disk you need to mount it in the menu you reach by pressing the <kbd>HELP</kbd> key. Then you reboot the Atari by pressing <kbd>F11</kbd>.



Some programs require that the BASIC ROM is disabled. To achieve that, hold <kbd>F1</kbd> while pressing <kbd>F11</kbd>.



Many older games in `.atr` format require the `Atari 400/800` mode you can find in `System Settings`.



\### Loading programs (.xex)

Many Atari Games have been repacked into a format that resembles a \*\*.prg\*\* on the C64, but can continue loading data while a picture is displayed or an intro is running. You mount and start a `.xex` directly in the <kbd>HELP</kbd> menu. Games in this format require the machine to be set in `xL/xE` mode in the `System Settings`



\### Joystick control

Standard Joysticks with one fire button are supported. They should be connected in the front port (near the reset button). The Core does not support port switching yet.



\## Atari ST



\### Good to know

While the Core does come with an OS ROM called "EmuROM", it is neccessary to get a TOS ROM for better compatiblity. Most games on disk will work fine with TOS 1.02 (TOS102) ROMs, especially the UK version (tos102uk.img MD5: b2a8570de2e850c5acf81cb80512d9f6). 



\### Harddisk Emulation

You can also search archive.org for a harddisk image called Atari3GB.vhd which you can mount as a hard disk image. To use this, switch the Core to \*\*STe\*\* mode and use TOS 2.06 (tos206.img MD5: 4a0d4f282c3f2a0196681adf88862dd4).



\### Mouse Emulation

While the Core does support an Amiga-type mouse, you can also move the moue cursor with the keyboard. In standard configuration, the <kbd>MEGA</kbd> key and the cursor keys will move. To simulate a left click, press <kbd>MEGA</kbd> together with <kbd>NO SCROLL</kbd> (which is the equivalent of the Insert-Key of an Atari ST).



\### Disk Formats

The Core does accept basically all valid `.st` files regardless of size, so many unprotected disc formats work. The `.stx` format for copy protected disks is not supported, it is a very specific emulation format that will not work well with FPGA implementations. Many games in `.st` format are defective; games found in "Menu Disks" like "Automation" usually work a lot better.



\## MSX Computers



\### Good to know

The current version of the Core can only load Cartridge files. Disk and Tape support is coming. Only MSX-1 cartridges work; games designed for MSX-2 will not work.











