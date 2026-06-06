# Quarter Car Suspension Control System

## Project Overview

This project presents the modeling, simulation, and control of a Quarter Car Suspension System using MATLAB and Simulink.

The objective is to analyze the suspension response under road disturbances and compare different control approaches for improving ride comfort and vehicle stability.

The project includes:

* Open Loop Suspension Model
* PID Controller Design
* LQR Controller Design
* MATLAB App Designer GUI
* Controller Performance Comparison

---

## System Description

A quarter-car model represents one wheel and one-quarter of the vehicle body.

The system consists of:

* Sprung Mass (Vehicle Body)
* Unsprung Mass (Wheel Assembly)
* Suspension Spring
* Tire Spring
* Suspension Damper
* Tire Damper

---

## System Parameters

| Parameter | Description                    | Value     |
| --------- | ------------------------------ | --------- |
| m1        | Sprung Mass                    | 1430 kg   |
| m2        | Unsprung Mass                  | 40 kg     |
| k1        | Suspension Spring Constant     | 12000 N/m |
| k2        | Tire Spring Constant           | 6000 N/m  |
| c1        | Suspension Damping Coefficient | 4000 Ns/m |
| c2        | Tire Damping Coefficient       | 3000 Ns/m |

---

## Open Loop Model

The open-loop model was developed using Simulink by implementing the dynamic equations of the quarter-car suspension system.

The response of the system to a road disturbance was analyzed to evaluate vehicle body displacement and wheel displacement.

---

## PID Controller

A PID controller was implemented to improve the suspension performance.

The controller reduces vibration effects and improves system response by using:

* Proportional Action (P)
* Integral Action (I)
* Derivative Action (D)

---

## LQR Controller

The system was converted into State-Space form and an optimal Linear Quadratic Regulator (LQR) was designed.

The LQR gain matrix obtained using MATLAB is:

K = [4.5551 3.2541 3.7753 0.1470]

The controller minimizes a quadratic cost function while improving stability and dynamic performance.

---

## MATLAB GUI

An interactive graphical user interface was developed using MATLAB App Designer.

Features:

* Adjustable system parameters
* Controller selection
* Simulation execution
* Controller comparison
* Response visualization
* Performance summary table

---

## Software Tools

* MATLAB
* Simulink
* Control System Toolbox
* App Designer

---

## Repository Contents

* quarterCar_OpenLoop.slx
* quarterCar_PID.slx
* quarterCar_LQR.slx
* app1.mlapp

---

## Author

Noor Adel

Master's Student in Artificial Intelligence and Robotics
