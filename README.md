# Race Against AI (RAAI)

Welcome to **Race Against AI**, a cutting-edge project where humans compete in a thrilling time trial against artificial intelligence. The project integrates hardware and software modules to create a high-tech racing experience with remote-controlled (RC) cars. Drivers control the RC car using a racing rig (pedals, steering wheel) and experience the race through a VR headset connected to a camera mounted on the car. The AI opponent, powered by a rule-based algorithm, uses line detection for real-time decision-making.

This repository provides an overview of the modules and their respective GitHub repositories, allowing you to explore and contribute to the development of this innovative project.

---

## Project Overview

### Features
- **Immersive Driving Experience:** VR headset delivers a first-person perspective from the RC car’s camera.
- **AI Competitor:** A rule-based algorithm navigates the track using line detection.
- **Real-Time Visualizations:** Live race tracking with checkpoints and lap times.
- **Modular Design:** Each component is developed independently for maximum flexibility and scalability.

---

## Modules Overview

### 1. **Live Visualization**
   - **Description:** Displays the race, including a live camera feed of the track and checkpoint visualization similar to Formula 1.
   - **Repository:** [RAAI Module Live Visualization](https://github.com/race-against-ai/module_live_visualization)

### 2. **VR Camera Module**
   - **Description:** Handles the connection to the VR camera, delivering real-time video feed to the headset.
   - **Repository:** [RAAI Module VR Camera](#)

### 3. **Camera Image Stream**
   - **Description:** Streams the track’s camera feed via UDP multicast and pynng sockets.
   - **Repository:** [RAAI Module Camera Image Stream](#)

### 4. **Vehicle Tracker**
   - **Description:** Tracks the RC car’s position on the track using color detection in the camera feed.
   - **Repository:** [RAAI Module Vehicle Tracker](#)

### 5. **Time Tracking**
   - **Description:** Manages lap and sector times, ensuring accurate timing when passing checkpoints.
   - **Repository:** [RAAI Module Time Tracking](#)

### 6. **Platform**
   - **Description:** The physical platform for the racing rig, integrating pedals and steering wheel.
   - **Repository:** [RAAI Module Platform](#)

### 7. **Control Panel**
   - **Description:** Provides a dashboard to monitor and adjust parameters like throttle, brake, and steering.
   - **Repository:** [RAAI Module Control Panel](#)

### 8. **Vehicle Output Writer**
   - **Description:** Sends processed control signals to the RC car’s Pikoder system.
   - **Repository:** [RAAI Module Vehicle Output Writer](#)

### 9. **Platform Output Writer**
   - **Description:** Outputs platform data for integration with other modules.
   - **Repository:** [RAAI Module Platform Output Writer](#)

### 10. **Driver Input Reader**
   - **Description:** Reads inputs from the driver, such as pedal and steering wheel positions.
   - **Repository:** [RAAI Module Driver Input Reader](#)

### 11. **Vehicle Tracking Configurator**
   - **Description:** Provides a GUI for configuring the tracker’s settings, such as regions of interest.
   - **Repository:** [RAAI Module Vehicle Tracking Configurator](#)

### 12. **NGITL MicroManager**
   - **Description:** A project management tool to start and manage all RAAI modules.
   - **Repository:** [NGITL MicroManager](#)

---

## Getting Started

Each module repository contains detailed instructions for installation, configuration, and usage. Refer to the linked repositories for specific setup guides.

### Prerequisites
- Python 3.7+
- Raspberry Pi (for certain modules)
- VR Headset compatible with the RAAI setup
- RC car with Pikoder control system

---

## Contributing
We welcome contributions to this project! Please refer to the contribution guidelines in each module’s repository.

---

## License
The project is licensed under the [MIT License](LICENSE.md). See the LICENSE file for details.

---

## Contact
For any questions, please contact the RAAI development team at [support@example.com](mailto:support@example.com).

