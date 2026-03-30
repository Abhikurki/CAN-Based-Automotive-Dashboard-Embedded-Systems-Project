# 🚗 CAN-Based Automotive Dashboard  
### Embedded Systems Project  

## 📌 Overview  
This project implements a **CAN (Controller Area Network)-based automotive dashboard system** that simulates real-time communication between multiple Electronic Control Units (ECUs).  

It demonstrates how modern vehicles use a **distributed architecture** where different modules communicate over a CAN bus without a central controller.

The dashboard node collects and displays real-time vehicle parameters such as **speed, RPM, gear position, and indicator status**.

---

## ⚙️ System Architecture  

The system consists of **three ECU nodes** connected via CAN bus:

### 🔹 ECU Node 1 – Speed & Gear Control  
- Reads speed input using a potentiometer  
- Determines gear position  
- Sends speed & gear data over CAN  

### 🔹 ECU Node 2 – RPM & Indicator Control  
- Simulates engine RPM using a potentiometer  
- Detects left/right indicator status  
- Transmits RPM & indicator data via CAN  

### 🔹 ECU Node 3 – Dashboard Display  
- Receives CAN messages from other ECUs  
- Decodes CAN IDs and extracts parameters  
- Displays data on CLCD  
- Generates alerts for abnormal conditions  

---

## 💻 Technologies Used  
- Embedded C  
- CAN Communication Protocol  
- Interrupt Handling  
- Real-Time Data Processing  
- Automotive Network Architecture  

---

## 🔧 Hardware Components  
- PIC18F4580 Microcontroller  
- CAN Controller (MCP2515 or internal CAN module)  
- CAN Transceiver (MCP2551 / TJA1050)  
- CLCD Display  
- LM35 Temperature Sensor  
- Potentiometers (for Speed & RPM simulation)  
- Power Supply Module  

---

## 🔌 Working Principle  
1. Each ECU node collects input data (speed, RPM, indicators).  
2. Data is transmitted over the **CAN bus** using unique message IDs.  
3. The dashboard node listens to all CAN messages.  
4. It decodes the received data and updates the display in real time.  
5. Alerts are triggered for abnormal conditions.  

---

## 📡 Features  
✔ Multi-node CAN communication  
✔ Real-time data transmission  
✔ Interrupt-driven architecture  
✔ Modular ECU design  
✔ Automotive-inspired system design  

---

## 📸 Output (Add Images Here)  
/images/dashboard.jpg  
/images/hardware_setup.jpg  
/images/can_network.jpg  

---

## 🚀 How to Run  

### 🔹 Hardware Setup  
1. Connect all ECU nodes via CAN bus (CANH & CANL lines)  
2. Interface sensors and CLCD  
3. Power up the system  

### 🔹 Software  
1. Compile code using MPLAB IDE / XC8 Compiler  
2. Flash code into PIC18F4580 microcontrollers  
3. Monitor CAN communication and dashboard output  

---

## 📊 Applications  
- Automotive embedded systems  
- Vehicle diagnostics simulation  
- ECU communication learning  
- Real-time embedded networking  

---

## 🔮 Future Improvements  
- Add fault detection & diagnostics (OBD simulation)  
- Wireless CAN monitoring  
- Integration with IoT dashboard  
- Advanced GUI display  

---

## 🤝 Contributing  
Feel free to fork this repository and improve the project. Contributions are welcome!

---

## 📬 Contact  
If you have any questions or suggestions, feel free to connect.

---

## ⭐ Acknowledgment  
This project was built as part of hands-on learning in **embedded systems and automotive communication**.
