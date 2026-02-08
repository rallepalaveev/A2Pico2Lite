# A2Pico2 Reference Hardware

This repository is the home of the A2Pico2Lite-SMD reference hardware based on the RP2354A processor. It is an expansion mass storage card for Apple2 computers. It is a limited version of the A2Pico2 design with the restriction that it can use only a USB stick as a storage device. Please refer to the repository at https://github.com/oliverschmidt/a2pico2lite for general information on A2Pico2.

## Hardware Revision History

Version 1.0 is the innitial design.

Version 1.1 is the current version with added parallel capacitors to the voltage dividers of the 5V non-tolerant GPIOs for correction of the waveforms.

The GPIO usage is as follows:

| GPIO    | Usage     |
|:--------|:----------|
| 0       |  IRQ      |
| 1       |  PHI0     |
| 2 - 13  | A0 - A11  |
| 14-21   | D0-D7     |
| 25      | LED       |
| 26      | DEVSEL    |
| 27      | IOSEL     |
| 28      | IOSTB     |

