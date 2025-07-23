
# RFID and Keypad Based Security System 🔒

This project is a **microcontroller-based security system** that uses both **RFID technology** and a **keypad interface** to allow or restrict access. Designed as a part of our academic final year project, it showcases both hardware design and embedded system integration.

---

## 📌 Project Overview

The **RFID and Keypad Based Security System** is a dual-authentication security model that grants access only when:
1. A registered RFID tag is detected.
2. A correct password is entered via the keypad.

This dual-step approach enhances the security for restricted areas such as labs, doors, lockers, etc.

---

## 📷 PCB Layout

Key highlights visible on PCB:
- **ATMEGA328P** microcontroller as the brain of the system
- 4x4 matrix **Keypad** connector
- **RFID reader** header
- **Buzzer** for alert system
- **LEDs** for visual feedback
- Power regulation circuit and other components

---

## 📦 Components Used

- ATMEGA328P Microcontroller
- EM-18 RFID Reader
- RFID Tags
- 4x4 Keypad
- 16x2 LCD Display (optional)
- Buzzer
- LEDs
- Resistors, Capacitors, Switches
- 7805 Voltage Regulator
- Crystal Oscillator (16MHz)
- PCB Designed using EasyEDA

---

## ⚙️ Working Principle

1. System powers up and waits for RFID tag input.
2. If a valid RFID is detected, the keypad activates.
3. The user enters a numeric password.
4. If the password is correct, access is granted (e.g., a relay may be activated).
5. Invalid attempts trigger the buzzer.

---

## 👥 Team Members

- **Sameer Roshan** (19–21–25)  
- **Sushma** (19–21–26)  
- **G. Sathish** (19–21–27)  
- **Tanmay** (19–21–28)  

> Project submitted to: Central Institute of Tool Design (CITD)  
> Year: DARE – 2021 | Group-6

---

## 💡 Future Improvements

- Add GSM module for SMS alerts on invalid access
- Include a biometric module for 3-factor authentication
- Use an OLED screen instead of 16x2 LCD
- Store data logs on SD card

---


## 🖥️ Tools Used

- EasyEDA for PCB Design
- Arduino IDE (for code development)
- Proteus (for simulation)
- Soldering and testing hardware setup

---


## 🎥 Demo Video

https://drive.google.com/file/d/1lOz96UARif3ife1b1oXDjsadFlsFR274/view?usp=sharing

