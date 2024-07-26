---
title: "Automated Noise Controller for Television"
description: "An Embedded System for Adaptive Volume Control"
dateString: June 2022
draft: false
tags: ["Embedded Programming", "Audio Processing", "Microcontrollers", "Arduino", "Sensors & Transducers"]
showToc: false
weight: 210
cover:
    image: "projects/noise/se2.jpg"  # Update the image path accordingly
---

## Automated Noise Controller for Television 🎶📺

### Project Overview

This project, completed as part of the Sensors and Transducers module, involved creating an Automated Noise Controller device for television. The system automatically adjusts the TV volume based on the ambient noise level, enhancing the viewing experience by preventing sudden loud or quiet moments. Users can set a desired sound threshold using a potentiometer, allowing for personalized volume control.

### Key Features

- **Dynamic Volume Adjustment**: The system automatically adjusts the TV volume when ambient noise levels exceed or fall below the user-set threshold.
- **User-Controlled Threshold**: Users can adjust the desired sound threshold level using a potentiometer, providing a customizable experience.
- **Directional Sound Sensing**: Equipped with three sound sensors positioned to capture ambient noise from different directions, ensuring accurate noise level detection.
- **Visual Feedback**: An LCD display shows real-time sound levels and system status, aiding in easy monitoring and adjustments.

### Technical Specifications

- **Microcontroller**: Arduino Uno
- **Components**: Three sound sensors, IR transmitter, IR receiver, 1602 LCD display, potentiometer
- **Programming**: Developed using Arduino IDE with C/C++
- **Functionality**: Uses IR communication to interface with the TV, adjusting volume based on detected sound levels

### Project Outcome

The project successfully demonstrated a working model that dynamically adjusts TV volume in response to ambient noise. The sound level is measured by three sensors positioned to capture noise from multiple directions, providing a robust solution for noise-sensitive environments. My primary contribution was developing the Arduino code that drives the system.

### Team & Acknowledgements

This project was a team effort, with contributions from Wenuranga Weerawardhana, Tharushi Witharana, Sachini Ranaweera and Kajawahini . Special thanks to our instructor Hasalanka Nagahawatta, for their guidance. My role focused on coding the microcontroller to handle noise detection and volume adjustment logic.

### Skills Gained

- Embedded systems programming with Arduino
- Real-time audio signal processing
- Integration of multiple sensors for directional noise detection
- Practical application of IR communication in consumer electronics

---



![](/projects/noise/se1.jpg)
![](/projects/noise/se2.jpg)
![](/projects/noise/se3.jpg)
![](/projects/noise/se4.jpg)