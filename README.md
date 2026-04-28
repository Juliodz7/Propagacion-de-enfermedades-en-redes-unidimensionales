# SIR Disease Propagation Model in One-Dimensional Networks

The SIR model is a classic mathematical framework used to understand the spread of infectious diseases within a population. In this README, we will explore how the SIR model can be applied to one-dimensional networks, with a focus on the dynamics of disease propagation among individuals.

## Overview of the SIR Model

The SIR model categorizes the population into three compartments:
1. **Susceptible (S)**: Individuals who are not infected but are at risk of contracting the disease.
2. **Infectious (I)**: Infected individuals who can transmit the disease to susceptible individuals.
3. **Recovered (R)**: Individuals who have recovered from the disease and are assumed to have immunity, thus can no longer be infected.

## Dynamics of the Model

In a one-dimensional network, we can visualize individuals arranged in a line, where each individual interacts only with their immediate neighbors. The dynamics of the disease propagation can be described by the following transitions:
- A susceptible individual becomes infected by interacting with an infectious neighbor.
- An infectious individual recovers after a certain period, transitioning to the recovered state.

### Parameters
- **β (Beta)**: The infection rate; it represents how often a susceptible individual comes into contact with an infectious individual.
- **γ (Gamma)**: The recovery rate; it defines the fraction of infected individuals that recover per time unit.

## Simulation

The model can be simulated using basic cellular automata principles, where time is discrete, and at each timestep, individuals update their states based on the interaction rules. Simulations can provide insights into:
- The speed of the outbreak.
- The total number of infections over time.
- The impact of different parameters on disease spread.

### Visualization
Visual results from the simulation can be used to illustrate the infection dynamics over time, providing clear insight into how diseases propagate in a linear structure.

## Conclusion

The SIR model offers a fundamental approach to understanding disease spread in populations. By analyzing one-dimensional networks, we can refine our understanding and develop strategies for disease management and control.