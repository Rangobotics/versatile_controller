# versatile_controller

A collection of ROS packages for a controller that can be used for navigating a global path (using a carrot point at a horizon distance), or to arrive as straight as possible to a goal (align with y axis and yaw angle first then steer towards the xy position).

## ROS2 Integration

## Parameters

## Interfaces

## Jerk Limited Profiles

This controller uses `ruckig` to limit jerk.

## Benchmark

## Navigation2 Plugin integration

## Reference

Based on "A Smooth Control Law for Graceful Motion of Differential Wheeled Mobile Robots in 2D Environments" by Park and Kuipers, ICRA 2011.
