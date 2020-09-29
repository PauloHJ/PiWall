# PiWall - Configuration Guide

This tutorial has the intention of walking you through the necessary steps to successfully configure your PiWall, also known as a multiscreen application with Raspberry Pis. It's important to point out that this tutorial is based on the [PiWall](https://piwall.co.uk/) proyect developed by Alex Goodyear, Colin Hogben & Dr. Adam Stephen.

This simple guide is divided in 4 main sections:
- Materials
- Configuration
- Hardware Connections
- Displaying on screen

## Overview
PiWall is a smart solution developed in 2013 to configure a video wall. According to the Collins English Dictionary, a video wall can be defined as 
>multiple computer monitors, video projectors, or television sets tiled together contiguously or overlapped in order to form one large screen".

![Video wall example](https://hackaday.com/wp-content/uploads/2013/07/rpi-video-wall.png?w=876&h=522)

In this way, a PiWall must have a master computer/Raspberry Pi that is in charge of storing and distributing the video signal across the tiles of the video wall. Each tile has the job of displaying a part of the picture in its assigned screen. At the end, all the tiles together form a wall with a unique video playing.

## Materials

In order to build a PiWall some materials are required. It's important to point out that this guide describes the materials I used. However, it's possible to use different resources that provide the same or even better solution to the one stated in this guide. 

**HARDWARE**
-Raspberry Pi 3 Model B (1 master + _n_ tiles)*
    For each Raspberry:
        -Micro USB B Power Supply (2.5 A, 5.1 V)
        -Micro SD card (> 2 GB)
-Screens
-HDMI Cable (1 x _n_ screen)
-Wireless router

*For example, if your PiWall is 3x3 screens, then you'll need 1 RaspberryPi for each, plus 1 more for the master. 10 Raspberry Pi in total 
**SOFTWARE**


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

## WrapUp
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Contact

Please, if you have any trouble while configuring your PiWall, I´ll be glad to help, if possible. Don't hesitate to contact me at [paulo_hdez@outlook.com](mailto:paulo_hdez@outlook.com). 
