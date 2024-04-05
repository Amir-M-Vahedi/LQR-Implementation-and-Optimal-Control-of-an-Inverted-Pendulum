# LQR Implementation and Optimal Control of an Inverted Pendulum
## Overview
This project focuses on the Linear Quadratic Regulator (LQR) implementation and optimal control of an inverted pendulum system. The project includes a detailed analysis and simulation of the state-space equations governing the dynamics of an inverted pendulum. It provides a comprehensive approach to understanding and controlling this nonlinear system using LQR, a powerful tool in control theory for designing controllers to operate in uncertain environments. The given livescript (.mlx file) extracts the state-space equations for an inverted pendulum that is shown below. It also represents the simulation results.
<p align="center">
<img width="302" alt="Screenshot 2022-10-06 235219" src="https://user-images.githubusercontent.com/115154998/194411072-4a66a71b-6964-49f2-b3f9-92892a165619.png">
</p>
The dynamic equation of this plant is given as follows:
<p align="center">
<img width="330" alt="Screenshot 2022-10-07 000702" src="https://user-images.githubusercontent.com/115154998/194413703-dc414dd6-4697-49d6-9aa4-d6ca1c869fb6.png">
</p>

The cost function and required parameters for simulation are given as follow:
<p align="center">
<img width="467" alt="Screenshot 2022-10-07 000734" src="https://user-images.githubusercontent.com/115154998/194413796-53c4b58b-c5d0-4f53-9135-495d6fdfcd82.png">
<img width="428" alt="Screenshot 2022-10-07 000807" src="https://user-images.githubusercontent.com/115154998/194413886-ff43c430-e2a0-4694-9bc2-d0865506814c.png">
</p>
The Simulink file (.slx file) simulate dynamic equations of the given Inverted Pendulum.
The Matlab function file (.m file) is a riccati diffrential equation for ODE45 command.

