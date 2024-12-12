# Human-Following-Robot
Arduino + Proteus Simulation

### Human Following Robot Simulation Using Arduino in Proteus

![Circuit Diagram](https://github.com/user-attachments/assets/3b49295c-f042-430c-8638-72a5ca6c4722)


This repository contains the simulation files, code, and detailed documentation for a **Human Following Robot Simulation** developed using **Arduino** and simulated in **Proteus**. The project demonstrates how to design, implement, and simulate a robot that autonomously follows a human while avoiding obstacles.


### Features

- **Human Following**: Detects and follows a human at a constant distance using IR and ultrasonic sensors.  
- **Obstacle Avoidance**: Ultrasonic sensors detect and avoid obstacles in the robot's path.  
- **Smooth Movement**: Proportional-Integral-Derivative (PID) control for precise and smooth navigation.  
- **Simulation**: Developed and tested in Proteus to validate both hardware and software.  

---

### Getting Started

#### Prerequisites
1. **Hardware (if deploying):**
   - Arduino UNO
   - Ultrasonic Sensor (HC-SR04)
   - IR Sensors
   - L298N/L293D Motor Driver IC
   - DC Motors
   - Servo Motor

2. **Software:**
   - [Arduino IDE](https://www.arduino.cc/en/software)
   - [Proteus Simulation Tool](https://www.labcenter.com/)
   - Embedded C/C++

#### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/human-following-robot.git
   cd human-following-robot
   ```
2. Open the `Human_Following_Robot.ino` file in Arduino IDE.  
3. Upload the code to the Arduino board (if hardware is available).  
4. Load the Proteus simulation file (`Human_Following_Robot.pdsprj`) in Proteus.

---

### Project Structure

```plaintext
human-following-robot/
├── assets/     # Block Diagram, Circuit Diagram, Result Images, Sensor and component images
├── HFR5/
│   ├── build/     #Hex and Bin files
│   └── HFR5.ino   # Arduino C++ code
├── Libraries/
│   ├── Infrared Sensor Library for Proteus             # Infrared Sensor library
│   ├── Ultrasonic Sensor Library for Proteus           # Ultrasonic Sensor library
│   └── PID_Control_Explanation.md                      # Details on PID algorithm
├── Project Backups/   #Proteus Backup Files
├── human following robot.pdsprj                        # Proteus project file
├── human following robot.pdsprj...wasim.workspace      # Proteus Workspace file
└── README.md                        # This file
```

---

### Usage Instructions

1. **Simulation**:  
   Open the `human following robot.pdsprj` in Proteus and run the simulation. Observe the robot's ability to follow a human while avoiding obstacles.

2. **Hardware Deployment**:  
   - Assemble the hardware components as per the circuit diagram in the `Assets` folder.  
   - Upload the Arduino code in the location `HFR5/HFR5.ino`  to the Arduino UNO.  
   - Power the system and test functionality.

---

### Technologies Used

- **Microcontroller**: Arduino UNO (ATmega328p)  
- **Programming**: Embedded C++  
- **Simulation**: Proteus  
- **Control**: PID Algorithm  

---

### Contributions

Contributions are welcome!  
1. Fork the repository.  
2. Create a new feature branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:  
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

### License

This project is licensed under the MIT License.

---

### Contact

**Wasimuddin Salar Fathimullah**  
📧 Email: [wasimsalar.f.m@gmail.com](mailto:wasimsalar.f.m@gmail.com)  
🌐 LinkedIn: [linkedin.com/in/wasimuddinsalar](https://www.linkedin.com/in/wasimuddinsalar/)

---

### Acknowledgments

- **Arduino Community** for their incredible resources.  
- **Proteus Software** for the robust simulation environment.  
- **Online Forums and Blogs** for troubleshooting and development tips.

--- 

Feel free to star 🌟 this repository if you find it helpful!
