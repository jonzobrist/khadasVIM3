# khadasVIM3
[Khadas SBC VIM3/VIM3 Pro - Available from their store](https://www.khadas.com/product-page/vim3) related code

Khadas is an SBC that supports Linux and Android in roughly the same size as a Raspberry Pi 4. The Basic has 2GB RAM and 16GB of eMMC, and the Pro has 4GB of RAM and 32GB of eMMC and costs $139.90 USD.

Khadas boards feel like high quality, and so do their add ons. The *new* M2X extension is only $8 and snaps onto the M.2 slot of the SBC. With it you can add an NVMe disk and a 4G LTE modem.

Currently this only contains SD card images built using [Khadas fenix](https://github.com/khadas/fenix)

[Ubuntu Bionic (18.04) img.xz](https://github.com/jonzobrist/khadasVIM3/raw/main/fenix-built-images/VIM3_Ubuntu-minimal-bionic_Linux-5.16_arm64_SD-USB_V1.0.10-220320-develop.img.xz)

[Ubuntu Focal (20.04) img.xz](https://github.com/jonzobrist/khadasVIM3/raw/main/fenix-built-images/VIM3_Ubuntu-minimal-focal_Linux-5.16_arm64_SD-USB_V1.0.10-220320-develop.img.xz)

Download and flash with [Balena Etcher](https://www.balena.io/etcher/), or similar, to a MicroSD card *SMALLER* than 128GB. Plug into your Khadas VIM3 and boot.

![](https://github.com/jonzobrist/khadasVIM3/raw/main/images/zob-VIM3Pro.jpeg)
