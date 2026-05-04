# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/envs/cube_env.py

Prompts

```
['create a CubeEnv gym environment with a RandomInitializer for the TriFingerPro cube moving simulation', 'create a FixedInitializer with a specific initial pose and goal pose for deterministic cube tasks', 'run a single step on the CubeEnv with a position action and collect observation and reward', 'reset the CubeEnv to initialize a new episode with a fresh initial state and goal', 'compute the reward for a given achieved goal versus desired goal using the CubeEnv compute_reward method', 'create a CubeTrajectoryEnv with a RandomInitializer and POSITION action type for simulation', 'run a single step of the CubeTrajectoryEnv with a joint position action', 'reset the CubeTrajectoryEnv to initialize a new episode with a fresh trajectory', 'compute the reward for an achieved goal position against the desired goal trajectory', 'create a TriFingerPush gym environment with a control rate, finger type, and visualization flag', 'run a single environment step by passing an action and receiving observation, reward, done, and info', 'reset the TriFingerPush environment to start a new episode with random goal and block positions', 'review the _compute_reward method that calculates negative distance between object position and goal', 'summarize the _get_state method that builds the observation dict from joint positions, velocities, and goal', 'create a TriFingerReach gym environment instance with control rate, finger type, and smoothing params', 'run a single environment step by passing an action and receiving observation, reward, and done signal', 'reset the TriFingerReach environment to start a new episode with a random goal and position', 'review the _compute_reward method that calculates negative distance-to-goal reward using forward kinematics', 'refactor the update_smoothing method to customize how the smoothing alpha coefficient increases across episodes']
```

Usage

