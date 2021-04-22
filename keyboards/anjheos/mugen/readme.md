# mugen

![mugen](https://i.imgur.com/bn0itC9.png)

The Mugen keyboard is a passion project born from a curiosity of designing the most ideal keyboard for myself. Featuring an accent midpiece that goes from one side of the board to the other, terminating toward the front in a sharp angular feature that captures the aesthetic and vision I had. 

![mugenpcb](https://i.imgur.com/AOPSQpr.jpg)

The Mugen PCB is compatible with the C3 UDB to allow for better placement of the USB port during the design phase of the case. This allowed me to preserve the midpiece as one continuous accent from one side of the case to the other. 

The PCB is also compatible with different physical layouts such as ANSI, ISO, Tsangan, and also Stepped Capslock. 

* Keyboard Maintainer: [Anjheos](https://github.com/Anjheos)
* Hardware Supported: Anjheos Mugen PCB Rev 1.1
* Hardware Availability: TBD

Make example for this keyboard (after setting up your build environment):

    make anjheos/mugen:ansi_default
    make anjheos/mugen:iso_default
    make anjheos/mugen:tsangan_default
    make anjheos/mugen:split_backspace

Flashing example for this keyboard:

    make anjheos/mugen:ansi_default:flash
    make anjheos/mugen:iso_default:flash
    make anjheos/mugen:tsangan_default:flash
    make anjheos/mugen:split_backspace:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

How to reset the board into bootloader mode:

   - Get some metal tweezers or something to short pads.
   - Connect the PCB to your computer via the UDB and a USB cable.
   - Stick the tweezers to short these two pads boxed in green here:
   ![reset](https://i.imgur.com/1z0Vpd2.png)
   - The computer should give the notification sound if successful, the keyboard should now be in bootloader mode.
   - Flash the PCB using your preferred method.
   - Done!
   (note: The PCB should come pre-flashed with the default QMK "ansi_default" keymap and should be detected by the PC right out of the packaging.)

