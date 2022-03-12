---
title: "rubedos"
---

# rubedos

# LT

# LT

# LT

Rubedos is an SME specializing in mobile robotics. One of their products is a control
suite for an autonomous forklift. The forklift is able to autonomously locate a
pallet in a loading zone and transfer it to the target location.

In the initial phase of the development they needed a boost in their computer vision
capacity and we joined them for 8 months and developed a pallet detection and
localisation stack. Our deliverable was a ROS service that indentifies the pallet, it's
orientation and location from the stereo image and lidar data streams.

Our solution was based on convolutional neural networks (Yolo v3), adapted to the
Rubedos Viper device. During the project we subcontracted a third party labeling
providers, and managed the full scope of algorithm development, from data gathering
to algorithm deployment.

Rubedos autonomous forklift PoC successfully passed the trials in a test deployment
in the warehouse of a major logicstics company, and is currently being productised.