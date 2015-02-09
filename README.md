Yale OpenHand Project
=======

CAD and STL files for the various OpenHand hardware designs. Complete documentation, including assembly directions, can be found at the [OpenHand website](http://www.eng.yale.edu/grablab/openhand/)

Based on the original SDM Hand, the Model T is the OpenHand Project's first released hand design. the four underactuated fingers are differentially coupled through a floating pulley tree, allowing for equal force output on all finger contacts. All finger joints are flexure-based, made with Smooth-On polyurethane. An alternative design with pin-based base joints is also available.

The Model T42 is a two-finger, two-actuator hand designed for more dexterous planar tasks. It is still capable of underactuated, adaptive grasping, but the additional actuator makes it capable of some in-hand manipulation primitives as well as precision grasping. Dynamixels can be replaced by Power HD servos in this design.

The Model O is a three-finger, four-actuator hand designed to replicate the capabilities of commercial hands such as [BarrettHand](http://www.barrett.com/robot/products-hand.htm), RightHand Robotics' [Reflex Hand](http://www.righthandrobotics.com/main:reflex), and Robotiq's [3-Finger Adaptive Gripper](http://robotiq.com/products/industrial-robot-hand/). Each underactuated finger is independently controlled, while a fourth actuator controls the adduction/abduction angle between two of the fingers. This allows the hand to transition between spherical-grasping and power-grasping configurations. 

The Model M2, short for Multi-Modality Gripper, is a minimalist gripper with a single underactuated finger and a library of modular thumb designs. It can only require a single actuator with very simple assembly requirements. Each thumb design can enable a different grasping behavior and allows for faster, more versatile design iterations.

======= 

To start, open up the assembly files for the various hands. Complete sets of stl's should be in each hand directory.


