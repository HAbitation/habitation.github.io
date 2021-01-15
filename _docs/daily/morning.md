---
title: 🌞 Morning
category: Daily
order: 1
---

## Flows

| Trigger       | Conditions    | Actions | Devices |
|:------------- |:-------------:|:-------:| ------: |
| Motion detected in the downstairs hallway | While motion was detected in the upstairs hallway within the last minute | Turn off the alarm<br>Turn on the lights when the light sensitivity is below a certain threshold | Motion Detection<br> Light Sensor
| When it's 08:30 | It's a working day and I'm home | Turn on the heating in my home office | Smart Radiator Valve |

## Devices

| Purpose | Device | Description |
|:------- | :----- | :---------- |
| Motion Detection | Xiaomi Mi Occupancy Sensor | Detecting movement and marking an area or floor as active for a period of time |
| Presence Detection | Any network-based tool, for Homey you can use [NetScan](https://homey.app/nl-nl/app/nl.terryhendrix.netscan/Net-Scan/) | Presence based on IP availability of your phone |
| Smart Radiator Valve | TADO Smart Radiator Thermostat | Multi-room heating system |
| Light Sensor | Xiaomi Mi Light Sensor | Measuring light intensity in LUX |
