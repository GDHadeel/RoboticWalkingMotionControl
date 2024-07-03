# RoboticWalkingMotionControl

## Description
This repository includes an algorithm to control servo motors for shaping a robot's walking motion. Task 1 focuses on developing precise movements, while Task 2 integrates and simulates a circuit with six servo motors for implementation.

# Task 1: Algorithm for Operating Servo Motors to Shape Robotic Walking Motion
* Objective: Develop an algorithm to control the servo motors for simulating a walking motion.

* Algorithm Steps:
  
1. Initialization:
   * Attach Servos: Connect the hip and knee servos to the appropriate pins on the microcontroller.
   * Set Initial Positions: Set both the hip and knee servos at neutral positions, typically around 90 degrees, to prepare the robot to stand still.

2. Define Parameters:
   * Establish the length of each step, the height of the foot lift, and the movement speed.
   * These parameters will control the angular positions and speeds of the servos.

3. Leg Movement Loop**:
   - Lift the Leg:
   * Hip Servo: Incrementally rotate the hip servo forward from its initial position (e.g., from 90 to 120 degrees).
   * Knee Servo: Bend the knee servo to lift the foot (e.g., decrease angle to 60 degrees).
   * Timing: Introduce a delay between angle adjustments to ensure smooth motion.

  - Swing the Leg Forward:
     * Hip Servo: Gradually rotate the hip servo backward to move the foot forward (e.g., from 120 back to 90 degrees).
     * Knee Servo: Straighten the knee servo to bring the foot forward (e.g., increase angle back to 90 degrees).
     * Timing: Maintain consistent timing delays for fluid motion.

   - Lower the Leg:
     * Knee Servo: Extend the knee servo to lower the foot onto the ground (e.g., from 90 back to 120 degrees).
     * Hip Servo: Adjust the hip servo to position the foot correctly on the ground (e.g., maintain at 90 degrees).

   - Shift Weight:
     * Adjust both hip servos to shift the body’s weight onto the forward leg for balance.

4. Repeat for the Opposite Leg:
   * Execute the same movements with the other leg, mirroring the sequence of actions.

5. Continue the Cycle:
   * Loop through the walking cycle, continuously adjusting the angles and speeds of all hip and knee servos to maintain a smooth and balanced walking motion.


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





