# ARLAN (Atmega32u4 + W5500 Network Security Tool)

A controlled research project focused on network visibility, ARP behavior analysis, and defensive network security experimentation using embedded hardware.

---

## 📌 Overview

ARLAN is an embedded network security platform built on:

- **Atmega32u4**
- **W5500 Ethernet Controller**

The project is designed for:

- Network scanning research
- ARP protocol behavior analysis
- Controlled ARP spoofing simulation (lab environment only)
- USB HID-based security experimentation

This repository documents hardware design, firmware, and defensive research methodology.

---

## 🧠 Project Objectives

- Study ARP protocol mechanics in local networks
- Understand MITM attack surfaces at Layer 2
- Evaluate defensive detection methods
- Explore embedded Ethernet-based security tooling
- Develop a compact red-team research device for controlled environments

---

## 🛠 Hardware Architecture

### Core Components

- **MCU:** Atmega32u4 (USB HID capable)
- **Ethernet:** W5500 SPI-based Ethernet controller
- **Interface:** RJ45
- **Communication:** SPI
- **Power:** 5V USB

### Hardware Features

- Ethernet-based packet manipulation
- USB HID support
- Visual indicators (LED status)
- Compact PCB design

Gerber files and PCB production files are available under:

