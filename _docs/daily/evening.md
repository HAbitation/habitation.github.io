---
title: 🌅 Evening
category: Daily
order: 3
---

## Flows

| Trigger       | Conditions    | Actions | Devices |
|:------------- |:-------------:|:-------:| ------: |
| When my girlfriend goes to bed | My office lights are on and the TV downstairs is off | Turn off the lights and heating downstairs | Smart Plug |
| When my office lights are turned on | It is evening/night, my girlfriend is asleep and the TV downstairs is off | Turn off the lights and heating downstairs | TV State Detection |
| When it becomes 23:00 | My girlfriend is asleep, my office lights are on and the TV downstairs is off | Turn off the lights and heating downstairs | Smart Thermostat |

## Devices

| Purpose | Device | Description |
|:------- | :----- | :---------- |
| Smart Plug | INNR SP-120 | Keeping track of power consumption to check whether a phone is charging |
| TV State Detection | Network Based detection | Keeping track of the TV's state based on ICMP ECHO response |
| Smart Thermostat | TADO Smart Control | Multi-room heating system |
