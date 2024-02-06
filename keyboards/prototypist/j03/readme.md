# prototypist/j03

![prototypist/j03](imgur.com image replace me!)

*The latest addition to the J-Series Family of designs by Jae of Proto[Typist]. Featuring a compact 1800 style layout, in lieu of an F-row is the staple of the J-Series: the Pen Rail. The design features the same aesthetic as its predecessors, as well as the same mounting and construction. Definitely a board for those in need of a more productivity-focused layout.*

* Keyboard Maintainer: [Josh @ Prototypist](https://github.com/Anjheos)
* Hardware Supported: **J-03 PCB**
* Hardware Availability: [Proto[Typist]](https://prototypist.net)

Make example for this keyboard (after setting up your build environment):

    make prototypist/j03:default
    make prototypist/j03:via
    make prototypist/j03:default_ansi

Flashing example for this keyboard:

    make prototypist/j03:default:flash
    make prototypist/j03:via:flash
    make prototypist/j03:default_ansi:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
