# VR Driver Perspective Safety Simulator  
**Author: Abhishek Dubasi**

This project presents a Virtual Reality–based safety simulation environment built in Unity. It demonstrates advanced driver safety systems applied to a high-performance vehicle. The vehicle model is a Volvo S90.

Developed as part of a capstone research project at the Deggendorf Institute of Technology, Bavaria, Germany.

___

## Main Objective

To design and implement a driver-perspective safety simulation framework that evaluates driver behavior and reaction time under various road and hazard conditions. The system includes:

- Automatic Emergency Braking (AEB)
- Collision warning logic
- Pedestrian detection and avoidance
- Distracted driving scenarios
- Dynamic urban environments
- First-person VR experience
- In-cabin voice assistance

___
## Euro NCAP Integration

This simulator was developed with direct reference to the **Euro NCAP (European New Car Assessment Programme)** protocols, specifically the **2025 roadmap for Vulnerable Road User (VRU) protection** and **Automated Driving (AD) safety features**.

The implemented logic and scene setups align with Euro NCAP's guidelines for:

- **AEB VRU scenarios**, including adult and child pedestrian crossing paths
- **Vehicle speed thresholds and timing** for Forward Collision Warning (FCW) and AEB activation
- **Occlusion-based hazard detection**, such as pedestrians emerging between parked vehicles
- **Driver attention and reaction timing**, mapped to scenario timing rules
- **Repeatable, measurable testing environments** for pre-crash events

These standards helped structure the pedestrian AI, collision zone triggers, and test layouts to reflect real-world safety test cases. This approach allows developers and researchers to simulate and iterate on ADAS behavior in a controlled, immersive environment without physical risk or high cost.


## Relevance to Automotive Safety

This simulator explores the evolving human-machine interface (HMI) needs in high-speed and high-risk driving contexts. It demonstrates how immersive simulation environments can support the development and validation of advanced driver-assistance systems (ADAS), including:

- Forward Collision Warning (FCW)
- Automatic Emergency Braking (AEB)
- Pedestrian response zones
- Scene occlusion handling in urban environments

___

## Role of Development  

This repository contains only the components I directly developed and implemented:

- Custom vehicle physics for realistic driving feedback
- Waypoint-based pedestrian AI and movement system
- Scene design with dynamic hazards and occlusion logic
- Meta Quest 3 integration for VR testing and interaction
- Input mapping for steering wheel and HMD support
- Voice-triggered in-cabin assistant with contextual alerts

___

## Media Resources

Screenshots, videos and the project presentation are kept in a university folder that needs a login. They are available on request.

## License

Licensed under the [MIT License](LICENSE).
