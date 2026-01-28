# Persephone 3 Pro Face Tracking
Experimental Face Tracking for Persephone 3 Pro

## 27.01.2026
- Installed VRCFaceTracking on Steam
- Assembled Raspberry Pi Zero and webcam
- Installed [Project Babble](https://github.com/Project-Babble/ProjectBabble/releases/latest)
- Installef [Baballonia](https://github.com/Project-Babble/Baballonia/releases/latest)

#### - Baballonia seems to be more robust than Project Babble itself.

#### There is built-in support for eye tracking as well and GUI looks way better.


## Hardware

### - Recommended - [XIAO ESP32-S3 Sense Modules]()

- Compact size with both wireless and wired support.

- No need for an additional programmer or separate antennas.

### - Alternative - [Freenove ESP 32-S3 WROOM]()

- Slightly larger and potentially more expensive than the XIAO.

- Supports both wired and wireless connections.

- Does not require a separate programmer
  
-Lacks support for an external antenna.

### - Budget - [ESPCAM32 Modules]()

- A more affordable choice.
  
- Requires a separate programmer board for flashing firmware.

- Supports only wireless streaming.
  
- May need soldering to attach external antennas.

## Lighting

#### For Project Babble, you can use either Infrared or visible light. Each has its advantages and considerations

### Infrared Lighting:

- Less distracting as the light is not visible to the naked eye.

- Susceptible to flicker from base stations if not sufficiently bright

### Visible Lighting:

- Immune to base station flicker.

- Potential for distraction if the headset doesn't block light effectively.

## TODO
- Build a prototype with Raspberry Pi or Orange Pi
