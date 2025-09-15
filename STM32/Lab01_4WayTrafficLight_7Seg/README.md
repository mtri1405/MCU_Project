# Lab 01 – Ex05 Traffic Light Project - 7 Segment LED

This project implements a **simple traffic light system** using **STM32** microcontroller and **HAL library**.  
It controls two traffic lights (LED sets) with a 7-segment display showing the countdown timer for each state.

---

## 📌 Features

- **Traffic Light Cycle:**  
  - 🔴 **RED:** 5 seconds  
  - 🟢 **GREEN:** 3 seconds  
  - 🟡 **YELLOW:** 2 seconds  
- **7-Segment Countdown:** Displays remaining seconds for the active light.
- **Dual Traffic Lights:** Two sets of LEDs working **out of phase** (when one is red, the other is green/yellow).
- **Accurate Timing:** Using `HAL_Delay(1000)` for 1-second increments.