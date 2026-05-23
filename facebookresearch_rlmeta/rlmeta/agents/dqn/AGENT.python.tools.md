# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/rlmeta/agents/dqn/apex_dqn_agent.py

Prompts

```
['create an ApexDQNAgent with a model, replay buffer, controller, and optimizer for DQN training', 'train an ApexDQNAgent for a specified number of steps using replay buffer sampling and gradient updates', 'evaluate an ApexDQNAgent over a set number of episodes and return training stats', 'create an ApexDQNAgentFactory with an eps function to instantiate multiple ApexDQNAgent instances', 'create a FlexibleEpsFunc that computes epsilon values per agent index following the RAINBOW paper schedule', 'create a subclass of DQNModel that implements forward, q, act, and sync_target_net methods', 'implement the forward method to return Q values for each action given an observation tensor', 'implement the q method to compute the Q(s, a) value for a given state and action pair', 'implement the act method to select actions using epsilon-greedy policy and return action, q value, and state value', 'compute the temporal difference error by calling td_error with observation, action, and target tensors']
```

Usage

```
{'create_ApexDQNAgent': 'create an ApexDQNAgent with a model, replay buffer, controller, and optimizer for DQN training', 'train_ApexDQNAgent': 'train an ApexDQNAgent for a specified number of steps using replay buffer sampling and gradient updates', 'eval_ApexDQNAgent': 'evaluate an ApexDQNAgent over a set number of episodes and return training stats', 'create_ApexDQNAgentFactory': 'create an ApexDQNAgentFactory with an eps function to instantiate multiple ApexDQNAgent instances', 'create_FlexibleEpsFunc': 'create a FlexibleEpsFunc that computes epsilon values per agent index following the RAINBOW paper schedule'}
```

## File: facebookresearch_rlmeta/rlmeta/agents/dqn/dqn_model.py

Prompts

```
['create an ApexDQNAgent with a model, replay buffer, controller, and optimizer for DQN training', 'train an ApexDQNAgent for a specified number of steps using replay buffer sampling and gradient updates', 'evaluate an ApexDQNAgent over a set number of episodes and return training stats', 'create an ApexDQNAgentFactory with an eps function to instantiate multiple ApexDQNAgent instances', 'create a FlexibleEpsFunc that computes epsilon values per agent index following the RAINBOW paper schedule', 'create a subclass of DQNModel that implements forward, q, act, and sync_target_net methods', 'implement the forward method to return Q values for each action given an observation tensor', 'implement the q method to compute the Q(s, a) value for a given state and action pair', 'implement the act method to select actions using epsilon-greedy policy and return action, q value, and state value', 'compute the temporal difference error by calling td_error with observation, action, and target tensors']
```

Usage

```
{'create_dqn_subclass': 'create a subclass of DQNModel that implements forward, q, act, and sync_target_net methods', 'implement_forward_method': 'implement the forward method to return Q values for each action given an observation tensor', 'implement_q_method': 'implement the q method to compute the Q(s, a) value for a given state and action pair', 'implement_act_method': 'implement the act method to select actions using epsilon-greedy policy and return action, q value, and state value', 'compute_td_error': 'compute the temporal difference error by calling td_error with observation, action, and target tensors'}
```

