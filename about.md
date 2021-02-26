---
layout: page
title: About
sidebar_link: true
---

Aux (short for Auxiliary) is a line of internet-connected consumer electronics-inspired devices that collect and displays locally captured and internet queried data.

Aux requires and immense amount of research and prototyping. Along with the [Github repo]("https://github.com/thomascountz/aux") that stores various artifacts for the project (schematics, documentation, firmware, etc), this microfeed augments the project by creating a space for quick updates and ideas.

## Techical Details
### `PROTO 1` (Data Cube)

  Aux `PROTO 1` is driven by an ESP-WROOM-32 from Espressif and programmed via their Arduino-compatible library. It's a portable environmental sensor suite that communicates via MQTT.

  It measures temperature, humidity, CO2, TVOC, lux, noise levels, heart rate, and blood oxygen levels. Sensor data and real-time data queried through internet APIs are readable via a gesture-sensitive onboard OLED display. `PROTO 1`'s enclosure is built from FR4, most commonly used to build printed circuit boards.

  `PROTO 1`'s job is to monitor environmental conditions.

### `PROTO 2` (Wrist Watch)

  Aux `PROTO 2` is driven by an ESP-WROOM-32 from Espressif and programmed via their Arduino-compatible library. It's a smart watch that communicates via MQTT and BLE.

  Time is kept using a real-time clock and its output is readable via a gesture-sensitive OLED display. An onboard accelerometer allows `PROTO 2` to monitor activities, behaviors, and gestures. `PROTO 2`'s housing is built from FR4, most commonly used to build printed circuit boards.

  `PROTO 2`'s job is to tell time.
