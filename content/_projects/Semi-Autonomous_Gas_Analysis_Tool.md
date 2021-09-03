---
layout: project
order_number: 10
title: Semi-Autonomous Gas Analysis Tool
event: Computer Engineering Senior Design Project
place-time: CSU Sacramento - 2020

language:
    - Python
    - HTML
    - CSS
    - JavaScript
    - C++

software:
    - Jquery
    - Ajax
    - Flask-SocketIO

hardware:
    - Raspberry Pi 3 Model B
    - Arduino Uno
    - SIM868 GPS Module
    - OV5647 Camera
    - ME2-O2 Oxygen
    - MQ2 Hydrocarbon/Carbon Monoxide
    - MQ135 Carbon Dioxide
    - DHT22 Humidity/Temperature

preview: >
    The Semi-Autonomous Gas Analysis Tool is a remotely operated rover designed to detect hazardous concentrations
    of gas. Equipped with a multitude of sensors, the device provides users near real-time data of particulate matter
    to effectively locate leaks in a commercial or industrial setting.
---

### About

The Semi-Autonomous Gas Analysis Tool is a senior design project created to solve a small aspect of climate change.
The scope of this project focused on mitigating the impact of gas leaks in a commercial or industrial setting by
creating a device that can quickly locate the source of the leak. The idea was then expanded to include the capability
to detect other potentially harmful gases that may result asphyxiation or poisoning.

In terms of the device itself, the working prototype consists of a WiFi remote-control rover that is equipped with a
camera and a multitude of sensors that will regularly measure the surrounding temperature, humidity, and particulate matter.
These devices along with other hardware such as motors are connected to a Raspberry Pi 3 which acts as the central unit
tying everything together. Additionally, the Raspberry Pi was essential for computing and parsing data which was then
stored in a CSV file and transmitted to the user in near real-time via Web UI.


#### My Contribution

Due to the nature of the Senior Design Course the project was completed in collaboration with three other individuals. My role
in this project was geared more towards software where I spent most of my time developing the underlying system. For
instance, a critical part that I developed was the Flask-SocketIO server that served as the foundation for the remote feature
of the rover. This goes hand in hand with another feature that I developed which was the Web UI that's responsible for providing
visual feedback through the camera and a near real-time stream of sensor data. This was accomplished with the use of Ajax so that
the sensor values could be updated without having to refresh the entire page.


### Features

- WiFi controlled rover with forward/reverse movement and neutral steering
- Sensors for measuring humidity, temperature, oxygen, hydrocarbons, carbon monoxide, and carbon dioxide
- Camera with adjustable tilt, resolution, and frame rate
- Web UI with camera stream and asynchronous refresh for near real-time sensor data
- Sensor data and GPS location written to CSV file for future reference


### View Project
[GitHub Link](https://github.com/AHueya/Semi-Autonomous-Gas-Analysis-Tool)

<!--more-->

## Images

<figure>
    <img src="..\assets\images\projects\Semi-Autonomous_Gas_Analysis_Tool\01.jpg" alt="Working prototype">
    <figcaption>Working Prototype</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\Semi-Autonomous_Gas_Analysis_Tool\02.jpg" alt="Web UI">
    <figcaption>Web UI</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\Semi-Autonomous_Gas_Analysis_Tool\03.jpg" alt="Implementation diagram">
    <figcaption>Implementation diagram</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\Semi-Autonomous_Gas_Analysis_Tool\04.jpg" alt="Hardware diagram">
    <figcaption>Hardware diagram</figcaption>
</figure>