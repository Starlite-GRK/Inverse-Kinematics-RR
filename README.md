# Inverse-Kinematics-RR
The objective of the project was to create a workspace of RR manipulator and find inverse kinematics of the position selected by user.

**Introduction:**

A robot is a mechanical device (software controlled) that uses sensors to guide/control one or more end effectors though programmed motions in a workspace in order to manipulate physical objects.

Manipulators are the kind of robots which have a fixed base and manipulate their environment. In simple words they can be undertood as a robot with a fixed base that can move the objects around it such as the industrial arms.

This project has a RR manipulator i.e. it has two revolute joints therefore it has 2 degrees of freedom.

In robot kinematics, forward kinematics refers to the computation of the pose (position and orientation) of the end-effector using the joint parameters (in this case the two joint angles) by the application of kinematic equations.

Whereas, inverse kinematics refers to the computation of the joint parameters (in this case the two joint angles) using the pose (position and orientation) of the end-effector.

Workspace of a robot is the collection of all the cartesian co-ordinates where the robot can reach.

![image](https://user-images.githubusercontent.com/77966030/221344318-f7e7aff1-3131-456c-8163-babd459dfe2a.png)

**MATLAB Add-Ons used:** RVC Toolbox

**Calculations**

The workspace was caculated using joint constraints. The joint parameters were calculated by equating the final forward kinematics model that was found using the DH method and the position selected from the workspace. 

![image](https://user-images.githubusercontent.com/77966030/221344453-517babf0-cf53-45a2-9eae-0c7abf1afe0e.png)

![image](https://user-images.githubusercontent.com/77966030/221344528-458c7bab-89e7-4433-814b-eb1feb5e5b68.png)
