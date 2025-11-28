---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

---
<span style="font-size: 22px; font-weight: bold;">Wheel-Legged Balancing Robot</span>\
***Team Leader/Control Engineer, Capstone Project in UIUC***\
**Hall of Fame，[Grainger Best Overall Project Award](https://courses.grainger.illinois.edu/ece445/hall-of-fame.asp) (Fall 2023)**
![cad](/images/projects/Wheel-Legged/cad.png)![real](/images/projects/Wheel-Legged/real.png)\
This project develops a fully self-designed wheel-legged balancing robot that integrates mechanical design, actuator selection, embedded electronics, and control algorithms in one unified system. Traditional four-wheel delivery robots are efficient on flat terrain but fail when encountering curbs, slopes, or irregular ground. To overcome these limitations, our robot combines wheels with extendable leg mechanisms, enabling both smooth rolling and adaptive height or posture adjustment when navigating obstacles.

All core components of the robot are developed in-house: the mechanical structure is custom-designed for lightweight, high-stiffness wheel-leg actuation; the motor system is selected and tuned specifically to provide sufficient torque for balancing and leg extension; and a custom PCB hosts the microcontroller, power distribution, and sensors. On the software side, we implement a closed-loop balancing controller and validate it through MATLAB dynamic simulations.

**What I have done in this project:**
* Conducted **classical mechanics analysis** to establish the physics and dynamical model for the robot movement.
* Applied **linear quadratic regulator (LQR)** algorithm for wheel control, enabling self-balancing.
* Leveraged **virtual model control (VMC)** algorithm(model the leg motion as a **spring–damper system**) to control the leg motion, making the robot have adaptive suspension and keeping the robot level even with the difference in leg heights.
* Simulated robot motion in **Matlab (Simulink)** and implemented the control system in C++ for hybrid testing.

***The code has been open-sourced and can be found [here](https://github.com/N9nGe/Wheel_Legged_Robot/)***\
***demonstration video can be found [here](https://www.youtube.com/watch?v=a-dle_tm7Tk)***\
***Project final paper can be found [here](https://github.com/N9nGe/Wheel_Legged_Robot/blob/main/files/ECE_445_Final_Report.pdf).***\
***Control system development log can be found [here](https://github.com/N9nGe/Wheel_Legged_Robot/blob/main/LabNotebook/Naixiang(Gabriel)/Wheeled_Legged_Balancing_Robot_Development_NoteBook.pdf)***


