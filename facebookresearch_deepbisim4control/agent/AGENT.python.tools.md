# Agent Python Tools

- repo: facebookresearch/deepbisim4control
- repo_uri: https://github.com/facebookresearch/deep_bisim4control

## File: facebookresearch_deepbisim4control/agent/baseline_agent.py

Prompts

```
['create a BaselineAgent with SAC, transition model, and configurable decoder types for RL training', 'run the BaselineAgent select_action method to get a deterministic action from an observation', 'run the BaselineAgent sample_action method to sample a stochastic action from the policy', 'run the BaselineAgent update method to perform one training step using a replay buffer sample', 'run the BaselineAgent save and load methods to persist and restore actor, critic, and decoder weights', 'create a BisimAgent instance with observation shape, action shape, device, and transition model type', 'select a greedy action from the actor policy given an observation tensor', 'sample a stochastic action from the actor policy given an observation tensor', 'run one training step updating critic, encoder, transition model, and actor from replay buffer', 'save or load BisimAgent model checkpoints for actor, critic, and reward decoder', 'create a DeepMDPAgent instance with pixel encoder, transition model, and SAC-based actor-critic networks', 'select a deterministic action from the agent given an observation tensor input', 'update the agent by sampling from replay buffer and updating critic, actor, transition, and decoder', 'save the actor, critic, and decoder model state dicts to disk at a given step', 'load the actor, critic, and decoder model state dicts from disk for a given step']
```

Usage

```
{'create_BaselineAgent': 'create a BaselineAgent with SAC, transition model, and configurable decoder types for RL training', 'run_select_action': 'run the BaselineAgent select_action method to get a deterministic action from an observation', 'run_sample_action': 'run the BaselineAgent sample_action method to sample a stochastic action from the policy', 'run_update': 'run the BaselineAgent update method to perform one training step using a replay buffer sample', 'run_save_load': 'run the BaselineAgent save and load methods to persist and restore actor, critic, and decoder weights'}
```

## File: facebookresearch_deepbisim4control/agent/bisim_agent.py

Prompts

```
['create a BaselineAgent with SAC, transition model, and configurable decoder types for RL training', 'run the BaselineAgent select_action method to get a deterministic action from an observation', 'run the BaselineAgent sample_action method to sample a stochastic action from the policy', 'run the BaselineAgent update method to perform one training step using a replay buffer sample', 'run the BaselineAgent save and load methods to persist and restore actor, critic, and decoder weights', 'create a BisimAgent instance with observation shape, action shape, device, and transition model type', 'select a greedy action from the actor policy given an observation tensor', 'sample a stochastic action from the actor policy given an observation tensor', 'run one training step updating critic, encoder, transition model, and actor from replay buffer', 'save or load BisimAgent model checkpoints for actor, critic, and reward decoder', 'create a DeepMDPAgent instance with pixel encoder, transition model, and SAC-based actor-critic networks', 'select a deterministic action from the agent given an observation tensor input', 'update the agent by sampling from replay buffer and updating critic, actor, transition, and decoder', 'save the actor, critic, and decoder model state dicts to disk at a given step', 'load the actor, critic, and decoder model state dicts from disk for a given step']
```

Usage

```
{'create_BisimAgent': 'create a BisimAgent instance with observation shape, action shape, device, and transition model type', 'select_action_BisimAgent': 'select a greedy action from the actor policy given an observation tensor', 'sample_action_BisimAgent': 'sample a stochastic action from the actor policy given an observation tensor', 'update_BisimAgent': 'run one training step updating critic, encoder, transition model, and actor from replay buffer', 'save_load_BisimAgent': 'save or load BisimAgent model checkpoints for actor, critic, and reward decoder'}
```

## File: facebookresearch_deepbisim4control/agent/deepmdp_agent.py

Prompts

```
['create a BaselineAgent with SAC, transition model, and configurable decoder types for RL training', 'run the BaselineAgent select_action method to get a deterministic action from an observation', 'run the BaselineAgent sample_action method to sample a stochastic action from the policy', 'run the BaselineAgent update method to perform one training step using a replay buffer sample', 'run the BaselineAgent save and load methods to persist and restore actor, critic, and decoder weights', 'create a BisimAgent instance with observation shape, action shape, device, and transition model type', 'select a greedy action from the actor policy given an observation tensor', 'sample a stochastic action from the actor policy given an observation tensor', 'run one training step updating critic, encoder, transition model, and actor from replay buffer', 'save or load BisimAgent model checkpoints for actor, critic, and reward decoder', 'create a DeepMDPAgent instance with pixel encoder, transition model, and SAC-based actor-critic networks', 'select a deterministic action from the agent given an observation tensor input', 'update the agent by sampling from replay buffer and updating critic, actor, transition, and decoder', 'save the actor, critic, and decoder model state dicts to disk at a given step', 'load the actor, critic, and decoder model state dicts from disk for a given step']
```

Usage

```
{'create_DeepMDPAgent': 'create a DeepMDPAgent instance with pixel encoder, transition model, and SAC-based actor-critic networks', 'select_action_DeepMDPAgent': 'select a deterministic action from the agent given an observation tensor input', 'update_DeepMDPAgent': 'update the agent by sampling from replay buffer and updating critic, actor, transition, and decoder', 'save_DeepMDPAgent': 'save the actor, critic, and decoder model state dicts to disk at a given step', 'load_DeepMDPAgent': 'load the actor, critic, and decoder model state dicts from disk for a given step'}
```

