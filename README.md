# Video-Frame-Generator
Verilog Implementation of a frame generator that can output to a video display.

The vga_example.v is the top level design and contains a simple test pattern that displays colured lines on the edges of the active display. Yellow at the top, red at the bottom, green on the left and blue on the right. The active display interior is filled grey. 

vga_timing.v is the actual IP.

The testbench instantiates a tiff_writer which outputs a single frame of video after the simulation is run. Helps debugging.  

This design is targeted towards Basys™3 Artix-7 FPGA Board.
