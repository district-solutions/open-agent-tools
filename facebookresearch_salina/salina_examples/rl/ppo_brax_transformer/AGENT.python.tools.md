# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/ppo_brax_transformer/agents.py

Prompts

```
['build a TransitionEncoder agent that encodes state-action-next_state tuples into embedding vectors with positional encoding', 'build an ActionAgent that samples actions from a normal distribution and applies tanh for Brax environments', 'build a CriticAgent that evaluates state-value estimates from transformer output embeddings', 'create an action transformer pipeline combining TransitionEncoder, TransformerMultiBlockAgent, and ActionAgent for PPO policy', 'create a critic transformer pipeline combining TransitionEncoder, TransformerMultiBlockAgent, and CriticAgent for value estimation', 'run the PPO reinforcement learning training loop with action and critic agents on a Brax environment', 'create a Normalizer agent that computes running mean and variance to normalize environment observations online', 'create a BatchNormalizer agent that applies PyTorch BatchNorm1d to normalize environment observations', 'clip the gradient norm of model parameters to a specified maximum value during training', 'run the main entry point that instantiates agents from Hydra config and starts PPO training']
```

Usage

```
{'build_TransitionEncoder': 'build a TransitionEncoder agent that encodes state-action-next_state tuples into embedding vectors with positional encoding', 'build_ActionAgent': 'build an ActionAgent that samples actions from a normal distribution and applies tanh for Brax environments', 'build_CriticAgent': 'build a CriticAgent that evaluates state-value estimates from transformer output embeddings', 'create_action_transformer': 'create an action transformer pipeline combining TransitionEncoder, TransformerMultiBlockAgent, and ActionAgent for PPO policy', 'create_critic_transformer': 'create a critic transformer pipeline combining TransitionEncoder, TransformerMultiBlockAgent, and CriticAgent for value estimation'}
```

## File: facebookresearch_salina/salina_examples/rl/ppo_brax_transformer/ppo.py

Prompts

```
['build a TransitionEncoder agent that encodes state-action-next_state tuples into embedding vectors with positional encoding', 'build an ActionAgent that samples actions from a normal distribution and applies tanh for Brax environments', 'build a CriticAgent that evaluates state-value estimates from transformer output embeddings', 'create an action transformer pipeline combining TransitionEncoder, TransformerMultiBlockAgent, and ActionAgent for PPO policy', 'create a critic transformer pipeline combining TransitionEncoder, TransformerMultiBlockAgent, and CriticAgent for value estimation', 'run the PPO reinforcement learning training loop with action and critic agents on a Brax environment', 'create a Normalizer agent that computes running mean and variance to normalize environment observations online', 'create a BatchNormalizer agent that applies PyTorch BatchNorm1d to normalize environment observations', 'clip the gradient norm of model parameters to a specified maximum value during training', 'run the main entry point that instantiates agents from Hydra config and starts PPO training']
```

Usage

```
{'run_PPO_training': 'run the PPO reinforcement learning training loop with action and critic agents on a Brax environment', 'create_Normalizer_agent': 'create a Normalizer agent that computes running mean and variance to normalize environment observations online', 'create_BatchNormalizer_agent': 'create a BatchNormalizer agent that applies PyTorch BatchNorm1d to normalize environment observations', 'clip_gradients': 'clip the gradient norm of model parameters to a specified maximum value during training', 'run_main_entry': 'run the main entry point that instantiates agents from Hydra config and starts PPO training'}
```

