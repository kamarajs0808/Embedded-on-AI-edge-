# Internship Project Submission

## Intern Details

**Intern Name:** Kamaraj S
**Intern ID:** CITS2534
**Project Title:** Embedded AI on Edge for Environmental Risk Prediction using ESP32

---

## Project Scope

The objective of this project is to develop an Embedded AI-based environmental monitoring system using ESP32 and DHT22 sensor. The system continuously monitors temperature and humidity values and performs local decision-making to classify environmental conditions into SAFE, WARNING, and CRITICAL states.

The project demonstrates the concept of Edge AI where data processing and decision-making are performed directly on the embedded device without relying on cloud services.

---

## Hardware Components Used

1. ESP32 Development Board
2. DHT22 Temperature and Humidity Sensor
3. Green LED
4. Yellow LED
5. Red LED
6. 220Ω Resistors
7. Breadboard
8. Jumper Wires

---

## Software Used

1. Wokwi Simulator
2. Arduino IDE
3. ESP32 Board Package
4. DHT Sensor Library

---

## Working Principle

The DHT22 sensor measures temperature and humidity from the environment. The ESP32 reads these values and applies predefined decision logic.

* SAFE Condition → Green LED ON
* WARNING Condition → Yellow LED ON
* CRITICAL Condition → Red LED ON

The complete analysis is performed locally on the ESP32, demonstrating Edge AI functionality.

---

## Output Obtained

### SAFE Condition

* Temperature = 25°C
* Humidity = 50%
* Green LED ON

### WARNING Condition

* Temperature = 32°C
* Humidity = 65%
* Yellow LED ON

### CRITICAL Condition

* Temperature = 38°C
* Humidity = 75%
* Red LED ON

---

## Results

The project successfully monitored environmental conditions and classified them into SAFE, WARNING, and CRITICAL states. The system provided real-time visual indications through LEDs and demonstrated the practical implementation of Edge AI using ESP32.

---

## Wokwi Project Link

https://wokwi.com/projects/465743812112265217

---

## Conclusion

The Embedded AI on Edge project was successfully designed and implemented using ESP32 and DHT22 sensor. The system performed local environmental analysis and classification without cloud dependency, making it suitable for smart monitoring and IoT applications.
