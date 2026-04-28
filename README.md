# STM32 Reaction Timer Game

Interactive embedded game built on STM32 using timer interrupts, external interrupts, GPIO, and UART communication.

## Author: Vaishnavi Ravindra Shanbhag

## Overview

This project measures a user's reaction time. After a short delay, the onboard LED turns on as the "GO!" signal. The user presses the onboard button as quickly as possible, and the reaction time is calculated and printed over UART.

## Features

- TIM2 periodic interrupt for reaction time measurement
- External interrupt (EXTI) for button press detection
- LED signal output using GPIO
- UART score reporting at 115200 baud
- Real-time game state control in Embedded C

## Hardware

- STM32 Nucleo-F401RE

## Tools & Technologies

- STM32CubeIDE
- STM32CubeMX
- STM32 HAL
- Embedded C
- Serial Monitor / UART Terminal

## How It Works

1. System prints `Reaction Timer Game Ready`
2. Displays `Get Ready...`
3. Waits briefly
4. LED turns ON
5. User presses blue button
6. Reaction time is printed over UART
7. Game resets and repeats

## Example Output

```text
Reaction Timer Game Ready
Get Ready...
GO!
Reaction Time: 243 ms
```
## Embedded Concepts Demonstrated
- Interrupt-driven programming
- Timer configuration and callbacks
- GPIO input/output
- UART communication
- Real-time event handling
- State machine logic
- Firmware validation on hardware
- 
