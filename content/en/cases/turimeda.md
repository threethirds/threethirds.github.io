# EndoArt: Aortic aneurysm segmentation and monitoring system

## Client's challenge

[Turimeda](https://www.turimeda.com/) is an early stage MedTech startup that wants to measure and monitor internal organs without tedious manual labeling effort. Their first product measures **abdominal aortic aneurysm** – a life-threatening condition when aorta, the main blood vessel, expands and may rupture – based on raw CT scans, and tracks the development of the condition over time.

## Our solution

- We built a PyTorch-based **deep neural network** for aortic aneurysm segmentation, trained for multiple days on our custom cloud infrastructure.
- We developed a **3D post-processing stack** for locating and measuring landmarks on the reconstructed aorta's 3D mesh.
- Our algorithm runs as a web service on a cloud infrastructure.

## Impact

- We delivered a PoC in 12 months, reaching the field's standard **Dice index of .9** in a blind test on unseen patients CT scans.
- The PoC is currently tested at three national hospitals in Lithuania to get ready for clinical trials.