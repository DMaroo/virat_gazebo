# virat_potholes

Gazebo and ROS integration of Abhiyaan's VIRAT model, used for detecting potholes (IGVC challenge)

## Setting up

To launch the `grass_plane` world, run

```
roslaunch virat_potholes grass_world.launch
```

To launch VIRAT in the `grass_plane` world, run

```
roslaunch virat_potholes spawn_virat.launch
```

## Navigation

To navigate, first of all launch the `spawn_virat.launch` file. Now in a new terminal, run

```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```