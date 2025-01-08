# Smart Automatic Bin with Gas Detection

## Project Overview
This smart bin automates waste disposal and monitors gas levels for safety and efficiency. It features touchless operation and environmental monitoring capabilities.

## Components Used
1. Arduino UNO R3
2. Ultrasonic Sensor (HC-SR04)
3. Servo Motor
4. Gas Sensor
5. RGB LED (4-pin)
6. Resistors (220Ω × 3)
7. Connecting Wires
8. Breadboard

## Functionality

### Automatic Lid Operation
- Ultrasonic sensor detects presence within 30cm range
- Servo motor automatically opens lid when motion is detected
- Lid remains open for 3 seconds
- Automatically closes after the set time

### Gas Level Monitoring
The system uses color coding to indicate gas concentration levels:
- Green: Safe level - Normal operation
- Yellow: Warning level - Moderate gas concentration
- Red: High level - Requires attention
- Blinking Red: Danger level - Immediate action required

### Safety Features
1. Touchless operation prevents direct contact with bin
2. Continuous gas monitoring for safety
3. Visual alerts through RGB LED
4. Serial monitoring capability for maintenance

### Pin Configuration
- Ultrasonic Sensor: Trigger (Pin 5), Echo (Pin 6)
- Servo Motor: Pin 9
- Gas Sensor: A0
- RGB LED: 
  - Red: Pin 11
  - Green: Pin 12
  - Blue: Pin 13
  - Cathode: GND

## Applications
- Homes
- Offices
- Hospitals
- Public spaces
- Areas requiring hygiene monitoring

## Future Improvements
- Adding WiFi connectivity for remote monitoring
- Implementing fill-level detection
- Adding data logging capabilities
- Battery level monitoring

## Note
Adjust gas threshold values based on environmental conditions and specific requirements.
