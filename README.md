# SmartHat: A Arduino-Based Smart Helmet for Bike Rider’s Security

## Project Overview
SmartHat is an **Arduino-based smart helmet** designed to enhance **motorcycle rider safety** by detecting accidents and notifying emergency contacts with real-time GPS location. The system integrates **GSM, GPS, and knock sensors** to reduce response time in case of a crash.

## Features
- **Accident Detection**: Knock and vibration sensors detect crashes.
- **Real-time Location Tracking**: GPS module provides the rider's coordinates.
- **Emergency Alert System**: Sends SMS alerts via GSM module to emergency contacts.
- **Speed Monitoring**: Warns the rider if speed exceeds a predefined limit.
- **Bluetooth Communication** (Future Update): Enables rider-to-rider communication.

## Components Used
| Component | Purpose |
|-----------|---------|
| Arduino UNO R3 | Main microcontroller |
| GPS NEO-M8N Module | Tracks real-time location |
| GSM SIM800L Module | Sends SMS alerts |
| Knock Sensor KY-031 | Detects crash impact |
| 801S Vibration Sensor | Monitors helmet vibration |
| LM2596 DC-DC Buck Converter | Power supply regulation |
| 35MM Mini Speaker | Audio alerts |
| HC-06 Bluetooth Module | Future enhancement |

## System Architecture
![System Architecture](docs/diagrams/system_architecture.png)

## Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/SmartHat.git
   cd SmartHat
   ```
2. **Upload Firmware to Arduino:**
   - Open `software/firmware/smart_helmet.ino` in **Arduino IDE**.
   - Connect your Arduino UNO.
   - Select the correct board and COM port.
   - Upload the code.
3. **Hardware Setup:**
   - Connect **GPS, GSM, and Knock Sensor** as per the **circuit diagram** in `docs/diagrams/circuit_diagram.png`.
4. **Power On & Test:**
   - Ensure the helmet receives **5V power**.
   - Test GPS and GSM connectivity.

## Usage Instructions
- Wear the **SmartHat helmet** while riding.
- In case of a crash, the system will:
  1. Detect the impact.
  2. Track location using **GPS module**.
  3. Send an alert SMS via **GSM module**.
- The system can also warn about **high speed** and provide real-time monitoring.

## Test Results
| Module | Testing Success Rate |
|--------|---------------------|
| GPS Module | 100% (Outdoor) |
| GSM Module | 83%-100% |
| Knock Sensor | 75%-100% |

## Future Improvements
- **Rider Condition Monitoring**: Detects rider’s movement status post-crash.
- **Helmet Wear Detection**: Ensures the helmet is worn before allowing ignition.
- **AI-based Crash Analysis**: Uses machine learning to analyze accident patterns.

## Credits
Developed by **Md. Anik** & **Nishat Tasnim Ali** as part of a Computer Science & Engineering project at **City University, Bangladesh**.

## Contact
For any inquiries, please email **mdanikk630@gmail.com** or open an [issue](https://github.com/anikmd) on GitHub.

---
_Stay safe, ride smart!_


