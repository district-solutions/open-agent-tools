# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlstructures/rl_batchers/agent.py

Prompts

```
['create a subclass of RL_Agent implementing initial_state, update, and __call__ methods for a custom policy', 'wrap an RL_Agent with RL_Agent_CheckDevice to validate tensor device placement on GPU or CPU', 'replay an agent over trajectories step by step using replay_agent to collect actions and states', 'replay an agent over all transitions at once using replay_agent_stateless for stateless policies', 'implement call_replay on an RL_Agent subclass to handle single-step trajectory replay with state', 'create a multi-process RL_Batcher with agent factory, env factory, seeds, and n_processes', 'reset all batcher workers with sliced agent_info and env_info DictTensors', 'execute batcher workers by acquiring slots and distributing agent_info slices', 'get completed Trajectories and still-running count from the batcher buffer', 'update all batcher process workers with new info DictTensor', 'create a shared S_Buffer with n_slots and s_slots to store RL trajectories and transitions', 'write observation, action, and next observation tensors into specific buffer slots at current positions', 'retrieve TemporalDictTensor data from buffer slots by slot IDs with optional erase and clone flags', 'acquire free buffer slots and run agent-environment interaction loop for s_slots timesteps', 'start an S_ProcessWorker subprocess that manages agent-environment interaction via in/out queues']
```

Usage

```
{'create_RL_Agent_subclass': 'create a subclass of RL_Agent implementing initial_state, update, and __call__ methods for a custom policy', 'use_RL_Agent_CheckDevice': 'wrap an RL_Agent with RL_Agent_CheckDevice to validate tensor device placement on GPU or CPU', 'replay_agent_step_by_step': 'replay an agent over trajectories step by step using replay_agent to collect actions and states', 'replay_agent_stateless_all_at_once': 'replay an agent over all transitions at once using replay_agent_stateless for stateless policies', 'implement_call_replay_method': 'implement call_replay on an RL_Agent subclass to handle single-step trajectory replay with state'}
```

## File: facebookresearch_rlstructures/rlstructures/rl_batchers/batcher.py

Prompts

```
['create a subclass of RL_Agent implementing initial_state, update, and __call__ methods for a custom policy', 'wrap an RL_Agent with RL_Agent_CheckDevice to validate tensor device placement on GPU or CPU', 'replay an agent over trajectories step by step using replay_agent to collect actions and states', 'replay an agent over all transitions at once using replay_agent_stateless for stateless policies', 'implement call_replay on an RL_Agent subclass to handle single-step trajectory replay with state', 'create a multi-process RL_Batcher with agent factory, env factory, seeds, and n_processes', 'reset all batcher workers with sliced agent_info and env_info DictTensors', 'execute batcher workers by acquiring slots and distributing agent_info slices', 'get completed Trajectories and still-running count from the batcher buffer', 'update all batcher process workers with new info DictTensor', 'create a shared S_Buffer with n_slots and s_slots to store RL trajectories and transitions', 'write observation, action, and next observation tensors into specific buffer slots at current positions', 'retrieve TemporalDictTensor data from buffer slots by slot IDs with optional erase and clone flags', 'acquire free buffer slots and run agent-environment interaction loop for s_slots timesteps', 'start an S_ProcessWorker subprocess that manages agent-environment interaction via in/out queues']
```

Usage

```
{'create_rl_batcher': 'create a multi-process RL_Batcher with agent factory, env factory, seeds, and n_processes', 'reset_rl_batcher': 'reset all batcher workers with sliced agent_info and env_info DictTensors', 'execute_rl_batcher': 'execute batcher workers by acquiring slots and distributing agent_info slices', 'get_trajectories': 'get completed Trajectories and still-running count from the batcher buffer', 'update_rl_batcher': 'update all batcher process workers with new info DictTensor'}
```

## File: facebookresearch_rlstructures/rlstructures/rl_batchers/tools.py

Prompts

```
['create a subclass of RL_Agent implementing initial_state, update, and __call__ methods for a custom policy', 'wrap an RL_Agent with RL_Agent_CheckDevice to validate tensor device placement on GPU or CPU', 'replay an agent over trajectories step by step using replay_agent to collect actions and states', 'replay an agent over all transitions at once using replay_agent_stateless for stateless policies', 'implement call_replay on an RL_Agent subclass to handle single-step trajectory replay with state', 'create a multi-process RL_Batcher with agent factory, env factory, seeds, and n_processes', 'reset all batcher workers with sliced agent_info and env_info DictTensors', 'execute batcher workers by acquiring slots and distributing agent_info slices', 'get completed Trajectories and still-running count from the batcher buffer', 'update all batcher process workers with new info DictTensor', 'create a shared S_Buffer with n_slots and s_slots to store RL trajectories and transitions', 'write observation, action, and next observation tensors into specific buffer slots at current positions', 'retrieve TemporalDictTensor data from buffer slots by slot IDs with optional erase and clone flags', 'acquire free buffer slots and run agent-environment interaction loop for s_slots timesteps', 'start an S_ProcessWorker subprocess that manages agent-environment interaction via in/out queues']
```

Usage

```
{'create_s_buffer': 'create a shared S_Buffer with n_slots and s_slots to store RL trajectories and transitions', 'write_buffer_slots': 'write observation, action, and next observation tensors into specific buffer slots at current positions', 'get_single_slots': 'retrieve TemporalDictTensor data from buffer slots by slot IDs with optional erase and clone flags', 'acquire_slot_s_acquire': 'acquire free buffer slots and run agent-environment interaction loop for s_slots timesteps', 'start_process_worker': 'start an S_ProcessWorker subprocess that manages agent-environment interaction via in/out queues'}
```

