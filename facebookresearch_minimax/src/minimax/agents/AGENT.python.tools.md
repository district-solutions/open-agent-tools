# Agent Python Tools

- repo: facebookresearch/minimax
- repo_uri: https://github.com/facebookresearch/minimax

## File: facebookresearch_minimax/src/minimax/agents/agent.py

Prompts

```
['review the Agent abstract base class and its generic interface for agent implementations', 'implement the Agent act method to compute actions from observations and carry state', 'implement the Agent init_params method to initialize parameters given an RNG and observations', 'implement the Agent get_action_dist method to return an action distribution from dist_params and dtype', 'implement the Agent update method to perform a learning update step on the agent', 'build a PPOAgent with configurable epochs, minibatches, value loss coefficient, and entropy coefficient for RL training', 'initialize PPO model parameters and RNN hidden state given an observation shape and random key', 'run a JIT-compiled forward pass to get value estimates, action logits, and carry state from observations', 'evaluate an action against the PPO policy to get log probability, entropy, and value estimates', 'update PPO model parameters using clipped surrogate loss, value loss, and entropy regularization across epochs']
```

Usage

```
{'review_Agent_class': 'review the Agent abstract base class and its generic interface for agent implementations', 'implement_Agent_act': 'implement the Agent act method to compute actions from observations and carry state', 'implement_Agent_init_params': 'implement the Agent init_params method to initialize parameters given an RNG and observations', 'implement_Agent_get_action_dist': 'implement the Agent get_action_dist method to return an action distribution from dist_params and dtype', 'implement_Agent_update': 'implement the Agent update method to perform a learning update step on the agent'}
```

## File: facebookresearch_minimax/src/minimax/agents/ppo.py

Prompts

```
['review the Agent abstract base class and its generic interface for agent implementations', 'implement the Agent act method to compute actions from observations and carry state', 'implement the Agent init_params method to initialize parameters given an RNG and observations', 'implement the Agent get_action_dist method to return an action distribution from dist_params and dtype', 'implement the Agent update method to perform a learning update step on the agent', 'build a PPOAgent with configurable epochs, minibatches, value loss coefficient, and entropy coefficient for RL training', 'initialize PPO model parameters and RNN hidden state given an observation shape and random key', 'run a JIT-compiled forward pass to get value estimates, action logits, and carry state from observations', 'evaluate an action against the PPO policy to get log probability, entropy, and value estimates', 'update PPO model parameters using clipped surrogate loss, value loss, and entropy regularization across epochs']
```

Usage

```
{'build_ppo_agent': 'build a PPOAgent with configurable epochs, minibatches, value loss coefficient, and entropy coefficient for RL training', 'init_ppo_params': 'initialize PPO model parameters and RNN hidden state given an observation shape and random key', 'act_ppo_agent': 'run a JIT-compiled forward pass to get value estimates, action logits, and carry state from observations', 'evaluate_ppo_action': 'evaluate an action against the PPO policy to get log probability, entropy, and value estimates', 'update_ppo_model': 'update PPO model parameters using clipped surrogate loss, value loss, and entropy regularization across epochs'}
```

