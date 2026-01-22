# Icepi SBC

A low-cost single-board computer for the H3 CPU: A cheap yet powerful Linux device that you can take anywhere.

![](assets/top.jpg)

| Interested? [Subscribe to updates!](https://cyao.dev/subscribe.html) | Check out [Icepi Zero](https://github.com/cheyao/icepi-zero) too |
| -------------------------------------------------------------------- | ---------------------------------------------------------------- |

If there's a lot of people interested, there's a chance that I'll try to sell this at a relatively low price :P

## Features

- H3 Quad-Core ARM Cortex-A7 @ 1.296GHz CPU
    - Mali400 MP2 OpenGL ES 2.0 GPU
- 512MiB of DDR3 RAM, stable at 696MHz (Upgradable to 1GiB)
- Ethernet PHY, WiFi & Bluetooth
- GPDI video out
- USB connectors:
    - 2x USB-A 
    - 2x USB-C (One OTG port)
    - 1x USB-C 100W PD power port
- 3.5mm audio jack
- uSD card slot
- eMMC 5.1 storage

![](assets/top.jpg)

## System support

The single-board computer is capable of running Linux (debian) and Android ([H3Droid](https://h3droid.com/project)). It can output 4k video via it's GPDI-A connector, output a tty consol via UART, or act as an remote host via ssh.

It's small, compact form factor allows it to be a nice portable computer that you can take anywhere! It supports GPU acceleration and 4k video decoding, letting you view anything in full confort.

![](assets/linux.jpg)

## PCB

[Check out the online version here](https://github.com/cheyao/icepi-sbc/tree/main/hardware).

The PCB is only 4 layered, ensuring minimal cost and overhead during production. But for mass production 6 layers is recommended, putting solid ground on In.1 and In.4, then copy the power plane to In.2 and In.3. (Impedance matching might be required depending on stackup)

![](assets/routing.png)

The current setup uses [JLCPCB's](https://jlcpcb.com/) JLC04161H-3313 stackup, and the BOM is optimized for use there. Using other fabs would require re-tuning the DDR3, USB and GPDI traces.

## Open source

This project is licensed under the [Solderpad](/LICENSE) hardware license, granting the maximum amount of liberty :)

It is also OSHWA certified under the identifier [FR000029](https://certification.oshwa.org/fr000029.html).

![](assets/top-with-cables.jpg)

## Contact

Any questions? Dm `@Cyao.` on Discord (Send a friend request or join the KiCAD Discord server) or send an email to `cyao _at_ duck.com`!

![](assets/back.jpg)

## Bonus

POV: Running Android on the single board computer to study Eigenvectors in the middle of the night:

![](assets/android.jpg)

