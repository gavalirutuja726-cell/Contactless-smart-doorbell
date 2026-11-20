# Contactless Smart Door Bell System

## Project Overview
The Contactless Smart Door Bell System is designed using NodeMCU ESP8266 and an HC-SR04 ultrasonic sensor. It detects a person approaching the door and automatically activates a buzzer without requiring physical contact.

## Objectives
- To develop a contactless doorbell system.
- To detect visitors using an ultrasonic sensor.
- To activate a buzzer automatically.
- To prevent repeated buzzer activation.

## Hardware Components
- NodeMCU ESP8266
- HC-SR04 Ultrasonic Sensor
- Buzzer
- Connecting Wires
- USB Cable

## Software Requirements
- Arduino IDE
- ESP8266 Board Package

## Pin Connections

| Component | NodeMCU Pin |
|---|---|
| Sensor TRIG | D6 |
| Sensor ECHO | D5 |
| Buzzer Signal | D2 |

## Working Principle
1. The ultrasonic sensor continuously measures distance.
2. When a person comes within 50 cm, the buzzer beeps for 500 milliseconds.
3. The buzzer does not beep again while the person stays nearby.
4. When the person moves beyond 60 cm for 1 second, the system resets.

## Project Files
- Circuit Diagram and Components
- System Architecture
- Arduino Code
- Project Report
- Hardware Implementation Images

## Applications
- Homes
- Offices
- Hospitals
- Contactless entry systems

## Conclusion
This project provides a simple and low-cost contactless doorbell solution using an ultrasonic sensor and NodeMCU ESP8266.

## Developed By
Electronics and Telecommunication Engineering Students
