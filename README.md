Final code for 4-DOF Ball-Sorting Robotic Arm for Unified Robotics III: Manipulation (RBE 3001)

- Along with 2 of my classmates, I went through all the steps to program a 4 degree-of-freedom robotic arm to detect and sort colored balls placed at arbitrary positions on a chessboard
- Forward, inverse, and differential kinematics were used in order to achieve desired motion and plan trajectories with respect to both joint- and task space
- To accurately locate the 3D-printed balls, we utilized a stationary camera opposite the arm and facing the chessboard to provide visual data. This data was then used to create a mask for each color of ball, which were then combined into one and used to convert from the balls' pixel coordinates in the camera's frame of reference to task-space coordinates in the arm's frame of reference. The following were used:
   - Image Processing Toolbox
   - Image Acquisition Toolbox
   - Computer Vision Toolbox
   - Symbolic math Toolbox
   - MATLAB Support Package for USB Webcam
- Combining kinematics for motion of the arm, determinants of Jacobian matrices for singularity avoidance, a computer vision algorithm for ball localization, and endeffector orientation control via kinematic decoupling, the fully automated system correctly identifies any practical amount of colored balls on the chessboard and sorts them into their corresponding boxes placed adjacent to the chessboard

Video: [General overview](https://youtu.be/4wtvsY7mxtw?si=9fpaC8NpLDnFX1OM)