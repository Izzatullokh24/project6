# project6


# Running the node in the new tab

```
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ source devel/setup.bash
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ rossrv list
control_msgs/QueryCalibrationState
control_msgs/QueryTrajectoryState
control_toolbox/SetPidGains
controller_manager_msgs/ListControllerTypes
controller_manager_msgs/ListControllers
controller_manager_msgs/LoadController
controller_manager_msgs/ReloadControllerLibraries
controller_manager_msgs/SwitchController
controller_manager_msgs/UnloadController
diagnostic_msgs/AddDiagnostics
diagnostic_msgs/SelfTest
dynamic_reconfigure/Reconfigure
gazebo_msgs/ApplyBodyWrench
gazebo_msgs/ApplyJointEffort
gazebo_msgs/BodyRequest
gazebo_msgs/DeleteLight
gazebo_msgs/DeleteModel
gazebo_msgs/GetJointProperties
gazebo_msgs/GetLightProperties
gazebo_msgs/GetLinkProperties
gazebo_msgs/GetLinkState
gazebo_msgs/GetModelProperties
gazebo_msgs/GetModelState
gazebo_msgs/GetPhysicsProperties
gazebo_msgs/GetWorldProperties
gazebo_msgs/JointRequest
gazebo_msgs/SetJointProperties
gazebo_msgs/SetJointTrajectory
gazebo_msgs/SetLightProperties
gazebo_msgs/SetLinkProperties
gazebo_msgs/SetLinkState
gazebo_msgs/SetModelConfiguration
gazebo_msgs/SetModelState
gazebo_msgs/SetPhysicsProperties
gazebo_msgs/SpawnModel
laser_assembler/AssembleScans
laser_assembler/AssembleScans2
map_msgs/GetMapROI
map_msgs/GetPointMap
map_msgs/GetPointMapROI
map_msgs/ProjectedMapsInfo
map_msgs/SaveMap
map_msgs/SetMapProjections
nav_msgs/GetMap
nav_msgs/GetPlan
nav_msgs/LoadMap
nav_msgs/SetMap
nodelet/NodeletList
nodelet/NodeletLoad
nodelet/NodeletUnload
pcl_msgs/UpdateFilename
polled_camera/GetPolledImage
project6/OddEvenCheck
project6/TurnCamera
roscpp/Empty
roscpp/GetLoggers
roscpp/SetLoggerLevel
roscpp_tutorials/TwoInts
rospy_tutorials/AddTwoInts
rospy_tutorials/BadTwoInts
rviz/SendFilePath
sensor_msgs/SetCameraInfo
std_srvs/Empty
std_srvs/SetBool
std_srvs/Trigger
tf/FrameGraph
tf2_msgs/FrameGraph
topic_tools/DemuxAdd
topic_tools/DemuxDelete
topic_tools/DemuxList
topic_tools/DemuxSelect
topic_tools/MuxAdd
topic_tools/MuxDelete
topic_tools/MuxList
topic_tools/MuxSelect
turtlesim/Kill
turtlesim/SetPen
turtlesim/Spawn
turtlesim/TeleportAbsolute
turtlesim/TeleportRelative
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ source devel/setup.bash
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ rosrun project6 turn_camera_service_server
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/turn_camera_service_server
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/
[ INFO] [1685269899.316202797]: Turn Camera Server Running...
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/30.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/15.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/30.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/15.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/15.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/0.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/30.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/30.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/15.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/15.png
/home/ubuntu2005/project6_ws/project6_ws/sms-project6/src/project6/images/30.png

```


# This is a testing panel for the service in the new tab


```
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ source devel/setup.bash
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ rosrun project6 turn_camera_service_client 
Enter an angle to turn robot camera: 15
Enter an angle to turn robot camera: Killed
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ 15
15: command not found
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ rosrun project6 turn_camera_service_client 
Enter an angle to turn robot camera: 5 
Enter an angle to turn robot camera: 90
Enter an angle to turn robot camera: 100
Enter an angle to turn robot camera: 10      
Enter an angle to turn robot camera: 15
Enter an angle to turn robot camera: 55
Enter an angle to turn robot camera: 

```


# Here is picture about how my project is working
![smartmobility](https://github.com/Izzatullokh24/midterm/assets/86156093/f967feb6-f510-4ca2-8307-cee3dc9fbd45)

