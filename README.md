# 2_link_manipulatormodel
I have created a Python model of a two-link planar manipulator to apply my understanding of the fundamental concepts of planar manipulators in practice.

->Initially represented the DH parameter table in the non-standard form.

->Developed a program to compute the transformation matrix between multiple pairs of frames.

->Developed a function for performing forward kinematics on a two-link planar manipulator. 
    By providing the input parameters of the link lengths and joint angles, the function calculates and returns the position of the end effector of the manipulator.
    
->Developed a function for performing inverse kinematics on a two-link planar manipulator. 
    By providing the input parameters of the link lengths and end effector position, the function calculates and returns the joint angles of the manipulator.
    
->Developed a function for deriving the workspace of a two-link planar manipulator.
    By providing the input parameters of the link lengths , the function plots the workspace for various joint angles in the range (-pi/2,pi/2)
