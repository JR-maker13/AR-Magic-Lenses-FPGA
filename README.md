# AR-Magic-Lenses-FPGA
FPGA-based Augmented Reality Magic Lenses for Truck Blind Spot Elimination This repository provides the hardware and software implementation of an AR system designed to eliminate blind spots around vehicle A-pillars. The system uses FPGA for real-time image processing, eye tracking, and dynamic perspective adjustment to enhance driver safety.
基于FPGA的卡车盲点消除增强现实魔术镜头
该存储库提供了AR系统的硬件和软件实现，旨在消除车辆a柱周围的盲点。该系统采用FPGA进行实时图像处理、眼动跟踪和动态视角调整，以提高驾驶员的安全性。

# AR Magic Lenses: FPGA Implementation for Blind Spot Elimination

## 📖 Project Overview  
This project aims to solve the critical safety issue of blind spots around vehicle A-pillars by leveraging **Augmented Reality (AR)** and **FPGA-based real-time image processing**. The system dynamically adjusts the driver’s perspective using dual cameras, eye tracking, and spatial coordinate transformation, rendering the display transparent to reveal obscured areas.  

### Key Features  
- **Real-Time Eye Tracking**: Front camera detects driver’s eye position for FOV analysis.  
- **Dynamic Image Cropping**: Rear camera feeds are adjusted based on spatial coordinates.  
- **FPGA Acceleration**: Zynq-7000 SoC ensures low-latency processing for seamless AR effects.  
- **HDMI Output**: Integrated display interface for real-time visualization.  

---

## 🛠 Hardware Requirements  
1. **FPGA Board**: Mizar Z7020 (Zynq XC7Z020clg400-2)  
2. **Cameras**:  
   - Front: Linbo USB camera (for eye tracking)  
   - Rear: OV5640 binocular camera (1080P)  
3. **Display**: Standard HDMI-compatible LCD screen  
4. **Peripherals**: HDMI cables, GPIO connectors, power supply  

---

## 📦 Software Dependencies  
1. **Vivado Design Suite 2018.3** (for FPGA synthesis and IP integration)  
2. **Vivado HLS** (for image processing IP core generation)  
3. **OpenCV** (for skin detection and face tracking algorithms)  

---

 
