---
layout: project
order_number: 30
title: EcoSense
event: HackDavis 2018
place-time: UC Davis - 2018

language:
    - Python

software:
    - Weather Underground API
    - Json

hardware:
    - Raspberry Pi 3 Model B

preview: >
    EcoSense is a smart device designed to efficiently water your lawn. The device uses both color detection and weather
    forecast to gather data on current lawn condition, time, temperature, and potential rainfall. These variables are
    then used to determine if watering can left to rainfall or if sprinklers are required.
---

### About

EcoSense is a smart device designed to efficiently water your lawn. The project was developed for the UC Davis annual
Hackathon, HackDavis 2018 under the environment category. The intent of the design is to tackle an aspect of California’s
reoccurring drought issue by providing homeowners a water saving, hands-off approach to lawn care.  

Comparing existing irrigation technology, most homes use a system consisting of a controller and a timer that will
regularly water lawns regardless of temperature or weather forecast. The purpose of EcoSense is to prevent that scenario
and take advantage of these natural events to efficiently maintain your lawn. 

Describing the project, EcoSense is a Raspberry Pi with connections to a camera and an external watering mechanism. The
device works by capturing an image of the lawn and taking the average color to determine the state (e.g., green (healthy),
yellow (unhealthy), etc.). This information is combined with local weather forecast found using ZIP code inputted into
Weather Underground’s API to decide if the watering mechanism must be activated.

Because of the nature of Hackathons, the time to conceptualize, plan, and develop was extremely short. Thus, the project
serves more as a proof of concept with the main substance being the rudimentary algorithm that controls watering.
Likewise, the camera and watering mechanism were substituted with stock photos and pseudo signals to test the device as
if all components were present.


### Features

- Algorithm that uses average lawn color and weather forecast to determine watering needs
- Inputtable ZIP code to obtain local weather forecast


### View Project
[Github Link](https://github.com/AHueya/EcoSense)

<!--more-->

