# Sofle Keyboard

![SofleKeyboard](Images/IMG_20200126_114622.jpg)

Sofle is 6×4+5 keys column-staggered split keyboard with encoder support. Based on [Lily58](https://github.com/kata0510/Lily58), [Corne](https://github.com/foostan/crkbd) and [Helix](https://github.com/MakotoKurauchi/helix) keyboards.


## More information and documentation

It is still in [development](https://github.com/josefadamcik/SofleKeyboard/tree/develop), but the first version gained some popularity and there was even some group buys.

More details about the keyboard on my blog: [Let me introduce you SofleKeyboard - a split keyboard based on Lily58 and Crkbd](https://josef-adamcik.cz/electronics/let-me-introduce-you-sofle-keyboard-split-keyboard-based-on-lily58.html)

The current (temporary) build guide and a build log is available here: [SofleKeyboard build log/guide](https://josef-adamcik.cz/electronics/soflekeyboard-build-log-and-build-guide.html)

If you are interested in building the board and don't want to bother with KiCad, the gerber files are available in [releases](https://github.com/josefadamcik/SofleKeyboard/releases).

## Firmware 

Sofle uses [QMK firmware](https://qmk.fm/)

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

Make example for this keyboard (after setting up your build environment):

    make sofle:default

Flash the default keymap: 

    make sofle:default:avrdude

Press reset button on he keyboard when asked.

Disconnect the first half, connect the second one and repeat the process.

## Default layout 

![Default layout for SofleKeyboard](Images/soflekeyboard.png)

## Images of keyboard

![SofleKeyboard](Images/IMG_20191110_131443.jpg)

![SofleKeyboard Choc](Images/chocclear.jpg)

![SofleKeyboard PCB](Images/IMG_20191104_202757.jpg)
