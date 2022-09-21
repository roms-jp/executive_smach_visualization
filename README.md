executive_smach_visualization [![Build Status](https://travis-ci.com/ros-visualization/executive_smach_visualization.svg?branch=melodic-devel)](https://travis-ci.com/ros-visualization/executive_smach_visualization)
=====================================================================================================================================================================================================================

## Installing Dependencies

```bash
# update
sudo apt-get update

# Installing system python-gi python-gi-cairo libgtk-3-dev
sudo apt-get install -y python-gi python-gi-cairo python-wxversion libgtk-3-dev

# Installing python3 wxpython graphviz
sudo apt install python3-wxgtk4.0 --fix-missing
```

## Command

```bash
ros2 run smach_viewer smach_viewer_gui.py
```
