# IoT-Based Smart Home Network Monitoring System

## Project Overview
This project designs an IoT system that monitors home network traffic and device activity using a Raspberry Pi or ESP8266.

## Features
- Monitor connected devices & network traffic
- Visualize network activity in real-time dashboards
- Cloud integration with AWS IoT
- CI/CD pipeline for firmware updates

## Tech Stack
- MQTT (for IoT communication)
- Node-RED (for data processing)
- Python (for scripting)
- InfluxDB & Grafana (for storage and visualization)

## DevOps Practices
- Cloud integration (AWS IoT)
- CI/CD for firmware updates

## Installation
1. Install dependencies: `pip install paho-mqtt influxdb-client`
2. Configure InfluxDB and MQTT settings in `mqtt_listener.py`
3. Run the script: `python mqtt_listener.py`

## Author
Created by ChatGPT
