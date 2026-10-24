<h1 align="center">Hi, I'm Anand 👋</h1>
<h3 align="center">I build autonomous robots end to end, from the estimation and planning algorithms down to the firmware and wiring that run them.</h3>
 
<p align="center">
<b>Controls · Perception · Embedded Software · Hardware Integration</b><br>
EE @ Purdue
</p>
<p align="center"><i>Open to Summer 2027 internships in robotics, and embedded systems.</i></p>
 
## 🚀 Core Projects

### 🎯 Swerve-Drive Localization:

Our autonomous routines kept missing because the robot's position estimate drifted by about 8 feet. I modeled the real causes (wheel skew and swerve module lag), which cut the error to under 10 in. Then I fused odometry with AprilTag vision in a Kalman filter and got it to 0.5–1 in.

I wrote the motor drivers and the interfaces to the motors so that they could be used for various subsystems that were being built.
 
`Java` `Kalman Filter` `AprilTags` `Computer Vision` `Pure Pursuit` `Kinematics`
 
### 🚗 Autonomous Mobile Robot
 
Drop it in an unfamiliar room and it builds the map and navigates anywhere in it, using LIDAR with Cartographer SLAM, A\* for planning, and Pure Pursuit for tracking. SLAM is only as good as the odometry it's fed, so getting the wiring and motor control solid was half the work.
 
`Jetson Nano` `LIDAR` `Motor Control` `Cartographer SLAM` `A*` `Pure Pursuit` `Python` `C++`
 
### 🚀 TOAD Lander: Thrust Vector Control Firmware
 
Engine-controller firmware for a custom **STM32H7** board, built with PlatformIO. It commands the pitch and yaw **TVC linear actuators** over an **FDCAN** bus and translates gimbal angles into actuator positions. A startup handshake confirms that every actuator is powered and talking on the bus, so a dead or unplugged actuator is caught before the engine fires.
 
`C++` `STM32H7` `CAN` `PlatformIO` `Actuator Control` `Gimbal Kinematics`
 

 
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
 

 
## 📫 Let's Talk
 
<p align="center">
<a href="mailto:anandkrishnan1835@gmail.com"><img src="https://img.shields.io/badge/anandkrishnan1835@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="mailto:krish454@purdue.edu"><img src="https://img.shields.io/badge/krish454@purdue.edu-CEB888?style=for-the-badge&logo=maildotru&logoColor=black"/></a>
<a href="https://www.linkedin.com/in/anand-krishnan-508297246"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>
