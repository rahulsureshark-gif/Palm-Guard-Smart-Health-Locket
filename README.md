# PalmGuard – Smart IoT Health Monitoring Locket

## Overview

PalmGuard is a wearable IoT-based health monitoring system designed as a compact locket. It continuously tracks essential health parameters and provides real-time insights through a connected web dashboard and mobile application.

---

## Problem

Most health monitoring solutions either track limited vitals or require manual interaction. There is a need for an affordable and compact system that can continuously monitor multiple health parameters.

---

## Solution

PalmGuard integrates multiple sensors with an ESP32-based system to collect and process health data and sync it to a web platform.

---

## Key Features

* Continuous monitoring of temperature, heart rate, and SpO₂
* Respiratory signal tracking
* Real-time anomaly detection
* Web dashboard + mobile app
* Secure data transmission

---

## Tech Stack

Hardware: ESP32, MAX30102, MLX90614, INMP441
Software: Arduino, Web App, Capacitor

---

## Run the Project

Clone repo:
git clone https://github.com/rahulsureshark-gif/Palm-Guard-Smart-Health-Locket.git

Go to folder:
cd Palm-Guard-Smart-Health-Locket

Install:
npm install

Run:
Open www/index.html in browser
(or use Live Server)

---

## Build Android App (Capacitor)

Install:
npm install @capacitor/core @capacitor/cli

Init:
npx cap init

Add Android:
npx cap add android

Copy files:
npx cap copy

Open Android Studio:
npx cap open android

Run from Android Studio ▶️

---

## Project Context

BMSE Hackathon – IoT Healthcare

---

## Author

Rahul B S
