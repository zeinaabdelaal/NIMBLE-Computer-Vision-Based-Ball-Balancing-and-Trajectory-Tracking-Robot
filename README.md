# NIMBLE: Computer Vision Based Ball Balancing & Trajectory Tracking Robot

<img width="1599" height="899" alt="f4afa68b-89f5-4ad4-aba0-d910d50fece1" src="https://github.com/user-attachments/assets/5f14064a-081a-4e7b-88a6-b7b69e64b23e" />


NIMBLE is a full-stack mechatronics system combining computer vision, embedded real-time control, inverse kinematics, and mechanical design into a single cohesive robot. A webcam detects the ball's position in real time, a Python application computes the positional error, and an STM32 microcontroller runs dual independent PID controllers that command two stepper motors to tilt a platform and keep the ball exactly where you want it.

Beyond simple balancing, the system supports trajectory tracking — the ball can follow a circle, a figure-eight, or any freehand path you sketch in the GUI.

Developed as a final project for Mechatronics Engineering (MCTR601) at the German University in Cairo.  
Supervised by Prof. Ayman A. El-Badawy.

This repo contains full documentation of the project and all CAD, lasercuting and code files.

Contributers:  
Zeina Abdelaal, Farah Abdelaal, Ahmed Shawki
