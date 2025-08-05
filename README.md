# YOU MUST CHECK fingerguns.overlay TO ENSURE THE PROPER PHYSICAL LAYOUT IS CHOSEN

Please see the comments on line 4 of fingerguns.overlay.  In the 'chosen' node, you will need to adjust zmk,physical-layout depending on if you are using the 12 column variant or the 10 column variant of the Fingerguns PCB.

The 12 column is represented by &layout_12col
The 10 column is represented by &layout_10col

# YOU MUST SELECT OR CREATE AN APPROPRIATE KEYMAP

In the ergomech community a keymap is an intensely personal thing.  That being said, I've included my own 12 column and 10 column keymaps in case you need somewhere to start.  Please note that fingerguns.keymap is intended for the 10 column variant.  A 12 column keymap is also included under the name fingerguns.keymap.12col.  If you wish to use 12 columns, simply append '.10col' to the default keymap and delete '.12col' from the other one.

# BOM
36-42 choc switches & keycaps
36-42 choc hotswaps
36-42 smd diodes
6 M2 heat set inserts
6 M2 x 6mm screws
1 MSK12C02 switch
1 Panasonic EVQPUJ_EVQPUA button
1 pro micro form factor MCU
1 301230 110mAh battery (optional)

If you are confused about switches, all parts except the inserts and screws can be sourced from typeractive.xyz.

# BUILDING
If planning to use the case, the MCU should be soldered with the included headers, NOT sockets.  The sockets add too much height to fit in the case.  A hot plate is recommended for assembly, as it makes the whole process very quick and easy.  Assembly is possible by hand with a soldering iron, though it can be delicate and frustrating.  For the diodes and switches, I recommend tinning one pad first, then placing the component with tweezers before soldering the other side.  Some of the photos show a battery pigtail, but ultimately I decided to solder the battery wires directly to the board and stick the battery down with a command strip.

# CASES
Files are included to 3d print a case for the 12col variant, designed by my brother.  PCB is secured with 6 M2 heat set inserts. The 10col case is still in development, but will be added to the repo when it's done.  I've also included a .step file of the PCB under /gerbers_and_kicad if you'd like to design your own.

# LICENSING
All hardware in this repo is licensed under CERN-OHL-S-2.0, available at https://gitlab.com/ohwr/project/cernohl/-/wikis/uploads/819d71bea3458f71fba6cf4fb0f2de6b/cern_ohl_s_v2.txt