# Meteor Storm DX
This game is a remake of [Meteor Storm](https://thenetworknomad.itch.io/meteor-storm), originally released January 2021 for the MSX using DM SYSTEM/2. This is a port of the game to MSX-DOS written in [PARASOL](http://www.cpm.z80.de/develop.htm) for improved performance and smoothness of gameplay. Additionally, it serves as an example game (and served as the test game) for integrating the Gemini FM music playroutine as well as writing a game in PARASOL (although as my first compiled game, it is not exactly a shining paragon of MSX programming best practices- you've been warned!).

# Compiling and Running
The PARASOL compiler is a CP/M-80 program, so it must be used on a CP/M-80 device or in an emulator such as [iz-cpm](https://github.com/ivanizag/iz-cpm). While CP/M programs are largely compatble with MSX-DOS, the PARASOL compiler has a number of issues with it so compiling on MSX may not work correctly. To compile in CP/M, enter the directory containing the SRC file and the compiler and type:

`PARASOL METEORDX.COM`

Or to compile using iz-cpm without actually entering the CP/M command line on your modern machine, enter the directory containing the SRC file and the compiler and type:

`IZ-CPM PARASOL.COM METEORDX.COM`

Either of these will create the METEORDX.COM executable for use in MSX-DOS. 

To run, simply type:

`METEORDX` 

at the MSX-DOS command prompt to launch the game. GFMRAM.BIN and METBGM.BIN must be present in the same directory in order for the game to run.

# Requirements 
- MSX (any generation) with 64KB RAM
- MSX-DOS

This game is playable with keyboard or joystick, but for the intended and best experience use a paddle controller or mouse.

# Acknowledgements
This game is public domain. If you paid for it, you got ripped off! The game logic is based on the original Meteor Storm which was a joint venture between myself and Maddie Russell. The music driver uses the [GETSLT routine](http://map.grauw.nl/sources/getslot.php) from the MSX Assembly Page written by Grauw. This game would not be possible without the MAP or MSX.org.
