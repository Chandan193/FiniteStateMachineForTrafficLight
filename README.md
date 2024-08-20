# Finite State Machine for Traffic Light Controller

This repository contains the implementation of a Finite State Machine (FSM) for a Traffic Light Controller.

## Project Overview

The project aims to design and implement a reliable and efficient Traffic Light Controller using a Finite State Machine (FSM) approach. The controller is designed to manage traffic flow at intersections, ensuring optimal usage of road space and reducing congestion.

## Objective

The objective of this project is to create a traffic light controller that efficiently controls traffic at an intersection. The controller is designed to manage multiple lanes and synchronize signal timings, ensuring compliance with traffic regulations and promoting road safety.

## Methodology

1. **FSM Design**: Identification of states, inputs, and outputs for the traffic light controller.
2. **State Diagram**: Visual representation of states and their transitions.
3. **State Transition Table**: Structured representation of transitions based on inputs and current states.
4. **VHDL Implementation**: Translation of the FSM design into VHDL code, defining states, transitions, and the control logic for traffic lights.
5. **Simulation**: Testing and verifying the FSM implementation using VHDL testbenches.

## Code Structure

- **Arduino Code**: Contains the code to control traffic lights based on the FSM design.
- **VHDL Implementation**: VHDL code for the traffic light controller.
- **Simulation**: Testbenches and files for simulating and verifying the FSM in VHDL.

## Features

- **Multi-Lane Support**: Manages traffic signals for multiple lanes.
- **Fault Tolerance**: Designed to handle power interruptions and component failures.
- **Scalability**: Flexible design allows for future enhancements like additional lanes or advanced traffic management systems.

## Future Enhancements

- **Sensor Integration**: Incorporate real-time sensors for dynamic traffic signal adjustments.
- **Adaptive Timing**: Implement algorithms to optimize traffic signal timings based on traffic patterns.
- **Pedestrian Crosswalks**: Extend the system to include pedestrian signals.
- **Centralized Control**: Coordinate multiple traffic controllers through a central system.



