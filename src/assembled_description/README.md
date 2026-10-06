# assembled_description

Combined UR10e arm and Robotiq 2F-85 gripper description. The gripper is
attached to the arm's `tool0` frame using the adapter supplied by
`robotiq_description`.

After building and sourcing the workspace, view the robot with:

```bash
ros2 launch assembled_description view_assembled_robot.launch.py
```

The launch starts `robot_state_publisher`, the joint-state publisher GUI, and
RViz2. Joint positions can be adjusted in the GUI.
