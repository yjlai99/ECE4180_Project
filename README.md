# Obstacle Avoidance and Manual Control Car
### Team Members: Mengxuan Xie, Yijun Lai

## Project Overview
### Autonomous mode
- Detect obstacles using an Ultrasonic sensor.
- Alerts through auditory warning using a Speaker.
- Capability to avoid obstacles.

### Manual control mode
- Bluetooth control to switch between modes and control movement.

## Parts Used
- **LPC1768 microcontroller**: Central processing unit of the car.
- **Adafruit Bluetooth module**: Enables wireless communication for remote control.
- **Ultrasonic sensor**: Used for obstacle detection.
- **Speaker**: Provides auditory alerts.
- **uLCD screen**: Displays distance information.
- **Dual H-bridge motor driver**: Controls the car's movement.

## Block Diagram
[Insert block diagram image here]

## Device Setup
[Insert images of the car setup here]

## Demo
[Insert YouTube video link here]

## Summary
- The Smart Obstacle Avoidance and Manual Control Car has been successfully developed and tested, performing largely as expected. A notable limitation is the ultrasonic sensor's narrow field of view, which can lead to the car's edges occasionally colliding with obstacles. This is primarily due to the sensor's inability to detect objects that are not directly in front of it.
- To address the current limitation, integrating a 360-degree LiDAR sensor is proposed. This would significantly enhance the car's spatial awareness, allowing it to navigate more complex environments, such as efficiently exiting a 2D maze by following the right wall.
- For future iterations, adding a camera system could provide visual feedback to the remote operator. 
