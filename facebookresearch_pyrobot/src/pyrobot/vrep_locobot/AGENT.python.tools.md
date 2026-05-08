# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/src/pyrobot/vrep_locobot/arm.py

Prompts

```
['compute inverse kinematics to get joint angles for a desired end-effector position and orientation', 'command the robot arm to move to a desired end-effector pose using IK and path planning', 'get the current joint angles of all arm joints as a numpy array', 'compute forward kinematics to get the end-effector position and rotation matrix from joint angles', 'move the end effector by a displacement in xyz directions with linear interpolation and IK solving', 'initialize a LoCoBotBase instance with configs and a V-Rep simulator object', 'get the current 2D pose as an (x, y, yaw) tuple from the LoCoBotBase', 'check if the LoCoBotBase robot is currently in collision using the in_collision property', 'stop the LoCoBotBase robot by setting both joint target velocities to zero', 'move the LoCoBotBase robot to a goal state relative to its current pose', 'capture an RGB image from the LoCoBot Kinect RGB camera sensor in V-REP simulation', 'capture a depth image from the LoCoBot Kinect depth camera sensor in V-REP simulation', 'capture both RGB and depth images simultaneously from the LoCoBot Kinect camera sensors', 'set the pan and tilt joint angles of the LoCoBot head camera to specified values', 'get the current pan and tilt joint angles of the LoCoBot head camera as a list', 'create a LoCoBotGripper instance with configs and simulator to control a VREP gripper', 'open the LoCoBotGripper fully by calling the open method with a blocking wait', 'close the LoCoBotGripper fully by calling the close method with a blocking wait', 'get the current LoCoBotGripper state returning 0 for open, 2 for holding, or 3 for closed', 'reset a stuck LoCoBotGripper by calling open, close, then open in sequence', 'create a VrepSim instance with configs and a v-rep scene file path to launch the simulator', 'build a VrepSim that launches a CoppeliaSim scene in non-headless mode and runs 50 initial steps', 'review the VrepSim reset method which raises NotImplemented for v-rep simulator reset', 'summarize the VrepSim destructor that stops and shuts down the PyRep simulator on deletion', 'review the VrepSim class that interfaces with Habitat sim using PyRep and CoppeliaSim']
```

Usage

```
{'compute_ik_joint_angles': 'compute inverse kinematics to get joint angles for a desired end-effector position and orientation', 'set_ee_pose': 'command the robot arm to move to a desired end-effector pose using IK and path planning', 'get_joint_angles': 'get the current joint angles of all arm joints as a numpy array', 'compute_fk_position': 'compute forward kinematics to get the end-effector position and rotation matrix from joint angles', 'move_ee_xyz': 'move the end effector by a displacement in xyz directions with linear interpolation and IK solving'}
```

## File: facebookresearch_pyrobot/src/pyrobot/vrep_locobot/base.py

Prompts

```
['compute inverse kinematics to get joint angles for a desired end-effector position and orientation', 'command the robot arm to move to a desired end-effector pose using IK and path planning', 'get the current joint angles of all arm joints as a numpy array', 'compute forward kinematics to get the end-effector position and rotation matrix from joint angles', 'move the end effector by a displacement in xyz directions with linear interpolation and IK solving', 'initialize a LoCoBotBase instance with configs and a V-Rep simulator object', 'get the current 2D pose as an (x, y, yaw) tuple from the LoCoBotBase', 'check if the LoCoBotBase robot is currently in collision using the in_collision property', 'stop the LoCoBotBase robot by setting both joint target velocities to zero', 'move the LoCoBotBase robot to a goal state relative to its current pose', 'capture an RGB image from the LoCoBot Kinect RGB camera sensor in V-REP simulation', 'capture a depth image from the LoCoBot Kinect depth camera sensor in V-REP simulation', 'capture both RGB and depth images simultaneously from the LoCoBot Kinect camera sensors', 'set the pan and tilt joint angles of the LoCoBot head camera to specified values', 'get the current pan and tilt joint angles of the LoCoBot head camera as a list', 'create a LoCoBotGripper instance with configs and simulator to control a VREP gripper', 'open the LoCoBotGripper fully by calling the open method with a blocking wait', 'close the LoCoBotGripper fully by calling the close method with a blocking wait', 'get the current LoCoBotGripper state returning 0 for open, 2 for holding, or 3 for closed', 'reset a stuck LoCoBotGripper by calling open, close, then open in sequence', 'create a VrepSim instance with configs and a v-rep scene file path to launch the simulator', 'build a VrepSim that launches a CoppeliaSim scene in non-headless mode and runs 50 initial steps', 'review the VrepSim reset method which raises NotImplemented for v-rep simulator reset', 'summarize the VrepSim destructor that stops and shuts down the PyRep simulator on deletion', 'review the VrepSim class that interfaces with Habitat sim using PyRep and CoppeliaSim']
```

