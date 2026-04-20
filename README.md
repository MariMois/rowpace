# RowPace 🚣‍♂️

A lightweight, mobile-first rowing metronome and training companion designed to help rowers maintain consistent stroke rates and master rate-change progressions.

[**Live Demo**](https://marimois.github.io/row-pace/)

## ✨ Features

* **Dynamic RPM Progression**: Automatically increases your stroke rate by +2 RPM every 2 minutes, helping you build intensity throughout your workout.
* **Smart Progression Tooltip**: Real-time feedback during setup that tells you if your selected time fits the RPM range perfectly or if it will hold at the max rate.
* **Warmup & Cooldown**: Optional, customizable phases to prepare your body and recover properly.
* **Visual Stroke Indicator**: A high-precision "boat" slider that visualizes the catch, drive, and recovery phases perfectly synced to your target RPM.
* **Audio Feedback**:
  * Metronome "catch" sounds for timing.
  * Distinct transition sounds when changing rates or phases.
  * Final 5-second countdown beeps to get you ready.
* **Session History**: Track your past workouts locally on your device.
* **Mobile Optimized**: Responsive design that works in portrait or landscape, featuring a "Wake Lock" to prevent your screen from dimming during a row.
* **Single-File Architecture**: No complex installation—runs entirely from a single `index.html`.

## 🛠 Setup & Usage

### How to use
1. Set your **Start RPM** (baseline) and **Max RPM** (peak).
2. The app will automatically calculate the **Total Duration** required to fit that progression.
3. Toggle the **Warmup** and **Cooldown** sliders to your preference.
4. Hit **Start Workout** and follow the 10-second countdown.

### Installation for personal use
Since this is a single-file application, you don't need to install anything.
* Simply download `index.html`.
* Open it in any modern web browser.
* (Optional) "Add to Home Screen" on iOS or Android to use it like a native app.

## 🧮 Progression Logic
RowPace uses a "2+2" logic by default:
* Every **2 minutes**, the target rate increases by **2 RPM**.
* Each 2-minute block is split into:
  * **1 Minute: Low Steady** (Maintain the base rate for that block).
  * **1 Minute: Hard Drive** (Maintain the same rate but with increased power/intensity).

## ☕ Support
If you find this tool helpful for your training, consider supporting the developer:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/G2G41N6HQ1)

## 📄 License
This project is open-source and available under the MIT License.
