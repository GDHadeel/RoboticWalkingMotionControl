# RoboticWalkingMotionControl

## Description
This repository includes an algorithm to control servo motors for shaping a robot's walking motion. Task 1 focuses on developing precise movements, while Task 2 integrates and simulates a circuit with six servo motors for implementation.

# Task 1: Algorithm for Operating Servo Motors to Shape Robotic Walking Motion
* Objective: Develop an algorithm to control the servo motors for simulating a walking motion.

* Algorithm Steps:
  
1. Set Initial Positions: Position all servos (hips and knees) at starting angles.
   
3. Define Parameters: Establish the length of each step, the height of the foot lift, and the movement speed.
   
5. Perform Walking Cycle:
   - Lift the Leg: Move the hip forward and bend the knee to lift the foot.
   - Swing the Leg Forward: Move the hip backward and straighten the knee to bring the foot forward.
   - Lower the Leg: Extend the knee and move the hip to lower the foot onto the ground.
   - Shift Weight: Shift the body’s weight onto the forward leg.
     
6. Repeat for the Opposite Leg: Execute the same movements with the other leg.
   
8. Continue the Cycle: Loop through the walking cycle, adjusting balance and speed as necessary.


# Task 2: Connect and Program an Electronic Circuit Containing 6 Servo Motors in a Simulation Program

* Objective: Connect and program an electronic circuit with six servo motors using a simulation environment.

1. Circuit Design:
   
Develop and simulate the electronic circuit for the six servo motors.

![6 servo motors](https://github.com/GDHadeel/RoboticWalkingMotionControl/assets/126657301/825dc10a-9be9-41ea-af0d-a68f8ddc271a)

2. Code:
   
The code to control the six servo motors is provided in a separate file. The code initializes the servos and performs basic movements to demonstrate the setup.

The detailed code file can be found here: https://github.com/GDHadeel/RoboticWalkingMotionControl/blob/main/6ServoMotors.cpp

## Acknowledgments

* https://www.tinkercad.com/embed/5Z1wX4s72l8?editbtn=1





