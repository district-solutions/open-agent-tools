# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/tasks/simple_locomotion_task.py

Prompts

```
['create a SimpleForwardTask instance with custom weight and terminal condition for a minitaur robot', 'reset the SimpleForwardTask by capturing the robot base position and initializing the action history sensor', 'calculate the forward locomotion reward based on velocity, action acceleration penalty, and energy consumption', 'check if the task is done by evaluating the minimum COM height and terminal condition', 'update the SimpleForwardTask internal state by refreshing the last robot base position', 'implement a subclass of Task that overrides reward, reset, update, and done methods', 'override the Task reward method to return a float based on the gym environment state', 'override the Task reset method to initialize task state when the environment resets', 'override the Task update method to update internal task state each step', 'override the Task done method to return a boolean indicating task completion', 'interpolate target speed from a speed profile and simulation timesteps for robot locomotion tasks', 'calculate the Euclidean distance between two vectors in 3D space using numpy', 'calculate the change in orientation angle between two robot front vectors projected to the x-y plane', 'calculate the front vector of a robot from its quaternion orientation using a PyBullet client', 'estimate total motor energy consumption in watts from torques, velocities, and simulation parameters', 'check if the Minitaur robot has fallen by evaluating base orientation and height', 'check if Laikago v2 has fallen using configurable roll, pitch, height, and foot contact thresholds', 'check if an agile robot episode should terminate based on roll, pitch, height, and unwanted collisions', 'create a MaxTimeTerminalCondition class instance that terminates an episode after a given simulation time limit', 'create a MovementDetectorTerminalCondition that terminates an episode if the robot stops advancing within a time window']
```

Usage

