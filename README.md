# Real-Time Factory I/O Digital Twins & Virtual Commissioning

## Project Overview
This repository focuses on my competencies in **Virtual Commissioning, Digital Twin development, and Industrial Plant Simulation** using **Factory I/O**. 

By building real-time, physics-based 3D industrial manufacturing and logistical environments, I bridge the gap between abstract control logic and physical factory floors. This portfolio demonstrates my ability to design, map, and validate complex automation sequences—such as synchronized robotic assembly, multi-lane parcel sorting, and analog check-weighing arrays—under realistic operational stresses before deployment to physical hardware.


## Key Engineering Skills Demonstrated
* **Real-Time 3D Physics Validation:** Modeling material handling systems where mass distribution, kinetic friction, conveyor velocity, and sensor blind spots mirror physical manufacturing boundaries.
* **Sensor-Actuator Interfacing:** Mapping complex 3D virtual device registers (capacitive, inductive, diffuse, and retroreflective photoelectric sensors) to standardized digital and analog I/O memory tables.
* **Closed-Loop Data Tracking:** Implementing advanced sequential logic to manage continuous package tracking, sorting timing gates, and dynamic diverting loops without bottlenecking line throughput.


## Technical Stack
* **Simulation Engine:** Factory I/O (Real-Time 3D Manufacturing Simulator)
* **Control Interfacing:** Software-PLC Drivers (Built-in Simulation / External Driver Mapping)
* **Automation Paradigms:** Digital Twins, Virtual Plant Commissioning, Hardware-in-the-Loop (HIL) Logic Verification, Automated Material Handling Systems (AMHS).


### 1. Automated Robotic Pick & Place Cells
* **Standard Pick & Place:** Programmed a synchronized two-axis robotic arm cell utilizing vacuum grippers to transfer items between independent conveyor zones based on sensor-latching indicators.
* **Pick & Place with Assembler:** Advanced the pick-and-place logic to manage an automated assembly station, coordinating part-clamping sequences, dual-axis part feeding, and mechanical assembly validation handshakes.

### 2. Dimension & Height-Based Sorting Arrays
* **Sorting by Height (Chain Transfer):** Engineered a multi-directional sorting hub using 90-degree chain transfer mechanisms. The logic parses photoelectric array beams to measure item height data and smoothly routes items without stopping line flow.
* **Sorting by Height (Pneumatic Pushers):** Configured a high-volume sorting lane using precise high-speed pneumatic pusher actuators, matching item dimensions to targeted collection chutes using low-latency timer interlocks.

### 3. Advanced Material Weighing & Diverting Cells
* **Sorting by Weight:** Modeled an industrial check-weigher system integrating an analog scale. The control loop reads raw weight telemetry, classifies items based on precise threshold data ranges, and routes rejects via separate reject arms.
* **Pop-Up Sorter Array:** Engineered a complex, multi-lane logistical routing matrix utilizing specialized pop-up wheel sorters. This system handles intricate sorting timing loops to divert high-speed, continuous package streams based on digital tracking flags.

## Video Demonstrations & Simulation Playback
To view live runtime recordings of these automated cells executing logic in real-time, visit the centralized portfolio vault:
-->**[Watch Live Project Simulation Videos](https://drive.google.com/drive/folders/1LX5n3qPfqe00K4KUQTa8ruhs8AlEMvZE?usp=drive_link)**
