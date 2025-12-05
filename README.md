# SMART-IOT-BASED-AUTOMATIC-PET-FEEDER-SYSTEM
A simple IoT system that automates pet feeding using NodeMCU ESP8266, ultrasonic sensor, servo motor, and a web-based control interface. The system dispenses food at scheduled times and monitors food levels in real-time.

# 📌 Features

•Automatic feeding at scheduled times

•Real-time food level monitoring (ultrasonic sensor)

•LED alerts

•Steady light: Food enough

•Blinking: Food low/empty

•Web interface (set feeding times, view status)

•Wi-Fi enabled remote control

•Sensor retry mechanism for accurate readings


# ⚙️ How It Works

1.NodeMCU connects to Wi-Fi

2.Ultrasonic sensor reads food height

3.LED indicates food status

4.Servo dispenses food at scheduled times

5. User can update feeding times through a simple web page

# 🖥️ Main Functionalities

✔️ Food Level Detection

< 15 cm → Enough

> 15 cm → Low / Empty

✔️ Feeding Schedule

Default hours → 9, 13, 20

User can update via web form

✔️ Web Interface

Shows:
•Food level (cm)

•Status message

•Form to update feed times


# 📥 Code

All core logic is written in Arduino C++ for ESP8266.

Includes:

•WiFi connection

•Web server routes

•NTP (time sync)

•Servo control

•Ultrasonic reading

•LED alert logic

# 📌 Limitations

•NodeMCU cannot power servo + sensor alone → requires Arduino power

•Depends on stable Wi-Fi

•Breadboard wiring not ideal for long-term use

# 📘 Credits
This project was developed for:KD34303 – Internet of Things (IoT)
