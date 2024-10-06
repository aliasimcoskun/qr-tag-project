# QR Tag Project - Location Tracking Module (ESP32)

## Overview
The ESP32 devices are used to track player positions in real-time using RSSI values and transmit this data to the game server.

## Installation Instructions
1. Install Arduino CLI:
curl -fsSL https://raw.githubusercontent.com/arduino/arduino-cli/master/install.sh | sh sudo mv bin/arduino-cli /usr/local/bin/

2. Set up the ESP32 board:
arduino-cli config init arduino-cli config set board_manager.additional_urls https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json arduino-cli core install esp32

3. Compile and upload the code:
arduino-cli compile --fqbn esp32:esp32
scanner.ino arduino-cli upload --port /dev/ttyUSB0 --fqbn esp32:esp32
scanner.ino

## Features
- Real-time player position tracking.
- Data transmission to the game server for visualization.
