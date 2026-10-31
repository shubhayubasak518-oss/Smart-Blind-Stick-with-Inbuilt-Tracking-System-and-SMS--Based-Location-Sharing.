# Smart-Blind-Stick-with-Inbuilt-Tracking-System-and-SMS--Based-Location-Sharing.
### Project Description

The **Smart Blind Stick with Inbuilt GPS Tracking and SMS-Based Location Sharing** is an assistive technology solution designed to improve the safety, mobility, and independence of visually impaired individuals. The system integrates embedded systems, ultrasonic sensing, GPS positioning, and GSM communication to provide obstacle detection and emergency location sharing.

An ultrasonic sensor detects nearby obstacles and alerts the user through a buzzer and vibration motor, helping them navigate their surroundings more safely. A GPS module (NEO-6M) retrieves the user's geographical coordinates, while a GSM module (SIM800L) sends an SMS containing a Google Maps location link to predefined emergency contacts when the emergency button is pressed. The system is programmed using Embedded C/C++ in the Arduino IDE, enabling real-time sensor processing, location tracking, and SMS communication.

The project aims to provide an affordable, portable, and practical assistive device that combines obstacle detection with emergency location sharing to support safer navigation and faster assistance when needed.

### Key Features
- Ultrasonic-based obstacle detection
- Audio and vibration alerts
- GPS-based geographical location tracking
- GSM-enabled emergency SMS notifications
- Google Maps link sharing with predefined contacts
- Embedded system integration and real-time processing

### Technology Stack
**Hardware:** Arduino Uno/ESP32, HC-SR04 Ultrasonic Sensor, NEO-6M GPS Module, SIM800L GSM Module, Buzzer, Vibration Motor, Emergency Push Button.

**Software:** Embedded C/C++, Arduino IDE, TinyGPS++ Library, SoftwareSerial Library.

**Communication:** UART, GSM/SMS, GPS, Google Maps URL Integration.
