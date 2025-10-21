# MATLAB Simulation of DC Motor

## Overview
This repository contains a MATLAB and Simulink model for simulating a **DC motor** using the Simscape framework.  
The simulation analyzes motor behavior under various load and voltage conditions, including visualization of **electrical torque**, **armature current**, and **rotational speed** characteristics.  
  

## Features
- Simulation of DC motor dynamic behavior  
- Real-time plotting of torque, speed, and current  
- Modular parameter initialization through MATLAB script  
- Customizable motor parameters and load conditions  

## Motor Model Equations
The DC motor model is governed by the following fundamental equations:

\[
V = L \frac{di}{dt} + Ri + K_e \omega
\]
\[
T = K_t i - B\omega - J \frac{d\omega}{dt}
\]

Where:  
- \(V\): Armature voltage (V)  
- \(i\): Armature current (A)  
- \(R\): Armature resistance (Ω)  
- \(L\): Armature inductance (H)  
- \(K_e\): Back EMF constant  
- \(K_t\): Torque constant  
- \(B\): Damping coefficient  
- \(J\): Moment of inertia  
- \(\omega\): Rotational speed (rad/s)



