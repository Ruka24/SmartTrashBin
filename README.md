# Smart Trash Bin - BinGenious

**An Intelligent Waste Container**

## Overview

The **Smart Trash Bin** is an innovative Arduino project designed to revolutionize waste disposal. Combining advanced hardware functionality with a user-friendly app, it offers a hygienic, efficient, and interactive solution for modern waste management. The bin automatically detects hand motion to open the lid, monitors fill levels in real time using sensors and LED indicators, and provides visual feedback through an LCD display. Additionally, the accompanying Flutter-based mobile app enables users to monitor the bin’s status, earn gamification rewards, and receive notifications, making waste management more engaging and sustainable.

**Start Date:** October 8, 2024  
**Duration:** 3 months  
**Status:** Ongoing  
![image](https://github.com/user-attachments/assets/2114d054-571c-41bb-861a-5a4066dc37b1)
![image](https://github.com/user-attachments/assets/4d6c7ee7-86ff-4e40-bf3d-0489dfd1fecd)

## Features

### **Hardware**
- **Ultrasonic Sensor (HC-SR04):** Detects motion to trigger the automatic lid opening, enhancing hygiene.
- **IR Sensors:** Measure fill levels, detecting when the bin is 0%, 50%, or 100% full.
- **Motorized Lid Mechanism:** Enables hands-free lid operation.
- **LCD Display (16x2):** Displays real-time bin fill levels.
- **Speaker/Buzzer:** Provides audio feedback and plays a melody as a gesture of gratitude.

### **Software**
- **Real-Time Monitoring:** Displays bin fill level, syncs with hardware sensors, and notifies users when thresholds are met.
- **Authentication:** Secure login system powered by Firebase for user data protection.
- ![image](https://github.com/user-attachments/assets/78daae22-42c2-4372-9ab1-fc08f781d7a0)

- **Gamification:** Features such as achievements and progress tracking to encourage responsible waste disposal.
- ![image](https://github.com/user-attachments/assets/921f9013-9bd1-4cab-b401-c45e5921e54a)
- ![image](https://github.com/user-attachments/assets/3165af16-6867-4659-ad80-039b2303c871)

- **Flutter-Based App:** A user-friendly interface offering dashboards, notifications, and settings.

### **Future Improvements**
1. **AI-Based Waste Sorting:** Real-time waste classification using a camera and machine learning.
2. **Enhanced UI Design:** Integration of material design principles, animations, and interactive features.
3. **Multilingual Support:** Localization for global accessibility, with support for English, Spanish, French, German, and Chinese.

## Challenges Encountered
- **Hardware Issues:**
  - High friction in the lid-opening mechanism resolved with lubrication.
  - LCD connection instability in low temperatures, ongoing investigation.
- **Software Issues:**
  - Firebase authentication challenges resolved through system reinitialization.

## Core Technologies
- **Hardware:** Arduino UNO, Arduino Nano IoT 33, ultrasonic sensors, IR sensors, motorized mechanisms.
- **Software:** Flutter for mobile development, Firebase for authentication, REST APIs for communication.
- **Programming Languages:** Dart (Flutter), C++ (Arduino), Python (server-side).

## Contributors
- **Adrian-Ioan Campean**
- **Ioana-Cristina Stefanoiu**
- **Mircea-Dan Deaconu**
- **Mario-Alexandru Rodina**
- **Rares-Cristian Manole**
- **Valentina Pipirigeanu**

## Git Repository
[Smart Trash Bin Repository](https://github.com/Ruka24/SmartTrashBin)

## Screenshots
- **Authentication Interface**: Secure login system.
- **Dashboard**: Displays fill levels and gamification features.
- **Apple Gamification Element**: Visual representation of fill levels.

## Future Goals
- **Optimize waste management practices.**
- **Promote recycling habits and user convenience.**
- **Expand global reach through multilingual support and improved user engagement.**

## Conclusion
The Smart Trash Bin represents an innovative step in modern waste management, providing convenience, hygiene, and user interaction in a sustainable and efficient manner. With ongoing improvements, BinGenious aims to lead the market for intelligent waste management solutions.
