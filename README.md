# Arachne 1.0  
**An Advanced Robotic Surveillance Platform for Smooth Movement**

Arachne 2.0 is a sophisticated robotic quadbot designed to provide smooth and fluid movement using sine wave values. This project implements precise servo control for effective navigation and is ideal for various environments. The bot features serial input control for user-defined movement commands.

---

## Key Features
- **Spider-Inspired Gait**: Imitates the gait of a spider to mimic its movement, helping cover rough and uneven terrains more evenly.  
- **Multiple Servo Control**: Capable of controlling multiple servos simultaneously for complex movements.  
- **Serial Communication**: Allows user input via a serial interface to control the bot's movements.  
- **Remote Operation**: Compatible with web/mobile interfaces for real-time control.

---

## Hardware Requirements

| Component            | Specification                                |
|---------------------|----------------------------------------------|
| Microcontroller      | Arduino UNO                          |
| Servo Controller     | Adafruit PCA9685 PWM Driver                  |
| Servos               | 8x Servos          |
| Power                | 7.4V–12V Rechargeable Battery Pack           |
| Chassis              | Ice cream sticks-based custom chassis             |
| Extras               | Jumper Cables, Screws, Zip Ties              |

---

## Setup Instructions

### 1. Hardware Assembly
- Connect servos to PCA9685 driver.
- Link the power supply to Arduino and PCA9685.
- Secure the ice cream-based chassis, ensuring all components are properly connected.

### 2. Software Installation
Install required libraries via Arduino IDE Library Manager:
- `Wire`  
- `Adafruit_PWMServoDriver`

### 3. Clone the repository
Clone the repository:
```bash
git clone (https://github.com/SurajKumarKonda/Arachne-2.0)
```
- Open the Arduino IDE and include `arachne2.cpp` into a new sketch.

## Contributing

Contributions are welcome! Fork the repository and submit pull requests for bug fixes, enhancements, or new features.

---

## License

MIT License – see [LICENSE](LICENSE) for details.

---

**Arachne 1.0**: *Where Robotics Meets Smooth Motion.*
