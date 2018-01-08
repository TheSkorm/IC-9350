# IC-9350
Codan 9350/3040 to Icom IC-7000 and IC-706 interface circuit and software.

DO NOT connect a IC-706 or an IC-7000 directly to a 5V microcontroller! The Icom radios use open-collector logic, with the IO lines pulled high to 13.8V. This can fry your microcontroller!

Included in this repository is a schematic showing how to handle the level conversions and drive the inputs appropriately.

Some Notes:
  * You can find instructions on how to build in the source file
  * code can be build in the latest 1.8.5 environment
  * doc directory contains schematic, simple enough to build on vero board
  * Refer to the comment block at the top of Icom9350.ino for more information, including wiring info.

TODO
----
* Create PCB gerbers
