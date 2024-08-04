# Autonomous Intersection Management System

This project implements an Autonomous Intersection Management System (AIMS) using Simulink. The system utilizes reinforcement learning to train a car agent to navigate through intersections while avoiding collisions with other vehicles.

## Project Overview

Modern transportation systems face challenges related to traffic congestion and accidents at intersections. This project addresses these challenges by developing a system that manages traffic flow without human intervention. AIMS optimizes vehicle timing and order at intersections to reduce waiting time and improve safety.

### Key Features

- **Dynamic Vehicle Modeling:** Each vehicle in the simulation is modeled dynamically with a focus on engine, gearbox, and braking systems.
- **Reinforcement Learning (RL):** The car agent is trained using the Twin Delayed Deep Deterministic Policy Gradient (TD3) algorithm, enabling it to make decisions based on real-time traffic conditions.
- **Low-Level PID Control:** A PID controller manages the vehicle's speed by adjusting the throttle and brakes to maintain the desired velocity, enhancing stability and responsiveness.
- **Collision Avoidance:** The system prioritizes safety by using a reward function that penalizes collisions and encourages efficient intersection crossing.
