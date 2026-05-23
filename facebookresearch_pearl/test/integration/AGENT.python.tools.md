# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/test/integration/test_integration.py

Prompts

```
['run a DQN agent on CartPole-v1 using DeepQLearning and BasicReplayBuffer to reach 500 return', 'run a PPO agent on CartPole-v1 using ProximalPolicyOptimization and PPOReplayBuffer to reach 500 return', 'run a continuous SAC agent on Pendulum-v1 using ContinuousSoftActorCritic to reach negative 250 return', 'run an Implicit Q Learning agent trained on offline CartPole-v1 data to reach 100 return', 'run a TD3 agent on Pendulum-v1 using TD3 with NormalDistributionExploration to reach negative 250 return', 'test the HindsightExperienceReplayBuffer integration with a sparse reward environment and DQN agent', 'create a DiscreteSparseRewardEnvironment with configurable width, height, action count, and max episode duration', 'build a PearlAgent with a DeepQLearning policy learner and HindsightExperienceReplayBuffer', 'run episodes to precollect experience data without learning or exploiting for the agent', 'check if the agent reaches a target return within a maximum number of episodes']
```

Usage

```
{'run_DQN_CartPole': 'run a DQN agent on CartPole-v1 using DeepQLearning and BasicReplayBuffer to reach 500 return', 'run_PPO_CartPole': 'run a PPO agent on CartPole-v1 using ProximalPolicyOptimization and PPOReplayBuffer to reach 500 return', 'run_SAC_continuous': 'run a continuous SAC agent on Pendulum-v1 using ContinuousSoftActorCritic to reach negative 250 return', 'run_IQL_offline': 'run an Implicit Q Learning agent trained on offline CartPole-v1 data to reach 100 return', 'run_TD3_Pendulum': 'run a TD3 agent on Pendulum-v1 using TD3 with NormalDistributionExploration to reach negative 250 return'}
```

## File: facebookresearch_pearl/test/integration/test_integration_replay_buffer.py

Prompts

```
['run a DQN agent on CartPole-v1 using DeepQLearning and BasicReplayBuffer to reach 500 return', 'run a PPO agent on CartPole-v1 using ProximalPolicyOptimization and PPOReplayBuffer to reach 500 return', 'run a continuous SAC agent on Pendulum-v1 using ContinuousSoftActorCritic to reach negative 250 return', 'run an Implicit Q Learning agent trained on offline CartPole-v1 data to reach 100 return', 'run a TD3 agent on Pendulum-v1 using TD3 with NormalDistributionExploration to reach negative 250 return', 'test the HindsightExperienceReplayBuffer integration with a sparse reward environment and DQN agent', 'create a DiscreteSparseRewardEnvironment with configurable width, height, action count, and max episode duration', 'build a PearlAgent with a DeepQLearning policy learner and HindsightExperienceReplayBuffer', 'run episodes to precollect experience data without learning or exploiting for the agent', 'check if the agent reaches a target return within a maximum number of episodes']
```

Usage

```
{'test_her_integration': 'test the HindsightExperienceReplayBuffer integration with a sparse reward environment and DQN agent', 'create_sparse_reward_env': 'create a DiscreteSparseRewardEnvironment with configurable width, height, action count, and max episode duration', 'build_pearl_agent': 'build a PearlAgent with a DeepQLearning policy learner and HindsightExperienceReplayBuffer', 'run_episode_precollect': 'run episodes to precollect experience data without learning or exploiting for the agent', 'check_target_return': 'check if the agent reaches a target return within a maximum number of episodes'}
```

