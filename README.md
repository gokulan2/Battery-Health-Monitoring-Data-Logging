# 🔋 Battery Health Monitoring & Data Logging using PIC16F877A

A real-time **Battery Health Monitoring and Data Logging System** built using the **PIC16F877A** microcontroller. The system continuously monitors critical battery parameters, detects abnormal operating conditions, and stores battery data with timestamps for future analysis. It is designed to demonstrate embedded system concepts such as ADC interfacing, sensor integration, EEPROM data storage, I²C communication, and LCD interfacing.

---

## 📌 Features

* Real-time battery voltage monitoring
* Battery temperature monitoring
* Continuous battery health tracking
* Automatic fault detection
* Data logging with date and time
* EEPROM-based non-volatile storage
* LCD display for live battery parameters
* I²C communication with RTC and EEPROM
* Embedded C firmware developed using MPLAB X IDE

---

## 🛠 Hardware Used

| Component                   | Description                 |
| --------------------------- | --------------------------- |
| PIC16F877A                  | Main Microcontroller        |
| LM35                        | Temperature Sensor          |
| Voltage Divider Circuit     | Battery Voltage Measurement |
| DS3232 RTC                  | Real-Time Clock             |
| 24LC256 EEPROM              | Data Storage                |
| 16×2 LCD                    | Display Module              |
| Crystal Oscillator (20 MHz) | System Clock                |
| Power Supply (5V)           | System Power                |

---

## 💻 Software Used

* MPLAB X IDE
* XC8 Compiler
* Proteus 8 Professional
* Embedded C

---

## 📂 Project Structure

```text
Battery-Health-Monitoring-Data-Logging/
│
├── Source_Code/
│   ├── main.c
│   ├── adc.c
│   ├── adc.h
│   ├── lcd.c
│   ├── lcd.h
│   ├── i2c.c
│   ├── i2c.h
│   ├── rtc.c
│   ├── rtc.h
│   ├── eeprom.c
│   └── eeprom.h
│
├── Proteus/
│   ├── Battery_Logger.pdsprj
│
├── Images/
│   ├── Circuit.png
│   ├── Simulation.png
│   ├── LCD_Output.png
│
├── Documentation/
│   └── Project_Report.pdf
│
├── README.md
└── LICENSE
```

---

## ⚙️ Working Principle

1. The PIC16F877A continuously samples the battery voltage through its built-in ADC.
2. The LM35 sensor measures the battery temperature.
3. The DS3232 RTC provides the current date and time for each measurement.
4. Battery parameters are displayed on the 16×2 LCD.
5. Each reading is stored in the 24LC256 EEPROM along with its timestamp.
6. Logged records remain available even after power is removed, enabling later analysis of battery performance and operating history.

---

## 📊 Logged Parameters

* Date
* Time
* Battery Voltage (V)
* Temperature (°C)
* Battery Status
* Fault Status (if detected)

---

## 📷 Project Images

Add the following images to the `Images` folder:

* System Block Diagram
* Circuit Diagram
* Proteus Simulation
* LCD Output
* EEPROM Data Logging
* Hardware Prototype (Optional)

---

## 🚀 Applications

* Battery monitoring systems
* UPS battery diagnostics
* Solar energy storage monitoring
* Industrial battery maintenance
* Educational embedded systems projects
* Data acquisition systems

---

## 🔮 Future Improvements

* SD Card data logging
* Bluetooth monitoring
* Wi-Fi/IoT dashboard
* PC data visualization
* State of Charge (SoC) estimation
* State of Health (SoH) prediction
* Mobile application integration

---

## 🎯 Learning Outcomes

* PIC16F877A Programming
* Embedded C Development
* ADC Interfacing
* I²C Communication
* RTC Integration
* EEPROM Data Logging
* LCD Interfacing
* Battery Monitoring Techniques

---

## 👨‍💻 Author

**Gokulan S**
Embedded Systems Engineer


---

## 📄 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it for educational and research purposes.