```
{'create_SimpleForwardTask': 'create a SimpleForwardTask instance with custom weight and terminal condition for a minitaur robot', 'reset_SimpleForwardTask': 'reset the SimpleForwardTask by capturing the robot base position and initializing the action history sensor', 'reward_SimpleForwardTask': 'calculate the forward locomotion reward based on velocity, action acceleration penalty, and energy consumption', 'done_SimpleForwardTask': 'check if the task is done by evaluating the minimum COM height and terminal condition', 'update_SimpleForwardTask': 'update the SimpleForwardTask internal state by refreshing the last robot base position'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/tasks/task_interface.py

Prompts

```
['create a SimpleForwardTask instance with custom weight and terminal condition for a minitaur robot', 'reset the SimpleForwardTask by capturing the robot base position and initializing the action history sensor', 'calculate the forward locomotion reward based on velocity, action acceleration penalty, and energy consumption', 'check if the task is done by evaluating the minimum COM height and terminal condition', 'update the SimpleForwardTask internal state by refreshing the last robot base position', 'implement a subclass of Task that overrides reward, reset, update, and done methods', 'override the Task reward method to return a float based on the gym environment state', 'override the Task reset method to initialize task state when the environment resets', 'override the Task update method to update internal task state each step', 'override the Task done method to return a boolean indicating task completion', 'interpolate target speed from a speed profile and simulation timesteps for robot locomotion tasks', 'calculate the Euclidean distance between two vectors in 3D space using numpy', 'calculate the change in orientation angle between two robot front vectors projected to the x-y plane', 'calculate the front vector of a robot from its quaternion orientation using a PyBullet client', 'estimate total motor energy consumption in watts from torques, velocities, and simulation parameters', 'check if the Minitaur robot has fallen by evaluating base orientation and height', 'check if Laikago v2 has fallen using configurable roll, pitch, height, and foot contact thresholds', 'check if an agile robot episode should terminate based on roll, pitch, height, and unwanted collisions', 'create a MaxTimeTerminalCondition class instance that terminates an episode after a given simulation time limit', 'create a MovementDetectorTerminalCondition that terminates an episode if the robot stops advancing within a time window']
```

Usage

```
{'implement_Task_subclass': 'implement a subclass of Task that overrides reward, reset, update, and done methods', 'override_Task_reward': 'override the Task reward method to return a float based on the gym environment state', 'override_Task_reset': 'override the Task reset method to initialize task state when the environment resets', 'override_Task_update': 'override the Task update method to update internal task state each step', 'override_Task_done': 'override the Task done method to return a boolean indicating task completion'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/tasks/task_utils.py

Prompts

```
['create a SimpleForwardTask instance with custom weight and terminal condition for a minitaur robot', 'reset the SimpleForwardTask by capturing the robot base position and initializing the action history sensor', 'calculate the forward locomotion reward based on velocity, action acceleration penalty, and energy consumption', 'check if the task is done by evaluating the minimum COM height and terminal condition', 'update the SimpleForwardTask internal state by refreshing the last robot base position', 'implement a subclass of Task that overrides reward, reset, update, and done methods', 'override the Task reward method to return a float based on the gym environment state', 'override the Task reset method to initialize task state when the environment resets', 'override the Task update method to update internal task state each step', 'override the Task done method to return a boolean indicating task completion', 'interpolate target speed from a speed profile and simulation timesteps for robot locomotion tasks', 'calculate the Euclidean distance between two vectors in 3D space using numpy', 'calculate the change in orientation angle between two robot front vectors projected to the x-y plane', 'calculate the front vector of a robot from its quaternion orientation using a PyBullet client', 'estimate total motor energy consumption in watts from torques, velocities, and simulation parameters', 'check if the Minitaur robot has fallen by evaluating base orientation and height', 'check if Laikago v2 has fallen using configurable roll, pitch, height, and foot contact thresholds', 'check if an agile robot episode should terminate based on roll, pitch, height, and unwanted collisions', 'create a MaxTimeTerminalCondition class instance that terminates an episode after a given simulation time limit', 'create a MovementDetectorTerminalCondition that terminates an episode if the robot stops advancing within a time window']
```

Usage

```
{'calculate_target_speed_at_timestep': 'interpolate target speed from a speed profile and simulation timesteps for robot locomotion tasks', 'calculate_distance': 'calculate the Euclidean distance between two vectors in 3D space using numpy', 'turn_angle': 'calculate the change in orientation angle between two robot front vectors projected to the x-y plane', 'front_vector': 'calculate the front vector of a robot from its quaternion orientation using a PyBullet client', 'calculate_estimated_energy_consumption': 'estimate total motor energy consumption in watts from torques, velocities, and simulation parameters'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/tasks/terminal_conditions.py

Prompts

```
['create a SimpleForwardTask instance with custom weight and terminal condition for a minitaur robot', 'reset the SimpleForwardTask by capturing the robot base position and initializing the action history sensor', 'calculate the forward locomotion reward based on velocity, action acceleration penalty, and energy consumption', 'check if the task is done by evaluating the minimum COM height and terminal condition', 'update the SimpleForwardTask internal state by refreshing the last robot base position', 'implement a subclass of Task that overrides reward, reset, update, and done methods', 'override the Task reward method to return a float based on the gym environment state', 'override the Task reset method to initialize task state when the environment resets', 'override the Task update method to update internal task state each step', 'override the Task done method to return a boolean indicating task completion', 'interpolate target speed from a speed profile and simulation timesteps for robot locomotion tasks', 'calculate the Euclidean distance between two vectors in 3D space using numpy', 'calculate the change in orientation angle between two robot front vectors projected to the x-y plane', 'calculate the front vector of a robot from its quaternion orientation using a PyBullet client', 'estimate total motor energy consumption in watts from torques, velocities, and simulation parameters', 'check if the Minitaur robot has fallen by evaluating base orientation and height', 'check if Laikago v2 has fallen using configurable roll, pitch, height, and foot contact thresholds', 'check if an agile robot episode should terminate based on roll, pitch, height, and unwanted collisions', 'create a MaxTimeTerminalCondition class instance that terminates an episode after a given simulation time limit', 'create a MovementDetectorTerminalCondition that terminates an episode if the robot stops advancing within a time window']
```

Usage

```
{'check_minitaur_fallen': 'check if the Minitaur robot has fallen by evaluating base orientation and height', 'check_laikago_v2_terminal': 'check if Laikago v2 has fallen using configurable roll, pitch, height, and foot contact thresholds', 'check_agility_terminal': 'check if an agile robot episode should terminate based on roll, pitch, height, and unwanted collisions', 'create_maxtime_terminal': 'create a MaxTimeTerminalCondition class instance that terminates an episode after a given simulation time limit', 'create_movement_detector_terminal': 'create a MovementDetectorTerminalCondition that terminates an episode if the robot stops advancing within a time window'}
```

