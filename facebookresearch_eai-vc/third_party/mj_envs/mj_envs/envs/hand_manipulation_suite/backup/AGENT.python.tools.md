# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/backup/door_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door placement', 'step the DoorEnvV0 environment with an action array to simulate hand movement and compute reward', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the DoorEnvV0 environment to randomize door body position and return initial observation', 'evaluate success percentage across rollout paths by checking if door was open for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step in the hammer environment by providing a clipped action array', 'test the get_obs method to retrieve concatenated state vectors including hand qpos, object position, and nail impact', 'refactor the step method reward function to adjust bonus rewards for hammer lifting or nail hammering', 'review the evaluate_success method that calculates success percentage based on goal achievement across simulation paths', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator sensitivity settings', 'run a simulation step on the PenEnvV0 environment by passing a clipped action array and receiving reward', 'get the observation vector from PenEnvV0 including joint positions, object pose, and desired orientation', 'reset the PenEnvV0 environment to initial state with a randomized target orientation for the pen', 'evaluate success percentage across rollout paths by checking if goal was achieved for more than 20 steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation simulation environment', 'run a single simulation step with action array a and receive observation reward and goal info', 'test the reset_model method to randomize object and target positions and return initial observation', 'review the get_obs method that concatenates hand qpos palm object and target relative positions', 'summarize the evaluate_success method that computes success percentage from paths where goal was achieved for 25+ steps']
```

Usage

```
{'create_door_env': 'create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door placement', 'step_door_env': 'step the DoorEnvV0 environment with an action array to simulate hand movement and compute reward', 'get_observation': 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset_door_env': 'reset the DoorEnvV0 environment to randomize door body position and return initial observation', 'evaluate_success': 'evaluate success percentage across rollout paths by checking if door was open for more than 25 steps'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/backup/hammer_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door placement', 'step the DoorEnvV0 environment with an action array to simulate hand movement and compute reward', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the DoorEnvV0 environment to randomize door body position and return initial observation', 'evaluate success percentage across rollout paths by checking if door was open for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step in the hammer environment by providing a clipped action array', 'test the get_obs method to retrieve concatenated state vectors including hand qpos, object position, and nail impact', 'refactor the step method reward function to adjust bonus rewards for hammer lifting or nail hammering', 'review the evaluate_success method that calculates success percentage based on goal achievement across simulation paths', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator sensitivity settings', 'run a simulation step on the PenEnvV0 environment by passing a clipped action array and receiving reward', 'get the observation vector from PenEnvV0 including joint positions, object pose, and desired orientation', 'reset the PenEnvV0 environment to initial state with a randomized target orientation for the pen', 'evaluate success percentage across rollout paths by checking if goal was achieved for more than 20 steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation simulation environment', 'run a single simulation step with action array a and receive observation reward and goal info', 'test the reset_model method to randomize object and target positions and return initial observation', 'review the get_obs method that concatenates hand qpos palm object and target relative positions', 'summarize the evaluate_success method that computes success percentage from paths where goal was achieved for 25+ steps']
```

Usage

```
{'create_HammerEnvV0': 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run_HammerEnvV0_step': 'run a single simulation step in the hammer environment by providing a clipped action array', 'test_HammerEnvV0_get_obs': 'test the get_obs method to retrieve concatenated state vectors including hand qpos, object position, and nail impact', 'refactor_HammerEnvV0_step_reward': 'refactor the step method reward function to adjust bonus rewards for hammer lifting or nail hammering', 'review_HammerEnvV0_evaluate_success': 'review the evaluate_success method that calculates success percentage based on goal achievement across simulation paths'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/backup/pen_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door placement', 'step the DoorEnvV0 environment with an action array to simulate hand movement and compute reward', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the DoorEnvV0 environment to randomize door body position and return initial observation', 'evaluate success percentage across rollout paths by checking if door was open for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step in the hammer environment by providing a clipped action array', 'test the get_obs method to retrieve concatenated state vectors including hand qpos, object position, and nail impact', 'refactor the step method reward function to adjust bonus rewards for hammer lifting or nail hammering', 'review the evaluate_success method that calculates success percentage based on goal achievement across simulation paths', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator sensitivity settings', 'run a simulation step on the PenEnvV0 environment by passing a clipped action array and receiving reward', 'get the observation vector from PenEnvV0 including joint positions, object pose, and desired orientation', 'reset the PenEnvV0 environment to initial state with a randomized target orientation for the pen', 'evaluate success percentage across rollout paths by checking if goal was achieved for more than 20 steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation simulation environment', 'run a single simulation step with action array a and receive observation reward and goal info', 'test the reset_model method to randomize object and target positions and return initial observation', 'review the get_obs method that concatenates hand qpos palm object and target relative positions', 'summarize the evaluate_success method that computes success percentage from paths where goal was achieved for 25+ steps']
```

Usage

```
{'create_PenEnvV0': 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator sensitivity settings', 'run_step_PenEnvV0': 'run a simulation step on the PenEnvV0 environment by passing a clipped action array and receiving reward', 'get_obs_PenEnvV0': 'get the observation vector from PenEnvV0 including joint positions, object pose, and desired orientation', 'reset_model_PenEnvV0': 'reset the PenEnvV0 environment to initial state with a randomized target orientation for the pen', 'evaluate_success_PenEnvV0': 'evaluate success percentage across rollout paths by checking if goal was achieved for more than 20 steps'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/backup/relocate_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door placement', 'step the DoorEnvV0 environment with an action array to simulate hand movement and compute reward', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the DoorEnvV0 environment to randomize door body position and return initial observation', 'evaluate success percentage across rollout paths by checking if door was open for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step in the hammer environment by providing a clipped action array', 'test the get_obs method to retrieve concatenated state vectors including hand qpos, object position, and nail impact', 'refactor the step method reward function to adjust bonus rewards for hammer lifting or nail hammering', 'review the evaluate_success method that calculates success percentage based on goal achievement across simulation paths', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator sensitivity settings', 'run a simulation step on the PenEnvV0 environment by passing a clipped action array and receiving reward', 'get the observation vector from PenEnvV0 including joint positions, object pose, and desired orientation', 'reset the PenEnvV0 environment to initial state with a randomized target orientation for the pen', 'evaluate success percentage across rollout paths by checking if goal was achieved for more than 20 steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation simulation environment', 'run a single simulation step with action array a and receive observation reward and goal info', 'test the reset_model method to randomize object and target positions and return initial observation', 'review the get_obs method that concatenates hand qpos palm object and target relative positions', 'summarize the evaluate_success method that computes success percentage from paths where goal was achieved for 25+ steps']
```

Usage

```
{'create_RelocateEnvV0': 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation simulation environment', 'run_step': 'run a single simulation step with action array a and receive observation reward and goal info', 'test_reset_model': 'test the reset_model method to randomize object and target positions and return initial observation', 'review_get_obs': 'review the get_obs method that concatenates hand qpos palm object and target relative positions', 'summarize_evaluate_success': 'summarize the evaluate_success method that computes success percentage from paths where goal was achieved for 25+ steps'}
```

