#  Automatic Plant Watering System - PCB Project

This is a simple PCB project for an automatic plant watering system using an Arduino Nano.
It monitors temperature and humidity, tracks time with a real-time clock (RTC), and controls a water pump via a relay.
The system includes an LCD for displaying data and a push button for manual pump activation.

## Overview
This project is a custom PCB for an automated plant watering system. It integrates an RTC module, temperature/humidity sensor, relay for pump control, and an LCD for displaying status.

While this version does not include soil moisture sensing, it can be manually activated using a button and is fully extendable for automatic operation in the future.

##  Components

- Arduino Nano
- DHT11 sensor (temperature and humidity)
- DS1302 Real Time Clock (RTC) module
- HL-525 Relay module (controls water pump)
- 16x2 LCD display with I2C
- Push button (manual pump activation)
- LED indicator (pump status)
- Resistors: 10kΩ (pull-up), 330Ω (LED current limiting)
- 2-pin screw terminal (pump connector)
- 3-pin headers (for DHT11, RTC, and other I/O connections)

##  Schematic & PCB

[KiCAD 8](https://www.kicad.org/)


### Sensors & Modules

- DS18B20 Temperature Sensor (digital, 3-pin)
- HL-52S Relay Module
- DS1302 Real Time Clock (RTC) module

## 📁 Project Structure

- `KiCAD/`: All KiCAD schematic and layout files
- `Images/`: 3D renders and screenshots of the board


## Author

Anđela Pantelić, Electronics student 2025.
