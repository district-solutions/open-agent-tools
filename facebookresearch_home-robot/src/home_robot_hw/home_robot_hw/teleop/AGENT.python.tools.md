# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/teleop/keyboard_teleop.py

Prompts

```
['run the keyboard teleoperation loop for the Stretch robot using run_teleop', 'create a RobotController instance to connect to and control a Stretch robot', 'switch between NAV and MANIP control modes using RobotController _switch_mode method', 'compute a net movement command from positive and negative key states using _compute_net_command', 'handle keyboard press and release events using RobotController on_press and on_release callbacks', 'create a StretchXboxController instance to teleoperate a Stretch robot using an Xbox controller via ROS joy messages', 'convert a ROS Joy message into a dictionary mapping Xbox controller axes and buttons to named state keys', 'handle incoming joystick messages to command robot base movement, arm lift, wrist rotation, gripper, and head motion', 'create a timer callback that repeatedly extends the robot arm based on the current controller state', 'create a timer callback that repeatedly commands robot base translation and rotation velocity from controller input', 'run the stretch robot xbox controller teleoperation main loop for live robot control', 'create a CommandToLinearMotion instance to convert joystick commands into distance, velocity, and acceleration values', 'create a CommandToRotaryMotion instance to convert joystick commands into angle, velocity, and acceleration values', 'manage the robot base translation and rotation using xbox controller left stick and right trigger inputs', 'manage the robot head pan and tilt using xbox controller directional pad button inputs']
```

Usage

```
{'run_teleop_keyboard': 'run the keyboard teleoperation loop for the Stretch robot using run_teleop', 'create_robot_controller': 'create a RobotController instance to connect to and control a Stretch robot', 'switch_control_mode': 'switch between NAV and MANIP control modes using RobotController _switch_mode method', 'compute_net_command': 'compute a net movement command from positive and negative key states using _compute_net_command', 'handle_keyboard_input': 'handle keyboard press and release events using RobotController on_press and on_release callbacks'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/teleop/stretch_xbox_controller.py

Prompts

```
['run the keyboard teleoperation loop for the Stretch robot using run_teleop', 'create a RobotController instance to connect to and control a Stretch robot', 'switch between NAV and MANIP control modes using RobotController _switch_mode method', 'compute a net movement command from positive and negative key states using _compute_net_command', 'handle keyboard press and release events using RobotController on_press and on_release callbacks', 'create a StretchXboxController instance to teleoperate a Stretch robot using an Xbox controller via ROS joy messages', 'convert a ROS Joy message into a dictionary mapping Xbox controller axes and buttons to named state keys', 'handle incoming joystick messages to command robot base movement, arm lift, wrist rotation, gripper, and head motion', 'create a timer callback that repeatedly extends the robot arm based on the current controller state', 'create a timer callback that repeatedly commands robot base translation and rotation velocity from controller input', 'run the stretch robot xbox controller teleoperation main loop for live robot control', 'create a CommandToLinearMotion instance to convert joystick commands into distance, velocity, and acceleration values', 'create a CommandToRotaryMotion instance to convert joystick commands into angle, velocity, and acceleration values', 'manage the robot base translation and rotation using xbox controller left stick and right trigger inputs', 'manage the robot head pan and tilt using xbox controller directional pad button inputs']
```

Usage

```
{'create_StretchXboxController': 'create a StretchXboxController instance to teleoperate a Stretch robot using an Xbox controller via ROS joy messages', 'convert_joy_msg_to_xbox_state': 'convert a ROS Joy message into a dictionary mapping Xbox controller axes and buttons to named state keys', 'joystick_callback': 'handle incoming joystick messages to command robot base movement, arm lift, wrist rotation, gripper, and head motion', 'create_arm_extension_loop': 'create a timer callback that repeatedly extends the robot arm based on the current controller state', 'create_move_base_loop': 'create a timer callback that repeatedly commands robot base translation and rotation velocity from controller input'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/teleop/stretch_xbox_controller_teleop.py

Prompts

```
['run the keyboard teleoperation loop for the Stretch robot using run_teleop', 'create a RobotController instance to connect to and control a Stretch robot', 'switch between NAV and MANIP control modes using RobotController _switch_mode method', 'compute a net movement command from positive and negative key states using _compute_net_command', 'handle keyboard press and release events using RobotController on_press and on_release callbacks', 'create a StretchXboxController instance to teleoperate a Stretch robot using an Xbox controller via ROS joy messages', 'convert a ROS Joy message into a dictionary mapping Xbox controller axes and buttons to named state keys', 'handle incoming joystick messages to command robot base movement, arm lift, wrist rotation, gripper, and head motion', 'create a timer callback that repeatedly extends the robot arm based on the current controller state', 'create a timer callback that repeatedly commands robot base translation and rotation velocity from controller input', 'run the stretch robot xbox controller teleoperation main loop for live robot control', 'create a CommandToLinearMotion instance to convert joystick commands into distance, velocity, and acceleration values', 'create a CommandToRotaryMotion instance to convert joystick commands into angle, velocity, and acceleration values', 'manage the robot base translation and rotation using xbox controller left stick and right trigger inputs', 'manage the robot head pan and tilt using xbox controller directional pad button inputs']
```

Usage

```
{'run_xbox_teleop': 'run the stretch robot xbox controller teleoperation main loop for live robot control', 'create_linear_motion_command': 'create a CommandToLinearMotion instance to convert joystick commands into distance, velocity, and acceleration values', 'create_rotary_motion_command': 'create a CommandToRotaryMotion instance to convert joystick commands into angle, velocity, and acceleration values', 'manage_base_motion': 'manage the robot base translation and rotation using xbox controller left stick and right trigger inputs', 'manage_head_motion': 'manage the robot head pan and tilt using xbox controller directional pad button inputs'}
```

