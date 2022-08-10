# Sequence To Sequence Regression Of Particle Positions

## Data
The dataset consists of simulations of the trajectory of a single particle. The simulations are of varying length. All simulations start at t = 0 and end at t = 10 ± 1. A subset of the simulations are continued for an additional 4 ± 2 seconds, i.e. ending the entire simulation at t = 14 ± 3.
There are 150 simulations for training, 100 for validation, and 100 for testing. The simulations are of 100 ± 10 steps alongside their continuation of 40 ± 20 steps.

## ML Task
Using the positions of the particle during a simulation up to t = 10±1, the task is to continue its trajectory for an additional 4 ± 2 seconds.
