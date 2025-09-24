# York FS Dashboard 
An embedded dashboard built around an STM32F103XX microcontroller with a 1920x480 LCD DWIN display for driver interaction and real time system status

## Features
- **Display**
  - 1920x480 DWIN TFT (https://www.dwin-global.com/8-88-inch-uart-smart-lcm-model-dmg19480c088_03w-product/)
  - Used for system feedback and driver information  
- **Controls**
  - 3-position illuminated rocker switch for *Ready to Drive* control  
- **Indicators**
  - 4 × 1 W high-power LEDs with dedicated PWM drivers  
  - Functions:  
    - IMD (Insulation Monitoring Device)  
    - BMS (Battery Management System)  
    - Ready to Drive  
    - TSAL (Traction System Active Light)  
- **Communication**
  - Integrated CAN transceiver  

## PCB Notes
- Designed in KiCad 9.0
- 3D models stored in external library (dashboard.pretty)

<img width="2048" height="1024" alt="dashboard" src="https://github.com/user-attachments/assets/e15cb0ef-eccc-4990-89a9-c3cd7dcd6f71" />
