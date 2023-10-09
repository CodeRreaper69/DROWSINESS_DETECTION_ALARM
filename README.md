# Drowsiness Detection
Made using dlib, opencv, and python.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Applications](#appplications)

## Introduction

This Drowsiness Detection System is a Python-based project using dlib and OpenCV to detect drowsiness in real-time from a video stream or camera feed. It can be used in various scenarios, such as monitoring the alertness of drivers or individuals operating heavy machinery - such as automobiles. Various studies have suggested that around 20% of all road accidents are fatigue-related, up to 50% on certain roads. Our project aims to reduce the risk of such fatalities.

## Features

- Real-time drowsiness detection.
- Alarm system to alert drivers.
- Face and eye tracking for accurate detection.
- Easy integration with existing systems.
- Can be implemented with an alarm system, in say, automobiles.

## Requirements

- Python 3.11
- OpenCV
- dlib
- NumPy
- A compatible webcam or video feed source.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/srijitt/drowsiness-detection.git
   
2. Install the required dependencies:
   ```bash
   pip install opencv-python dlib numpy

3. Run the Drowsiness Detection System:
   ```bash
   python drowsiness_detection.py

## Applications
- **Driver Monitoring Systems (DMS)**: Implementing the drowsiness detection system in vehicles can help prevent accidents caused by driver fatigue. It can alert drivers when they are becoming drowsy or distracted, potentially saving lives on the road.

- **Industrial Safety**: In industrial settings where heavy machinery is operated, the system can be used to monitor the alertness of workers. It can trigger alarms or safety measures when a worker shows signs of drowsiness, reducing the risk of accidents.

- **Public Transportation**: Drowsiness detection can be integrated into public transportation systems to ensure that bus and train drivers remain alert during their shifts, improving passenger safety.

- **Aviation**: Pilots and flight crew often have long and irregular working hours. This system can be employed to monitor their alertness during flights, enhancing aviation safety.

- **Healthcare**: In healthcare settings, especially in intensive care units (ICUs), nurses and medical professionals can benefit from drowsiness detection to ensure they stay alert during long shifts, improving patient care.

- **Security and Surveillance**: Drowsiness detection can be integrated into security and surveillance systems to ensure that security personnel and surveillance operators remain attentive while monitoring critical areas.