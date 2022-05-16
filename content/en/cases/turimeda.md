# Aortic aneurysm segmentation and monitoring system

![Automated aortic aneurysm annotation and 3D reconstruction (left) from raw DICOM images (right)](/images/turimeda.png)

## Client's challenge

[Turimeda](https://www.turimeda.com/) is an early stage MedTech startup that wants to measure and monitor internal organs without tedious manual labeling effort. Their first product focuses on *abdominal aortic aneurysm* – a life-threatening condition when aorta, the main blood vessel, expands and may rupture. Turimeda aims to develop a suite of tools that would help doctors track the development of condition over time based on regularly performed CT scans. Our task was to develop an algorithm which computes the exact dimensions of aorta from the CT scans.

## Our solution

- We built a PyTorch-based **deep neural network** for aortic aneurysm segmentation, trained for multiple days on our in-house cloud infrastructure.
- We developed a **3D post-processing stack** for locating and measuring landmarks on the reconstructed aorta's 3D mesh.
- We deployed our algorithm as a web service on a cloud infrastructure as well as packaged it as a standalone Docker container for the on-prem deployments.

## Impact

- We delivered a PoC in 12 months, reaching the field's standard **Dice index of .9** in a blind test on unseen patients CT scans.
- The PoC is currently tested at three national hospitals in Lithuania to get ready for clinical trials.