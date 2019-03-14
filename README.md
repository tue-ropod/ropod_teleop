# ropod_teleop

## Summary

A joypad for the ROPOD platform.

## Supported key combinations

* Controller initialisation: `LB + RB + A`
* Controller stopping: `LB + RB + X`
* Linear motion: `RB + left axis`
* Rotation: `RB + right axis`
* Docking: `RB + LB + B`
* Undocking: `RB + LB + Y`
* Event registration for data annotation: `LB + X`
* Individual smart wheel motion:
    * Wheel 1: `RB + Y + cross Y`
    * Wheel 2: `RB + B + cross Y`
    * Wheel 3: `RB + A + cross Y`
    * Wheel 4: `RB + X + cross Y`

## Dependencies

* `rospy`
* `roslaunch`
* `joy`
* `sensor_msgs`
* `geometry_msgs`
* `actionlib_msgs`
* `ropod_ros_msgs`
