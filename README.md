Biological Reinforcement Learning Simulation for Parasitoid Behavior
Overview
This project simulates parasitoid and pest interactions over a series of episodes within a simulated ecological environment. Utilizing reinforcement learning, the model predicts behavior patterns based on environmental conditions and inter-species interactions, with a focus on parasitoids' strategies in response to pest populations.

Simulation Details
Episodes/Iterations: 100
Simulation Duration: 12 months
Steps per Month: 30
Learning Rate (alpha): 0.1
Discount Factor (gamma): 0.9
State and Action Space
States: 10
Actions: 4 (search, approach, attack, lay eggs)
Environment
Monthly reward, climatic conditions, and crop availability matrices influence species behaviors.
Initial populations are set for both parasitoids and pests, adjusting dynamically based on interactions and environmental factors.
Sensitivity Analysis
Examines the impact of different parasitism rates on population dynamics, providing insights into effective pest control strategies.

Requirements
MATLAB or a compatible environment for running the simulations.
Setup & Execution
Initialize parameters and matrices for simulation.
Run the simulation across defined episodes, updating Q-tables for both species based on the environmental data and interaction outcomes.
Perform sensitivity analysis on parasitism rates to observe effects on population dynamics.
Visualization plots are generated to depict population changes and sensitivity analysis outcomes.
Saving Results
Ensure the specified directory in the figure saving command matches your local system setup.

