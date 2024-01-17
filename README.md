# LED Controller App

## Overview
An LED Light control App that uses a Microcontroller, Python, and various peripherals.
View in: https://www.youtube.com/watch?v=IP5TtW9Qeco

## Project Description
The goal of the project is to create an LED Controller App that can adjust LED brightness/intensity using push buttons and display relevant data on a computer using Python. The project involves the use of Microcontroller peripherals such as UART and Timer, along with efficient coding practices.

## Project Features
### LED Control Modes:

- Pressing PB1 toggles the system between ON and OFF modes.
- In ON mode, the LED operates at 95-100% intensity, adjustable with a Potentiometer using PWM.
- In OFF mode, the LED turns off, and the system enters low power Idle() mode.

### Blinking LED:

- Pressing PB2 makes the LED blink at 100% intensity with a 500ms interval.
- Pressing PB2 again stops the LED blinking.

### Python Script:

- Captures and stores intensity levels and average PWM voltage output over 1 minute.
- Generates CSV/Excel file with proper indexing and column names.
- Plots intensity levels and average voltage output vs. time on separate graphs.

### Graphical Display:

- Two graphs displaying intensity levels or PWM voltage (Vpwm) against time.
- Graph titles, X and Y axis labels, and pulse frequency information.

## Project Implementation
### Hardware Kit:

- Use of Microcontroller peripherals: UART, Timer, and IO (CN) interrupts.
- Efficient power usage through clock switching and sleep/idle modes.

### Code Organization:

- Implement in ANSI C with IO(CN) and Timer interrupts.
- Detailed comments, proper variable names, and adherence to efficient coding practices.

### Pulse Width Modulation (PWM):

- Generate PWM signals on Pin 12, controlling LED brightness with Potentiometer input.

### State Diagram:

- Utilizing microcontroller-specific registers, bit names, and flags.

