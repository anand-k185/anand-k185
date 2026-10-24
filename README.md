<h1 align="center">Hi, I'm Anand 👋</h1>
<h3 align="center">I build autonomous robots end to end, from the estimation and planning algorithms down to the firmware and wiring that run them.</h3>
 
<p align="center">
<b>Controls · Perception · State Estimation · Embedded Firmware · Hardware Integration</b><br>
EE @ Purdue · GNC @ Purdue Aerial Robotics · Firmware @ Purdue Space Program
</p>
---
 
<table>
<tr>
<td width="50%" valign="top">
### 🧠 Autonomy & Theory
- Kalman filtering & sensor fusion
- SLAM & occupancy mapping
- A\* planning · Pure Pursuit tracking
- Swerve-drive kinematics
- Vision-based localization (AprilTags)
</td>
<td width="50%" valign="top">
### ⚙️ Embedded & Hardware
- C++ firmware on STM32H7 microcontrollers
- CAN / FDCAN bus drivers & device protocols
- Real-time closed-loop motor & actuator control
- Edge compute on NVIDIA Jetson
- Sensor integration & hand-wired harnesses
</td>
</tr>
</table>
---
 
## 🚀 Core Projects
 
### 🚗 Autonomous Mobile Robot
> **Built from bare hardware to full autonomy: it maps a room and drives itself through it.**
 
**Hardware:** I integrated LIDAR, wheel encoders, and a motor controller on an NVIDIA Jetson Nano, wiring 200+ connections by hand.
**Autonomy:** **Cartographer SLAM** fuses LIDAR and encoder odometry into a live map. **A\*** plans the route, and **Pure Pursuit** closes the loop with the motors in real time. **Validated across 20 autonomous runs.**
 
`Jetson Nano` `LIDAR` `Motor Control` `Cartographer SLAM` `A*` `Pure Pursuit` `Python` `C++`
 
### 🚀 TOAD Lander: Thrust Vector Control Firmware
> **Embedded C++ that steers a rocket engine for Purdue Space Program's vertical-landing vehicle.**
 
Engine-controller firmware for a custom **STM32H7** board, built with PlatformIO. It commands the pitch and yaw **TVC linear actuators** over an **FDCAN** bus and translates gimbal angles into actuator positions. A startup handshake confirms that every actuator is powered and talking on the bus, so a dead or unplugged actuator is caught before the engine fires.
 
`C++` `STM32H7` `FDCAN / CAN` `PlatformIO` `Actuator Control` `Gimbal Kinematics`
 
### 🎯 Swerve-Drive Localization: 8 ft → 0.5 in
> **Cut a competition robot's position error by more than 99%.**
 
Custom swerve kinematics that model wheel skew and module lag brought pose error from **~8 ft to under 10 in**. A **Kalman filter** fusing odometry with AprilTag vision brought it down to **0.5–1 in**. That accuracy made Pure Pursuit autonomous routines reliable enough to win a **district event** and two awards: **Autonomous** and **Innovation in Control**.
 
`Java` `Kalman Filter` `AprilTags` `Computer Vision` `Pure Pursuit` `Swerve Kinematics`
 
<sub>Also built: a biometric facial-recognition system with 86% accuracy and anti-spoofing.</sub>
 
---
 
## 🛠 Tech Stack
 
**Languages**<br>
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
 
**Embedded & Hardware**<br>
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![CAN](https://img.shields.io/badge/CAN_|_FDCAN-333333?style=for-the-badge)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&logo=platformio&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![LIDAR](https://img.shields.io/badge/LIDAR-333333?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
 
**Controls, Perception & Autonomy**<br>
![Kalman](https://img.shields.io/badge/Kalman_Filtering-1f425f?style=for-the-badge)
![SLAM](https://img.shields.io/badge/SLAM-Cartographer-1f425f?style=for-the-badge)
![Planning](https://img.shields.io/badge/A*_|_Pure_Pursuit-1f425f?style=for-the-badge)
![Vision](https://img.shields.io/badge/AprilTags_|_CV-1f425f?style=for-the-badge)
![GNC](https://img.shields.io/badge/GNC-1f425f?style=for-the-badge)
 
**ML, Data & Tools**<br>
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
 
---
 
## 📫 Let's Talk Robots
 
<p align="center">
<a href="mailto:anandkrishnan1835@gmail.com"><img src="https://img.shields.io/badge/anandkrishnan1835@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="mailto:krish454@purdue.edu"><img src="https://img.shields.io/badge/krish454@purdue.edu-CEB888?style=for-the-badge&logo=maildotru&logoColor=black"/></a>
<a href="https://www.linkedin.com/in/anand-krishnan-508297246"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>
<p align="center"><i>Open to Summer 2027 internships in robotics, autonomy, controls, and embedded systems.</i></p>
