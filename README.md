# **CamVisioTech: AIoT-Driven Smart Security System**

CamVisioTech is an AI-powered IoT-based security system project, collaboratively developed to implement advanced surveillance features with iterative enhancements. Each version builds upon its predecessor, integrating cutting-edge technologies for home and office security.

---

## **Project Overview**

CamVisioTech aims to deliver comprehensive smart security solutions by leveraging:
- **Facial Recognition**: For automated user authentication.
- **Object Detection**: Real-time analysis using advanced detection algorithms.
- **Automated Alerts**: Notifications via Telegram and email.
- **Live Streaming**: Video feed and control interfaces through web apps.
- **Hardware Integration**: ESP32-CAM microcontroller for embedded AI applications.

With every iteration, CamVisioTech integrates improved hardware and software capabilities, ranging from basic facial recognition (MK-0) to advanced object detection and web-based control (MK-1).

---

## **CamVisioTech Versions**

### **CamVisioTech MK-0: ESP32-CAM Security System**

The foundational version focuses on facial recognition for access control and intruder alerts:
- **Face Recognition**: Controls a solenoid lock to unlock doors for known individuals.
- **Intruder Alerts**: Sends images of unauthorized users via Telegram and activates a buzzer.
- **Web Interface**: Streams video feed and provides control options.
- **Python GUI**: Desktop application for managing the system with both high and low latency options.

#### **Features**:
- Solenoid lock control via a relay.
- Hardware enhancements like heat sinks for improved reliability.
- Python-based GUI and Telegram integration for real-time alerts.

#### **Hardware**:
- ESP32-CAM microcontroller
- Solenoid lock, relay module, buzzer
- IC-7805 voltage regulator
- Additional components: diode, transistor, resistors, and capacitors.

#### **Software**:
- Arduino IDE for programming ESP32-CAM.
- Python with libraries like `opencv-python`, `face_recognition`, and `customtkinter`.

---

### **CamVisioTech MK-1: AI-Driven Smart Security Camera**

The enhanced version introduces real-time object detection and a Flask web application:
- **Haar Cascade**: Utilized for object and face detection.
- **Alerts via Email & Telegram**: Notifications for security breaches.
- **Flask Web App**: Streams live video feed with overlays.
- **Hardware Improvements**: Focused on scalability and performance.

#### **Objectives**:
1. Understand and implement the Haar Cascade method.
2. Develop Flask-based live monitoring and control systems.
3. Integrate AI and IoT seamlessly for enhanced surveillance.

#### **Features**:
- Combines face recognition and object detection.
- Real-time alerts for unauthorized access.
- Web-based video streaming with detection overlays.

#### **Hardware**:
- ESP32CAM module
- Similar components as MK-0 with enhanced integration.

#### **Software**:
- Python and Flask for backend and web streaming.
- Libraries for detection: `opencv`, `face_recognition`.

---

### **CamVisioTech MK-2: Advanced Security via Edge AI**

The MK-2 version of CamVisioTech moves beyond conventional surveillance by leveraging **Edge AI** for on-device processing. Unlike earlier iterations, it focuses on executing models locally, enhancing privacy, reliability, and efficiency, even in low-bandwidth environments. 

#### **Key Features**:
- **YOLOv2 Integration**: Enables precise object detection and activity recognition directly on the device.
- **Edge AI Processing**: All inference operations are performed on the hardware itself (Maixduino), eliminating the need for cloud-based computations.
- **Multi-Connectivity Support**: Offers Wi-Fi or GSM for sending real-time alerts and notifications.
- **Actuator Integration**: Supports on-site physical responses such as buzzer alerts or relay-controlled actions.
- Alerts are dispatched via Wi-Fi or GSM, with extensibility to third-party apps like Telegram using platforms such as IFTTT or PipeDream.

#### **Hardware Requirements**:
- **Maixduino RISC-V + AI Kit**: AI-capable development board with integrated ESP32 for Wi-Fi and Bluetooth capabilities.
- **OV2640 Camera Module**: High-quality imaging for real-time object detection.
- **Buzzer**: For audio alerts.
- **Breadboard & Jumper Wires**: For modular connections.
- **2.4-inch TFT Display**: For on-device status monitoring.
- **Type-C Data Cable**: For power and data transfer.

#### **Software Requirements**:
- **MicroPython**: Lightweight scripting language for development.
- **MaixPy IDE**: To build and deploy applications on the Maixduino hardware.
- **kflash_gui**: For uploading firmware and pre-trained models.
- **uPyLoader**: For accessing, updating, and managing files on the device.
- **YOLOv2 Model Files**: Optimized for real-time inference on the Maixduino platform.

---

## **Demo Videos**

- [CamVisioTech MK-0 Demo](https://www.instagram.com/p/CvfpnTPIu1L/)
- [CamVisioTech MK-1 Demo](https://www.instagram.com/p/C0wjcxdiWFX/)
- [CamVisioTech MK-2 Demo](https://www.instagram.com/p/MK2_demo_link/)

---

## **Future Enhancements**

- Integration of advanced AI models for object detection and activity recognition.
- Scalability for multi-camera setups.
- Mobile app for real-time control and notifications.
- Energy-efficient hardware for long-term deployments.

---

## **License**

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

---

By following the documentation, users can deploy a robust AIoT-based security system with advanced features and modular enhancements.

