AI-Based Oxygen Level Detection System for Room Heaters
A smart safety system to prevent oxygen depletion & gas hazards during winter heater usage.
🧠 AI Monitoring Dashboard

🌡️ Sensor Module Prototype

📱 Mobile Alert System

📘 Project Overview

During winter, room heaters often run in closed spaces. This leads to:

❌ Drop in indoor oxygen

❌ Buildup of CO₂ and CO

❌ Poor ventilation

❌ Risk of dizziness, suffocation, or CO poisoning

Your project solves this by building a real-time AI-powered air quality monitoring system that detects hazardous conditions and automatically reacts.

The system details (described in your uploaded PDF 

AI based oxygen level detectio…

) were transformed into a functioning engineering project below.

✨ Key Features
🧪 Real-time Air Quality Sensing

Oxygen (O₂) monitoring

CO₂ monitoring

CO (carbon monoxide) detection

Room temperature & humidity

🤖 AI Model for Prediction

Detects unusual patterns

Predicts oxygen drop before it becomes dangerous

Detects faulty heater combustion

⚙️ Automated Safety Actions

Turns ON ventilation fans

Alerts user instantly

Can shut off heater automatically

AI learns your room patterns over time

📱 Mobile App Integration

Live sensor values

Push notifications for unsafe conditions

Air quality history & graphs

🏗️ System Architecture

Based on diagrams & components described in the invention document (pages 8–11) 

AI based oxygen level detectio…

Sensors (O₂, CO₂, CO, Temp, Humidity)
           │
           ▼
     ESP32 Microcontroller
           │
           ▼
  AI Processing (Python/Edge ML)
           │
 ┌─────────┴─────────┐
 │                   │
 ▼                   ▼
Mobile Alerts     Heater Control
Ventilation Control

🧱 Hardware Components
Component	Purpose
MQ-135 / CO₂ Sensor	Detects CO₂ levels
CO Sensor (MQ-7)	Detects carbon monoxide
O₂ Sensor (Electrochemical)	Measures room oxygen percentage
ESP32 / Arduino	Reads sensors, connects WiFi
DHT22	Temperature & humidity
Relay Module	Controls heater and ventilation
Buzzer / LED	Local alerts

(Sensor list referenced from pages 8–9 in your PDF) 

AI based oxygen level detectio…

🧠 AI & Software
Machine Learning Tasks

Predict oxygen depletion trend

Detect abnormal CO/CO₂ spike

Alert before danger, not after

Tools Used

Python

NumPy, Pandas

Scikit-Learn / TensorFlow Lite

Firebase / MQTT for app communication

📲 Mobile App Features

Live oxygen level display

CO/CO₂ alerts

Warning history

Remote ventilation/heater control

🧪 How It Works (Step-by-Step)

According to the workflow diagram on Page 11 

AI based oxygen level detectio…

Sensors collect oxygen, CO₂, CO, temp & humidity.

Data goes to microcontroller → AI processing.

AI checks if values are normal or dangerous.

If unsafe → ventilation activates and heater adjusts.

Alerts sent to mobile app.

AI updates itself from new data.

📈 Why This System is Needed

According to the problem description (pages 3–4) 

AI based oxygen level detectio…

:

Heaters consume oxygen → air becomes unsafe

People close windows → no ventilation

CO gas can kill silently

No existing system monitors all gases + controls heater

This project solves all these issues in one integrated setup.

🚀 Project Status

✔ Concept Approved
✔ Full architecture designed
✔ AI workflow defined
✔ Sensors & logic validated
❌ Mobile app final UI pending
❌ Hardware prototype build in progress

🗺️ Future Improvements

Add battery backup

Build native Android/iOS app

Integrate with smart home systems

Add cloud-based analytics dashboard
