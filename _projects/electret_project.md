---
layout: page
title: EDL
description: Wide-Band Audio Acquisition Using Electret Microphone
img: assets/img/electret.jpg
importance: 1
category: Microcontroller
---

**Electronic Design Lab: EE 344**

Guides: [Prof. PC Pandey](https://www.ee.iitb.ac.in/%7Epcpandey/), [Prof. VM Gadre](https://www.ee.iitb.ac.in/wiki/faculty/vmgadre)

The primary objective of the project was to design and implement an **audio acquisition circuit** that effectively **compensates** for the **amplifier DC bias** current of the electret microphone, while maintaining a reasonably low cut-off frequency.
In addition, the circuit was required to incorporate an **automatic gain control** mechanism that avoids boosting the noise.

This was a group project in a team of three. My key contributions:

- Designed the pre-amplification circuit and tested the working of the circuit
- Developed an optimal 5cm×5cm PCB layout with the micro-controller mounting
- Engineered peak-valley detection and implemented the automatic gain control algorithm in the TIVA-C board
