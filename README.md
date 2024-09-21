# Surveillance-bot-using-ESP32-cam


## Overview
The **Surveillance Bot** is a remote-controlled car equipped with a camera that allows users to monitor areas that are inaccessible or unsafe for humans. The bot captures real-time footage, which can be monitored through a mobile device and recorded for later analysis. This bot is ideal for surveillance in dangerous or hard-to-reach locations.

## Features
- **Remote Surveillance**: Navigate and control the bot remotely in real-time using a mobile device.
- **Live Video Feed**: The bot's camera streams live video footage to a mobile application or web interface.
- **Recording Capability**: Footages captured by the camera can be recorded for future reference.
- **Inaccessible Area Monitoring**: Useful for surveillance in hazardous areas where human presence is not possible.

## Technologies and Components Used
- **Programming Language**: C++
- **Computer Vision**: To enable camera streaming and recording.
- **Microcontroller**: ESP32 CAM module for wireless communication and video streaming.
- **Motors**: For controlling the movement of the bot.
- **Motor Driver**: L298D motor driver to control the motors.
- **3D Printed Case**: A custom-made, 3D-printed case that houses the components and provides structural support.

## Components List
- **ESP32 CAM Module**: For capturing video and sending it wirelessly to a mobile device.
- **Motors**: For moving the bot forward, backward, and making turns.
- **L298D Motor Driver**: To control the motors for smooth operation.
- **3D Printed Case**: Protects the internal components and gives a compact structure to the bot.
- **Power Supply**: To power the ESP32 CAM and the motors.

## System Architecture
The surveillance bot combines the movement of a remote-controlled car with the real-time video capture and transmission capability of the ESP32 CAM module. The motor driver (L298D) controls the bot's movement, while the ESP32 CAM streams the live feed, which can be accessed via a mobile device. 

### Web Interface
- You can control the car and view the live camera feed using a web interface hosted on the ESP32 CAM module.
- **Access the Bot**: Open your browser and navigate to **[http://192.168.187.3](http://192.168.187.3)** to control the bot and view the camera feed.
  
## How to Use
1. **Set Up Hardware**: Assemble the components as per the circuit design (link to circuit diagram).
2. **Upload Code**: Flash the ESP32 CAM module and motor driver with the provided code using Arduino IDE.
3. **Control the Bot**: Use the web interface at [http://192.168.187.3](http://192.168.187.3) to control the bot’s movement and view live footage.
4. **Monitor and Record**: Monitor the live video feed via the web interface and record the footage as needed.

## Conclusion
The **Surveillance Bot** provides a robust solution for monitoring dangerous or inaccessible areas with real-time footage. The bot's portability and ability to record video make it an effective tool for security and surveillance operations.
