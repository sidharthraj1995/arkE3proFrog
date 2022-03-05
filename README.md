# arkE3proFrog

- [arkE3proFrog](#arke3profrog)
- [1. Introduction](#1-introduction)
- [2. Hardware](#2-hardware)
  - [2.1. Motion](#21-motion)
    - [X axis](#x-axis)
    - [Y axis](#y-axis)
    - [Z axis](#z-axis)
    - [E](#e)
  - [2.2. Hotend](#22-hotend)
  - [2.3. Electronics](#23-electronics)
- [3. Firmware](#3-firmware)
- [4. Slicer Configuration](#4-slicer-configuration)

# 1. Introduction

Started with stock Creality Ender 3 Pro - Microcenter $99 deal, to learn about the 3D printing.

Replaced the motherboard to employ TMC2208 stepper drivers, linear rails for better motion, dual Z lead
screw for stable printing, Haldis 3D Frog extruder w/ Volcano hotend for HSHF printing, MOSFET for heatbed 
and hotend power, inductive probe for ABL and PEI spring sheet for great first-layer adhesion and large 
touch screen for easy interface.

Running Octoprint on AtomicPi using Docker.

# 2. Hardware

## 2.1. Motion

### X axis

    - Stock Creality 42-34 Stepper Motor.
    - TMC2208
    - MGN12C Linear Rail

### Y axis

    - Stock Creality 42-34 Stepper Motor.
    - TMC2208
    - MGN12C Linear Rail

### Z axis

    - Dual Z setup with 42-34 Stepper Motors.
    - TMC2208
    - V-Slot

### E

    - LDO-36STH20-1004AHG
    - TMC2208
    - Direct Drive setup

## 2.2. Hotend

    - Haldis 3D Frog Extruder w/ Volcano Hotend
    - 24V 50W heat cartridge
    - E3D Semitec 104NT

## 2.3. Electronics

    - BTT SKR 1.4T
    - BTT TFT70 V3.0
    - MOSFET for Hotbed and Hotend
    - ABL: Generic Inductive probe LJ18A3-8-Z/AX

# 3. Firmware

Coming soon.

# 4. Slicer Configuration

Coming soon.