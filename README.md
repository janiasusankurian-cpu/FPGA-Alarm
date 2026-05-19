# FPGA-Alarm
This project implements a 24-hour digital alarm clock in Verilog HDL on a Cyclone V E FPGA. It uses a 50 MHz oscillator divided to 1 Hz for precise timing. Features include push-button settings, active-low 7-segment displays, and a buzzer/LED alarm. Designed and verified via Intel Quartus Prime Lite and ModelSim-Altera
# FPGA Alarm Clock

## Overview
This project implements a 24-hour digital alarm clock using Verilog HDL on Cyclone V FPGA. The system displays time using 7-segment displays and includes alarm functionality with buzzer and LED indication.

## Features
- 24-hour digital clock
- Alarm setting functionality
- Push button controls
- Active-low 7-segment display
- LED/Buzzer alarm indication
- 50 MHz clock divided to 1 Hz timing signal

## Hardware Used
- Cyclone V FPGA Board
- 50 MHz onboard oscillator
- Push buttons
- 7-segment display
- LEDs/Buzzer

## Software Used
- Intel Quartus Prime Lite
- ModelSim-Altera
- Verilog HDL

## Working
The FPGA receives a 50 MHz clock signal and divides it into a 1 Hz signal for accurate timing. Users can set time and alarm using push buttons. When the current time matches the alarm time, the buzzer/LED activates.

## Project Structure
- `alarm_clock.v` → Main Verilog module
- `clock_divider.v` → Clock division logic
- `testbench.v` → Simulation file

## Results
The project was successfully synthesized and verified in Quartus Prime Lite and simulated using ModelSim-Altera.

## Author
**Jania Susan**  
B.Tech ECE | VIT Chennai
