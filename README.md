# Autonomous Robot Simulation in a Warehouse

## Objective
This project simulates an autonomous robot navigating a 10x10 meter warehouse environment. The robot's goal is to move from the starting position `(0, 0)` to the destination `(7, 9)` while adhering to specified movement constraints.

## Project Description
This Python-based simulation implements a simple robotic control system with the following key features:
- **Warehouse Boundaries**: A 10m x 10m space within which the robot must operate.
- **Movement Constraints**: The robot moves at a speed of 0.1 meters per second and must pause for 2 seconds after each 0.1-second interval of travel.
- **Path Planning**: The robot is programmed to reach its destination while respecting boundaries and avoiding obstacles (if any are added in the future).

## Features
- **Speed Limitation**: Ensures the robot travels at a maximum speed of 0.5 m/s.
- **Periodic Stop**: The robot pauses for 2 seconds after every 0.1 seconds of movement to simulate a real-world operation delay.
- **Boundary Management**: The robot checks to stay within the boundaries of the warehouse and avoids out-of-bounds movement.
  
## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/AutonomousRobotSimulation.git
   cd AutonomousRobotSimulation

## libraries 
```bash
!pip install numpy
!pip install matplotlib
!pip install pygame

# Run the Simulation: To start the robot simulation, run:
python main.py

# Customize Parameters
You can adjust parameters like speed, stop interval, or destination within the script to test different scenarios.
