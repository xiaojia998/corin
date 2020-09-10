## About Firmware

Keyboard Name: Corin

Keyboard Maintainer: [Longnald](https://github.com/longnald) & [Seaton Jiang](https://github.com/seatonjiang)

Hardware Supported: [Corin PCB (uses 32U4)](https://github.com/longnald/corin)

## Build Firmware

Install QMK and QMK Toolbox, execute the following command to compile:

```shell
make longnald/corin:default
```

See [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) then the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information.

## Flashing Keyboard

### Put Your Keyboard into DFU (Bootloader) Mode

Press the physical RESET button. In order to flash your custom firmware you must first put your keyboard into a special flashing mode. While it is in this mode you will not be able to type or otherwise use your keyboard. It is very important that you do not unplug the keyboard or otherwise interrupt the flashing process while the firmware is being written.

Then you should see a message in yellow, similar to this in QMK Toolbox:

```shell
*** DFU device connected: Atmel Corp. ATmega32U4 (03EB:2FF4:0000)
```

### Flashing Your Keyboard with QMK Toolbox

The simplest way to flash your keyboard will be with the [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases).

See [Flashing Your Keyboard with QMK Toolbox](https://docs.qmk.fm/#/newbs_flashing) for more information.
