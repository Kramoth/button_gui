# button_gui

This package contain one node button_gui.py

When running, a window appears with a button, when the button has been clicked a topic named "button_state" is updated.

To install this package,

clone it into the src folder in your catkin workspace

```sh
cd ~/catkin_ws/src
git clone https://github.com/Kramoth/button_gui.git
catkin build
source ~/catkin_ws/devel/setup.bash
rosrun button_gui button_gui.py
```
When running a window pops up with a button named toggle, when it is clicked, the button state change, you can observe the topic /button_state to see how the click changes the topic.
