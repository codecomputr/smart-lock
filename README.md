![IMG_20250529_183933](https://github.com/user-attachments/assets/7f0f1955-a78d-4d67-bd47-15f9b7693421)

---

# Smart Face-Recognition Lock

This project implements a smart lock system that automatically unlocks when the Huskylens camera detects a recognized face. The system utilizes a Huskylens for face detection and recognition, an Arduino Uno for processing, a relay to control the locking mechanism, and basic electronic components to connect everything together.

## Features
- **Face Recognition**: Uses Huskylens to identify authorized users.
- **Automated Locking/Unlocking**: Unlocks when a compatible face is detected.
- **Simple Hardware Setup**: Minimal components with straightforward wiring.
- **Expandable**: Easy to add more recognized faces or integrate with other systems.

## Components
- **Arduino Uno**: Microcontroller to process data and control the relay.
- **Huskylens**: AI camera module for face detection and recognition.
- **Relay Module**: Controls the locking mechanism (e.g., electronic door lock).
- **Wires**: For connecting components.
- **Breadboard**: For prototyping connections.

## Wiring Overview
- Connect Huskylens to Arduino via I2C (SDA, SCL, VCC, GND).
- Connect the relay module to a digital pin on Arduino (e.g., D2) and power it appropriately.
- Connect the lock mechanism to the relay's normally open (NO) terminal.
- Use wires and breadboard for convenient connections.

## How It Works
1. Huskylens scans the environment for faces.
2. When a face is detected, Huskylens checks if it matches a known face.
3. If the face is recognized, Arduino activates the relay.
4. The relay unlocks the door by powering the locking mechanism.
5. After a set period, the lock re-engages automatically.

## Usage
- Upload the Arduino sketch provided in the repository.
- Train Huskylens with authorized faces.
- Power the system and observe it operate in real-time.

## Notes
- Ensure the Huskylens is properly trained with authorized faces for accurate recognition.
- Adjust the lock timing in the code as needed.
- Use a suitable power supply for the lock mechanism and components.

![IMG_20250529_183933](https://github.com/user-attachments/assets/7f0f1955-a78d-4d67-bd47-15f9b7693421)

![Uploading IMG_20250![Uploading IMG_20250529_183939.jpg…]()
529_183933.jpg…]()





















