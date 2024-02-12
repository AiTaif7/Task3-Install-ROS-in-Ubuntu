# Task3-Install-ROS-in-Ubuntu

1- install Ubuntu

2- Setup The sources.list:

  { sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' }
  
3- Set up The keys:

  { curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add - }

4- Update packages:

{ sudo apt update }

5- Desktop-Full Install, Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages:

{ sudo apt install ros-noetic-desktop-full }

6- Environment setup:

{ source /opt/ros/noetic/setup.bash }
