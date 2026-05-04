# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/rl/ppo/policy.py

Prompts

```
['build a PointNavBaselinePolicy from config with observation and action spaces for PPO navigation', 'create a CriticHead linear layer with orthogonal weight initialization for value estimation', 'run the Policy act method to sample actions and compute values from observations', 'test the Policy evaluate_actions method to get log probs and entropy for actions', 'review the PointNavBaselineNet forward pass that encodes goals and visual observations through RNN', 'build a PPO reinforcement learning agent with an actor-critic policy and Adam optimizer', 'update the PPO policy using rollout storage and return value, action, and entropy losses', 'get normalized advantage estimates from rollout storage returns and value predictions', 'evaluate actions using the actor-critic policy and return log probabilities and entropy', 'review the PPO before_step method that clips gradient norms on actor-critic parameters', 'train a PPO agent for navigation tasks using the PPOTrainer train method with config', 'setup an actor-critic policy and PPO agent from config with pretrained encoder support', 'evaluate a trained PPO checkpoint on test episodes and log reward metrics to tensorboard', 'save or load a PPO trainer checkpoint with agent state dict and config', 'collect a rollout step by computing actions and stepping environments for PPO training']
```

Usage

```
{'build_PointNavBaselinePolicy': 'build a PointNavBaselinePolicy from config with observation and action spaces for PPO navigation', 'create_CriticHead': 'create a CriticHead linear layer with orthogonal weight initialization for value estimation', 'run_Policy_act': 'run the Policy act method to sample actions and compute values from observations', 'test_Policy_evaluate_actions': 'test the Policy evaluate_actions method to get log probs and entropy for actions', 'review_PointNavBaselineNet_forward': 'review the PointNavBaselineNet forward pass that encodes goals and visual observations through RNN'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/rl/ppo/ppo.py

Prompts

```
['build a PointNavBaselinePolicy from config with observation and action spaces for PPO navigation', 'create a CriticHead linear layer with orthogonal weight initialization for value estimation', 'run the Policy act method to sample actions and compute values from observations', 'test the Policy evaluate_actions method to get log probs and entropy for actions', 'review the PointNavBaselineNet forward pass that encodes goals and visual observations through RNN', 'build a PPO reinforcement learning agent with an actor-critic policy and Adam optimizer', 'update the PPO policy using rollout storage and return value, action, and entropy losses', 'get normalized advantage estimates from rollout storage returns and value predictions', 'evaluate actions using the actor-critic policy and return log probabilities and entropy', 'review the PPO before_step method that clips gradient norms on actor-critic parameters', 'train a PPO agent for navigation tasks using the PPOTrainer train method with config', 'setup an actor-critic policy and PPO agent from config with pretrained encoder support', 'evaluate a trained PPO checkpoint on test episodes and log reward metrics to tensorboard', 'save or load a PPO trainer checkpoint with agent state dict and config', 'collect a rollout step by computing actions and stepping environments for PPO training']
```

Usage

```
{'build_PPO_agent': 'build a PPO reinforcement learning agent with an actor-critic policy and Adam optimizer', 'update_PPO_policy': 'update the PPO policy using rollout storage and return value, action, and entropy losses', 'get_PPO_advantages': 'get normalized advantage estimates from rollout storage returns and value predictions', 'evaluate_PPO_actions': 'evaluate actions using the actor-critic policy and return log probabilities and entropy', 'review_PPO_gradient_clipping': 'review the PPO before_step method that clips gradient norms on actor-critic parameters'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/rl/ppo/ppo_trainer.py

Prompts

```
['build a PointNavBaselinePolicy from config with observation and action spaces for PPO navigation', 'create a CriticHead linear layer with orthogonal weight initialization for value estimation', 'run the Policy act method to sample actions and compute values from observations', 'test the Policy evaluate_actions method to get log probs and entropy for actions', 'review the PointNavBaselineNet forward pass that encodes goals and visual observations through RNN', 'build a PPO reinforcement learning agent with an actor-critic policy and Adam optimizer', 'update the PPO policy using rollout storage and return value, action, and entropy losses', 'get normalized advantage estimates from rollout storage returns and value predictions', 'evaluate actions using the actor-critic policy and return log probabilities and entropy', 'review the PPO before_step method that clips gradient norms on actor-critic parameters', 'train a PPO agent for navigation tasks using the PPOTrainer train method with config', 'setup an actor-critic policy and PPO agent from config with pretrained encoder support', 'evaluate a trained PPO checkpoint on test episodes and log reward metrics to tensorboard', 'save or load a PPO trainer checkpoint with agent state dict and config', 'collect a rollout step by computing actions and stepping environments for PPO training']
```

Usage

```
{'train_ppo_agent': 'train a PPO agent for navigation tasks using the PPOTrainer train method with config', 'setup_actor_critic_agent': 'setup an actor-critic policy and PPO agent from config with pretrained encoder support', 'eval_checkpoint': 'evaluate a trained PPO checkpoint on test episodes and log reward metrics to tensorboard', 'save_load_checkpoint': 'save or load a PPO trainer checkpoint with agent state dict and config', 'collect_rollout_step': 'collect a rollout step by computing actions and stepping environments for PPO training'}
```

