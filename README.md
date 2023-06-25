# CNC Plotter Machine

Using Arduino Uno and a few resources, we have designed a CNC Plotter Machine that has the ability to draw with a pen via G-Code. This machine can draw with dimensions of 4 * 4 cm, and you can design a drawing machine with larger dimensions than these by enlarging the size of the x axis and y axis according to your requirements.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Components](#components)
- [Usage](#usage)
- [Configuration](#configuration)

## Features

- **Versatile Drawing Capability**: The CNC plotter machine can draw various patterns, shapes, and text based on the provided input.
- **Precise Movement Control**: The machine uses stepper motors to precisely control the positioning of the pen, ensuring accurate drawing.
- **Easy Control Interface**: The Arduino Uno serves as the control unit, allowing you to send commands to the plotter machine.
- **Customizable Pen Holder**: The plotter machine includes a pen holder that can be adjusted to accommodate different pen sizes and types.
- **Compact and Portable**: The use of an Arduino Uno and a CD-ROM drive makes the CNC plotter machine compact and portable.

## Getting Started

To get started with the CNC plotter machine, follow these steps:

Assemble the hardware components according to the provided schematic diagram.
    Connect the stepper motors to the motor driver, and then connect the motor driver to the Arduino Uno.
    Connect the CD-ROM drive to the Arduino Uno.
    Install the required libraries and upload the Arduino sketch to the Arduino Uno.
    Adjust the pen holder to securely hold the pen or marker.
    Place a sheet of paper or a drawing surface on the flat surface where you want the plotter to draw.
    Power on the Arduino Uno and initiate communication with the plotter machine.

![Circuit Diagram](circuit.jpg)

6. Put your finger on the sensor, wait some seconds then the measurments will appear in the LCD screen.

## Components

- 1 * Arduino Uno
- 1 * Motor Driver L293D Shield
- 2 * CD-ROMs

## Usage

Once the Heart Rate and SpO2 Measurements application is up and running, users can take advantage of the following functionalities:

Once the CNC plotter machine is set up and connected, you can use various methods to control its movements and create drawings:

- **Direct Commands**: You can send direct commands to the Arduino Uno via a serial terminal or a custom software interface to control the plotter machine's movements.
- **G-Code**: Generate G-code instructions using software such as Inkscape or CAD programs, and then send the G-code commands to the plotter machine for precise drawing.
- **Predefined Patterns**: Utilize preconfigured patterns or designs by storing them in the Arduino's memory or by creating specific functions in the Arduino sketch.

## Configuration

The Heart Rate and SpO2 Measurements Project provides configuration options for users to personalize their experience. These options may include:

- **Threshold Customization**: Adjust the heart rate and SpO2 thresholds according to individual preferences or medical recommendations.
- **Measurement Interval**: Set the frequency of heart rate and SpO2 measurements, determining how often the application records readings.
- **Sensor Calibration**: Calibrate the heart rate and SpO2 sensor for accurate measurements based on personal factors or environmental conditions.