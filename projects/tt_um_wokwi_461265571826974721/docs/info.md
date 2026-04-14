<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Uses d flip-flops to enter a dedupe state, filters bit stream (inverts duplication) and signals the events.  

## How to test

Receive OUT0 (RX) and average the number of bits received. The average for 0 and 1 should approach, approximately, 50% over time. 

## External hardware

A clock source and a random number generator transmitting a bit stream over a pinout (GPIO).

