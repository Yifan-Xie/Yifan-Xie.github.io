---
title: Set up
parent: Usages
nav_order: 2
---

## Usage
This project is built using Cmake and Makefiles in order to allow users to easily run our code and tets it.<br/>
Please follow these necessary steps: <br/>
1. Clone the project with: <br/>
    `git clone https://github.com/OmarJabri7/Cycle_Buddy.git`<br/>
2. Change directorites and relocate in Cycle_Buddy project: <br/>
    `cd Cycle_Buddy`<br/>
3. Make Build directory containing all executables: <br>
    `mkdir build && cd build`
4. Link the necessary executables and libraries using CMake (in build dir): <br>
    `cmake ..`<br/>
5. Build the project using make (in build dir): <br/>
     `make`<br/>
6. Before Testing and Running the system: <br>
    Be sure to either use our GPIO setup, or change to your own in: <br>
    [GPIO numbering](src/gpio_def.h)
7. Generate Unit tests and check if all components pass (in build dir):<br>
   `make test`<br>
8. Go to main directory:
    `cd ..`
9. Make sure you have permissions to execute run.sh: <br>
    `chmod +x run.sh`
11. Run the bash script labeled run.sh: <br/>
    `./run.sh`<br/>
    <br><br>

For more <b>information</b>, please visit this:

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/hLp1nWcYq-g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<br><br><br />
