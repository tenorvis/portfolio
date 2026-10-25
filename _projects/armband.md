---
layout: project
title: "Tracked Armband"
description: "VR Armband"
folder_name: "armband"
gallery_items:
  - image: protoa3a.webp
    annotation: "Early prototype of the tracked armband."
  - image: protoa3b.webp
  - image: protoa3c.webp
  - image: proto3demo.webp
  - image: protoa3ynoimu2.webp
  - image: protoa3z.webp
  - image: protoa3x.webp
  - image: protoa3v.webp
  - image: proto5a.webp
  - image: proto5b.webp
  - image: protoa3z2.webp
  - image: protoa3z6.webp
  - image: protoa3z5.webp
  - image: protoa3z11.webp
  - image: protoa3r.webp
  - image: protoa3m.webp
  - image: protoa3s.webp
  - image: protoa3k2.webp
  - image: protoa3j.webp
  - image: proto3jj.webp
  - image: protoak.webp
  - image: protoa3d.webp
  - image: divenodesnew11.webp
  - image: divenodesnew12.webp
  - image: protoa2a.webp
  - image: protoa2b.webp
  - image: protoa2f.webp
  - image: protoa2g.webp
  - image: protoa1a.webp
  - image: protoa1c.webp
  - image: protoa1f.webp
  - image: protoa1e.webp
  - image: proto1d.webp
  - image: proto1c.webp
  - image: proto1g.webp
  - image: proto1f.webp
  - type: video
    id: 2530ZBc48_w
    annotation: "Demonstration of the tracked armband in action."
  - type: video
    id: hKuFwdZ3yvU
    annotation: "Testing the armband with custom motorized rigs."
  - type: video
    id: g9xPwM_dKr0
    annotation: "Comparison of tracking accuracy with different devices."

---

Research Collaborator & XR Systems Engineer

While working under a NIST PSCR grant, I designed and prototyped a tracked device for our research team's simulations. Based on discussions with first responders, it was determined that anchoring the virtual UI to an armband would be useful. The location is familiar for those who wear a wristwatch and can be easily moved out of the way when not needed. To not clutter one’s vision. In a real traffic stop scenario, a wristband with buttons might be worn to enable and disable the device. My armband was used to track the EMS HUD in VR. A production version for AR might involve a physical anchor bracelet or a calculated anchor point.

The armband went through several iterations as I tried various tracker HDKs and familiarized myself with the Steam VR SDK. Early efforts were focused on calibrating the IMU and establishing reliable sensor placement. Using CAD and the Steam VR SDK, I generated JSON files experimented with sensor placement and various cover materials for the sensors.

Jason Jerald’s company NextGen was also awarded a sister NIST PSCR grant and we met with them to compare notes. Coincidentally, they also decided to develop a custom armband and we were able to use some of their software and hardware to evaluate tracking accuracy. To further assist with accuracy measurement, I designed and built two custom motorized rigs to compare two tracked devices. In most of my testing, I mounted a vive tracker for ground truth and my custom tracked armband for evaluation.

One of my custom rigs, a two platter belt drive turntable, borrowed by NextGen to compare tracked devices in their lab. I designed an interface to mount my rig directly to the robot.