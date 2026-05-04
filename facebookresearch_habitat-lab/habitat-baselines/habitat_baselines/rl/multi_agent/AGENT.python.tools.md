# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/multi_agent/multi_agent_access_mgr.py

Prompts

```
['create a MultiAgentAccessMgr instance with config, env_spec, device, and num_envs for multi-agent RL training', 'sample active agents from the population by calling _sample_active to randomly select agents for the current episode', 'load type 1 agent checkpoints from disk paths using _load_type1_ckpts to restore agent states', 'resample the active agent population after each update interval by calling after_update on the manager', 'get the resume state for all agents in the population by calling get_resume_state on the manager', 'build a multi-agent policy that splits observations and concatenates actions from multiple active policies', 'create a multi-agent storage wrapper that chunks and inserts rollout data per agent', 'test the MultiAgentPolicyActionData unpack method to split concatenated tensors per agent', 'refactor the MultiUpdater update method to aggregate losses from multiple agent updaters', 'review the MultiPolicy get_value method that computes stacked values across all active policies', 'create a SelfBatchedPolicy instance wrapping a SingleAgentAccessMgr for multi-agent self-play scenarios', 'create a SelfBatchedStorage instance wrapping a SingleAgentAccessMgr rollout buffer for multi-agent training', 'create a SelfBatchedUpdater instance wrapping a SingleAgentAccessMgr updater for multi-agent policy updates', 'review the SelfBatchedPolicy from_config class method that constructs a policy from config and agent', 'refactor the SelfBatchedStorage abstract methods to implement multi-agent rollout insertion and return computation', 'filter a dictionary to keys matching a specific agent index prefix and remove that prefix', 'generate an agent-prefixed key string by combining an agent index with a base key name', 'copy all key-value pairs from a source dict into a destination dict with agent index prefixes added', 'strip an agent prefix string from the beginning of a name if it matches', 'refactor update_dict_with_agent_prefix to support a custom prefix format instead of agent_N_']
```

Usage

