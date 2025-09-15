# Lab 01 – Ex04: 7 Segment LED (STM32)

This project demonstrates how to control a single 7-segment LED display using an STM32 microcontroller with HAL libraries.

# Overview

Uses GPIO pins on GPIOA to control each segment (a–g).

Displays numbers 0–9 using a lookup table for segment patterns.

Compatible with common anode or common cathode (adjust seg_pattern values if needed).

# Hardware Setup

7-Segment Display: Connect each segment (a–g) to STM32 GPIOA pins.

Resistors: Use current-limiting resistors (~220Ω) for each segment to prevent overcurrent.

Common Pin:

Connect COM to VCC (for common cathode) or GND (for common anode) accordingly.
