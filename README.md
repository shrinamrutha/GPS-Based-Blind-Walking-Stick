# GPS-Based Blind Walking Stick For the visually impared people

## 🚀 Project Overview

* This smart walking stick assists visually impaired users by combining ultrasonic sensors, an ESP32-CAM for real-time object recognition, and GPS tracking.
* Provides obstacle detection, location updates, and emergency alerts — enabling safer, more confident navigation.

## ✨ Features

* Obstacle detection using ultrasonic sensors to alert users of nearby objects
* Water sensor for detecting hazardous wet surfaces
* Real-time object recognition with ESP32-CAM using ultrasonic-based algorithms like FOMO
* Continuous GPS tracking for accurate location monitoring
* Emergency SMS alerts sent through Twilio API for quick assistance

## 🛠️ Technical Details

* Optimized UART communication between ESP32 and Arduino UNO minimizes latency and interference
* Real-time synchronization of GPS and camera data ensures timely alerts
* Modular architecture supports easy maintenance and future upgrades
* Collaborative development with active debugging and task sharing

## ⚙️ Components Used

* **ESP32-CAM Module:** Captures real-time images and performs object detection using onboard processing and ultrasonic data
* **Ultrasonic Sensors:** Detect obstacles by measuring distance to nearby objects, helping prevent collisions
* **Water Sensor:** Identifies wet or hazardous surfaces to warn the user of potential dangers
* **GPS Module:** Provides continuous tracking of the user’s location for navigation and emergency alerts
* **Arduino UNO:** Acts as the main microcontroller managing sensor data and communication between components
* **Twilio API:** Enables sending SMS emergency alerts with location data to predefined contacts

## 💻 Software Components

* Ultrasonic-based detection algorithms (FOMO)
* Twilio API integration for emergency SMS alerts
* Efficient UART communication protocol
* Custom data flow management for optimized performance

## 🚀 Usage

* Power on the device
* Ultrasonic sensors and ESP32-CAM continuously scan for obstacles
* GPS module tracks real-time location
* Alerts via vibration or audio signals (based on implementation)
* Sends emergency SMS alerts to contacts through Twilio when triggered

## 🔮 Future Improvements

* Hands-free voice command integration
* AI-enhanced object recognition using machine learning
* Longer battery life and more compact design
