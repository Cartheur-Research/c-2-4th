# c-2-4th

A c-2-4th compiler using direct translation - written in C and using Bison.

## NOTE

Reinsert support for Protocol 1.0 as the [AX-12A](https://emanual.robotis.com/docs/en/dxl/ax/ax-12a/) are being replaced by [XL430-W250](https://emanual.robotis.com/docs/en/dxl/x/xl430-w250/).

## Setting-up the environment

Make sure you have bison and a gcc compiler before utilizing the shared code.

## Project targets

* The C-code of the dynamixel [sdk](https://github.com/Cartheur-Research/dynamixel-sdk)
* And the manual to understand how it [works](https://github.com/Cartheur-Research/robotis-sdk-manual/tree/master/docs/en/software/dynamixel)

## Note

* Since head-two uses AX-12A, will need to re-introduce the protocol 1.0 code.
* Since wanting to use it for _both_ robots, will keep protocol 2.0 code.
* Hence, will make these changes in the dynamixel library.