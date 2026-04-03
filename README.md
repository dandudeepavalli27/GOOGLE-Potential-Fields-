# GOOGLE-Potential-Fields-
Aim
To compute the net force acting on a robot using the Artificial Potential Field method.
General Objective
To understand the Artificial Potential Field (APF) method in robot navigation and how attractive and repulsive forces guide a robot toward the goal while avoiding obstacles.
Specific Objective
To compute net force using:
Net Force
=
Attractive
−
Repulsive
Net Force=Attractive−Repulsive
Given:
Attractive Force = 12
Repulsive Force = 5
Dataset
Artificial Potential Field Data
Source: PythonRobotics
Procedure
Input attractive force
Input repulsive force
Subtract repulsive from attractive
Compute net force
Display result
Algorithm
Start
Input attractive and repulsive forces
Compute net force
Display result
Stop
Code Logic
force = attractive - repulsive
Python Code
# SESSION 25 – Potential Fields (Net Force Calculation)

# Step 1: Input values
attractive = 12
repulsive = 5

# Step 2: Compute net force
force = attractive - repulsive

# Step 3: Display result
print("Net Force =", force)

print("\nProgram Executed Successfully")
Output
Net Force = 7

Program Executed Successfully
Result
The computed net force is:
Force = 7
Industry Application
Artificial Potential Fields are used in:
Robot navigation
Obstacle avoidance
Autonomous systems
Path planning
Companies like Google use such concepts in:
Robotics
Autonomous navigation
AI-based systems
Conclusion
The Artificial Potential Field method effectively combines attractive and repulsive forces to guide robots safely toward their goals.
