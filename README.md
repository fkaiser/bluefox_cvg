# bluefox_vwg
*Before downloading and setting up the ROS node please download and install the driver according to the following steps.
*1. Download from the following page the driver and the shell script to a workspace folder. For the ARM Board use the hard float option
*2. Run installation as described here.
*3. Download the bluefox2 repository to your catkin_ws/src 
*4. Run catkin_make in your catkin_ws
*5. Open single_node.launch file (e.g. nano ~/catkin_ws/src/bluefox2/launch/single_node.launch) and add the device number (e.g. <arg name="device" default="25000060"/>
*6. source devel/setup.bash
*7. roslaunch bluefox2 single_node.launch 

