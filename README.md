DIY SmartHome System
 
This project is a DIY Smart Home system built from scratch using embedded hardware and custom software. The goal is to create a flexible and low-cost smart home platform that users can build, customize, and extend by themselves.
 
The system consists of a central master device, multiple smart nodes, and a mobile application. The master device is based on STM32 + Ethernet (W5500/ENC28J60) and communicates with devices through MQTT for real-time messaging and HTTP APIs for configuration and control.
 
A Raspberry Pi server is used as the MQTT broker and remote access gateway, allowing the system to work both in local LAN mode and remote internet mode.
 
The mobile application is developed with Flutter, providing a modern UI for controlling devices, creating schedules, managing rooms and homes, and monitoring device status in real time.
 
Main features include:
 
- Real-time device control via MQTT
- Local LAN discovery for faster connection
- Remote control through domain and port forwarding
- Device scheduling and automation
- Scene and room management
- OTA firmware update support
- Custom smart home hardware design
 
The long-term vision of this project is to build a fully open DIY smart home ecosystem, including mobile apps, firmware, hardware schematics, and documentation so that anyone can build their own smart home system.
