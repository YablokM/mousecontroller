# Mouse Controller for Xbox Controller

This Python application allows you to control your mouse and scroll using an Xbox controller. It maps controller buttons to mouse actions, including left, right, and middle clicks, as well as scroll controls. The program also includes sensitivity and dead zone adjustments for smooth and customizable control.

## Features:
- **Mouse Movement**: Controlled using the left joystick.
- **Scroll**: Controlled using the right joystick.
- **Left Click**: Mapped to the LB button.
- **Right Click**: Mapped to the RB button.
- **Middle Click**: Mapped to the right joystick press (click).
- **Adjustable Sensitivity**: Customize mouse and scroll sensitivity.
- **Adjustable Dead Zone**: Control the size of the dead zone to prevent joystick drift.

## Requirements:
- Python 3.x
- Dependencies:
  - `pygame`
  - `pynput`
  - `tkinter`

## Installation:

### 1. Install Python Dependencies
Install the necessary Python libraries by running the following command:

```bash
pip install pygame pynput
