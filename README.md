# 3D Facility Monitor — Node-RED Dashboard

A real-time change detection dashboard built with Node-RED.
Monitors distance sensor readings across 5 points in a facility
and alerts when any point moves beyond a 10cm threshold.

## Features
- Live scanning every 5 seconds
- Automatic baseline establishment on first scan
- Visual alerts when changes are detected
- Scrollable change event log with timestamps
- Reset baseline button

## How to use
1. Install Node-RED
2. Install node-red-dashboard
3. Import flows.json via Menu → Import
4. Deploy and open /ui in your browser

## To connect real sensors
Replace the "Simulate 5 sensor points" function node
with your actual sensor input (MQTT, HTTP, serial, etc.)
The rest of the flow works without any changes.

## Built with
- Node-RED
- node-red-dashboard
- JavaScript
