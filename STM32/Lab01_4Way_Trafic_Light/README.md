# Lab 01 – Ex03: Four-Way Traffic Light (STM32)

This project demonstrates a four-way traffic light control system using an STM32 microcontroller and the HAL library.

Description

The system controls traffic lights for four directions in a cyclic sequence.

Each traffic light follows a standard cycle:

RED: 5 seconds

YELLOW: 2 seconds

GREEN: 3 seconds

The GREEN LED is driven by its negative pin (active low).

# Implementation

Implemented using STM32 HAL GPIO functions.

Uses HAL_GPIO_WritePin() to switch LEDs ON/OFF based on timing.

Delay functions (HAL_Delay()) are used to maintain timing for each state.