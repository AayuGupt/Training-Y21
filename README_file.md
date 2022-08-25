Added sensors ,camera and imu to the robot made fot assignment 2. By updating m2wr.gazebo, rviz.launch and m2wr.xacro file. 
robotmodel.rviz file is created.
Base code was used from assignment 2 for this assignment.
After that gmapping node is added to the file rviz.launch.

Launching code: 
source ~/simulation_ws/devel/setup.bash
roslaunch my_simulations my_world.launch --screen
roslaunch m2wr_description rviz.launch
rostopic pub /cmd_vel geometry_msgs/Twist -- '[0.0,0.0,0.0]' '[1.0,0.0,1.0]'

youtube link -youtube.com/watch?v=kExtfv3lKlI
