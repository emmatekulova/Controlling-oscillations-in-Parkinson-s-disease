
# Controlling Oscillations in Parkinson’s Disease

Simulation and Analysis in NEST

This repository contains my final project for the *Controlling Oscillations in Parkinson’s Disease* assignment.
The goal of the project is to model a simplified STN–GPe network using the NEST simulator, reproduce Parkinsonian oscillations, and explore how Deep Brain Stimulation (DBS) affects network dynamics.

## Repository Structure

```
├── simulator.ipynb  # Main Jupyter notebook with simulation code and plots
│
├── modelling_project_task.pdf   # Original assignment description
│
├── Solution.pdf   # Final written report
│
└── README.md 
```

## Project Summary

The project simulates two neural populations:

* **STN (300 excitatory neurons)**
* **GPe (500 inhibitory neurons)**

Both are modeled using LIF neurons with fixed indegree connectivity.
Three main experimental conditions are included:

1. **Baseline** – only background Poisson input
2. **Parkinsonian state** – increased inhibitory input to GPe (simulating striatal overactivity)
3. **DBS condition** – direct current stimulation applied to STN

Additionally, two bonus explorations are included:

* **DBS amplitude sensitivity** (positive and negative values)
* **Manipulations to restore healthy-like activity**
