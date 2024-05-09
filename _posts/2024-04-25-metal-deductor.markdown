---
layout: posts
title:  "Self-Contained Metal Detection System"
date:   2024-02-18 16:13:27 -0500
tags: FPGA
author_profile: true
author: kaviyarasan
categories: work
highlight_home: true
tagline: "*Junior Design Project* - Metal detectors are like time machines, allowing us to glimpse into the past and uncover forgotten treasures."
header:
  overlay_image: https://tme.media.uconn.edu/wp-content/uploads/sites/1326/2016/12/compe.jpg
  teaser: https://t3.ftcdn.net/jpg/06/17/39/70/360_F_617397008_oyzYY0Ha4XKZM0LpBLyJydXpVZKJaVso.jpg
  
---
## Inspiration
The inspiration behind the Self-Contained Metal Detection System stemmed from the team's interest in creating a portable and efficient metal detection solution. Drawing inspiration from existing metal detectors and FPGA-based systems, the team aimed to develop a self-contained device that could accurately detect and analyze metal objects.

## Project Overview
The Self-Contained Metal Detection System is a portable device designed to detect the presence of metal objects and provide detailed information about their size and strength. The project was developed collaboratively by a team of Electrical Engineering and Computer Engineering students. It utilizes the Xilinx Basys 3 FPGA as the main controller and features a custom-designed circuit for metal detection. The system is battery-operated and includes user interface elements such as LEDs and a Seven-Segment Display (SSEG) for visual feedback.

<iframe width="560" height="315" src="https://www.youtube.com/embed/k5zdHi3A2SY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


![Project Overview](/assets/images/metal_project.jpg)
*Final Product Image*
![Project Design](/assets/images/metal_LT_spice.png)
*Full Schematic of Electrical Circuit*

![Project Design](/assets/images/metal_design.png)
*Hardware and Software Schematic*

<div style="display:flex">
  <figure style="width:50%;">
    <img src="/assets/images/metal_small.png" alt="Image 1" style="width:100%;">
    <figcaption>Waveform With Small Washer Present</figcaption>
  </figure>
  <figure style="width:50%;">
    <img src="/assets/images/metal_medium.png" alt="Image 2" style="width:100%;">
    <figcaption>Waveform With Medium Washer Present</figcaption>
  </figure>
</div>

<div style="display:flex">
  <figure style="width:50%;">
    <img src="/assets/images/metal_big.png" alt="Image 1" style="width:100%;">
    <figcaption>Waveform With Big Washer Present</figcaption>
  </figure>
  <figure style="width:50%;">
    <img src="/assets/images/metal_nometal.png" alt="Image 2" style="width:100%;">
    <figcaption>Waveform With No Washer Present</figcaption>
  </figure>
</div>


## Source Code
Check out my project [here](https://github.com/Kaviyarsan2004/Project_Metal_Detector)

## Tech Stack
- **Hardware:**
  - Xilinx Basys 3 FPGA
  - Custom-designed circuit
- **Software:**
  - VHDL (for FPGA programming)
  - C (for software components)
- **Other Technologies:**
  - Oscilloscope (for testing)
  - Multimeter (for measurements)

## Challenges Faced
One of the main challenges encountered during the development of the Self-Contained Metal Detection System was calibrating the circuit for accurate metal detection. The team had to experiment with different coil designs, resistor values, and signal processing techniques to achieve reliable results. Additionally, integrating the hardware and software components posed challenges in terms of synchronization and data processing.

## Accomplishments
The team successfully designed and implemented a self-contained metal detection system that meets the project requirements. The system accurately detects the presence of metal objects and provides real-time feedback on their size and strength. This accomplishment demonstrates the team's proficiency in hardware design, FPGA programming, and collaborative problem-solving.

## Learnings
The project provided valuable learning experiences in circuit design, FPGA programming, and interdisciplinary teamwork. The team gained insights into signal processing techniques, hardware-software integration, and project management practices.

## Team Credits
- Electrical Engineering Team:
  - Jax Todorovic
  - Joseph Tomassi
- Computer Engineering Team:
  - Kaviyarasan Ganesamoorthy
  - Thomas Byrnes
  - Arjun Sahansra


## What's Next for the Self-Contained Metal Detection System
- Further optimization of the circuit design for improved sensitivity and accuracy.
- Integration of additional sensors for detecting non-metallic objects.
- Exploration of wireless communication capabilities for remote monitoring and control.

## Built With
- VHDL
- C
- Xilinx Basys 3 FPGA
- Oscilloscope
- Multimeter
