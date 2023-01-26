---
title: "Jachère Solar Setup"
author: Adrian Demleitner
date: 2022-05-30
keywords:
	- solar
	- infrastructure
---
# Jachère Solar Setup
This entry outlines the current[^1] hardware setup of this tiny server. I wrote a bit about the software part under [Jachère Deployment and Publishing](notes/jachere-publishing.md). This setup works is rather small and was chosen to power a small server and some mobile devices. Bigger setups have to make different choices.

## Hardware in place
- [Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/)
- [Revolt 110W monocrystalline solar panel](https://www.revolt-power.de/Mobiles-Solarpanel-mit-monokristallinen-Solarzelle-NX-6199-919.shtml)
- [Revolt MPPT/Solar charge controller max 20A](https://www.revolt-power.de/Digital-Solar-Laderegler-20A-12V-24V-Auto-Switch--NX-6816-919.shtml)
- [Patona LiFePO4 battery 6000mAh](https://patona.de/patona-platinum-lifepo4-akku-batterie-ersatz-12v-6ah-72wh-6000mah-5974)

## Notes
All the hardware was quite cheap at the moment, especially the panel and the MPPT. The link to their products might break rather sooner than later.

A solar panel doesn't produce a stable output of power. That is why you'll need something like a MPPT or solar charge controller, which regulate that flow of power. Otherwise, your attached device get damaged and break. A MPPT usually does not work without a battery. 

Make sure, that your setup fits your needs. The solar panel should produce enough energy to load the battery and power your devices, for example a server, and maybe you also want to charge a mobile phone or so. The battery should hold enough energy during times without sun (nights and cloudy weather) to power the server. There are calculators[^2] around to help with that. I don't understand the concepts fully yet, but generally you need to know how much Ah or Wh your setup consumes. That is the amount of energy per hour. A Raspberry Pi 4 consumes 600mAh (6Ah) idling. My battery will be able to power this model for about 10h before it is empty.

The cables coming from the solar panel use the MC4 connector style. It's a connector system that is rainproof. I didn't know it and had to buy spare connectors in order to connect to the MPPT. I'm still not sure if I have the correct cables, but they were listed under solar equipment, so let's hope nothing burns down. 

![An electronic setup with a solar panel, a car battery, a little device called MPPT that regulates the power coming from the solar panel and a raspberry pi. All four are connected with red and black cables. The display of the MPPT shows 13V and the raspberry pi has a red LED lit up. ](/files/images/jachere-solar-setup.jpeg)

[^1]: 30th May 2022
[^2]: For example [https://spellfoundry.com/raspberry-pi-battery-runtime-calculator/](https://spellfoundry.com/raspberry-pi-battery-runtime-calculator/)
