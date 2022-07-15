# Install-ROS-on-Ubuntu

## Step 1: Download Ubuntu 20.04.4 LTS (Focal Fossa)
https://releases.ubuntu.com/focal/

## Step 2: Download VirtualBox
click on Windows hosts
https://www.virtualbox.org/wiki/Downloads

## Step 3: Ubuntu install of ROS Noetic
open the terminal and Write sequentially the following codes
### Setup your sources.list
Setup your computer to accept software from packages.ros.org.
####sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
Mirrors Source Debs are also available

http://wiki.ros.org/noetic/Installation/Ubuntu
