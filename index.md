---
title: Introduction
---

This website has been created to inspire people interested in **Home Automation** with ideas to implement into their homes. It is heavily based on my own home automation that I have been working on for the last 3 years.

Browse through the different categories in the menu on the left to see what I have created and let this inspire you to improve your own home automation.

### My Home Automation Principles

I build my home automation (HA) in a way that tasks in and around your house are automated while human interaction is removed or at least reduced.

HA should detect a broad variety of events and act upon it in a desirable, predictable and natural fashion.

In addition, HA should not only help you in your day-to-day activities by performing certain tasks, but also notify events from happening.

Since any type of automation comes with its fair amount of bugs and also down time is often inevitable, manual controls for important functions should always remain possible as a redudant or failover measure.

Voice controlled features are often mentioned when it comes to HA, however even though it is a nice addition, also voice commands should be limited and only used for ad-hoc commands that cannot be predicted.

While working out any type of automation, the risk of introducing a fire hazard should be taken into account, especially when using devices from companies or countries with less strict safety guideliness.

And finally, HA can be used to improve the security of your house, but should never in any circumstance be able to weaken its security.

### Choice of wireless protocols

Wireless protocols that I make use of:
- Zigbee
- Z-Wave
- Wi-Fi

I try to avoid the following protocols, since they are generally considered insecure:
- 433mhz
- Infrared (IR)

In the future I might use the following protocols:
- Bluetooth Low Energy (BLE)
- Near-Field Communication (NFC)

### Type of devices

#### Homey
The heart of my HA is controlled by Athom's Homey. Homey's strength lies in its:
- wide variety of sensors
- stable and intuitive interface both via the web as the mobile app 
- a community driven app store supporting a large number of devices and services.

Open source solutions such as Home Assistant or Domoticz are cheaper and more flexible solutions, however my experience with these solutions is that it is a bit more hacky and less stable. 

With my current level of automation I prefer a stable and reliable platform. In some cases this limits your possibility or requires you to take the extra mile of developing something yourself since the community of Homey is smaller.

#### Fibaro switches
I use Fibaro built-in switches to remain the possibility of manually switching a light but also remotely control the on/off state, brightness and read power usage

#### Xiaomi sensors
Xiaomi offers a large number of very cheap sensors using the Zigbee protocol to provide you insights of events and behaviour in and around you house.
Different sensors that I use:
- Light sensor
- Occupancy sensor
- Room/window sensor
- Temperature/Humidity sensor

And in addition I use the cube controller as a simple device to manually trigger an action.

#### INNR smart sockets
I use INNR SP-120 smart sockets not only to be able to remotely switch a device on/off but mainly to use it as a sensor by measuring the power consumption of the attached device.

#### TADO smart thermostat
TADO has replaced my Nest thermostat since it supports multiroom heating. Even when my thermostat has reached the targetted sensor, it can be triggered to fire up the boiler based on a TADO smart radiator valve not meeting its targetted temperature yet.

#### IKEA Tradfri
Cheap and simple smart light bulbs. However manual control is limited as with all smart light bulbs.

#### Shelly
Wi-Fi based relay using REST API's to read and control the on/off state of lights, but also usefull to create your own [smart doorbell](/devices/doorbell/).

#### Other
I use some other devices for entertainment purposes or to collect data about my house, such as:

- Google Home Mini / Chromecast / Nest Audio in combination with Google Assistant used as smart speakers or castable devices
- P1 smartmeter reader to read power and gas consumption of my smart meter
- Envoy S Metered (Solar Panel) to read power yield
