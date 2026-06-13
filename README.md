# 🎵 Arduino Sound Reactive LED VU Meter

A responsive LED VU Meter built with Arduino UNO and a sound sensor module. This project transforms ambient sound and music into a dynamic visual display, where eight LEDs react in real time to changing sound levels.

Perfect for beginners learning Arduino, electronics, and sensor-based projects.


✨ Features
* 🎶 Real-time sound visualization
* 💡 8-level LED bar graph display
* 🚀 Smooth startup animation sequence
* 🎚 Adjustable microphone sensitivity
* 📚 Beginner-friendly and easy to customize
* 🔧 Simple hardware setup using common components
---
🛠 Hardware Requirements

* Arduino UNO
* Sound Sensor Module (Microphone Sensor)
* 8 × LEDs
* 8 × 220Ω Resistors
* Breadboard
* Jumper Wires
* USB Cable
--

🔌 Circuit Connections

### Sound Sensor

| Sensor Pin | Arduino Pin |
| ---------- | ----------- |
| AO         | A0          |
| G          | GND         |
| +          | 5V          |

### LEDs

| LED   | Arduino Pin |
| ----- | ----------- |
| LED 1 | D2          |
| LED 2 | D3          |
| LED 3 | D4          |
| LED 4 | D5          |
| LED 5 | D6          |
| LED 6 | D7          |
| LED 7 | D8          |
| LED 8 | D9          |

Note:
Each LED should be connected through a 220Ω resistor. The cathodes (short legs) of all LEDs are connected to the common GND rail.

---

## 📷 Circuit Diagram

Insert your circuit diagram image here.
<img width="1280" height="853" alt="image" src="https://github.com/user-attachments/assets/f966ca48-c887-4b8f-97c3-2be1afba2ccd" />

---
## 🚀 Getting Started

1. Assemble the circuit according to the wiring diagram.
2. Open the .ino file using the Arduino IDE.
3. Select the correct Arduino board and COM port.
4. Upload the code to your Arduino.
5. Play music or make sounds near the microphone.
6. Watch the LEDs respond to the sound intensity in real time.
---
## 🎚 Sensitivity Adjustment

The sound sensor module includes a small onboard potentiometer.

Rotate the adjustment screw to increase or decrease sensitivity until the LEDs respond appropriately to your environment.
---
## 📺 Demonstration Video

Watch the complete project build and demonstration on YouTube:

▶[https://youtu.be/3Tqa6UWSaeg?si=ydpAfqX1yz7NcVvi](https://youtu.be/3Tqa6UWSaeg?si=waW7UMNhWMqvxA9j)
--
👩‍💻 Author

Aynur Nouri Anwar
Computer Engineering Student
---
⭐ If you found this project helpful, consider giving it a star!
