# Car Parking System – ATmega32

This project is a real-time embedded **Car Parking System** implemented using the **ATmega32 microcontroller**.  
It uses **infrared (IR) sensors** to detect vehicle entry and exit, controls a **servo motor gate**, and displays parking status on a **16x2 LCD**.

## Features
- IR sensor–based vehicle entry and exit detection  
- Automatic gate control using a servo motor  
- Real-time parking slot count  
- LCD display for system status  
- Active-low sensor logic with pull-up resistors  

## Files Included
- `main.c` – Complete source code for the system  
- `car parking system atmega 32 100.hex` – Compiled HEX file for ATmega32  
- `Atmega 32 Car System.pdsprj` – Proteus simulation project file  

## Simulation
The system was designed and tested using **Proteus**.  
A screenshot of the simulation is included below.

📸 *Simulation Screenshot:*  
![Image](https://github.com/user-attachments/assets/ade71f2a-4e01-4d42-aa9d-a2734f7c62fb)

## Microcontroller
- ATmega32  
- Clock Frequency: 16 MHz  

## Notes
- Entry and exit are detected using **active-low IR sensors**
- Internal pull-up resistors are enabled for stable input readings
- Designed as part of a **Real-Time & Embedded Systems course assignment**

---

