# Homebridge
8/22/24

I don't think that I have explained my struggles with Homebridge yet on here. For some reason I really want all of my devices on Apple HomeKit and controlled by HomeKit because I really like the Apple ecosystem and UI. Here I will explain each plugin or accessory that I get connected to Homebridge and how and what struggles I have. Connecting my Homebridge to HomeKit is in another post.

Hue lights

plug and play, super easy

OpenRGB

I use iCUE to control macros for keyboard/mouse and was using iCUE for lighting too, but I wanted something that could also control lighting inside of the actual computer housing (headers, cpu lights, etc), something that was free, and something that could connect to Homebridge. Luckily someone was nice enough to make a OpenRGB to Homebridge plugin. I set up the OpenRGB to control the lights, hosted a SDK server in OpenRGB, connected the Homebridge plugin to it, and it worked. Only problem I kind of had was getting OpenRGB to boot but it ended up being super easy to set a trigger at login to set up and connect OpenRGB and its server.

Tuya

Tuya sucks. It's huge and can do everything you can imagine but it sucks.
