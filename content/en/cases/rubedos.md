---
title: "Machine Vision: Application in Autonomous Forklifts"
description: "We created a real-time solution for pallet detection and localization from a video stream"
---
# Pallet detection and localization system

![Pallet detection results](/images/rubedos.png)

## Client's challenge

[Rubedos](https://rubedos.com) is an SME specializing in **mobile robotics**. In 2021 they started developing an autonomous forklift platform, aiming to autonomously locate a pallet in a loading zone and transfer it to the target location. We were contracted by Rubedos to develop a pallet detection and localization stack that identifies pallets, their orientation and location from a stereo image and LIDAR inputs.

## Our solution

- Pallet detection system is based on an ensemble of off-the-shelf **convolutional neural networks for object detection**, adapted to the constraints of Rubedos' GPU-powered VIPER stereo camera. The system is capable of detecting a variety of pallets from multiple angles, distances, and lighting conditions.
- Pallet localization is done by a purpose-built classical machine vision system that merges **LIDAR** and **stereo camera**'s data streams. The system can successfully handle many types of pallets and occlusions.
- The solution is deployed at multiple locations at the warehouse and on the forklift, and communicates with the forklift control stack (developed by Rubedos) via the standard Robotic Operating System (ROS) protocols.
- We managed the full scope of algorithm development, from **data gathering and annotation** service subcontracting to algorithm **training on the cloud** and deployment within Rubedos' infrastructure.

## Impact

- Within **five months**, we delivered a complete pallet detection and localization suite.
- Using our solution, Rubedos autonomous forklift PoC successfully **passed the trials** of a test deployment at the warehouse of a **major logistics company**.
- We are continuing our collaboration to **deploy an MVP** at a large logistics center by the end of 2022.