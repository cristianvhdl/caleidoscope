# Caleidoscope video generator with edge enhacement filter

FreeFull's caleidoscope-alike video generator adapted for FPGA
by DigitalCold, passed thru edge enhancement filter from
Mike Field and output to HDMI.

Creates ever-changing beautiful RGB color patterns on 640x480
VGA resolution, like on some screen savers.

It doesn't need external RAM for framebuffer, video is generated
on-the-fly using the state machine with only a couple of registers.

Boards readily working:
    scarab miniSpartan6+ (xilinx spartan-6)
    FleaFPGA Uno (lattice machxo2)

Might be easily ported to any.

Combination of those two effects suggested by Goran Mahovlic.

Credits (original sites where code is taken from):

    http://io.netgarage.org/arm/digitalcold
    https://github.com/hamsternz/Artix-7-HDMI-processing
    https://github.com/hamsternz/Artix-7-HDMI-processing/blob/master/src/edge_enhance.vhd
