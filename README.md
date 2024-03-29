# Breakout386

This project was inspired by the [Hand386 computer](https://yeokhengmeng.com/2023/06/teardown-and-review-of-hand386/), and it will reuse the same base components, but instead of a handheld device, it's going to be an extremely light SBC. By stripping down all extras (battery, screen, keyboard, graphics card, sound card, USB interface), it's possible to make the PCB design simple and low-cost. All the interfaces provided by the SoC will be broken out to expansion connectors, so all the extras can still be added as expansion cards.

The goals of this project are: simplicity, extandability and reusing old components as much as possible. Surface mount components are prefered over their through-hole counterparts, except for connectors.

# Specs

- M6117D SoC (M1386SX CPU + M1217B chipset)
- *TBD* DRAM
- *TBD* CMOS Flash (BIOS)
- ISA bus for expansion cards
- IDE interface for storage media
- PS/2 interface for keyboard and mouse
- PC speaker
- RTC battery
- GPIO
- 5V power input
