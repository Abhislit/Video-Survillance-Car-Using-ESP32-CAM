
# 🚘📹 ESP32-CAM Surveillance Robot Car  

A Wi-Fi-controlled robotic car powered by **ESP32-CAM**, capable of **live video streaming** and **remote navigation**.  
This project combines:  
- ESP32-CAM Video Streaming  
- IP-Based Robotic Car Control  
- Pan-Tilt Camera System  

<p align="center">
  <img src="https://raw.githubusercontent.com/YOUR-USERNAME/esp32-cam-surveillance-car/main/images/demo_car.jpg" width="500">
</p>  

---

## 📌 Features  
- 🎥 **Live Video Streaming** (MJPEG over Wi-Fi)  
- 🎮 **Web-Based Control Panel** (Forward, Backward, Left, Right, Stop)  
- 🎚️ **Camera Settings Control** (brightness, contrast, filters)  
- 🔄 **Pan-Tilt Mechanism** for flexible camera angles  
- 📡 **Static IP Configuration** for reliable access  
- 🔧 Built entirely with **Arduino IDE** + Open Source libraries  

---

## 📑 Block Diagram  

<p align="center">
  <img src="https://raw.githubusercontent.com/YOUR-USERNAME/esp32-cam-surveillance-car/main/images/block_diagram.png" width="600">
</p>  

**Explanation**  
- **ESP32-CAM** → Captures & streams video + processes movement commands  
- **Motor Driver + Wheels** → Enables car movement  
- **Pan-Tilt Servo System** → Controls camera angles  
- **Wi-Fi Router** → Provides network access  
- **Web Browser** → User interface for video + control  

---

## 🛠️ Hardware Components  

| Component | Qty | Description |
|-----------|-----|-------------|
| ESP32-CAM Module | 1 | Main microcontroller with camera |
| Motor Driver (L298N) | 1 | To control DC motors |
| DC Motors + Wheels | 2/4 | For car movement |
| Pan-Tilt Mechanism | 1 | For camera angle adjustment |
| 9V Battery | 1 | Power source |
| USB-UART Module | 1 | For programming ESP32-CAM |

---

## 💻 Software Requirements  
- Arduino IDE  
- ESP32 Board Manager  
- Libraries: `esp_camera.h`, `WiFi.h`  

---

## ⚡ Schematics  

<p align="center">
  <img src="https://raw.githubusercontent.com/YOUR-USERNAME/esp32-cam-surveillance-car/main/images/schematic.png" width="600">
</p>  

---

## 📂 Repository Structure  

