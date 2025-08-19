# MK1-Lab-
Hardware project in Altium with an STM32H7x uProcessor for educational purposem, to implement a general purpose platform for digital signal processing.
This project will use the STM32H7x with a BGA footprint, for educational routing, there is use of an audio codec for external ADC and DAC, but with its onboard ADC and DAC broken out.
A singular SMPS is to be implemented, following a chip specific design.
An FTDI USB-JTAG IC is used with onboard EEPROM for an onboard debugger for the STM32H7x.
A flash memory IC is also used with interface of QSPI to uProcessor.
The routing of the BGA is done via a dogbone fanout, and some experimental designs is applied to the PCB for educational and getting familiar with alitum designer.
