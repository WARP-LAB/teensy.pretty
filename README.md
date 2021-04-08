Teensy footprint library for KiCAD
=======================================

This repo includes KiCAD footprints for the following Teensy versions:

  - Teensy 1.0 ([C](https://www.pjrc.com/teensy/card1a.pdf), [Arduino](https://www.pjrc.com/teensy/card1b.pdf))
  - Teensy++ 1.0 ([C](https://www.pjrc.com/teensy/card3a.pdf), [Arduino](https://www.pjrc.com/teensy/card3b.pdf))
  - Teensy 2.0 ([C](https://www.pjrc.com/teensy/card2a_rev5_web.pdf), [Ardino](https://www.pjrc.com/teensy/card2b_rev5_web.pdf))
  - Teensy++ 2.0 ([C](https://www.pjrc.com/teensy/card4a_rev2_web.pdf), [Arduino](https://www.pjrc.com/teensy/card4b_rev2_web.pdf))
  - Teensy 3.0 ([Front](https://www.pjrc.com/teensy/card5a.pdf), [Back](https://www.pjrc.com/teensy/card5b.pdf))
  - Teensy 3.1 ([Front](https://www.pjrc.com/teensy/card5a_rev7.pdf), [Back](https://www.pjrc.com/teensy/card5b_rev6.pdf))
  - Teensy 3.2 ([Front](https://www.pjrc.com/teensy/card7a_rev3_web.pdf), [Back](https://www.pjrc.com/teensy/card7b_rev3_web.pdf))
  - Teensy LC ([Front](https://www.pjrc.com/teensy/card6a_rev4_web.pdf), [Back](https://www.pjrc.com/teensy/card6b_rev4_web.pdf))
  - Teensy 3.5 (Includes 3D Model by Darcy) ([Front](https://www.pjrc.com/teensy/card8a_rev3_web.pdf), [Back](https://www.pjrc.com/teensy/card8b_rev3_web.pdf))
  - Teensy 3.6 (Includes 3D Model by Darcy) ([Front](https://www.pjrc.com/teensy/card9a_rev2_web.pdf), [Back](https://www.pjrc.com/teensy/card9b_rev2_web.pdf))
  - Teensy 4.0 (Includes 3D Model) ([Front](https://www.pjrc.com/teensy/card10a_rev2_web.pdf), [Back](https://www.pjrc.com/teensy/card10b_rev2_web.pdf))
  - Teensy 4.0 SMT (Includes 3D Model)
  - Teensy 4.1 (Includes 3D model by Zack Kummer) ([Front](https://www.pjrc.com/teensy/card11a_rev3_web.pdf), [Back](https://www.pjrc.com/teensy/card11b_rev3_web.pdf))

Notes:
  - The Teensy 4.0 SMT footprint requires the addition of edge cuts (indicated
by lines in the Dwgs.User layer) which create castellated connections for most
pins.  Pins 2, 3, 31, 32 & 34 are not castellated and will require careful soldering
and probably a wire to ensure a reliable connection.

- There are two footprints for Teensy 3.0/3.1/3.2 and 3.5/3.6: one that includes the through-hole connections on Teensy and one that adds all of the SMT connections on the bottom of the Teensy.

For symbols look here: https://github.com/XenGi/teensy_library
