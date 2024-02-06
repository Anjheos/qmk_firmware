# prototypist/j01rev2

![prototypist/j01rev2](imgur.com image replace me!)

*The return of Jae's first designs, the J-01. Bringing back the original layered design of the very first iteration whilst applying the new changes from the J-02 Blackout Edition. The PCB has been refreshed for this iteration with full regional support and VIA compatiblity, as well as the fancy new pink soldermask. Default layout is in ISO.*

* Keyboard Maintainer: [Josh @ Prototypist](https://github.com/Anjheos)
* Hardware Supported: **J-01 Rev.2 PCB**
* Hardware Availability: [Proto[Typist]](https://prototypist.net)

Make example for this keyboard (after setting up your build environment):

    make prototypist/j01rev2:default
    make prototypist/j01rev2:via
    make prototypist/j01rev2:default_ansi

Flashing example for this keyboard:

    make prototypist/j01rev2:default:flash
    make prototypist/j01rev2:via:flash
    make prototypist/j01rev2:default_ansi:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
