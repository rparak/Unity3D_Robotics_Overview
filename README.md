# Unity3D Industrial Robotics: An Overview

## ABB IRB 120

The project is focused on a simple demonstration of client-server communication via RWS (Robot Web Services), which is implemented in Unity3D. The project demonstrates the Digital-Twin of the ABB IRB 120 robot with some additional functions. The application uses performance optimization using multi-threaded programming.

This solution can be used to monitor a real robot or to simulate it (ABB RobotStudio in Windows). The Unity3D Digital-Twin application was tested on the IRB120 robot, both on real hardware and on simulation.

The application can be installed on a mobile phone, tablet or computer, but for communication with the robot it is necessary to be in the same network.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Unity3D_Robotics_ABB                                        |
| Youtube               | https://www.youtube.com/watch?v=LVRx4pJCO2w                                           |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/abb_1.png" width="800" height="450">
</p>

## Universal Robots UR3

The project is focused on a simple demonstration of client-server communication via TCP / IP, which is implemented in Unity3D. The project demonstrates the Digital-Twin of the UR3 robot with some additional functions. The application uses performance optimization using multi-threaded programming.

This solution can be used to control a real robot or to simulate it (using VMware - UR Polyscope in Windows), E and CB series. The Unity3D Digital-Twin application was tested on the UR3 robot, both on real hardware and on simulation.

The application can be installed on a mobile phone, tablet or computer, but for communication with the robot it is necessary to be in the same network.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Unity3D_Robotics_UR                                         |
| Youtube               | https://www.youtube.com/watch?v=kReuJdESdz0&t=182s                                    |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/ur_1.png" width="800" height="450">
</p>

## Sorting Machine (B&R Automation, SMC)

The project is focused on a simple demonstration of client-server communication via OPC UA, which is implemented in Unity3D (Server - B&R Automation PLC, Client - Unity3D). The project demonstrates the Digital-Twin of the Sorting Machine with some additional functions. The application uses performance optimization using multi-threaded programming.

This solution can be used to control a real machine or to simulate it (Automation Studio Runtime Simulation/ Real PLC). The Unity3D Digital-Twin application was tested on the simulation using X20CP1584 PLC. It is possible to use another OPC UA server, but in accordance with certain principles (Input / Output nodes).

The application can be installed on a mobile phone, tablet or computer, but for communication with the machine it is necessary to be in the same network.


|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Unity3D_Robotics_Sorting_Machine                            |
| Youtube               | https://www.youtube.com/watch?v=AlEid_gWuA8&t=2s                                      |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/sm_1.png" width="800" height="450">
</p>

## B&R Automation ACOPOStrak transport system

The project is focused on a simple demonstration of client-server communication via OPC UA, which is implemented in Unity3D (Server - B&R Automation PLC, Client - Unity3D). The project demonstrates the Digital-Twin of the ACOPOStrak with some additional functions. The application uses performance optimization using multi-threaded programming.

The main idea of the application is to demonstrate the control of an amazing machine that can be used for adaptive production. For visual inspection of the object, we use a B&R 2D camera/sensor with additional light and the entire control program (velocity and / or position control of shuttles (min 1 - max 6) around multiple sectors (A, B), alarm handling, and others) is programmed on the PLC (OPC UA Server).

The application can be installed on a mobile phone, tablet or computer, but for communication with the machine it is necessary to be in the same network.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Unity3D_Robotics_ACOPOStrak                                 |
| Youtube               | https://www.youtube.com/watch?v=Dnw5PxeZf7k                                           |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/acpT_1.png" width="800" height="450">
</p>

## Simple Linear Axis (B&R Automation, SMC)

The project is focused on a simple demonstration of client-server communication via OPC UA, which is implemented in Unity3D (Server - B&R Automation PLC, Client - Unity3D). The project demonstrates simple motion control using Mapp Technology and PLCOpen. The application uses performance optimization using multi-threaded programming.

This solution can be used to control a real axis or to simulate it (Automation Studio Runtime Simulation/ Real PLC). The Unity3D Digital-Twin application was tested on both simulation and real PLC (X20CP1584). It is possible to use another OPC UA server, but in accordance with certain principles.

The application can be installed on a mobile phone, tablet or computer, but for communication with the machine it is necessary to be in the same network.


|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/BaR-Motion-Workshop                                         |
| Youtube               | https://www.youtube.com/watch?v=5xKj3ECSeZc&t=4s                                     |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/lin_ax_1.png" width="800" height="450">
</p>

## Augmented reality - Object control in the field of Robotics

The principle of Augmented Reality (AR) consists in detecting a key object (in our case a QR code), which after successful localization, displays the 3D model on the screen of the mobile phone, tablet or computer together with the control panel of the object.

The augmented reality application was developed for simple control of objects (Universal Robots, ABB, etc.) and for a better understanding of robotic movements and 3D visualization. The application was created in Unity3D using the Vuforia Engine and tested on Android (Tablet, Phone) and Windows (USB Webcam). In our case, the application uses a simple QR code to detect and display the scene.

The augmented reality application demonstrates several cases of control:
- movement of joints / links, scaling, information about the object (robot), animation, etc.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/AR-Robotics-Object-Control                                  |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/ar_1.png" width="800" height="450">
</p>

## ABB CRB 15000 (GoFa): Externally Guided Motion (EGM)

The project focuses on a simple demonstration of client-server communication via User Datagram Protocol (UDP), which is implemented in Unity3D. More precisely, it is the control of the robot by EGM (Externally Guided Motion). The main idea is to control the Tool Center Point (TCP) of the robot (Translation, Rotation - Quaternion / Euler Angles) and collect data from the ABB into the Unity3D simulation to visualize the robot motion. An additional feature of the project is the control of the SCHUNK end-effector via TCP/IP, which is also implemented in Unity3D.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Unity3D_ABB_CRB_15000_EGM                                   |
| Youtube               | coming soon ...                                  |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/gofa_egm.png" width="800" height="500">
</p>

## ABB IRB 120: Externally Guided Motion (EGM)

The project focuses on a simple demonstration of client-server communication via User Datagram Protocol (UDP), which is implemented in Unity3D. More precisely, it is the control of the robot by EGM (Externally Guided Motion). The main idea is to generate the motion of the absolute positions of the robot's joints through the Unity3D development platform. An additional feature of the project is to visualization of the robot's target position (with or without the end-effector).

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Unity3D_ABB_IRB_120_EGM                                     |
| Youtube               | coming soon ...                                  |

<p align="center">
<img src="https://github.com/rparak/Unity3D_Robotics_Overview/blob/main/images/irb_120_egm.png" width="800" height="500">
</p>

## Contact Info:
Roman.Parak@outlook.com

## Citation (BibTex)
```bash
@misc{RomanParak_Unity3D,
  author = {Roman Parak},
  title = {A digital-twins in the field of industrial robotics integrated into the unity3d development platform},
  year = {2020-2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/rparak/Unity3D_Robotics_Overview}}
}
```
## License
[MIT](https://choosealicense.com/licenses/mit/)
