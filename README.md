(Sources have not yet been uploaded)

# Unundulu's Demo

Unundulu has published the source files of music created with the Interruptive Sequence technique.
It is very interesting tasty music.

## Interruptive Sequence

Interruptive Sequence is a method of creating music in a single-track without overlapping notes.
This repository provides source files (ZMS) created with Interruptive Sequence on X68000.

## Path to Revitalization

ZMS is an MML source file for Z-MUSIC V2.
The contents of the source file is text written in Shift-JIS character code.
The line feed code is CR+LF (0x0D0A) in MS-DOS style.
Text editors that do not support old-style text files will not display the file correctly.

By following the steps below, you can enjoy the original sound as it is.
Reverbs, fades, delays, and other things that pollute the sound are useless. They should be extinct.

1. We will prepare a fully working SHARP X68000 actual machine.
2. Emulator is deprecated. This is because of dissatisfaction with the emulation of the sound source section. Two main points are as follows:
    - I have a problem with extreme sound reproduction. I use such sounds a lot.
    - Noise generated by the actual machine is not reproduced.
    - Sound quality is too clear.
    - Difficulty in operating the keyboard due to the different keyboard layout. Unbearable psychological distress.
    - DC offset is slightly off.
    - I am not denigrating emulators. It is a wonderful thing.
3. In a standard Human68k system, OPMDRV is registered as a device driver, 
which can cause problems, so delete the relevant line in config.sys to prevent OPMDRV from being registered.
4. Install Z-MUSIC V2 system, full set of Z-MUSIC V2.08 
(ZMSC208.LZH, ZMSC208X.LZH, ZMSC2MAN.LZH) after installation,
overwrite the Z-MUSIC universal version 2.09 (ZM209.ZIP) improved by Mr. Tachibana.
5. Make Z-MUSIC resident in the system. Specify option switches as needed.
To safely play zms with large file sizes, specify a larger track buffer,
work area more than the default value.
6. Type `zp MUSIC.zms` on the command line to play.
7. If you have read this far and still can't play it, you have to give up. Lack of talent.
8. What if it were “easy” and “certain” to obtain this talent...?