```
{'create_cube_env': 'create a CubeEnv gym environment with a RandomInitializer for the TriFingerPro cube moving simulation', 'create_fixed_initializer': 'create a FixedInitializer with a specific initial pose and goal pose for deterministic cube tasks', 'run_cube_env_step': 'run a single step on the CubeEnv with a position action and collect observation and reward', 'reset_cube_env': 'reset the CubeEnv to initialize a new episode with a fresh initial state and goal', 'compute_cube_reward': 'compute the reward for a given achieved goal versus desired goal using the CubeEnv compute_reward method'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/envs/cube_trajectory_env.py

Prompts

```
['create a CubeEnv gym environment with a RandomInitializer for the TriFingerPro cube moving simulation', 'create a FixedInitializer with a specific initial pose and goal pose for deterministic cube tasks', 'run a single step on the CubeEnv with a position action and collect observation and reward', 'reset the CubeEnv to initialize a new episode with a fresh initial state and goal', 'compute the reward for a given achieved goal versus desired goal using the CubeEnv compute_reward method', 'create a CubeTrajectoryEnv with a RandomInitializer and POSITION action type for simulation', 'run a single step of the CubeTrajectoryEnv with a joint position action', 'reset the CubeTrajectoryEnv to initialize a new episode with a fresh trajectory', 'compute the reward for an achieved goal position against the desired goal trajectory', 'create a TriFingerPush gym environment with a control rate, finger type, and visualization flag', 'run a single environment step by passing an action and receiving observation, reward, done, and info', 'reset the TriFingerPush environment to start a new episode with random goal and block positions', 'review the _compute_reward method that calculates negative distance between object position and goal', 'summarize the _get_state method that builds the observation dict from joint positions, velocities, and goal', 'create a TriFingerReach gym environment instance with control rate, finger type, and smoothing params', 'run a single environment step by passing an action and receiving observation, reward, and done signal', 'reset the TriFingerReach environment to start a new episode with a random goal and position', 'review the _compute_reward method that calculates negative distance-to-goal reward using forward kinematics', 'refactor the update_smoothing method to customize how the smoothing alpha coefficient increases across episodes']
```

Usage

```
{'create_cube_trajectory_env': 'create a CubeTrajectoryEnv with a RandomInitializer and POSITION action type for simulation', 'run_cube_trajectory_step': 'run a single step of the CubeTrajectoryEnv with a joint position action', 'reset_cube_trajectory_env': 'reset the CubeTrajectoryEnv to initialize a new episode with a fresh trajectory', 'compute_reward_cube_trajectory': 'compute the reward for an achieved goal position against the desired goal trajectory', 'create_fixed_initializer': 'create a FixedInitializer with a validated trajectory for deterministic cube movement episodes'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/envs/trifinger_push.py

Prompts

```
['create a CubeEnv gym environment with a RandomInitializer for the TriFingerPro cube moving simulation', 'create a FixedInitializer with a specific initial pose and goal pose for deterministic cube tasks', 'run a single step on the CubeEnv with a position action and collect observation and reward', 'reset the CubeEnv to initialize a new episode with a fresh initial state and goal', 'compute the reward for a given achieved goal versus desired goal using the CubeEnv compute_reward method', 'create a CubeTrajectoryEnv with a RandomInitializer and POSITION action type for simulation', 'run a single step of the CubeTrajectoryEnv with a joint position action', 'reset the CubeTrajectoryEnv to initialize a new episode with a fresh trajectory', 'compute the reward for an achieved goal position against the desired goal trajectory', 'create a TriFingerPush gym environment with a control rate, finger type, and visualization flag', 'run a single environment step by passing an action and receiving observation, reward, done, and info', 'reset the TriFingerPush environment to start a new episode with random goal and block positions', 'review the _compute_reward method that calculates negative distance between object position and goal', 'summarize the _get_state method that builds the observation dict from joint positions, velocities, and goal', 'create a TriFingerReach gym environment instance with control rate, finger type, and smoothing params', 'run a single environment step by passing an action and receiving observation, reward, and done signal', 'reset the TriFingerReach environment to start a new episode with a random goal and position', 'review the _compute_reward method that calculates negative distance-to-goal reward using forward kinematics', 'refactor the update_smoothing method to customize how the smoothing alpha coefficient increases across episodes']
```

Usage

```
{'create_TriFingerPush_env': 'create a TriFingerPush gym environment with a control rate, finger type, and visualization flag', 'run_TriFingerPush_step': 'run a single environment step by passing an action and receiving observation, reward, done, and info', 'reset_TriFingerPush_episode': 'reset the TriFingerPush environment to start a new episode with random goal and block positions', 'review_TriFingerPush_compute_reward': 'review the _compute_reward method that calculates negative distance between object position and goal', 'summarize_TriFingerPush_get_state': 'summarize the _get_state method that builds the observation dict from joint positions, velocities, and goal'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/envs/trifinger_reach.py

Prompts

```
['create a CubeEnv gym environment with a RandomInitializer for the TriFingerPro cube moving simulation', 'create a FixedInitializer with a specific initial pose and goal pose for deterministic cube tasks', 'run a single step on the CubeEnv with a position action and collect observation and reward', 'reset the CubeEnv to initialize a new episode with a fresh initial state and goal', 'compute the reward for a given achieved goal versus desired goal using the CubeEnv compute_reward method', 'create a CubeTrajectoryEnv with a RandomInitializer and POSITION action type for simulation', 'run a single step of the CubeTrajectoryEnv with a joint position action', 'reset the CubeTrajectoryEnv to initialize a new episode with a fresh trajectory', 'compute the reward for an achieved goal position against the desired goal trajectory', 'create a TriFingerPush gym environment with a control rate, finger type, and visualization flag', 'run a single environment step by passing an action and receiving observation, reward, done, and info', 'reset the TriFingerPush environment to start a new episode with random goal and block positions', 'review the _compute_reward method that calculates negative distance between object position and goal', 'summarize the _get_state method that builds the observation dict from joint positions, velocities, and goal', 'create a TriFingerReach gym environment instance with control rate, finger type, and smoothing params', 'run a single environment step by passing an action and receiving observation, reward, and done signal', 'reset the TriFingerReach environment to start a new episode with a random goal and position', 'review the _compute_reward method that calculates negative distance-to-goal reward using forward kinematics', 'refactor the update_smoothing method to customize how the smoothing alpha coefficient increases across episodes']
```

Usage

```
{'create_TriFingerReach_env': 'create a TriFingerReach gym environment instance with control rate, finger type, and smoothing params', 'run_step_TriFingerReach': 'run a single environment step by passing an action and receiving observation, reward, and done signal', 'reset_TriFingerReach_episode': 'reset the TriFingerReach environment to start a new episode with a random goal and position', 'review_compute_reward': 'review the _compute_reward method that calculates negative distance-to-goal reward using forward kinematics', 'refactor_update_smoothing': 'refactor the update_smoothing method to customize how the smoothing alpha coefficient increases across episodes'}
```

