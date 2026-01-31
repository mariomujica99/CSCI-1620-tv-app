# Television TV Remote Control App - PyQt6 GUI Application

## Overview

This is a television remote control simulator built with Python and PyQt6. This application mimics the functionality of a TV remote. The interface displays channel logos that change based on user input.

## Features

### Power Control
- Turn TV on/off with power button
- Screen displays appropriate state (black when off, welcome screen when on)
- All controls disabled when TV is off

### Channel Management
- 10 Available Channels (0-9)
- Direct channel selection via number buttons (0-9)
- Channel up/down buttons with wraparound functionality
- Visual channel indicator showing current selection

### Volume Control
- Volume range: 0-10
- Volume up and down buttons
- Visual slider showing current volume level
- Numeric volume display
- Mute/unmute functionality with volume memory

### Channel Lineup

| Channel | Network |
|---------|---------|
| 0 | HGTV |
| 1 | ESPN |
| 2 | The CW |
| 3 | Cartoon Network |
| 4 | PBS |
| 5 | History Channel |
| 6 | Hallmark |
| 7 | Nickelodeon |
| 8 | ABC |
| 9 | National Geographic |

## Technologies Used

- **Python**
- **PyQt6** - GUI framework
- **Qt Designer** - Visual UI design tool
- **QtGui** - Image handling for channel logos

## Learning Objectives

This project demonstrates:
- **Object-Oriented Programming**: Classes, encapsulation, inheritance
- **GUI Development**: Event handling, widget manipulation, layouts
- **State Management**: Tracking and updating application state
- **Image Handling**: Loading and displaying images dynamically
- **User Experience Design**: Intuitive interface, visual feedback
- **Code Organization**: Separation of concerns, modularity
- **Boundary Conditions**: Handling min/max values, wraparound logic

## Academic Integrity Notice

This project is submitted as academic work for CSCI 1620. Please do not copy or reproduce for academic submissions.
