# Gergoplex

![Gergoplex](https://assets.bigcartel.com/product_images/248890490/IMG_20191114_1406385-01-01.jpeg)

~~A compact 50% (14x4) Split Keyboard compatible with i2c modules and a trackball.~~

~~[More info on qmk.fm](http://qmk.fm/gergo/)~~

Keyboard Maintainer: [Jeremy Bernhardt](https://github.com/germ)
Hardware Supported: Gergoplex (Kit, Partial, Ready)
Hardware Availability: [gboards.ca](http://gboards.ca)

## Firmware building
After cloning the QMK repo and installing dfu-programmer build and flash with. Be sure to reset your keyboard!

    make gergoplex:default:dfu

To just test your build with the default keymap
   
    make gergoplex:default

Gadgets and options can be enabled/disabled in keyboards/gergoplex/keymaps/default/rules.mk . Copy the default directory and make any changes to your layout, if you think they're worth sharing submit a PR!

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Have an idea for a gadget? [Reach out to me!](mailto:bernhardtjeremy@gmail.com)
