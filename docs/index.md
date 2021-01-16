---
layout: default
---

![SofleKeyboard](images/sofle_keyboard.jpg)

Sofle is 6×4+5 keys column-staggered split keyboard with encoder support. Based on [Lily58](https://github.com/kata0510/Lily58), [Corne](https://github.com/foostan/crkbd) and [Helix](https://github.com/MakotoKurauchi/helix) keyboards.

SofleKeyboard was created by [Josef Adamcik](https://josef-adamcik.cz/). The motivation and process is covered in following blog-post: [Let me introduce you SofleKeyboard - a split keyboard based on Lily58 and Crkbd](https://josef-adamcik.cz/electronics/let-me-introduce-you-sofle-keyboard-split-keyboard-based-on-lily58.html)

It is still in [development](https://github.com/josefadamcik/SofleKeyboard/tree/develop), but the first version gained some popularity and there was even some group buys.

[Build guide is here]({{ baseurl }}/SofleKeyboard/build_guide.html).

If you are interested in building the board and don't want to bother with KiCad, the gerber files are available in [releases](https://github.com/josefadamcik/SofleKeyboard/releases).

## License

- Hardware source files are licensed under MIT license.
- The documentation (both on [josefadamcik.github.io/SofleKeyboard/](https://josefadamcik.github.io/SofleKeyboard/) and [https://josef-adamcik.cz/](https://josef-adamcik.cz/)) is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. This includes all photos and images in this repository and on the website.
- Firmware is part of QMK firmware and has the same licence (GPL v2)

## Firmware 

Sofle uses [QMK firmware](https://qmk.fm/)

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

Make example for this keyboard (after setting up your build environment):

    make sofle:default

Flash the default keymap: 

    make sofle:default:avrdude

Press reset button on he keyboard when asked.

Disconnect the first half, connect the second one and repeat the process.

You can also use [QMK configurator](https://config.qmk.fm/#/sofle/rev1/LAYOUT) but beware, it does not support rotary encoders yet.

## Default layout 

![Default layout for SofleKeyboard](images/soflekeyboard.png)

## Gallery

![SofleKeyboard](images/IMG_20200126_114622.jpg)

![SofleKeyboard](images/IMG_20191110_131443.jpg)

![SofleKeyboard](images/IMG_20200126_114622.jpg)

![SofleKeyboard Choc](images/sofle_choc.jpg)

![SofleKeyboard PCB](images/IMG_20191104_202757.jpg)
