# Marlin 3D Printer Firmware Configuration for the Ender 3 with BigTreeTech SKR MINI E3 V2.0 with BL Touch

## THIS IS A WIP CURRENTLY, I AM STILL TUNEING THE SETTINGS

Designed for the [BigTreeTech SKR MINI E3 V2.0](//https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/9b13018d639cf4fbecf004493517f72443d22bb0/hardware/BTT%20SKR%20MINI%20E3%20V2.0/Hardware/BTT%20SKR%20MINI%20E3%20V2.0%20Instruction%20Manual.pdf) with standart BL Touch Probe

The config is modified from the example from the [Marlin LTS 2.1.2 Repo](//https://github.com/MarlinFirmware/Marlin/tree/lts-2.1.2)

The BL Touch should be plugged directly into the `z_probe` port.
Configued to use an optional filimant runout sensor. 

The Mini E3 V2.0 uses a [STM32F103RCT6](//https://www.digikey.com/en/products/detail/stmicroelectronics/STM32F103RCT6/2035353), this is a 256KB flash chip. Use the `STM32F103RC_btt (256K)`



## Installing

- Pull Marlin version 2.1.2.5 from [Github](//https://github.com/MarlinFirmware/Marlin/tree/lts-2.1.2) or download the [source](//https://github.com/MarlinFirmware/Marlin/releases/tag/2.1.2.5)

- Copy the files under the `Marlin` folder of this repo to the `Marlin` folder of the pulled Marlin Firmware

- Build using `STM32F103RC_btt (256K)` or `STM32F103RC_btt_USB (256K)` for USB Media Share Support. 

The Mini E3 V2.0 uses a [STM32F103RCT6](//https://www.digikey.com/en/products/detail/stmicroelectronics/STM32F103RCT6/2035353), this is a 256KB flash chip. Maple uses a diffrent library which from what I can tell is no longer maintained.

I used [Visual Studio Code](//code.visualstudio.com/download) using the [Auto Build Marlin](//marlinfw.org/docs/basics/auto_build_marlin.html) extension. There are other ways to build the firmware documented on [Marlin's Website](//https://marlinfw.org/docs/basics/install.html)

## General Marlin Support

- [Marlin Documentation](//marlinfw.org) - Official Marlin documentation
- [Marlin Discord](//discord.com/servers/marlin-firmware-461605380783472640) - Discuss issues with Marlin users and developers
- Facebook Group ["Marlin Firmware"](//www.facebook.com/groups/1049718498464482/)
- RepRap.org [Marlin Forum](//forums.reprap.org/list.php?415)
- Facebook Group ["Marlin Firmware for 3D Printers"](//www.facebook.com/groups/3Dtechtalk/)
- [Marlin Configuration](//www.youtube.com/results?search_query=marlin+configuration) on YouTube

## Marlin License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.
