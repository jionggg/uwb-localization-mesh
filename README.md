# 🚀 Project Hub

Welcome to the **Location Intelligence** hub. This page links to all related repositories so you can quickly jump between them and understand how the pieces fit (embedded, mobile, and ROS if/when added).

---

## 📂 Repositories

| Repo | Scope / What it’s for | Link |
|---|---|---|
| **Embedded Firmware** | Low-level firmware for the hardware platform (sensors, control loops, comms) | 🔗 https://github.com/Hong-yiii/location_intelligence_embedded |
| **RPI Code** | iPhone-side code for interacting with Murata 2BP UWB module (control, testing, UX) | 🔗 TODO |
| **UWB Phone App** | iPhone-side code for interacting with Murata 2BP UWB module (control, testing, UX) | 🔗 https://github.com/Hong-yiii/Bang_and_olufsen_UWB_Testing |
| **Evals/Data Collections** | iPhone-side code for interacting with Murata 2BP UWB module (control, testing, UX) | 🔗 TODO |
| **MQTT Code** | MQTT Topics | https://github.com/anitej1/UWB-MQTT | 


---

## 🗺 Project Overview

This project is composed of three layers:

1. **Embedded** — Microcontroller firmware handling device I/O, timing, sensing, and protocol glue.
2. **Computational** — On the RPI-zero to convert raw distributed embedded data into useful readings on the network
3. **Mobile (iOS)** — App used to interact with the UWB module for testing

### Data Flow Diagram

![UWB preliminary data flow](assests/3301_preliminary_data_flow.drawio.png)
