---
layout: project
order_number: 20
title: CSUS Commuter App
event: Computer Software Engineering
place-time: CSU, Sacramento - Fall 2020

language:
    - HTML
    - CSS
    - JavaScript

software:
    - Draw.io
    - Agile SDLC model

#hardware:

preview: >
    The CSUS Commuter App is a web-based application that is intended to help Sacramento
    State commuters and visitors determine the best means of transportation when
    considering money, time, and Sustainability. The application uses a survey to collect
    users' travel preferences and data which are then processed to provide them with a
    list of recommended transportation methods in accordance with their needs and values.
---

### About

The CSUS Commuter App is a project created in my Computer Software Engineering class for
the University Transportation and Parking Services (UTAPS). The intent of this project
was to create a prototype application that would assist Sacramento State commuters and
visitors determine the best means of transportation when considering money, time, and
sustainability. Moreover, this assignment was heavily focused on utilizing the Agile SDLC
Model so regular feedback from UTAPS played a critical role in development.

Regarding the overall functionality of the application, it can be divided into two parts:
the user survey and the algorithm used to determine the users’ most suitable transportation
method. The survey begins with a pre-survey that will ask users to rank the importance of
sustainability, time, and money. This ranking will be used by the “point-based” algorithm to
establish the weight of the users’ upcoming answers. As for the survey itself, users will be
asked on their preferred method of transportation along with any associated information such
as the make, model, and year if car was selected. The results would then be displayed to show
the cost, sustainability in CO2, and time along with potential alternatives.


#### My Contribution

The project was completed in collaboration with three other individuals. Considering that I had
the most experience with developing websites, I opted to focus more on the algorithm, data storage,
and assisting my team with debugging. Expanding on the algorithm, it’s essentially a two-dimensional
array with preassigned values that correspond with the survey questions. Considering the nature of the
assignment and time constraints the data storage temporary local storage provided by the browser to
transfer data between pages. We found this to be acceptable for our proof-of-concept prototype since
it provides flexibility for integrating our application into UTAPS existing backend.


### Features

- Survey to collect users' transportation preferences and related information
- Point-based algorithm that uses users' ranked choice to calculate possible transportation options
- Colors and styling that conform to CSUS current design scheme and branding


### View Project
[GitHub Link](https://github.com/AHueya/CSUS-Commuter-App)

<!--more-->

## Images

<figure>
    <img src="..\assets\images\projects\CSUS_Commuter_App\01.jpg" alt="System Context Diagram">
    <figcaption>System Context Diagram</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\CSUS_Commuter_App\02.jpg" alt="Use Case Model">
    <figcaption>Use Case Model</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\CSUS_Commuter_App\03.jpg" alt="Homepage">
    <figcaption>Homepage</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\CSUS_Commuter_App\04.jpg" alt="Pre-survey pop-up">
    <figcaption>Pre-survey pop-up</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\CSUS_Commuter_App\05.jpg" alt="Survey page">
    <figcaption>Survey page</figcaption>
</figure>

<figure>
    <img src="..\assets\images\projects\CSUS_Commuter_App\06.jpg" alt="Results page">
    <figcaption>Results page</figcaption>
</figure>
