# PalmGuard – Smart IoT Health Monitoring Locket

## Overview

PalmGuard is a wearable IoT-based health monitoring system designed in the form of a compact locket. It continuously tracks key vital parameters and provides real-time insights through a connected web dashboard and mobile interface.

The system focuses on making health monitoring simple, passive, and accessible without requiring constant user interaction.

---

## Problem

Most existing solutions either monitor limited parameters or require active user involvement. There is a lack of an affordable, compact device that can continuously track multiple health metrics and provide meaningful insights in real time.

---

## Solution

PalmGuard combines multiple sensors with an ESP32-based system to collect and process health data. The data is analyzed for abnormal patterns and then synced to a web platform where users can view their health status and history.

---

## Key Features

* Continuous monitoring of temperature, heart rate, and SpO₂
* Respiratory signal tracking using a MEMS microphone
* Real-time anomaly detection and alerts
* Web dashboard for live data and history
* Mobile app support
* Secure data transmission

---

## Tech Stack

**Hardware:**
ESP32, MAX30102, MLX90614, INMP441

**Software:**
Arduino (firmware), Web dashboard, Mobile interface

---

## System Workflow

Sensor data is collected through the wearable device and processed on the ESP32.
Basic anomaly checks are performed at the device level, and the data is then transmitted securely to the web application for visualization and tracking.

---

## Outcome

The project demonstrates a practical approach to continuous health monitoring using affordable hardware and a simple user interface, making it suitable for real-world usage and further development.

---

## Project Context

Developed as part of the BMSE Hackathon under the IoT healthcare domain.

---
# Palm-Guard-Smart-Health-Locket
Smart IoT-based wearable health monitoring system with mobile app and web dashboard for real-time tracking of temperature, heart rate, SpO₂, and anomaly detection.
