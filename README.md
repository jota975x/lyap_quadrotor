# lyap_quadrotor
This repository contains the implementation of a control strategy for stabilizing and controlling the trajectory of a planar quadrotor using Lyapunov Control Functions. The goal is to achieve precise control over the quadrotor's position and orientation while ensuring system stability.

## Introduction
A planar quadrotor is a simplified model of a quadrotor that operates in a 2D plane with three degrees of freedom: horizontal position, vertical position, and rotation about the center of mass. This project uses Lyapunov-based control to ensure the stability of the quadrotor and regulate its trajectory to follow a desired path. Lyapunov's stability theory provides a systematic way to design control laws that guarantee system stability and desired performance.

## Features 
* Planar Quadrotor Dynamics: Models the dynamics of a quadrotor in a 2D plane with three degrees of freedom.
* Lyapunov Control Design: Implements control laws based on Lyapunov's second method to stabilize the system.
* Trajectory Tracking: Controls the quadrotor to follow a desired trajectory (e.g., circular, straight line).
* Visualization: Plots the quadrotor's position and orientation as it follows the desired trajectory.

## Control Strategy
This project uses a Lyapunov control approach to stabilize the quadrotor's motion. The basic steps include:

1. System Modeling: The planar quadrotor is modeled with state variables representing position, velocity, and orientation.
2. Lyapunov Function: A candidate Lyapunov function is designed to reflect the system's energy and ensure stability.
3. Control Law: Control inputs (thrust and torque) are derived to minimize the Lyapunov function, ensuring asymptotic stability and trajectory tracking.

## Lyapunov Function
The Lyapunov function, 𝑉(𝑥), is chosen to ensure that the quadrotor's energy decreases over time, stabilizing the system. The control law is designed such that the time derivative of 𝑉(𝑥) is negative definite.

## Results
The simulation results demonstrate that the Lyapunov-based control strategy effectively stabilizes the quadrotor and allows it to follow the desired trajectory. Key results include:
1. Stable Trajectory Tracking: The quadrotor successfully follows the reference trajectory with minimal deviation.
2. Control Inputs: The thrust and torque inputs remain within feasible limits.
3. Lyapunov Stability: The Lyapunov function decreases monotonically over time, confirming system stability.
