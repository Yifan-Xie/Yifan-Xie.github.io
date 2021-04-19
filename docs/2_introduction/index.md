---
title: Introduction
nav_order: 2
has_children: true
---

## Introduction
<br>
<p align="center">
    <img src="../images/Cycle_Buddy_introduction.png" width="600">
    <br> 
    <b>Introduction</b>    
    <br>     
</p>
  
Our project, Cycle Buddy, is a system that detects cars that endanger everyday cyclits.<br>

Once the car overpasses the biker's path with a relative high speed and within a close distance, the system can detect this unjust act and stimulates a camera to capture the car's plate number and recognizes it using a Computer Vision API.<br>

Then it will send the plate number, its photo and the relevant sensor readings to the mobile application through **socket connections**, which then stores the proof data in an online real-time database. With those infomation recorded as evidence, the bikers can then use it to contact local law enforcements to report the issue. <br />
