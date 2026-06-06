# Panasonic VT60 HTPC Project

## Overview

This project aims to transform an old Dell Inspiron 3000 laptop into a dedicated Home Theater PC (HTPC) for a Panasonic TH-P65VT60M plasma television.

The original laptop had a failing display and was no longer practical as a portable computer. Instead of discarding it, the system is being repurposed into a custom-built media center with a compact aluminum-and-wood enclosure.

The primary goal is to provide a reliable and easy-to-use living room media experience for streaming services, local media playback, and future expansion.

---

## Hardware

### Base System

* Dell Inspiron 3000 series laptop
* Intel Core i5 processor
* 8 GB DDR3 RAM
* Kingston HyperX 240 GB SSD
* Integrated Intel HD Graphics 5500
* NVIDIA GeForce 820M (currently unused)
* Wi-Fi and Bluetooth module

### Custom Enclosure

* Aluminum chassis
* Wooden outer frame
* Large 120 mm intake fan
* Removable top cover for easy servicing
* Custom I/O panel
* Dust filter
* Custom power switch interface

---

## Current Features

* Linux Mint installed
* System fully operational
* SSH remote administration
* Firefox configured for streaming services
* Kodi media center installed
* VLC media player installed
* Network media access through router-based NAS
* Static IP reservation on local network
* Custom aluminum enclosure completed and operational

---

## Design Goals

### Reliability

The system should be easy to maintain and repair.

The enclosure is designed so that the complete computer can be removed from the case by removing only a few screws while remaining largely assembled.

### Quiet Operation

The system uses the original laptop cooling system and is being upgraded with additional low-noise cooling.

### Expandability

Future upgrades may include:

* ESP32 system controller
* Fan monitoring and control
* IR receiver
* HDMI-CEC integration
* Bluetooth remote control
* Additional USB ports
* Status LEDs

### Living Room Experience

The HTPC is intended to function as a dedicated appliance rather than a general-purpose computer.

Planned improvements include:

* TV-friendly user interface
* Remote-control operation
* Direct access to streaming services
* Integrated media library through Kodi

---

## Current CAD Components

### Planned Models

* Lid skirt
* Power jack holder
* Wireless card mount

All CAD work is performed using FreeCAD.

---

## Future Work

### Hardware

* Complete custom power switch wiring
* Install Wi-Fi/Bluetooth antennas
* Install Noctua cooling fan
* Design and print remaining internal brackets
* Finalize top cover attachment method

### Electronics

* ESP32 integration
* Fan control
* Status LED control
* TV control integration

### Software

* Kodi library integration
* Remote control support
* TV automation
* Additional streaming shortcuts

---

## Project Philosophy

This project is based on reusing existing hardware whenever practical.

Many components originate from salvaged equipment, including the original laptop hardware and recycled PC components. The objective is to create a capable and maintainable HTPC while minimizing cost and electronic waste.

---

## Status

Current state: **Operational and in daily use**

The system is already capable of streaming media, playing local content, and serving as a living room HTPC while development continues.
