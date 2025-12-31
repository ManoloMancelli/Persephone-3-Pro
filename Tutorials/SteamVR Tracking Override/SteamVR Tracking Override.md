# SteamVR Tracking Override Tutorial
A simple way to make any kind of DiY VR device work with Lighthouse tracking via adding a SteamVR tracked device

- #### This method is fully working in time of writing this tutorial (SteamVR build 21281713)

## PC Setup
- Install all of the latest Windows updates
- Install Steam Windows App
- Install SteamVR

## SteamVR Setup
- Connect your VR headset and make sure it works properly
- Go trough the Room Setup
- Connect the SteamVR Dongle and pair the tracker
- In SteamVR go to Devices -> Manage Trackers

![1](/Tutorials/SteamVR%20Tracking%20Override/img/0.png)

- Make sure your tracker has a green dot next to it

![1](/Tutorials/SteamVR%20Tracking%20Override/img/1.png)

- Click on the "Tracker Role" and select "Disabled"

![1](/Tutorials/SteamVR%20Tracking%20Override/img/2.png)

- Write down the tracker name

![1](/Tutorials/SteamVR%20Tracking%20Override/img/3.png)

## Tracking Override
- Close SteamVR if it's running
- Go to C:\Program Files (x86)\Steam\config
- Open steamvr.VRSETTINGS file with text editor (notepad is fine)
- Add below text to the file

```
   "TrackingOverrides" : {
      "/devices/htc/vive_trackerLHR-F7DF1BC6" : "/user/head"
```
