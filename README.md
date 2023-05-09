Installing
----------
```bash
sudo apt install ros-${ROS_DISTRO}-multirobot-map-merge ros-${ROS_DISTRO}-explore-lite
```

Building
----------
```bash
mkdir ~/mexp_ws/src -p
cd ~/mexp_ws/src
git clone https://github.com/hrnr/m-explore
cd ~/mexp_ws
catkin_make
```
