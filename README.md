# Arduino-based RC (Remote Control) Transmitter Handset

![handset](diy_elrs_handset.png)

* Purpose:
  - This 3d printable shell and Arduino source code will let you build your own RC transmitter for planes, quadcopters, rovers, boats, robots, etc.


* Hardware needed:
  - Radiomaster zorro-sized AG01 mini; or zorro-sized style plastic gimbals (zorro is a model of radiomaster brand transmitter handset)
  - elrs serial receiver (as normally used in a quadcopter, etc); but flashed with 'rx as tx' firmware
  - Arduino nano (atmega 328) cpu; but could also be most any cpu
  - various switches
  - optional oled .96" i2c display
  
* Software:
  - Arduino source is included
  - This is experimental in nature; do not trust this until you personally verify it.  I'm considering this alpha quality, until I also get more experience with this code base.
  - Arduino older style is enough to build/flash this.  Newer style and PIO may also (should) work.


* 3D print STL files in the stl folder
  ![3dprints](3d-printables.png)


![modifiedtop](modified-top-stl.png)

![modifiedtop2](modified-top-stl-2.png)

![modifiedtop](3modified-top-stl-3.png)
