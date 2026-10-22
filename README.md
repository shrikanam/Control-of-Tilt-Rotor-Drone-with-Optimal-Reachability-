# Control of Tilt-Rotor Drones Using Optimal Reachability

Research project investigating reachability-based control methods for tilt-rotor drones with independently actuated motor orientations.

## Overview

Tilt-rotor drones combine the maneuverability of multirotor aircraft with the ability to reorient their thrust directions. By independently controlling motor orientations, these systems can achieve a wider range of force and torque configurations, making them an interesting platform for advanced control strategies.

This project explores the application of **optimal reachability methods** to tilt-rotor drone control. The objective is to study how system dynamics, control inputs, and actuator configurations influence the set of states that a drone can reach over time.

## Research Objectives

- Model the dynamics of a tilt-rotor drone as a dynamical system.
- Develop and simulate state-space representations of the system.
- Investigate reachable sets under specified control constraints.
- Explore optimal control strategies for steering the system toward desired target states.
- Evaluate how independently actuated motor orientations affect system controllability and reachability.

## Mathematical Framework

The initial simulation framework uses a state-space representation:

[
\dot{x}(t)=Ax(t)+Bu(t)
]

where:

- (x(t)) is the system state vector.
- (u(t)) is the control input vector.
- (A) describes the system dynamics.
- (B) describes how control inputs affect the system.

The model serves as a starting point for numerical simulation and subsequent reachability analysis. Additional nonlinear dynamics, actuator constraints, and model-specific parameters can be incorporated as the research progresses.

### Prerequisites

- Python 3.10 or later
- NumPy
- SciPy
- Matplotlib

## Current Progress

- [x] Establish the initial state-space model, (\dot{x}=Ax+Bu).
- [x] Begin simulation development.
- [x] Implement and validate the system dynamics.
- [ ] Develop numerical reachability analysis.
- [ ] Incorporate control and actuator constraints.
- [ ] Evaluate optimal control strategies.
- [ ] Analyze and visualize simulation results.


## Future Work

Potential directions for further development include:

- Computing reachable sets over finite time horizons.
- Investigating the effects of control constraints on reachable states.
- Studying optimal trajectories between initial and target states.
- Extending the model to capture the coupled dynamics of tilt-rotor configurations.
- Evaluating the robustness of reachability-based control methods under model uncertainty.

## Research Context

**Project:** Control of Tilt-Rotor Drones Using Optimal Reachability
**Research area:** Aerospace control systems, dynamical systems, and optimal control
**Institution:** University of Illinois Urbana-Champaign


This repository documents ongoing research and simulation development. Results, models, and algorithms are subject to revision as the project progresses.

