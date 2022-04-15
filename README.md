# ERC-hackathon-assignment
The ros noetic version of ros was installed in the ubuntu 20.04.2 arm64 version.
As instructed the omnibase and the ros-hackathon-2021 repo were cloned and then the obstacles.world file was copied into the omnibase_gazebo/worlds folder,hackathon_omnibase.launch file was copied into omnibase_gazebo/launch folder.
A catkin workspace was created with the package name as "omnibase_gazebo".
3 terminals were launched simultaneously using the terminator and each of them were sourced,the gazebo world was launched using the appropriate command in the first terminal,the controller was initialized in the second,and the last terminal was used to run the launch file containing the 3 nodes.
The codes for path planning(motion_planning.py),pid controller(controller_pid.py),obstacle avoidance(obstacle.py) was implemented in python,a launch file named "robot_mobility.launch" was created,which was instructed to launch all the 3 python codes simultaneously,on typing in the command "roslaunch omnibase_gazebo robot_mobility.launch" in the 3rd terminal resulted in the robot moving to the designated location in the world.
