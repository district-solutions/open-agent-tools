# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/envs/doom/wrappers/scenario_wrappers/gathering_reward_shaping.py

Prompts

```
['create a DoomGatheringRewardShaping Gym wrapper that adds health-based reward shaping to a Doom environment', "build a reward shaping function that grants a reward of 1.0 when the agent's health increases between steps", 'test the DoomGatheringRewardShaping reset method to ensure prev_health and orig_env_reward are properly initialized', 'review the DoomGatheringRewardShaping step method to understand how shaped rewards are added and true_reward is tracked on episode end', 'summarize the _reward_shaping method logic that compares current health to previous health and returns a shaped reward']
```

Usage

```
{'create_gym_wrapper_for_doom_gathering': 'create a DoomGatheringRewardShaping Gym wrapper that adds health-based reward shaping to a Doom environment', 'build_reward_shaping_for_health_delta': "build a reward shaping function that grants a reward of 1.0 when the agent's health increases between steps", 'test_DoomGatheringRewardShaping_reset': 'test the DoomGatheringRewardShaping reset method to ensure prev_health and orig_env_reward are properly initialized', 'review_DoomGatheringRewardShaping_step': 'review the DoomGatheringRewardShaping step method to understand how shaped rewards are added and true_reward is tracked on episode end', 'summarize_DoomGatheringRewardShaping_reward_shaping': 'summarize the _reward_shaping method logic that compares current health to previous health and returns a shaped reward'}
```

