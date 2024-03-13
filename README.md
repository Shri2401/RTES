# Real-time Lane Detection and Blind Spot Monitoring System

## Overview
This project aims to develop a real-time embedded system that enhances semi-autonomous vehicle safety by detecting lane departures and objects in blind spots. The system consists of sensors, algorithms, and hardware components to provide visual and audible alerts to the driver when necessary. With the increasing adoption of semi-autonomous driving features, ensuring safety and reliability becomes paramount. This project addresses these concerns by implementing advanced computer vision techniques and sensor-based detection systems.

## Features
- Lane detection using computer vision algorithms (Hough transform, edge detection)
- Blind spot detection using ultrasonic sensors
- Visual and audible alerts for lane departures and objects in blind spots
- Integration with hardware components (push buttons, LEDs)
- Real-time processing with low latency architecture
- Safety measures and fail-safe mechanisms


## Results:
| Thread               | WCET (ms) | Deadline / Period (ms) | Priority |
|----------------------|-----------|------------------------|----------|
| Lane Detection       | 125       | 300                    | 3        |
| Ultrasonic Sensor    | 20        | 60                     | 2        |
| Alarm                | <1        | 5                      | 1        |


## Motivation
According to the National Highway Traffic Safety Administration (NHTSA), over 800,000 accidents occur every year due to blind spot-related issues. Larger vehicles such as trucks, SUVs, and vans, along with motorcycles, are particularly vulnerable to blind spot accidents. Additionally, lane departure accidents are a significant concern, often leading to collisions and injuries. This project aims to mitigate these risks by providing drivers with real-time alerts for lane departures and objects in blind spots, thereby enhancing overall vehicle safety.

## Components
- Lane Assistance: Detects lane departures using a camera and processes data to alert the driver.
- Blind Spot Detection: Utilizes ultrasonic sensors to detect objects in blind spots.
- Alarm System: Provides visual and audible alerts to the driver based on lane departure and blind spot detection.

## Requirements
- Python 3.x
- OpenCV library
- Ultrasonic sensors
- Raspberry Pi or similar embedded system
- GPIO interrupt switch
- Logitech C270 camera (or similar)
- LED indicators
- Push buttons

## Installation
1. Clone the repository: `git clone <repository_url>`
2. Install Python dependencies: `pip install -r requirements.txt`
3. Connect hardware components (ultrasonic sensors, camera, LEDs, push buttons) to the Raspberry Pi or similar embedded system.
4. Configure GPIO interrupt switch for lane change indication.
5. Run the main script: `python main.py`

## Usage
- Ensure all hardware components are properly connected and configured.
- Run the main script to start the real-time lane detection and blind spot monitoring system.
- Follow on-screen instructions and listen for audible alerts for lane departures and objects in blind spots.
- Use push buttons to indicate lane changes and trigger appropriate alerts.

## Testing
- Unit tests: Test each component and algorithm individually to ensure functionality.
- Integration tests: Test the integration of hardware components and software modules.
- System tests: Test the complete system under various operating conditions to validate performance and reliability.

## Conclusion
In conclusion, this project represents a significant step towards improving the safety and reliability of semi-autonomous vehicles. By implementing real-time lane detection and blind spot monitoring systems, drivers can be alerted to potential hazards, reducing the risk of accidents and injuries. The integration of advanced computer vision algorithms and sensor-based detection systems showcases the potential for enhancing vehicle safety in the era of semi-autonomous driving. With further research and development, this technology has the potential to revolutionize the automotive industry and pave the way for safer and more efficient transportation systems.

