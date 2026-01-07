# Persephone 3 Pro Face Tracking
Experimental Face Tracking for Persephone 3 Pro

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

You need a micro-usb power source for the raspberry pi, I'm assuming anyone with a wireless PCVR setup has a battery for/on their headset which is what I have mine plugged into.

To slim it down you could use a more expensive 120-160 degree camera and lose the extended mount. And the Arducam actually comes with a shorter ribbon cable but I just don't have it on.

#### Software

The face tracking shown is not calibrated, just what I got when putting on the headset today.

The pi is streaming its video over the network to the Project Babble application. Babble then forwards this to VRChatFaceTracking.

Everything said and done, I'm very happy with the performance and latency and plan to continue daily driving this in VRChat.

#### Keep in mind

Forgive me if someone has posted something similar to this before, the only thing similar to this I've seen on this subreddit has been a closed source custom PCB for Babble.

Some of the parts differ in price depending on the vendor.

Depending on your particular setup you may have better or worse results than I do.
If people are interested I'll post the code & thingiverse models I used.







## Face Tracking no. 1
- Find a suitable, small camera
- Build a prototype with Raspberry Pi or Orange Pi
