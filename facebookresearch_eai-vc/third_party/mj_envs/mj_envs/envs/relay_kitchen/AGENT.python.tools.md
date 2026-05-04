# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/relay_kitchen/kitchen_multitask_v1.py

Prompts

```
['create a KitchenV0 environment instance with a Franka robot and MuJoCo kitchen simulation', 'run a single environment step by calling step with a clipped action array on KitchenV0', 'reset the KitchenV0 environment model to initial joint positions and sample a new task goal', 'set a custom goal vector on the KitchenV0 environment using the set_goal method', 'evaluate success percentage and mean score across rollout paths using evaluate_success on KitchenV0', 'create a KitchenFrankaFixed gym environment with a MuJoCo model path and configurable robot joint names', 'create a KitchenFrankaRandom gym environment that resets with randomized robot joint positions within range', 'create a KitchenFrankaDemo gym environment that resets to a fixed demonstration keyframe pose', 'review the KitchenBase get_obs_dict method that extracts hand, object, goal, and approach error observations', 'review the KitchenBase get_reward_dict method that computes goal, bonus, pose, and approach reward signals']
```

Usage

```
{'create_kitchen_env': 'create a KitchenV0 environment instance with a Franka robot and MuJoCo kitchen simulation', 'run_kitchen_step': 'run a single environment step by calling step with a clipped action array on KitchenV0', 'reset_kitchen_model': 'reset the KitchenV0 environment model to initial joint positions and sample a new task goal', 'set_kitchen_goal': 'set a custom goal vector on the KitchenV0 environment using the set_goal method', 'evaluate_kitchen_success': 'evaluate success percentage and mean score across rollout paths using evaluate_success on KitchenV0'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/relay_kitchen/kitchen_multitask_v2.py

Prompts

```
['create a KitchenV0 environment instance with a Franka robot and MuJoCo kitchen simulation', 'run a single environment step by calling step with a clipped action array on KitchenV0', 'reset the KitchenV0 environment model to initial joint positions and sample a new task goal', 'set a custom goal vector on the KitchenV0 environment using the set_goal method', 'evaluate success percentage and mean score across rollout paths using evaluate_success on KitchenV0', 'create a KitchenFrankaFixed gym environment with a MuJoCo model path and configurable robot joint names', 'create a KitchenFrankaRandom gym environment that resets with randomized robot joint positions within range', 'create a KitchenFrankaDemo gym environment that resets to a fixed demonstration keyframe pose', 'review the KitchenBase get_obs_dict method that extracts hand, object, goal, and approach error observations', 'review the KitchenBase get_reward_dict method that computes goal, bonus, pose, and approach reward signals']
```

Usage

```
{'create_KitchenFrankaFixed_env': 'create a KitchenFrankaFixed gym environment with a MuJoCo model path and configurable robot joint names', 'create_KitchenFrankaRandom_env': 'create a KitchenFrankaRandom gym environment that resets with randomized robot joint positions within range', 'create_KitchenFrankaDemo_env': 'create a KitchenFrankaDemo gym environment that resets to a fixed demonstration keyframe pose', 'review_KitchenBase_get_obs_dict': 'review the KitchenBase get_obs_dict method that extracts hand, object, goal, and approach error observations', 'review_KitchenBase_get_reward_dict': 'review the KitchenBase get_reward_dict method that computes goal, bonus, pose, and approach reward signals'}
```

