# Safe Untouched Doorbell using Bolt IoT

## Project Overview
The Safe Untouched Doorbell is an IoT-based touch-free doorbell system designed to reduce physical contact and improve safety, especially in situations where hygiene is a concern. The system triggers a doorbell when a visitor places their hand near a light-dependent resistor (LDR) or flashes a light onto it, eliminating the need for physical touch.

In addition to ringing the buzzer, the system can send a text notification to the homeowner if they are not present, ensuring awareness of visitors at the door.

---

## Objectives
- Design a contactless doorbell system
- Reduce the spread of germs by avoiding physical touch
- Notify homeowners remotely when a visitor arrives
- Leverage a simple and scalable IoT platform

---

## System Architecture
The project uses the **Bolt IoT platform** as the central interface, combining:
- Bolt WiFi Module
- Cloud-based configuration and control
- SMS notifications via a third-party messaging service

---

## Hardware Components
- Bolt WiFi Module  
- LDR (5MΩ)  
- 10kΩ Resistor  
- Buzzer  
- Breadboard  
- Jumper Wires (Male/Female)  
- USB-A to Mini-USB cable  

---

## Software & Tools
- Bolt IoT Cloud
- Bolt IoT Mobile Application
- Messaging application for SMS alerts
- Twilio (for SMS notifications)

---

## Working Principle
- The LDR detects a change in light intensity when a hand is placed near it or when light is flashed.
- The Bolt WiFi Module reads the sensor values via the A0 pin.
- When the threshold is crossed, the buzzer is triggered.
- If enabled, an SMS alert is sent to the homeowner using Twilio.

---

## Applications
- Touch-free doorbell systems
- Smart home safety solutions
- Hygiene-focused IoT devices
- Contactless visitor alert systems

---

## Cost of Manufacture
- Bolt IoT Starter Kit: ₹3500/-

---

## Conclusion
This project demonstrates a simple yet effective IoT solution for contactless interaction using minimal hardware and cloud-based services. It highlights the integration of sensors, cloud platforms, and messaging services to build a practical real-world application.
