`bash
roslaunch kinect2_bridge kinect2_bridge.launch
roslaunch ros_stepper_scan stepper_scan.launch
rosrun rosserial_python serial_node.py /dev/ttyACM0
rosservice call /start_stepper_scan "_1_empty_"
`
