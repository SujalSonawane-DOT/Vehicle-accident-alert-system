# Vehicle-accident-alert-system
accident detection system using ESP32 WROVER-B and GSM,Gyroscope,Vibration and microphone sound sensor

Overview
This project is an accident detection system that automatically sends emergency alerts when a collision is detected.

Features
- Detects accidents using various sensors
- Sends SMS alert using GSM module (SIM800L)
- Real-time emergency notification
- Fast response system

Components Used
- ESP32 WROVER-B
- GSM Module (SIM800L)
- NEO-6M GPS Module 
- Accelerometer and Gyroscope Sensor
- Vibration Sensor
- Electret Microphone Sound Sensor
- MicroSD Card Module
- Power Supply

 Working
1. All sensors work in combination and  detects sudden change in motion (impact)
2. ESP32 processes the signal
3. GSM module sends SMS alert to predefined number
4. Alert is sent within seconds


Future Improvements
- Mobile app integration will help simplify integration
- Cloud data storage will help expand storage boundaries
