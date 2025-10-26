# Acorn A3000 8MB RAM board

October 2025


![3D View](Generated/A3000_8MB_3D_View.PNG)

An 8MB RAM upgrade for Acorn A3000 machines.  The PAL, IC71, is a copy from that found in the Acorn A540.

The 1.0 design has been built and tested and works well, but does still need the motherboard reset line to ARM severed and looped to this board, so ARM reset can be controlled from this board -- still looking in to solutions for that.

An updated version using through-board SMT headers (with PCB holes for the tall RAM expansion pins to pass right through) for the data bus which significantly helps the issue of board alignment - allowing the board to sit perfectly parallel with the motherboard, reducing issues with MEMC socket contact.

The self-reset circuit does appear to achieve the reset required without the motherboard mod.


## Licence

No warranty is provided, and this work is used at your own risk.  

Licenced as CC BY-SA 4.0

Copyright 2025 Ian Jeffray

