 # CBM - Control Bot Mechanism
## Modular Robot Head Prototype Device: Terbinari BPQ-1

![Modular Robot Head](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/cbm-robot-modular-head-(3).png)

## Contents

- [CBM Control Bot Mechanism](#cbm-control-bot-mechanism-overview)
- [Design Architecture Method](#design-architecture-method)
- [Functionality](#functionality)
- [Application Control and Customization](#application-control-and-customization)
- [Engineering Research Lab](#engineering-research-lab)
- [Development Contributions](#development-contributions)
- [Contact and Support](#contact-and-support)
- [Legal Notice](#legal-notice)

## CBM Control Bot Mechanism Overview

The robot's control mechanism delivers a unique and engaging user experience, suitable for educational, therapeutic, and human-robot interaction research settings. Combining software and mechanical R&D, this initiative targets tailored solutions for therapeutic approaches such as Robot-Assisted Therapy/Training (RAT), addressing psychological and neurological conditions. The CBM robot head aims to explore educational and therapeutic applications through human-machine interaction. The humanoid robot software and device is a tool for interactive training and conversation. It is composed of a chatbot interface and a humanoid robot control mechanism with cervical motility, providing a unique and engaging experience for users. This makes it well-suited for use in educational and therapeutic settings, as well as for human-robot interaction research.

## Design Architecture Method

The CBM (Control Bot Mechanism) architecture provides a consistent method for designing robots, exemplified by various implementations including the Terbinari BPQ-1 model. The CBM method integrates software and mechanical components, ensuring a unified approach to vision-based gaze tracking, LED animations, mechanical eye movements, and neck orientation. While the Terbinari BPQ-1 is one of the robot designs utilizing this method, the underlying CBM principles are maintained across different models. This ensures that core functionalities, such as visual and motion parameters, remain consistent, even though specific processing and implementation details may vary between different types of devices.

## Functionality

The CBM modular robot head is designed with facial interactivity functions, using a transparent face capsule, incorporating a bicolor LED square pixel matrix for displaying emotions and reactions through eyes and mouth animations. The robot control device is powered by a 6V power supply and connects to the computer via a USB serial port. It comprises an operating system application software interface and a library of functions for a humanoid robot device. The CBM software and device facilitate interactive conversation via AI chatbot and artificial conversational entities, offering flexibility for adoption with existing chatbots and AI NLP systems like ChatGPT, primarily serving as an avatar. The CBM robot can be adopted as a module for service robots, functioning as a surrogate device with connectivity access or its own basic functions, thereby expanding the capabilities of various robotic systems.

### Speech Animation with Visemes

The control mechanism includes a Speech Viseme Motility Animation display for speech animation synchronization with speech lip motion, providing visual representations of phonemes (speech sounds) by synchronizing mouth movements with spoken words. It performs phonetically synchronized speech with mouth positions using 21 visemes according to the Viseme/Phoneme event set reference: [System.Speech.Synthesis Namespace SpeechSynthesizer.VisemeReached Event](https://docs.microsoft.com/en-us/dotnet/api/system.speech.synthesis.speechsynthesizer.visemereached?view=netframework-4.8). The software is designed to be compatible with Microsoft Windows operating systems and requires speech synthesis/recognition references.

![Modular Robot Head](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/modular-robot-mouth.png)

### Face Detection and Tracking

Facial detection/recognition enables computer vision face tracking/coordination with eye contact and head movement.

<!--- ![Modular Robot Head](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/eyes-and-neck.png) --->

- **Face Detection and Tracking**: The integrated video camera inside the head capsule allows for real-time face tracking and coordinated head movement using computer vision.

![Modular Robot Head](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/modular-robot-eyes.png)
 
- **Eyes Gaze Following**: The bicolor LED square pixel matrix mimics the eyes of the robot, dynamically adjusting to follow the observer's gaze, creating an interactive and engaging experience.

![Modular Robot Head](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/modular-robot-head-3.png)

The image illustrates the X and Y head movements of the Modular Robot Head. The central two blue quarters of the half-circle represent the zone where the robot's eyes track the observer's face and gaze. The turquoise quarters on either side show the area where the head starts to move, following the eyes' movements, until reaching the edge, which indicates the limit for body movement if tracking an object with vision.

<img src="https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/eyes-and-neck.png" alt="Modular Robot Head" height="300">

- **Neck Orientation**: The neck movement mechanism is synchronized with the face tracking system, enabling the robot's head to orient towards the observer, enhancing the natural interaction between the robot and its user. Neck movement supports motion along both the Y and X axes, allowing for precise head movements.

![Modular Robot Head](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/modular-robot-head-5.png)

### Application Control and Customization

The CBM robot is controlled via an application that manages actuator calibration and animation. This application also includes a built-in chatbot control feature, allowing for custom animations and character display sequences for eye movements, mouth expressions, and emotional displays on the robot’s screens. This functionality enables tailored interactions and enhances the versatility of the robot for various applications.

## Engineering Research Lab

Experimental Research and Development in Software and Mechanical Engineering for Artificial Intelligence, Robotics, and Design

The laboratory specializes in developing modular systems with versatile, customizable components. By creating individual parts, the lab ensures seamless integration and essential functionality across various systems. These modules offer a range of features, enhancing application versatility. Custom software, logic development, and independently engineered algorithms ensure each design embodies unique methodologies and technologies. These adaptable systems can be used or integrated into other platforms, emphasizing lightweight, compact, and easy-to-assemble designs with minimal components, achieved through mechanical and operational control solutions. Minimal hardware, a streamlined OS, and core function code libraries facilitate further development and integration.

### Development Contributions

Lado Oniani is responsible for the conceptual design and original architecture, artistic industrial design, programming and control algorithms development, mechanical engineering, and electronic assembly of the Modular Robot Head Prototype device.

## Contact and Support

For further assistance and support, please contact:

**Developer:**  
Lado Oniani  
Email: [expresearchlab@gmail.com](mailto:expresearchlab@gmail.com)  
GitHub: [Lado Oniani](https://github.com/ladooniani)

**Research Labs:**  
- [Engineering Research Lab](https://github.com/Engineering-Research-Lab)
- [Software Research Lab](https://github.com/Software-Research-Lab)
- [Game Development Lab](https://github.com/Game-Development-Lab)

## Legal Notice

This document and the associated materials are the intellectual property of Lado Oniani and the Engineering Research Lab. Unauthorized use, reproduction, or distribution of these materials is strictly prohibited and will be pursued to the fullest extent of the law. By accessing this document, you agree to abide by the following conditions:

1. **Confidentiality**: The information contained in this document is confidential and intended solely for the recipient. It is not to be shared with third parties without explicit written permission from Lado Oniani.
2. **Intellectual Property Rights**: All designs, algorithms, and other intellectual properties described herein are protected under applicable intellectual property laws. Unauthorized use or attempt to reverse-engineer these properties is illegal.
3. **Non-Commercial Use**: The recipient of this document agrees not to use the information for any commercial purposes without obtaining a formal license from Lado Oniani.
4. **No Resale or Distribution**: This document and its contents may not be sold or distributed without the prior consent of Lado Oniani. Any such actions will be considered a violation of intellectual property rights.

Violations of these conditions will result in legal action, including but not limited to claims for damages, injunctions, and other legal remedies available under applicable laws.

---

<img src="https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/qrcode.70410872.png" alt="QR Code" width="100"/>

© 2016-2024 [Lado Oniani Engineering Research.](https://github.com/Engineering-Research-Lab) All rights reserved.
 
📌 [Download PDF](https://github.com/Engineering-Research-Lab/Modular-Robot-Head/blob/main/image/Engineering-Research-Lab_Modular-Robot-Head.pdf)
 <!---
### Technical Specifications

- **Dimensions**: 20 x 20 x 30 cm
--->
 
