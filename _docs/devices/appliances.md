---
title: 🧺 Appliances
category: Devices
order: 1
---

## Flows

| Trigger       | Conditions    | Actions | Devices |
|:------------- |:-------------:|:-------:| ------: |
| Power consumption of dryer changed | Power consumption is higher than 50 | Set "dryer running" variable to TRUE | Smart Plug |
| Power consumption of dryer changed | Power consumption is lower than 2 and "dryer running" variable is TRUE | Send push notification | Smart Plug |
| Power consumption of washing machine changed | Power consumption is higher than 50 | Set "washing machine running" variable to TRUE | Smart Plug |
| Power consumption of washing machine changed | Power consumption is lower than 2 and "washing machine running" variable is TRUE | Send push notification | Smart Plug |

## Devices

| Purpose | Device | Description |
|:------- | :----- | :---------- |
| Smart Plug | INNR SP-120 | Keeping track of power consumption to check whether a phone is charging |
