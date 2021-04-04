---
title: 🧊 Cube Control
category: Devices
order: 1
---

## Flows

| Trigger       | Conditions    | Actions | Devices |
|:------------- |:-------------:|:-------:| ------: |
| Cube rotated clockwise | Rotation angle is more than 60° | Increase volume of the TV | Cube Control |
| Cube rotated counter-clockwise | Rotation angle is more than 60° | Decrease volume of the TV | Cube Control |
| Knock cube twice | none | (un)mute the TV | Cube Control | 
| Shake Cube | cube_shake_timer countdown is not running | Start cube_shake_timer countdown for 3 seconds | Cube Control |
| Shake Cube | cube_shake_timer countdown is running | Play Next on the TV | Cube Control |

## Devices

| Purpose | Device | Description |
|:------- | :----- | :---------- |
| Cube Control | Xiaomi Aqara Magic Cube | Trigger events using a small cube |
