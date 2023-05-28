# project6
# Starting the project number 6 and compling it 

```

ubuntu2005@ubuntu:~$ mkdir project6_ws
ubuntu2005@ubuntu:~$ cd project6_ws/
ubuntu2005@ubuntu:~/project6_ws$ mkdir src
ubuntu2005@ubuntu:~/project6_ws$ cd src
ubuntu2005@ubuntu:~/project6_ws/src$ catkin_create_pkg project6 roscpp
Created file project6/package.xml
Created file project6/CMakeLists.txt
Created folder project6/include/project6
Created folder project6/src
Successfully created files in /home/ubuntu2005/project6_ws/src/project6. Please adjust the values in package.xml.
ubuntu2005@ubuntu:~/project6_ws/src$ sudo snap install --classic code
code b3e4e68a from Visual Studio Code (vscode✓) installed
ubuntu2005@ubuntu:~/project6_ws/src$ mkdir launch
ubuntu2005@ubuntu:~/project6_ws/src$ cd ..
ubuntu2005@ubuntu:~/project6_ws$ catkin_make
Base path: /home/ubuntu2005/project6_ws
Source space: /home/ubuntu2005/project6_ws/src
Build space: /home/ubuntu2005/project6_ws/build
Devel space: /home/ubuntu2005/project6_ws/devel
Install space: /home/ubuntu2005/project6_ws/install
Creating symlink "/home/ubuntu2005/project6_ws/src/CMakeLists.txt" pointing to "/opt/ros/noetic/share/catkin/cmake/toplevel.cmake"
####
#### Running command: "cmake /home/ubuntu2005/project6_ws/src -DCATKIN_DEVEL_PREFIX=/home/ubuntu2005/project6_ws/devel -DCMAKE_INSTALL_PREFIX=/home/ubuntu2005/project6_ws/install -G Unix Makefiles" in "/home/ubuntu2005/project6_ws/build"
####
-- The C compiler identification is GNU 9.4.0
-- The CXX compiler identification is GNU 9.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Using CATKIN_DEVEL_PREFIX: /home/ubuntu2005/project6_ws/devel
-- Using CMAKE_PREFIX_PATH: /opt/ros/noetic
-- This workspace overlays: /opt/ros/noetic
-- Found PythonInterp: /usr/bin/python3 (found suitable version "3.8.10", minimum required is "3") 
-- Using PYTHON_EXECUTABLE: /usr/bin/python3
-- Using Debian Python package layout
-- Found PY_em: /usr/lib/python3/dist-packages/em.py  
-- Using empy: /usr/lib/python3/dist-packages/em.py
-- Using CATKIN_ENABLE_TESTING: ON
-- Call enable_testing()
-- Using CATKIN_TEST_RESULTS_DIR: /home/ubuntu2005/project6_ws/build/test_results
-- Forcing gtest/gmock from source, though one was otherwise available.
-- Found gtest sources under '/usr/src/googletest': gtests will be built
-- Found gmock sources under '/usr/src/googletest': gmock will be built
-- Found PythonInterp: /usr/bin/python3 (found version "3.8.10") 
-- Found Threads: TRUE  
-- Using Python nosetests: /usr/bin/nosetests3
-- catkin 0.8.10
-- BUILD_SHARED_LIBS is on
-- BUILD_SHARED_LIBS is on
-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
-- ~~  traversing 1 packages in topological order:
-- ~~  - project6
-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
-- +++ processing catkin package: 'project6'
-- ==> add_subdirectory(project6)
-- Configuring done
-- Generating done
-- Build files have been written to: /home/ubuntu2005/project6_ws/build
####
#### Running command: "make -j2 -l2" in "/home/ubuntu2005/project6_ws/build"
####
ubuntu2005@ubuntu:~/project6_ws$ mkdir project6_ws
ubuntu2005@ubuntu:~/project6_ws$ cd project6_ws
ubuntu2005@ubuntu:~/project6_ws/project6_ws$ git clone "https://github.com/online-courses-materials/sms-project6.git"
Cloning into 'sms-project6'...
remote: Enumerating objects: 441, done.
remote: Counting objects: 100% (441/441), done.
remote: Compressing objects: 100% (205/205), done.
remote: Total 441 (delta 200), reused 424 (delta 192), pack-reused 0
Receiving objects: 100% (441/441), 9.08 MiB | 4.84 MiB/s, done.
Resolving deltas: 100% (200/200), done.
ubuntu2005@ubuntu:~/project6_ws/project6_ws$ catkin_make
Base path: /home/ubuntu2005/project6_ws/project6_ws
The specified source space "/home/ubuntu2005/project6_ws/project6_ws/src" does not exist
ubuntu2005@ubuntu:~/project6_ws/project6_ws$ ls
sms-project6
ubuntu2005@ubuntu:~/project6_ws/project6_ws$ cd sms-project6
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ ls
README.md  src
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ catkin_make
Base path: /home/ubuntu2005/project6_ws/project6_ws/sms-project6
Source space: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/src
Build space: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/build
Devel space: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel
Install space: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/install
####
#### Running command: "cmake /home/ubuntu2005/project6_ws/project6_ws/sms-project6/src -DCATKIN_DEVEL_PREFIX=/home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel -DCMAKE_INSTALL_PREFIX=/home/ubuntu2005/project6_ws/project6_ws/sms-project6/install -G Unix Makefiles" in "/home/ubuntu2005/project6_ws/project6_ws/sms-project6/build"
####
-- The C compiler identification is GNU 9.4.0
-- The CXX compiler identification is GNU 9.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Using CATKIN_DEVEL_PREFIX: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel
-- Using CMAKE_PREFIX_PATH: /opt/ros/noetic
-- This workspace overlays: /opt/ros/noetic
-- Found PythonInterp: /usr/bin/python3 (found suitable version "3.8.10", minimum required is "3") 
-- Using PYTHON_EXECUTABLE: /usr/bin/python3
-- Using Debian Python package layout
-- Found PY_em: /usr/lib/python3/dist-packages/em.py  
-- Using empy: /usr/lib/python3/dist-packages/em.py
-- Using CATKIN_ENABLE_TESTING: ON
-- Call enable_testing()
-- Using CATKIN_TEST_RESULTS_DIR: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/build/test_results
-- Forcing gtest/gmock from source, though one was otherwise available.
-- Found gtest sources under '/usr/src/googletest': gtests will be built
-- Found gmock sources under '/usr/src/googletest': gmock will be built
-- Found PythonInterp: /usr/bin/python3 (found version "3.8.10") 
-- Found Threads: TRUE  
-- Using Python nosetests: /usr/bin/nosetests3
-- catkin 0.8.10
-- BUILD_SHARED_LIBS is on
-- BUILD_SHARED_LIBS is on
-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
-- ~~  traversing 1 packages in topological order:
-- ~~  - project6
-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
-- +++ processing catkin package: 'project6'
-- ==> add_subdirectory(project6)
-- Using these message generators: gencpp;geneus;genlisp;gennodejs;genpy
-- project6: 0 messages, 2 services
-- Configuring done
-- Generating done
-- Build files have been written to: /home/ubuntu2005/project6_ws/project6_ws/sms-project6/build
####
#### Running command: "make -j2 -l2" in "/home/ubuntu2005/project6_ws/project6_ws/sms-project6/build"
####
Scanning dependencies of target std_msgs_generate_messages_cpp
Scanning dependencies of target _project6_generate_messages_check_deps_TurnCamera
[  0%] Built target std_msgs_generate_messages_cpp
Scanning dependencies of target _project6_generate_messages_check_deps_OddEvenCheck
[  0%] Built target _project6_generate_messages_check_deps_TurnCamera
Scanning dependencies of target sensor_msgs_generate_messages_cpp
[  0%] Built target sensor_msgs_generate_messages_cpp
Scanning dependencies of target speed_calc
[  0%] Built target _project6_generate_messages_check_deps_OddEvenCheck
Scanning dependencies of target rpm_pub
[  4%] Building CXX object project6/CMakeFiles/speed_calc.dir/src/speed_calc.cpp.o
[  8%] Building CXX object project6/CMakeFiles/rpm_pub.dir/src/rpm_pub.cpp.o
[ 12%] Linking CXX executable /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/rpm_pub
[ 16%] Linking CXX executable /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/speed_calc
[ 16%] Built target rpm_pub
Scanning dependencies of target sensor_msgs_generate_messages_py
[ 16%] Built target sensor_msgs_generate_messages_py
Scanning dependencies of target std_msgs_generate_messages_py
[ 16%] Built target std_msgs_generate_messages_py
Scanning dependencies of target std_msgs_generate_messages_lisp
[ 16%] Built target speed_calc
[ 16%] Built target std_msgs_generate_messages_lisp
Scanning dependencies of target sensor_msgs_generate_messages_nodejs
Scanning dependencies of target sensor_msgs_generate_messages_lisp
[ 16%] Built target sensor_msgs_generate_messages_lisp
[ 16%] Built target sensor_msgs_generate_messages_nodejs
Scanning dependencies of target std_msgs_generate_messages_nodejs
Scanning dependencies of target std_msgs_generate_messages_eus
[ 16%] Built target std_msgs_generate_messages_nodejs
[ 16%] Built target std_msgs_generate_messages_eus
Scanning dependencies of target project6_generate_messages_cpp
Scanning dependencies of target sensor_msgs_generate_messages_eus
[ 16%] Built target sensor_msgs_generate_messages_eus
[ 20%] Generating C++ code from project6/OddEvenCheck.srv
Scanning dependencies of target project6_generate_messages_py
[ 25%] Generating Python code from SRV project6/OddEvenCheck
[ 29%] Generating C++ code from project6/TurnCamera.srv
[ 33%] Generating Python code from SRV project6/TurnCamera
[ 33%] Built target project6_generate_messages_cpp
Scanning dependencies of target project6_generate_messages_lisp
[ 37%] Generating Lisp code from project6/OddEvenCheck.srv
[ 41%] Generating Lisp code from project6/TurnCamera.srv
[ 41%] Built target project6_generate_messages_lisp
Scanning dependencies of target project6_generate_messages_nodejs
[ 45%] Generating Javascript code from project6/OddEvenCheck.srv
[ 50%] Generating Python srv __init__.py for project6
[ 54%] Generating Javascript code from project6/TurnCamera.srv
[ 54%] Built target project6_generate_messages_nodejs
Scanning dependencies of target project6_generate_messages_eus
[ 58%] Generating EusLisp code from project6/OddEvenCheck.srv
[ 58%] Built target project6_generate_messages_py
Scanning dependencies of target turn_camera_service_server
[ 62%] Generating EusLisp code from project6/TurnCamera.srv
[ 66%] Building CXX object project6/CMakeFiles/turn_camera_service_server.dir/src/turn_camera_service_server.cpp.o
[ 70%] Generating EusLisp manifest code for project6
[ 70%] Built target project6_generate_messages_eus
Scanning dependencies of target service_client
[ 75%] Building CXX object project6/CMakeFiles/service_client.dir/src/service_client.cpp.o
[ 79%] Linking CXX executable /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/service_client
[ 79%] Built target service_client
Scanning dependencies of target turn_camera_service_client
[ 83%] Building CXX object project6/CMakeFiles/turn_camera_service_client.dir/src/turn_camera_service_client.cpp.o
[ 87%] Linking CXX executable /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/turn_camera_service_server
[ 87%] Built target turn_camera_service_server
Scanning dependencies of target service_server
[ 91%] Building CXX object project6/CMakeFiles/service_server.dir/src/service_server.cpp.o
[ 95%] Linking CXX executable /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/turn_camera_service_client
[100%] Linking CXX executable /home/ubuntu2005/project6_ws/project6_ws/sms-project6/devel/lib/project6/service_server
[100%] Built target service_server
Scanning dependencies of target project6_generate_messages
[100%] Built target project6_generate_messages
[100%] Built target turn_camera_service_client
ubuntu2005@ubuntu:~/project6_ws/project6_ws/sms-project6$ 

```

#Restarting the roscore in the command line

```
ubuntu2005@ubuntu:~/project6_ws/project6_ws$ roscore
... logging to /home/ubuntu2005/.ros/log/9abba9a4-fd41-11ed-8577-a178a7ecd0de/roslaunch-ubuntu-4192.log
Checking log directory for disk usage. This may take a while.
Press Ctrl-C to interrupt
Done checking log file disk usage. Usage is <1GB.

started roslaunch server http://ubuntu:36435/
ros_comm version 1.16.0


SUMMARY
========

PARAMETERS
 * /rosdistro: noetic
 * /rosversion: 1.16.0

NODES

auto-starting new master
process[master]: started with pid [4203]
ROS_MASTER_URI=http://ubuntu:11311/

setting /run_id to 9abba9a4-fd41-11ed-8577-a178a7ecd0de
process[rosout-1]: started with pid [4213]
started core service [/rosout]


```


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

