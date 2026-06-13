# IoT-Enabled Smart Agriculture Monitoring System

An automated edge-to-cloud telemetry tracking and precision irrigation system built on an ESP32 architecture. This project uses non-blocking control loops to automate farm resources locally while streaming time-series field analytics directly to a cloud dashboard over a virtual Wi-Fi network.

## 📌 Problem Statement
Traditional agricultural practices rely heavily on manual field inspections or static automated timers. This often results in major water waste due to over-irrigation, or delayed reactions to sudden, damaging heatwaves. 

This project solves these issues by establishing a continuous, automated cyber-physical system. It monitors microclimate fluctuations and soil profiles in real-time, automatically running irrigation pumps only when crops need water, minimizing resource waste.

## 🛠️ System Features
- **Multi-Sensor Acquisition Matrix:** Tracks ambient temperature, humidity, and soil moisture levels simultaneously using digital and analog input mapping.
- **Edge Automation Loop:** Runs a localized control routine to automatically toggle an irrigation pump relay without relying on active internet connectivity.
- **Hysteresis Implementation:** Built-in software logic boundaries prevent rapid, high-frequency relay clicking when sensor readings hover close to threshold limits.
- **Live Cloud Synchronization:** Connects via standard network protocols to stream time-series sensor logs to an online dashboard every 15 seconds.

## 🎛️ System Architecture
