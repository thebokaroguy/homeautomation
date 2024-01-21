# homeautomation
We used Arduino Uno with ESP8266 for the Wi-Fi Functionality, 5V relays connected to UNO for the seamless switching and we added functionality to control Lights, Fans, Motors and their speed control through wirelessly by an app that we created with the help of our team and google firebase as an API.
# Smart Home Control System

## Overview

This project involves building a smart home control system using Arduino Uno, ESP8266, and Firebase. The system allows wireless control of lights, fans, and motors along with speed control for fans. The real-time status is displayed on a 16x2 LCD screen.

## Hardware Requirements

- Arduino Uno
- ESP8266 Module
- 5V Relays (for lights, fans, and motors)
- Fan speed control module
- 16x2 LCD Display
- Jumper wires
- Power supply

## Software Requirements

- Arduino IDE
- Firebase account

## Wiring

Connect the hardware components according to your specific setup. Here is a basic guide:

- Connect relayLightPin, relayFanPin, relayMotorPin to the corresponding relay modules.
- Connect fanSpeedPin to the fan speed control module.
- Connect the LCD display using I2C.
- Connect ESP8266 for Wi-Fi functionality.
- Power up the system.

## Firebase Setup

1. Create a Firebase account if you don't have one.
2. Create a new project.
3. Get the Firebase project URL and authentication token.

## Arduino Code

1. Install necessary libraries (Wire, LiquidCrystal_I2C, ESP8266WiFi, FirebaseArduino) in Arduino IDE.
2. Open the Arduino sketch and replace "your-ssid", "your-password", "your-firebase-host", and "your-firebase-auth-token" with your actual values.
3. Adjust pin assignments based on your hardware connections.

## Usage

1. Upload the Arduino code to your Arduino Uno.
2. Power up the system.
3. Open the Firebase console and update the values of "lightStatus", "fanStatus", "motorStatus", and "fanSpeed" to control the devices.
4. The LCD display will show the real-time status.

## Notes

- Ensure a stable Wi-Fi connection for reliable control.
- Always double-check the wiring before powering up the system.
- Adjust the delay in the loop function for real-time status updates based on your preferences.

Enjoy your smart home control system!
