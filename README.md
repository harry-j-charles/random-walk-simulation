# Random Walk Simulations

Python simulation of random walks in two dimensions, written for a University of Sheffield mathematics mini-project. It compares the simulated results with the theory.

## What it does

- Simulates a particle taking steps of length 1 in random directions, starting from the origin.
- Repeats each experiment 1,000 times and records where the walks end up.
- Compares an unbiased walk with a walk biased to travel east, as if there were a wind.
- Plots histograms of final position and distance, and how the averages change with the number of steps.

## Results

| Quantity (100 steps, 1,000 walks) | Simulated | Theory |
| --- | --- | --- |
| Mean of final x | 0.25 | 0 |
| Variance of final x | 48.8 | 50 |
| Mean squared distance | 101.2 | 100 |

- **Mean squared distance** was close to n for every walk length from 50 to 1,000 steps.
- **Biased walk:** mean final x grew by about 0.578 per step, matching the theoretical value.
