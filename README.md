# NIMBLE: Computer Vision Based Ball Balancing & Trajectory Tracking Robot


### System setup
<br>

<img width="1599" height="899" alt="f4afa68b-89f5-4ad4-aba0-d910d50fece1" src="https://github.com/user-attachments/assets/5f14064a-081a-4e7b-88a6-b7b69e64b23e" />  


<br>
<br>

### Robot assembly
<br>

<img width="783" height="760" alt="Screenshot 2026-06-08 133718" src="https://github.com/user-attachments/assets/5f0a31c9-42e0-4f65-bdbe-79b962e40c22" />  



<br>
<br>

### Functional diagram 
<br>

<img width="1586" height="992" alt="ChatGPT Image May 22, 2026, 03_35_27 PM" src="https://github.com/user-attachments/assets/e8c8a44e-1703-4def-b2e9-d2796221b2db" />  



<br>
<br>

NIMBLE is a full-stack mechatronics system combining computer vision, embedded real-time control, inverse kinematics, and mechanical design into a single cohesive robot. A webcam detects the ball's position in real time, a Python application computes the positional error, and an STM32 microcontroller runs dual independent PID controllers that command two stepper motors to tilt a platform and keep the ball exactly where you want it.

Beyond simple balancing, the system supports trajectory tracking — the ball can follow a circle, a figure-eight, or any freehand path you sketch in the GUI.

Developed as a final project for Mechatronics Engineering (MCTR601) at the German University in Cairo.  
Supervised by Prof. Ayman A. El-Badawy.

This repository contains full documentation of the project and all CAD, lasercuting and code files.

Contributers:  
Zeina Abdelaal, Farah Abdelaal, Ahmed Shawki
