# LVGL for BeagleBone Black with Element14 4.3" LCD Display

LVGL configured to run on BeagleBoneBlack with [Element14 4.3" LCD
Display](https://community.element14.com/products/devtools/product-pages/w/documents/22398/4-3-lcd-display-cape-for-beaglebone-board-white-black-or-wireless).

The very simple demo shows a slider on the screen, which can be manipulated
using the touch screen.

When cloning this repository, also make sure to download submodules (`git
submodule update --init --recursive`) otherwise you will be missing key
components.

Before building, make sure to `apt install libinput-dev`.

This repository is based off
[lv\_port\_linux\_frame\_buffer](https://github.com/lvgl/lv_port_linux_frame_buffer).
