# Robotic Arm: DESIGN AND SIMULATION OF 5 AXIS ROBOTIC GRIPPER USING SERVO

This directory contains CAD files and models for various robotic arm designs.
                                              
## 1. Introduction
In this project, I designed and built a robotic gripper using 5 servo motors. The gripper is capable of picking up and placing a small 3 cm cube using carefully coordinated movements across five axes. I made this project using Onshape for 3D CAD design and Arduino for motion control.
Fig.1 Assembled robotic arm gripper
## 2. Project Components and Movement Details:
For precise movements I came up with this 5 DOF robotic arm:
Joint/Part
Motion Type
Human Equivalent
DOF 1. Base Rotation Rotational (left/right) Waist 1
2. Shoulder Joint
Rotational (up/down)
Shoulder
1 3. Elbow Joint Rotational (bend arm) Elbow 1
4. Wrist Joint
Rotational (twist)
Wrist
1 5. Gripper (claw) Open/Close End Effector (hand) 1
## Tools Used:
• Design Software: Onshape
• Microcontroller: Arduino Uno
• Actuation: 5 Servo Motors (SG90 or MG995)
## 3. CAD Design using Onshape
All mechanical parts of the robotic arm were created in Onshape. I used different types of mates (connections between parts) to simulate the real movements:
• Revolute mates for rotating joints
• Slider mates for linear motion
• Gear mates for synchronized finger action (in the gear-based alternative model)
• Fasten mates for fixed parts
Gripper types created:
for this type of gripper(can be found in part studio 2) we need linear actuator(converts rotatory motion to linear motion) connected with servo motor like the above one which makes the gripper move.
In this type of gripper the servo is connected on one spur gear so that we can move the whole end effector.
In this type of gripper the servo motor can be directly attached behind the end effector rails it controls the slider motion of the gripper.
## 4. Simulation Results
Using Onshape's built-in animation tools, I simulated a complete pick-and-place motion:
• The arm lowers
• The gripper closes around the cube
• The arm raises and rotates
• The cube is placed down in a new position
Arduino UNO +5 Servo is the total materials needed for this project.
And I made the code for this using platformIO which is attached in GOOGLE DRIVE.
## 5. Future Improvements
• Manual control using a 2 dual axis joystick. [for all directions & objects]
• Implementation of OpenCV based system where the robot can recognize and grab objects automatically using a camera module.
