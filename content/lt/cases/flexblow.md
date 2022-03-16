# Real-time bottle blowing control system

## Client's challenge

[FlexBlow](https://flexblow.com/) is an SME specializing in **PET bottle manufacturing and equipment**. Their flagship product is a stretch blow molding machine that can be flexibly reconfigured to produce different shapes of bottles. However, the entire production process needs human supervision and continuous parameter adjustment in order to maintain bottle quality. We were contracted by Flexblow to design and implement an **autonomous bottle quality control system**.

## Our solution

The project required three components: control sensor, control software, and hardware for running quality control in production.

- **Control sensor.** FlexBlow's original quality sensor turned out to be inadequate for the task, so we took a lead in designing and sourcing the parts for a new sensor. Together with Elskaifa, a third-party electronics service provider, we developed a custom low-cost sensor that can perform up to 1 million accurate measurements per second.
- **Control software.** We developed a real-time closed-loop PID-style control system that seamlessly integrates with FlexBlow's machinery via industry-standard messaging protocols.
- **Hardware.** We worked together with FlexBlow's team to design such a hardware configuration that would integrate into the existing equipment without alterations.

## Impact

- Our system is expected to go to production in mid-2022.