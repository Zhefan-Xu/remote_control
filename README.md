# Remote Control for Rviz Configs and Command Scripts
This package contains Rviz configuration and launch files for easy visualization of the autonomous flight data. It also contains some useful scripts for sending commands.

**Author**: [Zhefan Xu](https://zhefanxu.com/), Computational Engineering & Robotics Lab (CERLAB) at Carnegie Mellon University (CMU).

If you find this work helpful, kindly show your support by giving us a free ⭐️. Your recognition is truly valued.

This repo can be used as a standalone package and also comes as a module of our [autonomy framework](https://github.com/Zhefan-Xu/CERLAB-UAV-Autonomy).

## I. Rviz Example
There are four rviz launch configuration files for visualization convenience:
- **Tracking Circle**: ```roslaunch remote_control track_circle.launch```
- **Navigation**: ```roslaunch remote_control navigation.launch```
- **Dynamic Navigation**: ```roslaunch remote_control dynamic_navigation.launch```
- **Inspection**: ```roslaunch remote_control inspection.launch```
- **Exploration**: ```roslaunch remote_control exploration.launch```

The following screenshot shows the example rviz visulization of **Exploration**:

![Screenshot from 2023-12-14 21-31-50](https://github.com/Zhefan-Xu/remote_control/assets/55560905/3dfd5516-e50b-4185-b502-1bfad6b36ae3)


## II. Command Scripts
There are also some useful bash commands that will be potentially used when operating the robot under the directory ```remote_control/scripts```.
