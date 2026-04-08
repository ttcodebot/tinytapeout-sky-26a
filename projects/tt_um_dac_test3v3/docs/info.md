<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
It is a 8 bit R2R ladder DAC, which digital signals to analog for GPR Application. The digital signal from the processor is converted and then given to the antenna. 

## How to test
DAC Test Setup
The DAC can be tested using two different modes: External Data Mode and Internal Sawtooth Wave Generator Mode.
1. External Data Mode
In this mode, the DAC receives digital inputs from an external source.
Steps:
Set External Data Input = HIGH to enable external data mode.
Apply digital values to the 8 input pins of the DAC.
Observe the corresponding analog output produced by the DAC.

## External hardware

A FPGA board to drive the 8-bit digital inputs.
