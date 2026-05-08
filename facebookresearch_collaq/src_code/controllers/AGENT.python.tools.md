# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/src_code/controllers/basic_controller_influence.py

Prompts

```
['initialize a BasicMACInfluence multi-agent controller with scheme, groups, and args for COLLAQ training', 'select actions for agents in a multi-agent episode batch using alone Q-value outputs', 'get individual Q-values including interactive, alone, and combined outputs for each agent in the batch', 'get alone Q-values from the target agent network for influence-based action selection', 'run a forward pass through the agent network to compute policy logits or Q-values', 'create a BasicMACInteractive multi-agent controller that shares parameters between agents using scheme, groups, and args', 'select actions for agents in a batch using the BasicMACInteractive controller with forward pass and action selector', 'initialize hidden states for all agents in a BasicMACInteractive controller given a batch size', 'save or load agent model state dictionaries to and from a file path using BasicMACInteractive', 'create a BasicMACInteractiveRegV2 controller with a target agent for regularized multi-agent reinforcement learning']
```

Usage

```
{'init_BasicMACInfluence': 'initialize a BasicMACInfluence multi-agent controller with scheme, groups, and args for COLLAQ training', 'select_actions_BasicMACInfluence': 'select actions for agents in a multi-agent episode batch using alone Q-value outputs', 'get_individual_q_BasicMACInfluence': 'get individual Q-values including interactive, alone, and combined outputs for each agent in the batch', 'get_alone_q_BasicMACInfluence': 'get alone Q-values from the target agent network for influence-based action selection', 'forward_BasicMACInfluence': 'run a forward pass through the agent network to compute policy logits or Q-values'}
```

## File: facebookresearch_collaq/src_code/controllers/basic_controller_interactive.py

Prompts

```
['initialize a BasicMACInfluence multi-agent controller with scheme, groups, and args for COLLAQ training', 'select actions for agents in a multi-agent episode batch using alone Q-value outputs', 'get individual Q-values including interactive, alone, and combined outputs for each agent in the batch', 'get alone Q-values from the target agent network for influence-based action selection', 'run a forward pass through the agent network to compute policy logits or Q-values', 'create a BasicMACInteractive multi-agent controller that shares parameters between agents using scheme, groups, and args', 'select actions for agents in a batch using the BasicMACInteractive controller with forward pass and action selector', 'initialize hidden states for all agents in a BasicMACInteractive controller given a batch size', 'save or load agent model state dictionaries to and from a file path using BasicMACInteractive', 'create a BasicMACInteractiveRegV2 controller with a target agent for regularized multi-agent reinforcement learning']
```

Usage

```
{'create_BasicMACInteractive': 'create a BasicMACInteractive multi-agent controller that shares parameters between agents using scheme, groups, and args', 'select_actions_BasicMACInteractive': 'select actions for agents in a batch using the BasicMACInteractive controller with forward pass and action selector', 'init_hidden_BasicMACInteractive': 'initialize hidden states for all agents in a BasicMACInteractive controller given a batch size', 'save_and_load_models_BasicMACInteractive': 'save or load agent model state dictionaries to and from a file path using BasicMACInteractive', 'create_BasicMACInteractiveRegV2': 'create a BasicMACInteractiveRegV2 controller with a target agent for regularized multi-agent reinforcement learning'}
```

