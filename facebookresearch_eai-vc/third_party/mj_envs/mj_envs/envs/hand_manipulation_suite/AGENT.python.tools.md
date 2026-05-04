# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/door_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door positions', 'run a single simulation step on the door environment with a clipped action vector and compute rewards', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the door environment model to initial state with randomized door body position', 'evaluate the success percentage of rollout paths where the door was opened for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step on the HammerEnvV0 environment with a clipped action vector', 'test the get_obs method to retrieve concatenated hand qpos, object position, and target state', 'review the reset_model method that randomizes the nail board height and returns initial observation', 'refactor the evaluate_success method to compute success percentage from paths where goal was achieved for 25+ steps', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator parameters', 'run a single simulation step on the PenEnvV0 environment with a clipped action vector', 'get the observation vector including joint positions, object velocity, orientation, and desired target', 'reset the PenEnvV0 environment to initial state with a randomized target orientation', 'evaluate success percentage across rollout paths where pen aligns with target for 20+ steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation environment', 'run a single environment step with action array a and observe reward and goal achieved', 'test the reset_model method to randomize object and target positions in the scene', 'review the get_obs method that returns concatenated hand qpos and relative position vectors', 'summarize the evaluate_success method that computes success percentage across multiple rollout paths']
```

Usage

```
{'create_door_env': 'create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door positions', 'run_step_simulation': 'run a single simulation step on the door environment with a clipped action vector and compute rewards', 'get_observation': 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset_door_model': 'reset the door environment model to initial state with randomized door body position', 'evaluate_success_rate': 'evaluate the success percentage of rollout paths where the door was opened for more than 25 steps'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/hammer_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door positions', 'run a single simulation step on the door environment with a clipped action vector and compute rewards', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the door environment model to initial state with randomized door body position', 'evaluate the success percentage of rollout paths where the door was opened for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step on the HammerEnvV0 environment with a clipped action vector', 'test the get_obs method to retrieve concatenated hand qpos, object position, and target state', 'review the reset_model method that randomizes the nail board height and returns initial observation', 'refactor the evaluate_success method to compute success percentage from paths where goal was achieved for 25+ steps', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator parameters', 'run a single simulation step on the PenEnvV0 environment with a clipped action vector', 'get the observation vector including joint positions, object velocity, orientation, and desired target', 'reset the PenEnvV0 environment to initial state with a randomized target orientation', 'evaluate success percentage across rollout paths where pen aligns with target for 20+ steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation environment', 'run a single environment step with action array a and observe reward and goal achieved', 'test the reset_model method to randomize object and target positions in the scene', 'review the get_obs method that returns concatenated hand qpos and relative position vectors', 'summarize the evaluate_success method that computes success percentage across multiple rollout paths']
```

Usage

```
{'create_HammerEnvV0': 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run_HammerEnvV0_step': 'run a single simulation step on the HammerEnvV0 environment with a clipped action vector', 'test_HammerEnvV0_get_obs': 'test the get_obs method to retrieve concatenated hand qpos, object position, and target state', 'review_HammerEnvV0_reset_model': 'review the reset_model method that randomizes the nail board height and returns initial observation', 'refactor_HammerEnvV0_evaluate_success': 'refactor the evaluate_success method to compute success percentage from paths where goal was achieved for 25+ steps'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/pen_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door positions', 'run a single simulation step on the door environment with a clipped action vector and compute rewards', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the door environment model to initial state with randomized door body position', 'evaluate the success percentage of rollout paths where the door was opened for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step on the HammerEnvV0 environment with a clipped action vector', 'test the get_obs method to retrieve concatenated hand qpos, object position, and target state', 'review the reset_model method that randomizes the nail board height and returns initial observation', 'refactor the evaluate_success method to compute success percentage from paths where goal was achieved for 25+ steps', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator parameters', 'run a single simulation step on the PenEnvV0 environment with a clipped action vector', 'get the observation vector including joint positions, object velocity, orientation, and desired target', 'reset the PenEnvV0 environment to initial state with a randomized target orientation', 'evaluate success percentage across rollout paths where pen aligns with target for 20+ steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation environment', 'run a single environment step with action array a and observe reward and goal achieved', 'test the reset_model method to randomize object and target positions in the scene', 'review the get_obs method that returns concatenated hand qpos and relative position vectors', 'summarize the evaluate_success method that computes success percentage across multiple rollout paths']
```

Usage

```
{'create_PenEnvV0': 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator parameters', 'run_step_PenEnvV0': 'run a single simulation step on the PenEnvV0 environment with a clipped action vector', 'get_obs_PenEnvV0': 'get the observation vector including joint positions, object velocity, orientation, and desired target', 'reset_model_PenEnvV0': 'reset the PenEnvV0 environment to initial state with a randomized target orientation', 'evaluate_success_PenEnvV0': 'evaluate success percentage across rollout paths where pen aligns with target for 20+ steps'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/hand_manipulation_suite/relocate_v0.py

Prompts

```
['create a DoorEnvV0 instance to initialize a MuJoCo door manipulation environment with randomized door positions', 'run a single simulation step on the door environment with a clipped action vector and compute rewards', 'get the current observation vector including hand qpos, door position, palm and handle positions', 'reset the door environment model to initial state with randomized door body position', 'evaluate the success percentage of rollout paths where the door was opened for more than 25 steps', 'create a HammerEnvV0 instance to initialize the MuJoCo hammer manipulation environment with actuator tuning', 'run a single simulation step on the HammerEnvV0 environment with a clipped action vector', 'test the get_obs method to retrieve concatenated hand qpos, object position, and target state', 'review the reset_model method that randomizes the nail board height and returns initial observation', 'refactor the evaluate_success method to compute success percentage from paths where goal was achieved for 25+ steps', 'create a PenEnvV0 instance to initialize the MuJoCo pen manipulation environment with actuator parameters', 'run a single simulation step on the PenEnvV0 environment with a clipped action vector', 'get the observation vector including joint positions, object velocity, orientation, and desired target', 'reset the PenEnvV0 environment to initial state with a randomized target orientation', 'evaluate success percentage across rollout paths where pen aligns with target for 20+ steps', 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation environment', 'run a single environment step with action array a and observe reward and goal achieved', 'test the reset_model method to randomize object and target positions in the scene', 'review the get_obs method that returns concatenated hand qpos and relative position vectors', 'summarize the evaluate_success method that computes success percentage across multiple rollout paths']
```

Usage

```
{'create_RelocateEnvV0': 'create a RelocateEnvV0 instance to initialize the MuJoCo hand object relocation environment', 'run_step': 'run a single environment step with action array a and observe reward and goal achieved', 'test_reset_model': 'test the reset_model method to randomize object and target positions in the scene', 'review_get_obs': 'review the get_obs method that returns concatenated hand qpos and relative position vectors', 'summarize_evaluate_success': 'summarize the evaluate_success method that computes success percentage across multiple rollout paths'}
```

