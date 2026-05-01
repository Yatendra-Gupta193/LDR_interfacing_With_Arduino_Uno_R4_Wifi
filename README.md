# LDR Interfacing with Arduino Uno R4 WiFi

![Platform](https://img.shields.io/badge/platform-Arduino-orange)
![Language](https://img.shields.io/badge/language-C++-blue)

This is a simple *IoT experiment* to interface an *LDR (Light Dependent Resistor)* with *Arduino Uno R4 WiFi*.

---

## Project Description

In this project, an *LDR sensor* is used to measure the *light intensity*.  
The Arduino reads the analog value from the LDR and displays it on the *Serial Monitor*. 

This experiment helps beginners understand:
- Analog input
- Sensor interfacing
- Light intensity measurement

---

## 🧰 Components Used

- Arduino Uno R4 WiFi  
- LDR (Light Dependent Resistor)  
- 10kΩ Resistor  
- Breadboard  
- Jumper Wires  

---

## 🔌 Pin Connections

| Component | Arduino Pin |
|---------|-------------|
| LDR Output | A0 |
| Resistor  | GND |
| VCC       | 5V  |

---

## 💻 Code Explanation

- analogRead() is used to read light intensity from LDR  
- The value changes according to *light and darkness*  
- Serial.print() is used to display values on Serial Monitor  

---

## 📟 Output

- High value in *bright light*  
- Low value in *darkness*  
- Real-time light intensity values on Serial Monitor
