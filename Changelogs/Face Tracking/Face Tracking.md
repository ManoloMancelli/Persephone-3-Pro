# Persephone 3 Pro Face Tracking
Experimental Face Tracking for Persephone 3 Pro

## 27.01.2026
- Installed VRCFaceTracking on Steam
- Assembled Raspberry Pi Zero and webcam
- Installed [Project Babble](https://github.com/Project-Babble/ProjectBabble/releases/latest)
- Installef [Baballonia](https://github.com/Project-Babble/Baballonia/releases/latest)

## TODO
- Build a prototype with Raspberry Pi or Orange Pi


# References
## Reddit Face Tracking
![1](https://preview.redd.it/25-wireless-face-tracking-for-vrchat-v0-3l1nmbsj7roe1.jpg?width=1080&crop=smart&auto=webp&s=5b24ceb215b9999c73637b9cef15f088f9b3d75e)

#### Hardware
This is a solution I put together using cheap/3D printed hardware. No soldering or glue required.

- [Raspberry Pi Zero 2 W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/)
- [Arducam](https://a.co/d/dBf3rPP)
- [3D Files](https://www.thingiverse.com/)

#### All free and open source software used

- [Project Babble](https://docs.babble.diy/docs/intro)
- [VRFaceTracking](https://docs.vrcft.io/docs/vrcft-software/vrcft)

The build is incredibly simple, just slide the camera connector into the pi. And pop the components into their cases. I used some random screws in the mounts lol.

To slim it down you could use a more expensive 120-160 degree camera and lose the extended mount. And the Arducam actually comes with a shorter ribbon cable but I just don't have it on.

#### Software

The pi is streaming its video over the network to the Project Babble application. Babble then forwards this to VRChatFaceTracking.

