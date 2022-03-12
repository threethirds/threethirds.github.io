---
title: "strato.homes"
---

# strato.homes

# LT

# LT

# LT

strato.homes is an exciting startup in a modular construction space that builds homes
in 3 months from the purchase to the move-in. A part of their vision is an AI
planner, that would create a floor-plan based on (1) buyer's choices and (2) engineering
restrictions imposed by their modular system.


We took on the challenge and built the PoC AI planner in 7 months. Our deliverable was
a floor-plan generation algorithm, a cloud infrastructure setup for high intensity
computations, a backend service and a user interface for the exploration of results. Our
algorithm is capable of generating plans for thousands of different configuration options.


Our solution was based on translations of the planner to linear programming and
constraint programming problems and solving them using coin-or and ortools solvers. We also
investigated reinforcement learning and conditional variational encoder based approaches
but found them unpractical.


The stack behind the is currently being developed futher, and we hope to see it
deployed soon!
