# Persephone 3 Pro Face Tracking
Experimental Face Tracking for Persephone 3 Pro

## 27.01.2026
- Installed VRCFaceTracking on Steam
- Assembled Raspberry Pi Zero and webcam
- Installed [Project Babble](https://github.com/Project-Babble/ProjectBabble/releases/latest)
- Installed [Baballonia](https://github.com/Project-Babble/Baballonia/releases/latest)

#### - Baballonia seems to be more robust than Project Babble itself.

#### There is built-in support for eye tracking as well and GUI looks way better.

## 04.02.2026
- Bought the ESP32-CAM module
![1](/Changelogs/Face%20Tracking/img/04.02.2026/1.jpeg)

## 07.02.2026
- Desoldered the ESP32-CAM pins
![1](/Changelogs/Face%20Tracking/img/07.02.2026/1.jpeg)

- Connected ESP32-CAM to Arduino Uno Mini
![1](/Changelogs/Face%20Tracking/img/07.02.2026/2.jpeg)

- Installed the VSCode
- Installed Platformio IDE Extension under VSCode
- Downloaded Git For Windows
- Cloned OpenIris repo
- ### Using Arduino Uno Mini as programmer doesn't seem to work

## TODO
- Build a prototype using ESP32CAM
- Reverse-engineer the ESP32CAM board
- Prepare 3D files for the mount
- Add mounting points on the [Front Housing](/Changelogs/Front%20Housing/Front%20Housing.md)

#
#
#

## Lighting

#### For Project Babble, you can use either Infrared or visible light. Each has its advantages and considerations

### [Infrared Lighting](https://www.aliexpress.us/item/3256803759925241.html?)

- Less distracting as the light is not visible to the naked eye.

- Susceptible to flicker from base stations if not sufficiently bright

### [Visible Lighting](https://www.aliexpress.us/item/3256807891285585.html)

- Immune to base station flicker.

- Potential for distraction if the headset doesn't block light effectively.

## [USB HUB](https://www.aliexpress.com/item/3256804584900810.html)

## Wiring guide for Seeed XIAO ESP32-S3

- Either 3.3V or 5V can be used to power the LEDs.
- 3.3V is compatible with both USB and battery power.
- 5V can only be used when the ESP32 is powered via USB

### - Resistor Requirements

- For 3.3V power: Use 82-ohm resistors in series with the LEDs
- For 5V power: Use 160-ohm resistors in series with the LEDs

### - Wiring

![1](https://docs.babble.diy/assets/images/babbleWiringGuide-82d4c4148e31022efda3133f4f478d04.png)

## Camera

### - Recommended [OV2640 160° FOV IR / Night Version (850nm)](https://www.aliexpress.com/item/3256802853835121.html)

- Ideal for use with infrared lighting. firmware cropping is recommended.

### - Alternative [OV2640 120° FOV (Requires Manual IR Filter Removal)](https://www.aliexpress.com/item/3256804332354572.html)

- A solid choice, but you'll need to remove the IR filter if using infrared lighting.


## TODO
- Build a prototype
