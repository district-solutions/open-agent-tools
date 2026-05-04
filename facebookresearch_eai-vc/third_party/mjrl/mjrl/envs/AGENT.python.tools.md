# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/envs/mujoco_env.py

Prompts

```
['create a subclass of MujocoEnv that implements reset_model for a custom MuJoCo robot environment', 'run get_sim with a model XML path to load and return an MjSim instance', 'test set_state by passing qpos and qvel arrays to set the simulation state', 'review visualize_policy to render episodes of a policy running in the MuJoCo viewer', 'summarize visualize_policy_offscreen to render policy episodes offscreen and save as MP4 video', 'create a PegEnv instance to initialize the peg insertion Sawyer robot simulation environment', 'run a single simulation step in the PegEnv by passing an action and receiving observation and reward', 'compute rewards for batched trajectory paths using the PegEnv compute_path_rewards method', 'reset the PegEnv model with an optional seed to randomize the target goal position', 'get or set the full environment state including joint positions, velocities, and target position', 'create a PointMassEnv instance to initialize the MuJoCo point mass simulation environment', 'run a single simulation step in the PointMassEnv with a given action array', 'compute the L1 and L2 distance-based reward for agent-to-target observations', 'reset the PointMassEnv model with randomized agent and target positions', 'evaluate the success rate of trajectories by checking solved status in paths', 'create a Reacher7DOFEnv instance to simulate a 7-DOF Sawyer robot reaching task', 'run a single simulation step on the Reacher7DOFEnv with a given action array', 'compute the L1 and L2 distance-based reward for hand-to-target observations', 'reset the Reacher7DOFEnv robot and randomize the target position for a new episode', 'get the current environment state including joint positions, velocities, and target position', 'create a SwimmerEnv instance to initialize the MuJoCo swimmer simulation environment', 'run a single simulation step on the swimmer environment with a given action', 'reset the swimmer model to a random initial joint angle and return the observation', 'get the current observation vector from the swimmer environment state', 'set the swimmer environment state by providing position and velocity dictionaries']
```

Usage

