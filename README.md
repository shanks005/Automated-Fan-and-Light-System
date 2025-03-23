# Automated-Fan-and-Light-System

## 📌 Project Overview
For our Microcontrollers course Mini Project my teammates and I have designed a circuit simulation that automatically controls fans and lights based on the number of people entering a room. The system uses an **8051 microcontroller** and **infrared sensors** for person detection.

My role was to write the assembly code and upload it on to the 8051 microcontroller and peform the following requirements


## ⚙️ Functionality
- **Person Detection:**  
  - An **infrared (IR) sensor** detects the presence of a person and sends a signal to the 8051 microcontroller.  
- **Counting Mechanism:**  
  - The microcontroller counts each sensor reading and tracks the number of people entering or exiting the room.  
- **Control Logic:**  
  - The microcontroller compares the current count with predefined reference values:  
    - `0`: Turns off all fans and lights.  
    - `1`: Activates a minimal number of fans and lights.  
    - `25` (maximum): Turns on all fans and lights.  
- **Fan and Light Activation:**  
  - The **microcontroller ports** are connected to the fans and lights, controlling their activation based on the count.

## 🔧 Technology Used
- 8051 Microcontroller  
- Infrared (IR) Sensors  
- Fan and Light Control Circuits

## Circuit Diagram Preview
![image_alt](https://github.com/shanks005/Automated-Fan-and-Light-System/blob/c97a81dd2fa80ccdd7c31a00b7242efb98294362/circuit_diagram.png)