Usage

```
{'init_locobot_base': 'initialize a LoCoBotBase instance with configs and a V-Rep simulator object', 'get_state_locobot': 'get the current 2D pose as an (x, y, yaw) tuple from the LoCoBotBase', 'check_collision_locobot': 'check if the LoCoBotBase robot is currently in collision using the in_collision property', 'stop_locobot': 'stop the LoCoBotBase robot by setting both joint target velocities to zero', 'go_to_relative_locobot': 'move the LoCoBotBase robot to a goal state relative to its current pose'}
```

## File: facebookresearch_pyrobot/src/pyrobot/vrep_locobot/camera.py

Prompts

```
['compute inverse kinematics to get joint angles for a desired end-effector position and orientation', 'command the robot arm to move to a desired end-effector pose using IK and path planning', 'get the current joint angles of all arm joints as a numpy array', 'compute forward kinematics to get the end-effector position and rotation matrix from joint angles', 'move the end effector by a displacement in xyz directions with linear interpolation and IK solving', 'initialize a LoCoBotBase instance with configs and a V-Rep simulator object', 'get the current 2D pose as an (x, y, yaw) tuple from the LoCoBotBase', 'check if the LoCoBotBase robot is currently in collision using the in_collision property', 'stop the LoCoBotBase robot by setting both joint target velocities to zero', 'move the LoCoBotBase robot to a goal state relative to its current pose', 'capture an RGB image from the LoCoBot Kinect RGB camera sensor in V-REP simulation', 'capture a depth image from the LoCoBot Kinect depth camera sensor in V-REP simulation', 'capture both RGB and depth images simultaneously from the LoCoBot Kinect camera sensors', 'set the pan and tilt joint angles of the LoCoBot head camera to specified values', 'get the current pan and tilt joint angles of the LoCoBot head camera as a list', 'create a LoCoBotGripper instance with configs and simulator to control a VREP gripper', 'open the LoCoBotGripper fully by calling the open method with a blocking wait', 'close the LoCoBotGripper fully by calling the close method with a blocking wait', 'get the current LoCoBotGripper state returning 0 for open, 2 for holding, or 3 for closed', 'reset a stuck LoCoBotGripper by calling open, close, then open in sequence', 'create a VrepSim instance with configs and a v-rep scene file path to launch the simulator', 'build a VrepSim that launches a CoppeliaSim scene in non-headless mode and runs 50 initial steps', 'review the VrepSim reset method which raises NotImplemented for v-rep simulator reset', 'summarize the VrepSim destructor that stops and shuts down the PyRep simulator on deletion', 'review the VrepSim class that interfaces with Habitat sim using PyRep and CoppeliaSim']
```

Usage

```
{'capture_rgb_image': 'capture an RGB image from the LoCoBot Kinect RGB camera sensor in V-REP simulation', 'capture_depth_image': 'capture a depth image from the LoCoBot Kinect depth camera sensor in V-REP simulation', 'capture_rgb_and_depth': 'capture both RGB and depth images simultaneously from the LoCoBot Kinect camera sensors', 'set_camera_pan_tilt': 'set the pan and tilt joint angles of the LoCoBot head camera to specified values', 'get_camera_state': 'get the current pan and tilt joint angles of the LoCoBot head camera as a list'}
```

## File: facebookresearch_pyrobot/src/pyrobot/vrep_locobot/gripper.py

Prompts