```
{'create_MujocoEnv_subclass': 'create a subclass of MujocoEnv that implements reset_model for a custom MuJoCo robot environment', 'run_get_sim': 'run get_sim with a model XML path to load and return an MjSim instance', 'test_set_state': 'test set_state by passing qpos and qvel arrays to set the simulation state', 'review_visualize_policy': 'review visualize_policy to render episodes of a policy running in the MuJoCo viewer', 'summarize_visualize_policy_offscreen': 'summarize visualize_policy_offscreen to render policy episodes offscreen and save as MP4 video'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/envs/peg_insertion_sawyer.py

Prompts

```
['create a subclass of MujocoEnv that implements reset_model for a custom MuJoCo robot environment', 'run get_sim with a model XML path to load and return an MjSim instance', 'test set_state by passing qpos and qvel arrays to set the simulation state', 'review visualize_policy to render episodes of a policy running in the MuJoCo viewer', 'summarize visualize_policy_offscreen to render policy episodes offscreen and save as MP4 video', 'create a PegEnv instance to initialize the peg insertion Sawyer robot simulation environment', 'run a single simulation step in the PegEnv by passing an action and receiving observation and reward', 'compute rewards for batched trajectory paths using the PegEnv compute_path_rewards method', 'reset the PegEnv model with an optional seed to randomize the target goal position', 'get or set the full environment state including joint positions, velocities, and target position', 'create a PointMassEnv instance to initialize the MuJoCo point mass simulation environment', 'run a single simulation step in the PointMassEnv with a given action array', 'compute the L1 and L2 distance-based reward for agent-to-target observations', 'reset the PointMassEnv model with randomized agent and target positions', 'evaluate the success rate of trajectories by checking solved status in paths', 'create a Reacher7DOFEnv instance to simulate a 7-DOF Sawyer robot reaching task', 'run a single simulation step on the Reacher7DOFEnv with a given action array', 'compute the L1 and L2 distance-based reward for hand-to-target observations', 'reset the Reacher7DOFEnv robot and randomize the target position for a new episode', 'get the current environment state including joint positions, velocities, and target position', 'create a SwimmerEnv instance to initialize the MuJoCo swimmer simulation environment', 'run a single simulation step on the swimmer environment with a given action', 'reset the swimmer model to a random initial joint angle and return the observation', 'get the current observation vector from the swimmer environment state', 'set the swimmer environment state by providing position and velocity dictionaries']
```

Usage

```
{'create_PegEnv_instance': 'create a PegEnv instance to initialize the peg insertion Sawyer robot simulation environment', 'run_PegEnv_step': 'run a single simulation step in the PegEnv by passing an action and receiving observation and reward', 'compute_PegEnv_rewards': 'compute rewards for batched trajectory paths using the PegEnv compute_path_rewards method', 'reset_PegEnv_model': 'reset the PegEnv model with an optional seed to randomize the target goal position', 'get_PegEnv_state': 'get or set the full environment state including joint positions, velocities, and target position'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/envs/point_mass.py

Prompts

```
['create a subclass of MujocoEnv that implements reset_model for a custom MuJoCo robot environment', 'run get_sim with a model XML path to load and return an MjSim instance', 'test set_state by passing qpos and qvel arrays to set the simulation state', 'review visualize_policy to render episodes of a policy running in the MuJoCo viewer', 'summarize visualize_policy_offscreen to render policy episodes offscreen and save as MP4 video', 'create a PegEnv instance to initialize the peg insertion Sawyer robot simulation environment', 'run a single simulation step in the PegEnv by passing an action and receiving observation and reward', 'compute rewards for batched trajectory paths using the PegEnv compute_path_rewards method', 'reset the PegEnv model with an optional seed to randomize the target goal position', 'get or set the full environment state including joint positions, velocities, and target position', 'create a PointMassEnv instance to initialize the MuJoCo point mass simulation environment', 'run a single simulation step in the PointMassEnv with a given action array', 'compute the L1 and L2 distance-based reward for agent-to-target observations', 'reset the PointMassEnv model with randomized agent and target positions', 'evaluate the success rate of trajectories by checking solved status in paths', 'create a Reacher7DOFEnv instance to simulate a 7-DOF Sawyer robot reaching task', 'run a single simulation step on the Reacher7DOFEnv with a given action array', 'compute the L1 and L2 distance-based reward for hand-to-target observations', 'reset the Reacher7DOFEnv robot and randomize the target position for a new episode', 'get the current environment state including joint positions, velocities, and target position', 'create a SwimmerEnv instance to initialize the MuJoCo swimmer simulation environment', 'run a single simulation step on the swimmer environment with a given action', 'reset the swimmer model to a random initial joint angle and return the observation', 'get the current observation vector from the swimmer environment state', 'set the swimmer environment state by providing position and velocity dictionaries']
```

Usage

```
{'create_PointMassEnv': 'create a PointMassEnv instance to initialize the MuJoCo point mass simulation environment', 'run_step_PointMassEnv': 'run a single simulation step in the PointMassEnv with a given action array', 'compute_reward_get_reward': 'compute the L1 and L2 distance-based reward for agent-to-target observations', 'reset_reset_model': 'reset the PointMassEnv model with randomized agent and target positions', 'evaluate_evaluate_success': 'evaluate the success rate of trajectories by checking solved status in paths'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/envs/reacher_sawyer.py

Prompts

```
['create a subclass of MujocoEnv that implements reset_model for a custom MuJoCo robot environment', 'run get_sim with a model XML path to load and return an MjSim instance', 'test set_state by passing qpos and qvel arrays to set the simulation state', 'review visualize_policy to render episodes of a policy running in the MuJoCo viewer', 'summarize visualize_policy_offscreen to render policy episodes offscreen and save as MP4 video', 'create a PegEnv instance to initialize the peg insertion Sawyer robot simulation environment', 'run a single simulation step in the PegEnv by passing an action and receiving observation and reward', 'compute rewards for batched trajectory paths using the PegEnv compute_path_rewards method', 'reset the PegEnv model with an optional seed to randomize the target goal position', 'get or set the full environment state including joint positions, velocities, and target position', 'create a PointMassEnv instance to initialize the MuJoCo point mass simulation environment', 'run a single simulation step in the PointMassEnv with a given action array', 'compute the L1 and L2 distance-based reward for agent-to-target observations', 'reset the PointMassEnv model with randomized agent and target positions', 'evaluate the success rate of trajectories by checking solved status in paths', 'create a Reacher7DOFEnv instance to simulate a 7-DOF Sawyer robot reaching task', 'run a single simulation step on the Reacher7DOFEnv with a given action array', 'compute the L1 and L2 distance-based reward for hand-to-target observations', 'reset the Reacher7DOFEnv robot and randomize the target position for a new episode', 'get the current environment state including joint positions, velocities, and target position', 'create a SwimmerEnv instance to initialize the MuJoCo swimmer simulation environment', 'run a single simulation step on the swimmer environment with a given action', 'reset the swimmer model to a random initial joint angle and return the observation', 'get the current observation vector from the swimmer environment state', 'set the swimmer environment state by providing position and velocity dictionaries']
```

Usage

```
{'create_Reacher7DOFEnv': 'create a Reacher7DOFEnv instance to simulate a 7-DOF Sawyer robot reaching task', 'run_step_Reacher7DOFEnv': 'run a single simulation step on the Reacher7DOFEnv with a given action array', 'compute_reward_Reacher7DOFEnv': 'compute the L1 and L2 distance-based reward for hand-to-target observations', 'reset_Reacher7DOFEnv': 'reset the Reacher7DOFEnv robot and randomize the target position for a new episode', 'get_env_state_Reacher7DOFEnv': 'get the current environment state including joint positions, velocities, and target position'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/envs/swimmer.py

Prompts

```
['create a subclass of MujocoEnv that implements reset_model for a custom MuJoCo robot environment', 'run get_sim with a model XML path to load and return an MjSim instance', 'test set_state by passing qpos and qvel arrays to set the simulation state', 'review visualize_policy to render episodes of a policy running in the MuJoCo viewer', 'summarize visualize_policy_offscreen to render policy episodes offscreen and save as MP4 video', 'create a PegEnv instance to initialize the peg insertion Sawyer robot simulation environment', 'run a single simulation step in the PegEnv by passing an action and receiving observation and reward', 'compute rewards for batched trajectory paths using the PegEnv compute_path_rewards method', 'reset the PegEnv model with an optional seed to randomize the target goal position', 'get or set the full environment state including joint positions, velocities, and target position', 'create a PointMassEnv instance to initialize the MuJoCo point mass simulation environment', 'run a single simulation step in the PointMassEnv with a given action array', 'compute the L1 and L2 distance-based reward for agent-to-target observations', 'reset the PointMassEnv model with randomized agent and target positions', 'evaluate the success rate of trajectories by checking solved status in paths', 'create a Reacher7DOFEnv instance to simulate a 7-DOF Sawyer robot reaching task', 'run a single simulation step on the Reacher7DOFEnv with a given action array', 'compute the L1 and L2 distance-based reward for hand-to-target observations', 'reset the Reacher7DOFEnv robot and randomize the target position for a new episode', 'get the current environment state including joint positions, velocities, and target position', 'create a SwimmerEnv instance to initialize the MuJoCo swimmer simulation environment', 'run a single simulation step on the swimmer environment with a given action', 'reset the swimmer model to a random initial joint angle and return the observation', 'get the current observation vector from the swimmer environment state', 'set the swimmer environment state by providing position and velocity dictionaries']
```

Usage

```
{'create_swimmer_env': 'create a SwimmerEnv instance to initialize the MuJoCo swimmer simulation environment', 'run_swimmer_step': 'run a single simulation step on the swimmer environment with a given action', 'reset_swimmer_model': 'reset the swimmer model to a random initial joint angle and return the observation', 'get_swimmer_observation': 'get the current observation vector from the swimmer environment state', 'set_swimmer_env_state': 'set the swimmer environment state by providing position and velocity dictionaries'}
```

