# QR Tag Project - Desktop Application (Qt)

## Overview
The desktop application provides the server-side management of game logic and a 3D representation of the game area.

## Installation Instructions
1. Install Qt and required tools:
sudo apt update sudo apt install qt5-default qtcreator build-essential

2. Generate the Makefile:
qmake server_desktop_app.pro make

3. Run the application:
./server_desktop_app

## Features
- Manage game settings and player connections.
- Display 3D visualizations of the game area.
