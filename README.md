
# 3D Printer Dashboard

A beautiful, mobile-friendly dashboard for controlling your 3D printer remotely via ESP32.

## 🌐 Live Demo
https://YOUR_USERNAME.github.io/3d-printer-dashboard

## 🛠 Setup Instructions

### 1. Flash ESP32
1. Upload the ESP32 code to your ESP32-C3
2. Update WiFi credentials in the code
3. Note the IP address from Serial Monitor

### 2. Connect Dashboard
1. Open the dashboard URL
2. Enter your ESP32 IP address
3. Click "Connect"

### 3. Wiring (ESP32 → Ender 3)
- TX (pin 21) → RX (white)
- RX (pin 20) → TX (green)
- GND → GND (black)

## 📱 Features
- Real-time temperature monitoring
- G-code file upload
- Progress tracking
- Temperature history chart
- Mobile responsive
- PWA support (install as app)

## 🔧 ESP32 Code
Find the ESP32 code in the `firmware/` directory or in the README.

## 📄 License
MIT
