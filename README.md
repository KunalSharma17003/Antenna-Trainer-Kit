---

# Antenna Trainer Kit: Radiation Pattern Analysis System

This repository contains the design, implementation, and code for an **Antenna Trainer Kit** developed to analyze and plot the radiation pattern of antennas over a 360-degree rotation. The project focuses on providing a precise and user-friendly system for educational and research purposes to study antenna characteristics.

## Features
- **Full 360° Rotation Measurement:** Automated rotation using a NEMA 23 stepper motor controlled by a TB6600 motor driver ensures accurate positioning and smooth operation.  
- **Polar Plot Display:** Plots radiation patterns in real-time on a polar plot for better visualization of antenna performance.  
- **Wide Frequency Range:** The transmitter utilizes the ADF4351 Wideband Synthesizer to generate signals in the range of **35 MHz to 4400 MHz** with adjustable power levels.  
- **Wireless and Wired Communication:** Includes Bluetooth connectivity for wireless control and a GUI developed in Visual Studio for easy interaction with the system.  
- **Power Detection:** Accurate measurement using the LTC5596 Linear-in-dB RMS Power Detector, covering frequencies from **100 MHz to 40 GHz**.  
- **LCD Display:** Provides a real-time update of measurements for quick reference.  

## Components Used
- **Hardware:** NEMA 23 stepper motor, TB6600 motor driver, SMPS, LTC5596 power detector, ADF4351 wideband synthesizer.  
- **Software:** Arduino IDE for embedded programming, Visual Studio for GUI development.  

## Applications
- **Antenna Research:** Analyze the performance of antennas in the UHF band.  
- **Education:** Serve as a practical tool for students to study antenna behavior and radiation patterns.  
- **Wireless Communication:** Test and evaluate antennas for communication systems.  

## Getting Started
This repository includes:  
1. **Arduino Sketches** for motor control, power detection, and Bluetooth communication.  
2. **GUI Code** for controlling the trainer kit and visualizing radiation patterns.  
3. **Documentation** for hardware setup, installation, and usage instructions.  
---

Feel free to adapt this to match the structure and details you want for your GitHub repository!
