---
layout: project
title: "Tracked Armband"
description: "VR Armband"
folder_name: "armband"
gallery_images:
  - protoa3a.webp
  - protoa3b.webp
  - protoa3c.webp
  - proto3demo.webp
  - protoa3j.webp
  - proto3jj.webp
  - protoa3k2.webp
  - protoa3s.webp
  - protoa3ynoimu2.webp
  - protoa3z.webp
  - protoa3x.webp
  - protoa3v.webp
  - protoa3z2.webp
  - protoa3z11.webp
  - divenodesnew11.webp
  - divenodesnew12.webp
  - protoa2a.webp
  - protoa2b.webp
  - protoa2f.webp
  - protoa2g.webp
  - protoa1a.webp
  - protoa1c.webp
  - protoa1f.webp
  - protoa1e.webp
  - proto1d.webp
  - proto1c.webp
  - proto1g.webp
  - proto1f.webp

---

While working under a NIST PSCR grant, I explored the possibility of using custom tracked devices for our simulations. Such devices could be used to track AR displays in VR. Based on discussions with first responders, it was felt that an armband location would be useful. The location is familiar for those who wear a wristwatch and can be easily moved out of the way when not needed. To not clutter one’s vision. In a real traffic stop scenario, a wristband with buttons might be worn to enable and disable the device. 
The armband went through several iterations as I tried various tracker HDKs and familiarized myself with the Steam VR SDK. Early efforts were focused on calibrating the IMU and establishing reliable sensor placement. Using CAD and the Steam VR SDK, I generated JSON files experimented with sensor placement and various cover materials for the sensors.

Jason Jerald’s company NextGen was also awarded a NIST PSCR grant for similar research so we partnered with them to compare notes. Coincidentally, they also decided to develop a custom armband and we were able to use some of their software and hardware to evaluate tracking accuracy. To further assist with accuracy measurement, I designed and built two custom motorized rigs to compare two tracked devices. In most of my testing, I mounted a vive tracker for ground truth and my custom tracked armband for evaluation.

One of my custom rigs, a two platter belt drive turntable, borrowed by NextGen to compare tracked devices in their lab. I designed an interface to mount my rig directly to the robot.