```
{'create_MultiAgentAccessMgr': 'create a MultiAgentAccessMgr instance with config, env_spec, device, and num_envs for multi-agent RL training', 'sample_active_agents': 'sample active agents from the population by calling _sample_active to randomly select agents for the current episode', 'load_type1_checkpoints': 'load type 1 agent checkpoints from disk paths using _load_type1_ckpts to restore agent states', 'resample_after_update': 'resample the active agent population after each update interval by calling after_update on the manager', 'get_resume_state': 'get the resume state for all agents in the population by calling get_resume_state on the manager'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/multi_agent/pop_play_wrappers.py

Prompts

```
['create a MultiAgentAccessMgr instance with config, env_spec, device, and num_envs for multi-agent RL training', 'sample active agents from the population by calling _sample_active to randomly select agents for the current episode', 'load type 1 agent checkpoints from disk paths using _load_type1_ckpts to restore agent states', 'resample the active agent population after each update interval by calling after_update on the manager', 'get the resume state for all agents in the population by calling get_resume_state on the manager', 'build a multi-agent policy that splits observations and concatenates actions from multiple active policies', 'create a multi-agent storage wrapper that chunks and inserts rollout data per agent', 'test the MultiAgentPolicyActionData unpack method to split concatenated tensors per agent', 'refactor the MultiUpdater update method to aggregate losses from multiple agent updaters', 'review the MultiPolicy get_value method that computes stacked values across all active policies', 'create a SelfBatchedPolicy instance wrapping a SingleAgentAccessMgr for multi-agent self-play scenarios', 'create a SelfBatchedStorage instance wrapping a SingleAgentAccessMgr rollout buffer for multi-agent training', 'create a SelfBatchedUpdater instance wrapping a SingleAgentAccessMgr updater for multi-agent policy updates', 'review the SelfBatchedPolicy from_config class method that constructs a policy from config and agent', 'refactor the SelfBatchedStorage abstract methods to implement multi-agent rollout insertion and return computation', 'filter a dictionary to keys matching a specific agent index prefix and remove that prefix', 'generate an agent-prefixed key string by combining an agent index with a base key name', 'copy all key-value pairs from a source dict into a destination dict with agent index prefixes added', 'strip an agent prefix string from the beginning of a name if it matches', 'refactor update_dict_with_agent_prefix to support a custom prefix format instead of agent_N_']
```

Usage

```
{'build_MultiPolicy_act': 'build a multi-agent policy that splits observations and concatenates actions from multiple active policies', 'create_MultiStorage_insert': 'create a multi-agent storage wrapper that chunks and inserts rollout data per agent', 'test_MultiAgentPolicyActionData_unpack': 'test the MultiAgentPolicyActionData unpack method to split concatenated tensors per agent', 'refactor_MultiUpdater_update': 'refactor the MultiUpdater update method to aggregate losses from multiple agent updaters', 'review_MultiPolicy_get_value': 'review the MultiPolicy get_value method that computes stacked values across all active policies'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/multi_agent/self_play_wrappers.py

Prompts

```
['create a MultiAgentAccessMgr instance with config, env_spec, device, and num_envs for multi-agent RL training', 'sample active agents from the population by calling _sample_active to randomly select agents for the current episode', 'load type 1 agent checkpoints from disk paths using _load_type1_ckpts to restore agent states', 'resample the active agent population after each update interval by calling after_update on the manager', 'get the resume state for all agents in the population by calling get_resume_state on the manager', 'build a multi-agent policy that splits observations and concatenates actions from multiple active policies', 'create a multi-agent storage wrapper that chunks and inserts rollout data per agent', 'test the MultiAgentPolicyActionData unpack method to split concatenated tensors per agent', 'refactor the MultiUpdater update method to aggregate losses from multiple agent updaters', 'review the MultiPolicy get_value method that computes stacked values across all active policies', 'create a SelfBatchedPolicy instance wrapping a SingleAgentAccessMgr for multi-agent self-play scenarios', 'create a SelfBatchedStorage instance wrapping a SingleAgentAccessMgr rollout buffer for multi-agent training', 'create a SelfBatchedUpdater instance wrapping a SingleAgentAccessMgr updater for multi-agent policy updates', 'review the SelfBatchedPolicy from_config class method that constructs a policy from config and agent', 'refactor the SelfBatchedStorage abstract methods to implement multi-agent rollout insertion and return computation', 'filter a dictionary to keys matching a specific agent index prefix and remove that prefix', 'generate an agent-prefixed key string by combining an agent index with a base key name', 'copy all key-value pairs from a source dict into a destination dict with agent index prefixes added', 'strip an agent prefix string from the beginning of a name if it matches', 'refactor update_dict_with_agent_prefix to support a custom prefix format instead of agent_N_']
```

Usage

```
{'create_SelfBatchedPolicy': 'create a SelfBatchedPolicy instance wrapping a SingleAgentAccessMgr for multi-agent self-play scenarios', 'create_SelfBatchedStorage': 'create a SelfBatchedStorage instance wrapping a SingleAgentAccessMgr rollout buffer for multi-agent training', 'create_SelfBatchedUpdater': 'create a SelfBatchedUpdater instance wrapping a SingleAgentAccessMgr updater for multi-agent policy updates', 'review_SelfBatchedPolicy_from_config': 'review the SelfBatchedPolicy from_config class method that constructs a policy from config and agent', 'refactor_SelfBatchedStorage_methods': 'refactor the SelfBatchedStorage abstract methods to implement multi-agent rollout insertion and return computation'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/multi_agent/utils.py

Prompts

```
['create a MultiAgentAccessMgr instance with config, env_spec, device, and num_envs for multi-agent RL training', 'sample active agents from the population by calling _sample_active to randomly select agents for the current episode', 'load type 1 agent checkpoints from disk paths using _load_type1_ckpts to restore agent states', 'resample the active agent population after each update interval by calling after_update on the manager', 'get the resume state for all agents in the population by calling get_resume_state on the manager', 'build a multi-agent policy that splits observations and concatenates actions from multiple active policies', 'create a multi-agent storage wrapper that chunks and inserts rollout data per agent', 'test the MultiAgentPolicyActionData unpack method to split concatenated tensors per agent', 'refactor the MultiUpdater update method to aggregate losses from multiple agent updaters', 'review the MultiPolicy get_value method that computes stacked values across all active policies', 'create a SelfBatchedPolicy instance wrapping a SingleAgentAccessMgr for multi-agent self-play scenarios', 'create a SelfBatchedStorage instance wrapping a SingleAgentAccessMgr rollout buffer for multi-agent training', 'create a SelfBatchedUpdater instance wrapping a SingleAgentAccessMgr updater for multi-agent policy updates', 'review the SelfBatchedPolicy from_config class method that constructs a policy from config and agent', 'refactor the SelfBatchedStorage abstract methods to implement multi-agent rollout insertion and return computation', 'filter a dictionary to keys matching a specific agent index prefix and remove that prefix', 'generate an agent-prefixed key string by combining an agent index with a base key name', 'copy all key-value pairs from a source dict into a destination dict with agent index prefixes added', 'strip an agent prefix string from the beginning of a name if it matches', 'refactor update_dict_with_agent_prefix to support a custom prefix format instead of agent_N_']
```

Usage

```
{'update_dict_with_agent_prefix': 'filter a dictionary to keys matching a specific agent index prefix and remove that prefix', 'add_agent_prefix': 'generate an agent-prefixed key string by combining an agent index with a base key name', 'add_agent_names': 'copy all key-value pairs from a source dict into a destination dict with agent index prefixes added', 'remove_agent_prefix': 'strip an agent prefix string from the beginning of a name if it matches', 'refactor_update_dict_with_agent_prefix': 'refactor update_dict_with_agent_prefix to support a custom prefix format instead of agent_N_'}
```

