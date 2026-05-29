

# Ricardo Balderrábano Rodriguez

**Robotics & Control Engineer** Specializing in multi-agent systems, custom state estimation (EKF), and ROS 2 middleware optimization. I bridge the gap between rigorous control theory and high-performance hardware implementation. My work focuses on deploying non-linear control and LIDAR perception algorithms onto resource-constrained, bare-metal hardware.

---

## Technical Toolkit

| Category | Tools & Technologies |
| :--- | :--- |
| **Control & Estimation** | LQR, Robust Control ($H_{\infty}, L_{1}, H_{2}$), Model Predictive Control (MPC), CBFs, LPV, EKF/UKF |
| **Programming** | Python (NumPy, SciPy, Pandas), C, C#, MATLAB/Simulink |
| **Robotics Frameworks** | ROS 2, Gazebo, PCL, TF2, URDF |
| **Perception & Algorithms** | DBSCAN Clustering, Least-Squares Fitting, Dynamic Sensor Gating, $SE(2)$ Kinematics |
| **Embedded & Hardware** | STM32 (CubeIDE/Bare-metal C), Raspberry Pi, I2C/SPI/UART, PCB Design (Proteus) |
| **Tools & Methods** | Git, Linux, VDI 2206 (V-Model), OptiTrack Ground-Truth Systems |

---

## Featured Projects

* **Swarm Robotics (Multi-Agent Control & Estimation):** Engineered a custom Adaptive $SE(2)$ Extended Kalman Filter (EKF) to fuse high-frequency wheel odometry with LIDAR data. Formulated and deployed a Hybrid Artificial Potential Field (Vortex Field Control Law) for collision avoidance and stable swarm formations.
* **Embedded PID Control for Aeropendulum:** Engineered a PID control system on an STM32 using Bare-metal C and direct register access. Implemented Sensor Fusion using a Kalman Filter to process raw IMU data for superior noise rejection.
* **Smart Building Automation System:** Executed the complete mechatronic design cycle following the VDI 2206 methodology. Implemented Edge AI Access Control using FaceNet on Raspberry Pi, seamlessly integrated with Oracle Cloud via a Python Flask REST API.
* **Formula SAE (Unical Reparto Corse):** Designed the High Voltage Battery Container and Driver Interface (HMI) Housing using SolidWorks to fulfill strict safety and vibration requirements.

---

## Current Focus

* Completing my **Master’s Degree in Robotics and Automation Engineering** at Università della Calabria (Expected July 2026).
* Conducting research on **Distributed Control & Perception for Multi-Agent Systems** using ROS 2.
* Validating onboard LIDAR perception pipelines against absolute OptiTrack motion capture ground-truth systems.

---

## Let's Connect
- **LinkedIn:** [https://www.linkedin.com/in/ricardobalderrabano/]
- **Email:** [balderrabanorodriguez@gmail.com]

Open to collaborations on open-source robotics projects, research, or internship/job opportunities in:
> **Multi-Agent Systems | ROS 2 Development | Control Theory | Embedded Robotics**

### 🧰 Languages and Tools
<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="Matlab" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matlab/matlab-original.svg" />
<img align="left" alt="C" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" />          
<img align="left" alt="RaspberryPi" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/raspberrypi/raspberrypi-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<img align="left" alt="TensorFlow" width="30px" style="padding-right:10px;"  src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tensorflow/tensorflow-original.svg" />
<img align="left" alt="Pandas" width="30px" style="padding-right:10px;"  src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" />
<img align="left" alt="MongoDB" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original-wordmark.svg" />
<img align="left" alt="MySQL" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" />
<img align="left" alt="C#" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" />
<img align="left" alt="R" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/r/r-original.svg" />
<img align="left" alt="LabView" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/labview/labview-original-wordmark.svg" />
<img align="left" alt="SolidWorks" width="30px" style="padding-right:10px;" src="https://img.icons8.com/?size=100&id=62397&format=png&color=000000"/>
<img align="left" alt="OpenCV" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/opencv/opencv-original.svg" />
<br />
<br />
<br />

### 💡 Projects

### 1. Swarm Robotics (Multi-Agent Control & Estimation)
[![View Code](https://img.shields.io/badge/View_Code-Repository-blue?logo=github)](https://github.com/RicardoBalderrabano/multirobot-control.git)

Engineered a custom Adaptive SE(2) Extended Kalman Filter (EKF) to fuse high-frequency wheel odometry with LIDAR data. Formulated and deployed a Hybrid Artificial Potential Field (Vortex Field Control Law) for collision avoidance and stable swarm formations.

<p align="center">
  <img src="images/multirobot_gif.gif" width="400" alt="Swarm Robotics Demo" />
</p>

**Tech Stack:** `ROS 2` `LIDAR` `EKF` `Python` `DBSCAN` `Sensor Fusion` `Multi-Robot Control System`   


### 2. Embedded PID Control for Aeropendulum
[![View Code](https://img.shields.io/badge/View_Code-Repository-blue?logo=github)](https://github.com/RicardoBalderrabano/Aeropendulum.git)

Engineered a PID control system on an STM32 using Bare-metal C (Direct Register Access), applying the Ziegler-Nichols method for precise gain tuning and rapid stabilization. Implemented Sensor Fusion using a Kalman Filter to process raw IMU data (Accelerometer/Gyroscope), achieving superior noise rejection and state estimation compared to complementary filters. Derived the mathematical state-space model in MATLAB to analyze controllability and developed a LabVIEW HMI for real-time telemetry analysis via UART.

<p align="center">

  <img src="images/Aeropendulo1_first.gif" alt="Aeropendulum" style="width:320px;height:569px;">

  <img src="images/Aeropendulo2.gif" alt="Aeropendulum2" style="width:320px;height:569px;">

</p>

**Tech Stack:** `STM32` `Bare-metal C` `Kalman Filter` `PID` `MATLAB` `LabVIEW` `UART`


### 3. Smart Building Automation System
[![View Code](https://img.shields.io/badge/View_Code-Repository-blue?logo=github)](https://github.com/RicardoBalderrabano/TT_Server.git)

Executed the complete mechatronic design cycle following the VDI 2206 methodology (V-Model), performing UML modeling and simulations prior to physical validation. Implemented Edge AI Access Control using FaceNet on Raspberry Pi for local inference, seamlessly integrated with Oracle Cloud via a custom Python Flask REST API. Designed a scalable distributed hardware network (up to 150 nodes) using I2C with I/O Expanders, creating custom PCBs in Proteus featuring Optocouplers for galvanic isolation.

<p align="center">
  <img src="images/inmoticsystem_gif.gif" width="400" alt="Smart Building System Demo" />
</p>
📄 **[View my Thesis]([https://github.com/user-attachments/assets/your-generated-link.pdf](https://github.com/RicardoBalderrabano/TT_Server/blob/a4dc35a4f5fa71e1ea7d5646077f53827940bad8/thesis_upiita.pdf))**
**Tech Stack:** `Raspberry Pi` `Python (Flask)` `FaceNet` `I2C` `PCB Design (Proteus)` `Oracle Cloud` `VDI 2206`
