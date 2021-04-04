---
title: 🚨 Alarm
category: Devices
order: 1
---

## Flows

| Trigger       | Conditions    | Actions | Devices |
|:------------- |:-------------:|:-------:| ------: |
| Motion detected | Alarm was armed and no guest is present | Send push notification<br>  | Motion Sensor |
| Motion detected downstairs hallway | Upstairs hallway zone is active and alarm is armed | Disarm the alarm | Motion Sensor |
| Motion detected upstairs hallway | Downstairs hallway zone is active and alarm is disarmed | Arm the alarm | Motion Sensor |

## Devices

| Purpose | Device | Description |
|:------- | :----- | :---------- |
| Motion Detection | Xiaomi Mi Occupancy Sensor | Detecting movement and marking an area or floor as active for a period of time |
