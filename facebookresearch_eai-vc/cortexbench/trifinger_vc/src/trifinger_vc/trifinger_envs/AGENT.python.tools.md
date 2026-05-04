# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/trifinger_vc/src/trifinger_vc/trifinger_envs/cube_reach.py

Prompts

```
['build a python module to create a CubeReachEnv gym environment for TriFingerPro cube reaching simulation', 'run a single step of the CubeReachEnv simulation with a given 3D action vector', 'test the CubeReachEnv reset method to initialize robot position and goal pose', 'review the HandKinematics class get_ft_pos method for computing fingertip positions from joint angles', 'summarize the CubeReachEnv compute_reward method that calculates negative distance-based reward for cube reaching', 'create a MoveCubeEnv gym environment for TriFingerPro cube manipulation with configurable action type and step size', 'run one timestep of the MoveCubeEnv dynamics using an action and return observation reward and done', 'reset the MoveCubeEnv with optional goal pose initial pose and eval mode settings', 'compute the reward based on fingertip positions achieved goal and desired goal distance', 'create a HandKinematics instance to compute fingertip positions and impedance control torque from joint states']
```

Usage

```
{'build_CubeReachEnv': 'build a python module to create a CubeReachEnv gym environment for TriFingerPro cube reaching simulation', 'run_CubeReachEnv_step': 'run a single step of the CubeReachEnv simulation with a given 3D action vector', 'test_CubeReachEnv_reset': 'test the CubeReachEnv reset method to initialize robot position and goal pose', 'review_HandKinematics_get_ft_pos': 'review the HandKinematics class get_ft_pos method for computing fingertip positions from joint angles', 'summarize_CubeReachEnv_compute_reward': 'summarize the CubeReachEnv compute_reward method that calculates negative distance-based reward for cube reaching'}
```

## File: facebookresearch_eai-vc/cortexbench/trifinger_vc/src/trifinger_vc/trifinger_envs/gym_cube_env.py

Prompts

```
['build a python module to create a CubeReachEnv gym environment for TriFingerPro cube reaching simulation', 'run a single step of the CubeReachEnv simulation with a given 3D action vector', 'test the CubeReachEnv reset method to initialize robot position and goal pose', 'review the HandKinematics class get_ft_pos method for computing fingertip positions from joint angles', 'summarize the CubeReachEnv compute_reward method that calculates negative distance-based reward for cube reaching', 'create a MoveCubeEnv gym environment for TriFingerPro cube manipulation with configurable action type and step size', 'run one timestep of the MoveCubeEnv dynamics using an action and return observation reward and done', 'reset the MoveCubeEnv with optional goal pose initial pose and eval mode settings', 'compute the reward based on fingertip positions achieved goal and desired goal distance', 'create a HandKinematics instance to compute fingertip positions and impedance control torque from joint states']
```

Usage

```
{'create_MoveCubeEnv': 'create a MoveCubeEnv gym environment for TriFingerPro cube manipulation with configurable action type and step size', 'run_MoveCubeEnv_step': 'run one timestep of the MoveCubeEnv dynamics using an action and return observation reward and done', 'reset_MoveCubeEnv': 'reset the MoveCubeEnv with optional goal pose initial pose and eval mode settings', 'compute_reward_MoveCubeEnv': 'compute the reward based on fingertip positions achieved goal and desired goal distance', 'create_HandKinematics': 'create a HandKinematics instance to compute fingertip positions and impedance control torque from joint states'}
```

