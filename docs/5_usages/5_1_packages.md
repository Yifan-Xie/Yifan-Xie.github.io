---
title: Packages
parent: Usages
nav_order: 1
---

## Packages
* WiringPi 
* Raspicam
* OpenALPR
* JSON
* Cmake
<br><br>

## Packages Installations
Before install any packages, please run the following:<br>
sudo apt-get update && upgrade<br>
1. [**WiringPi**](http://wiringpi.com/):<br>
   `sudo apt-get install wiringpi`<br/>
2. [**Raspicam**](https://sourceforge.net/projects/raspicam/files/) : (For Pi camera)<br>
    Download, build, make and install it.<br>
3. [**OpenALPR**](https://github.com/openalpr/openalpr):  (Github page)<br>
   `sudo apt-get update && sudo apt-get install -y openalpr openalpr-daemon openalpr-utils libopenalpr-dev`<br>
4. [**JSON Library**](https://github.com/nlohmann/json):  (Github page)<br>
   `sudo apt-get install -y nlohmann-json-dev`<br>
   If the above method does not work, please try the following:<br>
   a.`git clone https://github.com/nlohmann/json.git`<br>
   b.`cd json`<br>
   c.`mkdir build`<br>
   d.`cd build`<br>
   e.`cmake ..`<br>
   f.`make`<br>
   g.`make install`

5. [**Cmake**](https://cmake.org/) : (Website)<br>

   Click and download it from the website above.
<br><br><br />
