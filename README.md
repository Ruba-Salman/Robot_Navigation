# Robot_Navigation
In this task, we will use SLAM map that we created before to navigate the robot to a specific point or location.

**The steps taken to accomplish this task:
1. Open the terminal and type these commands:
2. For Launch Simulation World <br/>
$ export TURTLEBOT3_MODEL=burger <br/>
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch

3. Run Navigation Node
$ export TURTLEBOT3_MODEL=burger <br />
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

4. Estimate Initial Pose
-From the RViz menu, select 2D Pose Estimate.
-Click and drag the large green arrow toward the direction the robot is pointing on the map where the actual robot is positioned.
-Repeat steps 1–2 until the LDS sensor data is visible on the stored map.

at the end, the robot will move to the direction where the green arrow is indicated.
