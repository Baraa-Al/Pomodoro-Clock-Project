# Pomodoro-Clock-Project
# Pomodoro Study Clock

A custom Pomodoro timer built from the ground up using an Arduino, custom electronics, a 3D-printed enclosure, and a custom PCB. This project was created to improve my understanding of embedded systems, digital electronics, PCB design, and product development while also providing a practical tool for studying.

## Overview

The Pomodoro Study Clock helps users stay focused by alternating between study and break periods. The device runs a 45-minute study timer followed by a 15-minute break timer, using dedicated buttons and visual indicators to guide the user through each cycle.

Unlike a software timer, this project was designed as a standalone hardware device, requiring me to develop skills in circuit design, programming, CAD, and PCB development.

## Features

* 45-minute study timer
* 15-minute break timer
* Audible buzzer notification when a session ends
* Dedicated button to acknowledge and stop the buzzer
* Dedicated button to start the next session
* Seven-segment display countdown
* Session counter to track completed Pomodoro cycles
* Custom-designed enclosure
* Custom PCB designed in KiCad

## Hardware Components

* Arduino microcontroller
* 4-digit seven-segment display
* Additional seven-segment display for session tracking
* SN74HC595 shift register
* Push buttons
* Piezo buzzer
* Custom PCB
* 3D-printed enclosure

## How It Works

The Arduino acts as the central controller of the system.

1. The user starts a 45-minute study session.
2. The countdown is displayed on a multiplexed seven-segment display.
3. When the timer reaches zero, the buzzer sounds.
4. The user presses a button to acknowledge the notification.
5. A second button starts the 15-minute break period.
6. After the break ends, the process repeats.
7. A separate display tracks the number of completed study sessions.

## Engineering Concepts

This project introduced several important engineering and computer engineering concepts:

### Multiplexing

The four-digit seven-segment display is driven using multiplexing, allowing multiple digits to be controlled efficiently while minimizing the number of required I/O pins.

### Embedded Systems

The Arduino continuously monitors inputs, updates displays, controls timing logic, and activates outputs based on user interaction.

### Shift Registers

An SN74HC595 shift register was used to expand the available output pins and drive an additional display without requiring extra microcontroller pins.

### Digital Electronics

The project involved integrating displays, buttons, timing circuits, and output devices into a complete system.

### PCB Design

After validating the design on a breadboard, a custom PCB was designed in KiCad to improve reliability and create a cleaner final product.

### CAD and Product Design

A custom enclosure was designed in Onshape to house all electronics and transform the prototype into a finished product.

## Development Process

### Phase 1: Learning

* Learned how seven-segment displays operate
* Explored multiplexing techniques
* Experimented with timers and countdown displays
* Learned how to interface buttons and buzzers with Arduino

### Phase 2: Prototyping

* Built the initial circuit on a breadboard
* Developed timer and session-tracking functionality
* Tested user interactions and system logic

### Phase 3: Mechanical Design

* Designed a custom enclosure in Onshape
* Optimized the layout for components and accessibility

### Phase 4: PCB Design

* Learned KiCad fundamentals
* Created a custom schematic
* Designed and routed a custom PCB
* Prepared the design for manufacturing

## Skills Developed

* Arduino Programming
* Embedded Systems
* Digital Electronics
* Circuit Design
* PCB Design (KiCad)
* CAD Design (Onshape)
* Hardware Debugging
* System Integration
* Product Development
* Technical Problem Solving

## Future Improvements

* Battery-powered operation
* Adjustable study and break durations
* OLED display interface
* Multiple timer modes
* Data logging and productivity analytics
* Bluetooth or Wi-Fi connectivity
* Custom microcontroller instead of Arduino

## Project Motivation

This project started as a simple idea to create a dedicated study timer, but it evolved into a full engineering project that required hardware design, software development, PCB design, and mechanical design. It was one of my first experiences taking a product from concept to prototype to a more polished final design, and it significantly strengthened my interest in embedded systems and product engineering.

