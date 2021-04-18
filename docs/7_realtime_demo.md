---
title: Realtime Demo
nav_order: 7
---

## Realtime Demo
<br>
<div align="center">
  <video width="600" controls>
    <source src="videos/outdoor-demo-fix1.mp4" type="video/mp4">
  </video>
</div>
<br>

<p align="center">
  <img src="images/Results+RealTime.png" width="700">
  <br>   
  <b>Result of the Realtime Demo</b>    
</p>
<br><br><br />

## How does Cycle buddy work in Realtime Demo?
<br><br>
1. Ultrasonic Sensor: The latter aims at capturing the distance from the car relative to to the bike. Moreover, it will extract the speed at which the car was coming at with cm/s as units.<br>

2. Hall Effect Sensor: This sensor will enable the system to know when the bike is rotating, giving us its velocity with cm/s as units. This is needed to understand if the car is parked or not. We would not want to blame a driverless car.<br>

3. Pi Camera: Once the camera is triggered, it will be situated strategically to ensure it captures the driver's car plate. Once done, the system will send the captured image to an API that will recognise the car plate using Computer Vision.<br>

Moreover, the system includes some external components:<br>

1. Android app that can be easily downloaded by the user, which has the following assets:<br>
It plots the real time data coming from the sensor readings (car distance and velocity, bike velocity)<br>
Once a car gets too close to the bike at high speeds, it will extract the image and display the car plate's image and its recognised symbols, the car velocity, distance and the bike velocity at the instant the camera was triggered.<br>

2. Firebase:
A real time database that stores the results stated above which enables safe storage for the proof.<br>

3. Car Enquiry Website for UK cars:
Once the users have all the data needed, and especially the car plate of the driver's vehicle, they can visit the following [**link:**](https://vehicleenquiry.service.gov.uk/), plugging in the car plate recognised, and having enough proof to contact local authorities.
  
