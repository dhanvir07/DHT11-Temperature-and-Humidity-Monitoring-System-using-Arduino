# DHT11 Temperature and Humidity Monitor

## Overview
This project reads **temperature** and **humidity** using a DHT11 sensor connected to an Arduino and displays the readings on the Serial Monitor every 2 seconds.

## Features
- Real-time temperature monitoring (°C)
- Real-time humidity monitoring (%)
- Sensor error detection
- Beginner-friendly Arduino project

## Components Required
- Arduino Uno/Nano
- DHT11 Sensor Module
- Breadboard
- Jumper Wires
- USB Cable

## Connections

| DHT11 | Arduino |
|-------|---------|
| VCC | 5V |
| DATA | D2 |
| GND | GND |

> If using a bare DHT11 sensor, connect a 10kΩ pull-up resistor between VCC and DATA.

## Libraries
- DHT Sensor Library
- Adafruit Unified Sensor Library

## How to Run
1. Install the required libraries.
2. Open `DHT11_Temperature_Humidity.ino` in Arduino IDE.
3. Select the correct board and COM port.
4. Upload the code.
5. Open the Serial Monitor at **9600 baud**.

## Expected Output
Temperature: 28.5 °C    Humidity: 62.0 %

## Folder Structure

```
DHT11-Temperature-Humidity-Monitor/
│── DHT11_Temperature_Humidity.ino
│── README.md
│── results/
│   ├── serial_monitor_output.png
│   └── hardware_setup.jpg
```

## License
MIT License
