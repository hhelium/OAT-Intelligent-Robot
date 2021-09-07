# OAT Course: Introduction to Intelligent Robotics

The open educational resources are developed with the support of the *[Open and Alternative Textbooks Initiative](https://www.wichita.edu/academics/academic_affairs/OAT/)* at Wichita State University. The course materials include a collection of Jupyter notebooks covering fundamental topics in robotics in the areas of manipulation and navigation. Each notebook is designed to be self-contained with theoretical background, codes, demos and/or simulations. 

The developers of the course include Hui Li, Dang Tran, Josh Ogbonda, and Fujian Yan. Some of the course materials are collected online or from open sources. If you find any contents that are not properly cited or referred, please contact [Dr. He](hongsheng.he@wichita.edu).

## Robotics Topics

The notebooks are organized into topics in manipulation and navigation. 

1. Robotics fundamentals: configuration space, degree of freedoms, and coordinate transformation
1. Motion representation
1. Forward kinematics and inverse kinematics
1. Velocity kinematics
1. Dynamics
1. Trajectory generation
1. Grasping
1. Locomotion
1. Mobile kinematics
1. Localization
1. Simultaneous localization and mapping (SLAM)
1. Path planning
1. Robot learning

## Environment Setup

The required libraries to run the notebooks are provided in requirements.txt. You use pip command to install all the dependences:

    pip install -r requirements.txt

The environment primarily depends on the following set of libraries: 

- Numpy
- PyBullet
- Scipy
- Matplotlib
- Pandas


## References

- PythonRobotics [https://github.com/AtsushiSakai/PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics)
- pytransform [https://alexanderfabisch.github.io/pytransform.html](https://alexanderfabisch.github.io/pytransform.html)
- pybotics [https://github.com/nnadeau/pybotics/blob/master/examples/kinematics.ipynb](https://github.com/nnadeau/pybotics/blob/master/examples/kinematics.ipynb)
- ModernRobotics [https://github.com/NxRLab/ModernRobotics/blob/master/packages/Python/modern_robotics/core.py](https://github.com/NxRLab/ModernRobotics/blob/master/packages/Python/modern_robotics/core.py)
