# Intelligent Home: Gesture-Controlled Automation

A final-year capstone project from 2016 at Ming Chuan University that controls home appliances using hand gestures, built with a Leap Motion controller, C#, and Arduino.

> This project is archived and kept for reference. It is no longer maintained.

## About

An early project exploring IoT and human-computer interaction. A Leap Motion controller tracks hand gestures, a C# application interprets them and sends commands over Bluetooth to an Arduino, and the Arduino switches appliances such as lights and fans through relay modules.

## How It Works

1. **Gesture tracking** – the Leap Motion controller captures hand movements.
2. **Gesture processing** – a C# application recognises the gesture and maps it to a command.
3. **Wireless control** – the command is sent to the Arduino over Bluetooth.
4. **Appliance switching** – the Arduino triggers relay modules to turn appliances on or off.

## Features

- Appliance control with hand gestures
- Gesture recognition using a Leap Motion controller
- Wireless control over Bluetooth
- Real-time switching of lights and fans
- Low-cost hardware prototype

## Built With

- **Leap Motion** – hand and gesture tracking
- **C#** – gesture recognition and command logic
- **Arduino** – receiving commands and controlling relays
- **Bluetooth module** – wireless communication between PC and Arduino
- **Relay modules** – switching AC appliances

## What I Learned

- Integrating hardware and software
- Processing sensor data in real time
- Wireless communication between devices
- Working safely with AC-powered appliances

## Disclaimer

This is an educational prototype and isn't intended for production use. Follow proper electrical safety guidelines when working with mains-powered components.
