# Geyser Timer Switch

I'm using the [Astute Smart Controller (ASC)](https://cbi-lowvoltage.co.za/astute) from [[CBI-electric]]

The device uses the [[Tuya]] IoT platform so you can pair the device with the Tuya application.

The auto pairing didn't work for me, so I had to put the device in AP (Access Point) mode. This feature is not documented, but I found a usefull [post](https://powerforum.co.za/topic/7281-cbi-astute-smart-controller/page/4/#comment-100831) that describes the process.

- Hold the power button down for 5 seconds to put it in normal pairing mode
- Then hold the power button down again for 5 seconds to put it in AP pairing mode. The blue LED light will flash slowly
- Open the Tuya Smart application and manually add a device
- Select **Others** and then **Others (Wi-Fi)**
  ![[Tuya Smart App Add Other Device WiFi.png]]
- For the prompts and the device will be added
- It will show up as ASC (Wi-Fi) but you can rename it to something else