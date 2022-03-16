# 

## Client's challenge

[strato.homes](https://strato.homes/) is an innovative startup that designs and builds **modular houses** from purchase to move-in in mere three months. A part of their vision is an **AI planner** that would create a floor-plan based on buyer's choices and engineering restrictions imposed by their modular system. 

## Our solution

Our solutions comprises of three main components:

1. A floor-plan generation algorithm that formulates planning as a **linear programming** and **constraint programming** problem and solves it using *coin-or* and *ortools* solvers. We derived planning constraints by working closely with strato.homes' architects, and as a result our algorithm is capable of generating sensible plans for thousands of different configuration options. We also investigated reinforcement learning and conditional variational encoder approaches but found them unpractical at this stage.
2. A **cloud infrastructure** setup for high intensity computations.
3. A **backend service** and a **user interface** for the exploration of results.

## Impact

- We delivered a working PoC planner in **7 months**, allowing strato.homes to quickly gauge the potential of this approach.
- Encouraged by our PoC, strato.homes is continuing to expand the feature set, and we hope to see it deployed soon!