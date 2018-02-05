# hex2vga

This Ruby script writes a VGA/EGA ("console") font file to stdout, based on
a "hex" file as exported by gbdfed(1). I made this because I wanted
wscons(4) to load Christian Neukirchen's super awesome "sq" font.

    hex2vga infile input-height output-height > outfile

For example:

    ./hex2vga /path/to/sq.hex 13 16 > sq.816

To the maximum extent possible, I (Charlotte Koch) disclaim ownership of
this code and dedicate it to the public domain.
