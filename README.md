# lyap_quadrotor
This repository contains the implementation of a control strategy for stabilizing and controlling the trajectory of a planar quadrotor using Lyapunov Control Functions. The goal is to achieve precise control over the quadrotor's position and orientation while ensuring system stability.

## Introduction
A planar quadrotor is a simplified model of a quadrotor that operates in a 2D plane with three degrees of freedom: horizontal position, vertical position, and rotation about the center of mass. This project uses Lyapunov-based control to ensure the stability of the quadrotor and regulate its trajectory to follow a desired path. Lyapunov's stability theory provides a systematic way to design control laws that guarantee system stability and desired performance.

## Features 
* Planar Quadrotor Dynamics: Models the dynamics of a quadrotor in a 2D plane with three degrees of freedom.
* Lyapunov Control Design: Implements control laws based on Lyapunov's second method to stabilize the system.
* Trajectory Tracking: Controls the quadrotor to follow a desired trajectory (e.g., circular, straight line).
* Visualization: Plots the quadrotor's position and orientation as it follows the desired trajectory.
