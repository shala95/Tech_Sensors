# Tech_Sensors
Project Title: Development of a Plant Assist System

Table of Contents

Introduction
Team Members
Project Structure
Setup and Installation
Hardware Details
Software Details
Automatized Lighting
3-D Structure
Future Perspectives
Contributions
Acknowledgments
Introduction

This project involves the development of a plant assist system that uses sensors to monitor and control the environmental conditions of an indoor plant. The system aims to maintain optimal light and moisture levels to ensure healthy plant growth.

Team Members

Marta Albini
Fabiola Dassi
Chiara Gentile
Giulia Giorgiani
Valeria Marini
Mohamed Khaled Shala
Project Structure

final ppt 0606 (1).pptx: Presentation detailing the project summary, hardware, software, automatized lighting, 3-D structure, and future perspectives.
Setup and Installation

Clone the repository:
sh
Copy code
git clone <repository_url>
cd <repository_directory>
Follow the hardware and software setup instructions detailed in the project documentation.
Hardware Details

The hardware components used in this project include:

LDR sensor to measure light levels
Moisture sensor to measure soil humidity
Artificial LED lighting for controlled light exposure
Conditioning circuit for the LDR sensor
Small indoor plant (Red Lettuce)
MCP6002 operational amplifier
Capacitive moisture sensor
Software Details

The software components include firmware developed for Arduino to handle:

Sampling of sensor signals
Data comparison with predefined thresholds
Activation of actuators based on sensor data
LED indicators for soil moisture status
Control of LED strips for light management
Automatized Lighting

The system uses a MOSFET module to control LED strips based on signals from the Arduino, ensuring that the plant receives the necessary amount of light for optimal growth.

3-D Structure

A 3-D structure was designed to house the sensors, LED strips, and the plant, ensuring proper placement and functionality of all components.

Future Perspectives

Future enhancements to the system include:

Connecting lights to the electrical main for longer operation times
Adding a water pump for automated irrigation based on soil moisture levels
Contributions

Marta Albini: Hardware design and implementation
Fabiola Dassi: Sensor integration and conditioning circuits
Mohamed Khaled Shala: Software development and Arduino programming
Giulia Giorgiani: Data analysis and system testing
Valeria Marini: User interface design and real-time data display
Chiara Gentile: Project coordination and report preparation

Acknowledgments

We acknowledge the guidance and support provided by our course instructors for the Technologies for Sensors and Clinical Instrumentation course at Politecnico di Milano.
