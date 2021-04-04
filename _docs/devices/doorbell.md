---
title: 🚪 Doorbell
category: Devices
order: 1
---

I do not necessarily want to video record my front yard and definitly not want to store the footage in the cloud owned by a third party. The alternative "smart" doorbells typically use 433Mhz frequency which are typically not that secure and replaying the messages is fairly easy.
So I decided to make my current doorbell "smart".

The doorbell is a normally wired doorbell consisting of a transformer to turn 230V to 12V, a wire going to the outside doorbell and subsequently to the chime that rings the bell when the circuit is closed by pressing the doorbell.

I have followed the following [tutorial](https://www.vincenzocaputo.com/guide/door-bell-smart-shelly1-per-un-campanello-remoto-380) to connect a Shelly 1 to my existing setup. The Shelly simply monitors when the circuit is closed by a doorbell being pressed using the switch function. The Shelly is then configured to perform a REST API GET request towards my Homey to handle the event.

## Flows

| Trigger       | Conditions    | Actions | Devices |
|:------------- |:-------------:|:-------:| ------: |
| Doorbell was pressed | None | Send push notification and disable flow for 1 minute to prevent spamming<br/> Blink the lights in my home office | Shelly 1 |

## Devices

| Purpose | Device | Description |
|:------- | :----- | :---------- |
| Shelly 1 | Shelly 1 | Monitoring when the circuit is closed when the doorbell has been pressed |
