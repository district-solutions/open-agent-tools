# Agent Python Tools

- repo: facebookresearch/learningtolearn
- repo_uri: https://github.com/facebookresearch/learningtolearn

## File: facebookresearch_learningtolearn/ml3/envs/bullet_sim.py

Prompts

```
['create a BulletSimulationFromURDF instance by loading a robot URDF file with controlled joints and torque limits', 'create a BulletSimulationFromMJCF instance by loading a robot MJCF XML file with controlled joints and torque limits', 'reset the robot simulation to specified joint positions and velocities using the reset method', 'step the simulation forward by applying torque to controlled joints and returning the next state', 'calculate the target joint configuration for a desired end-effector position using inverse kinematics', 'create a MountainCar environment instance with default physics parameters for reinforcement learning', 'run a single simulation step on the MountainCar environment with a given action and get state and reward', 'run a stateless simulation step using numpy to compute the next state from a given state and action', 'run a stateless simulation step using PyTorch tensors to compute the next state from a given state and action', 'render a gif or mp4 animation of the MountainCar episode trajectory from a list of positions']
```

Usage

```
{'create_bullet_simulation_from_urdf': 'create a BulletSimulationFromURDF instance by loading a robot URDF file with controlled joints and torque limits', 'create_bullet_simulation_from_mjcf': 'create a BulletSimulationFromMJCF instance by loading a robot MJCF XML file with controlled joints and torque limits', 'reset_robot_joints': 'reset the robot simulation to specified joint positions and velocities using the reset method', 'step_simulation_with_torque': 'step the simulation forward by applying torque to controlled joints and returning the next state', 'calculate_inverse_kinematics': 'calculate the target joint configuration for a desired end-effector position using inverse kinematics'}
```

## File: facebookresearch_learningtolearn/ml3/envs/mountain_car.py

Prompts

```
['create a BulletSimulationFromURDF instance by loading a robot URDF file with controlled joints and torque limits', 'create a BulletSimulationFromMJCF instance by loading a robot MJCF XML file with controlled joints and torque limits', 'reset the robot simulation to specified joint positions and velocities using the reset method', 'step the simulation forward by applying torque to controlled joints and returning the next state', 'calculate the target joint configuration for a desired end-effector position using inverse kinematics', 'create a MountainCar environment instance with default physics parameters for reinforcement learning', 'run a single simulation step on the MountainCar environment with a given action and get state and reward', 'run a stateless simulation step using numpy to compute the next state from a given state and action', 'run a stateless simulation step using PyTorch tensors to compute the next state from a given state and action', 'render a gif or mp4 animation of the MountainCar episode trajectory from a list of positions']
```

Usage

```
{'create_mountain_car_env': 'create a MountainCar environment instance with default physics parameters for reinforcement learning', 'run_mountain_car_step': 'run a single simulation step on the MountainCar environment with a given action and get state and reward', 'run_mountain_car_sim_step': 'run a stateless simulation step using numpy to compute the next state from a given state and action', 'run_mountain_car_sim_step_torch': 'run a stateless simulation step using PyTorch tensors to compute the next state from a given state and action', 'render_mountain_car_animation': 'render a gif or mp4 animation of the MountainCar episode trajectory from a list of positions'}
```

