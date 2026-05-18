+++
title = "FreshAirIoT: ESP32 Air Quality Monitoring"
description = "Building an IoT air quality monitoring system with environmental sensors and real-time dashboards"
date = 2024-06-26
tags = ["IoT", "Embedded Systems", "ESP32"]
categories = ["projects"]
+++

# FreshAirIoT: IoT Air Quality Monitoring System

FreshAirIoT is a comprehensive air quality monitoring solution built on ESP32/8266 microcontrollers, combining real-time sensor data collection with cloud connectivity and user-friendly dashboards.

## What It Does

The system monitors environmental metrics (CO₂, PM2.5, temperature, humidity) from multiple sensor nodes and streams data via MQTT to a central aggregation point. Real-time alerts are sent through Telegram when thresholds are exceeded, and historical data is visualized through Node-RED dashboards.

## Technologies Used

- **Hardware:** ESP32, ESP8266, BME680 (environmental), PMS5003 (particulate)
- **Communication:** MQTT, WiFi, Telegram Bot API
- **Visualization:** Node-RED, JSON time-series data
- **Languages:** C++ (firmware), Python (backend services)

## Key Achievements

- **Low-power operation:** Optimized deep sleep cycles for battery-powered sensors
- **Reliable MQTT:** Implemented connection resilience with automatic reconnection
- **Scalable architecture:** Supports multiple sensor nodes reporting to single broker
- **User notifications:** Smart alerting prevents notification fatigue while catching critical events

## Why It Matters

Indoor air quality directly impacts health and productivity. FreshAirIoT enables data-driven decisions about ventilation, air purification, and occupancy patterns—critical for modern smart homes and offices.

## GitHub

[github.com/MaxBubblegum47/freshairiot](https://github.com/MaxBubblegum47/freshairiot)
