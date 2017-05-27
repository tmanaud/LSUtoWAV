# LSU to WAV Converter.

This simple (simple!) utility converts all the LSU files in a directory
to wave files. LSUs are used largely by microcontrollers (especially 
lightsabers) and are raw 16 bit, mono, 44100Hz data. This utility 
adds the WAV wrapper and writes a new file.

Source are provided on github.

## Notes

The original lsu files won't be changed. wav files will be created 
and placed in the same directory.

## Compiling

make

## Using

### The easy way
Place the binary file in the directory with your LSU files and run it to generate WAV files.

### The command line
- Open up the command line.
- Change directory to your .LSU files.
- \path\to\exe\lsuToWav

## Credits
- By Lee Thomason (www.grinninglizard.com) https://github.com/leethomason/LSUtoWAV
- Wave converter from: https://github.com/leethomason/wave_reader_and_writer



