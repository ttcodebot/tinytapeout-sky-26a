<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

clk pin = 1Mhz - 20Mhz clock
rst_pin = connect basic button or switch.
ui_in[0] = switch 3 measure for big capacitor 
ui_in[1] = switch 2 measure for medium capacitor
ui_in[2] = switch 1 measure for small capacitor

ui_in[3] = pulse delay control pin for small signal 1um
ui_in[4] = pulse delay control pin for small signal 3um
ui_in[5] = pulse delay control pin for small signal 4.3um
ui_in[6] = pulse delay control pin for small signal 6um

uio_in[0] = current source control pin for small current L= 2um 
uio_in[1] = current source control pin for small current L= 3um 
uio_in[2] = current source control pin for small current L= 6.5um 
uio_in[3] = current source control pin for small current L= 10um 
uio_in[4] = current source control pin for small current L= 13.5um 

uo_out[0:7] = counter results for 8-bit 

ua[0] connect to Capacitor
ua[1] connect to voltage source. because this pin is comparator input




## How to test

You can assign a logical 1 or 0 to the inputs and outputs given above and observe the resulting outcomes.

## External hardware

Button
Voltage source
Microcontroller

