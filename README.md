📡 ESP32 FPV CAM
ESP32-Based Access Point FPV Web Camera
📖 Overview

ESP32 FPV CAM is a portable, router-free FPV (First Person View) web camera built using the ESP32-CAM module.
The ESP32 operates in Access Point (AP) mode, creating its own Wi-Fi hotspot and allowing direct connection from a smartphone, tablet, or PC.

This makes the system fully standalone, lightweight, and ideal for FPV, robotics, drones, surveillance, and embedded projects.

✨ Features

📶 Standalone Wi-Fi Hotspot (AP Mode)

🔌 No External Router Required

📱 Direct connection to phone, tablet, or PC

🎥 Real-time MJPEG video streaming

🔐 Configurable SSID and password

🌍 Works anywhere (portable & field-ready)

🧠 Low-latency streaming optimized for FPV use

🛠 Hardware Requirements

ESP32-CAM (AI Thinker recommended)

5V power supply (≥ 2A recommended)

External antenna (optional but strongly recommended)

🔧 Software Requirements

Arduino IDE

ESP32 Board Package

Supported browser (Chrome / Edge / Firefox)

⚙️ Configuration

You can configure the Wi-Fi credentials directly in the source code:

const char* ssid = "ESP32_FPV";
const char* password = "12345678";


📌 Note: These are located on lines 21 and 22 of the main source file.

🌐 Usage

Upload the firmware to the ESP32-CAM

Power on the board

Connect your phone or PC to the ESP32 Wi-Fi network

Open a browser and navigate to:

http://192.168.4.1


For live stream:

http://192.168.4.1:81/stream

🚀 Applications

FPV camera systems

DIY drones & RC vehicles

Robotics vision

Portable surveillance

IoT camera projects

Educational demonstrations

🔮 Future Improvements

Mobile app support

Camera control UI

OSD (On-Screen Display)

Web-based RC control

ESP32-S3 camera support

Low-latency tuning options

📜 License

This project is open-source and intended for educational and experimental use.
