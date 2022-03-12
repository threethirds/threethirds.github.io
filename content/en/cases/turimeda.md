---
title: "turimeda"
---

# turimeda

Turimeda is an early stage medtech startup that want's to measure and monitor internal
organs without tedious manual labeling effort. Their first product measures the dilatation
of aorta based on raw CT scans and tracks the development of the condition over time.


We are responsible for building the CT scan segmentation part of the App. Our MVP
deliverable is able to accurately (dice index > 0.9) segment the aorta, construct a 3D
body and measure the volume of the aneurysm. The algorithm comes with an AWS based
backed which is consumed by the app. 

At the core of our solution is the U-Net convolutional neural net, optimized for ... /
modified to .... . It's output is then further processed by a custom-made code to produce
an accurate 3D body, locate specific arteries and other landmarks, and to measure
the volume.

The MVP is currently tested in three national hospitals in Lithuania, where it's accuracy
will be validated and additional data will be gathered.