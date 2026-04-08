<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

Low-Power SAR-ADC for PPG Signal Acquisition

This repository includes the design files and simulation results of a 10-bit SAR ADC implemented in 180 nm CMOS technology, optimized for low-power biomedical applications such as photoplethysmogram (PPG) signal acquisition.

Project Overview

The primary objective of this project is to develop an efficient and accurate ADC tailored for low-power wearable devices. The design adopts a 10-bit monotonic SAR ADC architecture with a time-domain comparator to achieve power consumption in the microwatt range.

Architecture Details

The design employs a monotonic switching SAR ADC architecture, recognized for its high power efficiency and reduced capacitor array size.

The primary innovation is the time-domain comparator, implemented using a voltage-controlled delay line (VCDL), which significantly lowers power consumption compared to conventional dynamic comparators.

Key components:

1. Track-and-Hold (T/H) Switch: A bootstrapped switch used for accurate input signal sampling.

2. Capacitive DAC (CDAC): Generates the reference levels for comparison.

3. Time-Domain Comparator: A low-power comparator based on the VCDL approach.

4. SAR Logic: Governs the successive approximation process.

