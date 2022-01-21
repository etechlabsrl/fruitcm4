# Salmonberry Pi, Fruit \ 'früt \

<a href="https://www.raspberrypi.org"><img src="https://www.raspberrypi.org/wp-content/uploads/2012/03/raspberry-pi-logo.png" alt="Raspberry Pi Logo" align="left" style="margin-right: 25px" height=150></a>

> The Raspberry Pi is a series of credit card-sized single-board computers developed in the United Kingdom by the Raspberry Pi Foundation to promote the teaching of basic computer science in schools and developing countries. Official Link: [Raspberry Pi Foundation Homepage](https://raspberrypi.org), [Raspberry Pi Computer Homepage](https://www.raspberrypi.com)

<p>

Salmonberry Pi is a group of open source hardware projects which allow the construction of cluster hardware from small to arbitrary size using Raspberry Pi platforms.  This includes the Raspberry Pi Compute Module 4 (CM4) Raspberry Pi Zero 2 W, Raspberry Pi 4 Model B, and Raspberry Pi RP2040 microcontrollers.

The goals of this project are to provide:
- infrastructure for clustering nodes
- self-sufficient nodes by default (no 'leader')
- remotely monitoring
- remote management
- standard form factors and connectors, although perhaps repurposed

The component projects are:
- [Face CM4](https://github.com/salmonberrypi/facecm4), 8TE 3U faceplate with jacks, microSD card slot and LEDs.
- [Fruit CM4](https://github.com/salmonberrypi/fruitcm4), carrier board for CM4, general purpose compute or storage or both.
- [Graft](https://github.com/salmonberrypi/graft), development board to bring up Fruit board, allows diversion to on-board connectors for rhizome served power and signals. Can be used with or without rhizome boards. (out of date)
- [Thorn](https://github.com/salmonberrypi/thorn), passive board to protect the male plug on the Fruit or Graft boards. (out of date)
- [Rhizome](https://github.com/salmonberrypi/rhizome), life support systems and connectivity
- [Stem 3U x 160mm](https://github.com/salmonberrypi/stem_3U_160mm_X4), 3U x 160mm passive slot extension for debugging

(images are from a previous revision and out of date, shown for reference)

PCB front:

<img src="https://github.com/salmonberrypi/fruitcm4/blob/main/artifacts/fruitcm4.png?raw=true" height=400 width=775>

PCB back:

<img src="https://github.com/salmonberrypi/fruitcm4/blob/main/artifacts/fruitcm4%20back.png?raw=true" height=400 width=775>

Dimensions: 160 x 100mm (0.562 x 0.478 [bananas](http://bananaforscale.info/#!/convert/length/bananas/millimeters)) without connector and faceplate, 4 layer PCB (pwr/signal, gnd, gnd, pwr/signal).

Review [Interactive BOM](https://htmlpreview.github.io/?https://raw.githubusercontent.com/salmonberrypi/fruitcm4/main/artifacts/bom/ibom.html).

Review [Schematic](https://github.com/salmonberrypi/fruitcm4/blob/main/artifacts/fruitcm4%20schematic.pdf).

---

Designed in [KiCad 6](https://kicad.org) on [Ubuntu](https://ubuntu.org) 21.10 (impish).

---

Raspberry Pi is a trademark of Raspberry Pi Trading

---

Copyright (C) 2022 Christian Kuhtz

This source describes Open Hardware and is licensed under the CERN-OHLW v2
<P>
You may redistribute and modify this documentation and make products
using it under the terms of the CERN-OHL-W v2 (https:/cern.ch/cern-ohl).
<P>
This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED
WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY
AND FITNESS FOR A PARTICULAR PURPOSE. Please see the <a href="https://ohwr.org/cern_ohl_w_v2.txt">CERN-OHL-W v2</a> for applicable conditions.
<P>
Source location: https://github.com/salmonberrypi
<P>
As per CERN-OHL-W v2 section 4.1, should You produce hardware based on
these sources, You must maintain the Source Location visible on the
external case of the Salmonberry Pi or other product you make using
this documentation.