```
['compute inverse kinematics to get joint angles for a desired end-effector position and orientation', 'command the robot arm to move to a desired end-effector pose using IK and path planning', 'get the current joint angles of all arm joints as a numpy array', 'compute forward kinematics to get the end-effector position and rotation matrix from joint angles', 'move the end effector by a displacement in xyz directions with linear interpolation and IK solving', 'initialize a LoCoBotBase instance with configs and a V-Rep simulator object', 'get the current 2D pose as an (x, y, yaw) tuple from the LoCoBotBase', 'check if the LoCoBotBase robot is currently in collision using the in_collision property', 'stop the LoCoBotBase robot by setting both joint target velocities to zero', 'move the LoCoBotBase robot to a goal state relative to its current pose', 'capture an RGB image from the LoCoBot Kinect RGB camera sensor in V-REP simulation', 'capture a depth image from the LoCoBot Kinect depth camera sensor in V-REP simulation', 'capture both RGB and depth images simultaneously from the LoCoBot Kinect camera sensors', 'set the pan and tilt joint angles of the LoCoBot head camera to specified values', 'get the current pan and tilt joint angles of the LoCoBot head camera as a list', 'create a LoCoBotGripper instance with configs and simulator to control a VREP gripper', 'open the LoCoBotGripper fully by calling the open method with a blocking wait', 'close the LoCoBotGripper fully by calling the close method with a blocking wait', 'get the current LoCoBotGripper state returning 0 for open, 2 for holding, or 3 for closed', 'reset a stuck LoCoBotGripper by calling open, close, then open in sequence', 'create a VrepSim instance with configs and a v-rep scene file path to launch the simulator', 'build a VrepSim that launches a CoppeliaSim scene in non-headless mode and runs 50 initial steps', 'review the VrepSim reset method which raises NotImplemented for v-rep simulator reset', 'summarize the VrepSim destructor that stops and shuts down the PyRep simulator on deletion', 'review the VrepSim class that interfaces with Habitat sim using PyRep and CoppeliaSim']
```

Usage

```
{'create_locobot_gripper': 'create a LoCoBotGripper instance with configs and simulator to control a VREP gripper', 'open_gripper': 'open the LoCoBotGripper fully by calling the open method with a blocking wait', 'close_gripper': 'close the LoCoBotGripper fully by calling the close method with a blocking wait', 'get_gripper_state': 'get the current LoCoBotGripper state returning 0 for open, 2 for holding, or 3 for closed', 'reset_gripper': 'reset a stuck LoCoBotGripper by calling open, close, then open in sequence'}
```

## File: facebookresearch_pyrobot/src/pyrobot/vrep_locobot/simulator.py

Prompts

```
['compute inverse kinematics to get joint angles for a desired end-effector position and orientation', 'command the robot arm to move to a desired end-effector pose using IK and path planning', 'get the current joint angles of all arm joints as a numpy array', 'compute forward kinematics to get the end-effector position and rotation matrix from joint angles', 'move the end effector by a displacement in xyz directions with linear interpolation and IK solving', 'initialize a LoCoBotBase instance with configs and a V-Rep simulator object', 'get the current 2D pose as an (x, y, yaw) tuple from the LoCoBotBase', 'check if the LoCoBotBase robot is currently in collision using the in_collision property', 'stop the LoCoBotBase robot by setting both joint target velocities to zero', 'move the LoCoBotBase robot to a goal state relative to its current pose', 'capture an RGB image from the LoCoBot Kinect RGB camera sensor in V-REP simulation', 'capture a depth image from the LoCoBot Kinect depth camera sensor in V-REP simulation', 'capture both RGB and depth images simultaneously from the LoCoBot Kinect camera sensors', 'set the pan and tilt joint angles of the LoCoBot head camera to specified values', 'get the current pan and tilt joint angles of the LoCoBot head camera as a list', 'create a LoCoBotGripper instance with configs and simulator to control a VREP gripper', 'open the LoCoBotGripper fully by calling the open method with a blocking wait', 'close the LoCoBotGripper fully by calling the close method with a blocking wait', 'get the current LoCoBotGripper state returning 0 for open, 2 for holding, or 3 for closed', 'reset a stuck LoCoBotGripper by calling open, close, then open in sequence', 'create a VrepSim instance with configs and a v-rep scene file path to launch the simulator', 'build a VrepSim that launches a CoppeliaSim scene in non-headless mode and runs 50 initial steps', 'review the VrepSim reset method which raises NotImplemented for v-rep simulator reset', 'summarize the VrepSim destructor that stops and shuts down the PyRep simulator on deletion', 'review the VrepSim class that interfaces with Habitat sim using PyRep and CoppeliaSim']
```

Usage

```
{'init_VrepSim': 'create a VrepSim instance with configs and a v-rep scene file path to launch the simulator', 'launch_VrepSim': 'build a VrepSim that launches a CoppeliaSim scene in non-headless mode and runs 50 initial steps', 'reset_VrepSim': 'review the VrepSim reset method which raises NotImplemented for v-rep simulator reset', 'cleanup_VrepSim': 'summarize the VrepSim destructor that stops and shuts down the PyRep simulator on deletion', 'review_VrepSim_class': 'review the VrepSim class that interfaces with Habitat sim using PyRep and CoppeliaSim'}
```

