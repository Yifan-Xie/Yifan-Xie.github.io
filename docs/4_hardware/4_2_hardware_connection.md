---
title: Hardware connection
parent: Hardware
nav_order: 2
---

## Hardware connection
<br>
<p align="center">
  <img src="../images/circuits.png" width="300">
  <br> 
  <b> Circuits </b>    
</p>
<br>

### Hardware connection for Raspberry Pi 3B 
<p align="center">
  <img src="../images/gpio-readout.png" width="600">
  <br> 
  <b> Hardware connection for Raspberry Pi 3B </b>    
</p>
<br>

Raspberry Pi 3B，GPIO and wiringPi pin usage defination, required to be modified given different GPIO layout: <br><br>
**#define HALL 0 <br>
#define SONAR 1 <br>
#define pinInHall 1 <br>
#define pinOutHall 4 <br>
#define pinInSonarOne 24 <br>
#define pinOutSonarOne 23** <br>

### Hardware connection for Raspberry Pi 4B 
<p align="center">
  <img src="../images/Hardware_Connection.png" width="600">
  <br> 
  <b> Hardware connection for Raspberry Pi 4B </b>    
</p>
<br>

* This hardware connection is for **Raspberry Pi 3B / 4B**, if you do not use this type, you should connect GPIO according to your version.
