# PID Implementation With NXT Robot

This project demonstrates the implementation of a Proportional-Integral-Derivative (PID) controller on a LEGO Mindstorms NXT robot. The PID controller is used to help the robot maintain a desired behavior, such as following a line or maintaining a set distance from an obstacle.

## Table of Contents
- [Project Overview](#project-overview)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [PID Control Overview](#pid-control-overview)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [License](#license)

## Project Overview
In this project, a LEGO NXT robot is programmed to follow a target behavior using a PID controller, which adjusts the motor power based on feedback from sensors. This project serves as a practical example of using control theory in robotics to achieve precise control over the robot’s actions.

## Hardware Requirements
- LEGO Mindstorms NXT brick
- Motors and sensors (based on the specific PID application, such as ultrasonic sensors for distance control or light sensors for line following)
- Connection cable

## Software Requirements
- [Bricx Command Center (BCC)](http://bricxcc.sourceforge.net/) (for writing and uploading code to the NXT robot)
- Not Exactly C (NXC) programming language
- This project assumes basic familiarity with control theory and PID concepts.

## PID Control Overview
A PID controller is a control loop mechanism that calculates an error value and applies corrective adjustments based on proportional, integral, and derivative terms. Here’s a brief explanation of each term:
- **Proportional (P)**: Reacts to the current error. A larger error results in a proportionally larger control effort.
- **Integral (I)**: Accounts for past errors, helping eliminate residual steady-state errors.
- **Derivative (D)**: Predicts future errors based on the current rate of change, helping to dampen oscillations.

The PID algorithm constantly adjusts the robot's motor speeds to maintain the desired behavior based on real-time sensor data.

## Installation and Setup
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/mturan33/PID_Implementation_With_NXT_Robot.git
   ```
2. Open the project in Bricx Command Center.
3. Connect your LEGO NXT robot to the computer.
4. Upload the program to the NXT brick.

## Usage
1. Power on the LEGO NXT robot and navigate to the uploaded program.
2. Run the program to observe the robot’s behavior.
3. Adjust PID parameters in the code to tune the robot’s response, if necessary.

### Example Parameters
You may need to experiment with different values for the proportional, integral, and derivative constants to find the optimal settings for your specific setup.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
