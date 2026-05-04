# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/r2d3/agent.py

Prompts

```
['build an R2D3 agent that mixes demonstrations with actor experience using a recurrent network', 'create a Reverb replay server with a uniform sampler and FIFO remover for sequence data', 'combine a Reverb replay dataset with a demonstration dataset using sample_from_datasets with a ratio', 'run the sequence_from_episode function to produce Reverb-like sequences from full episode trajectories', 'update the R2D3 agent and save snapshots and checkpoints for the learner and network', 'test the R2D3 agent by running it in a fake discrete environment for multiple episodes', 'build a SimpleNetwork RNNCore subclass with LSTM and MLP layers for action prediction', 'create a DemonstrationRecorder to record environment timesteps and actions as demonstration episodes', 'run an acme EnvironmentLoop with a fake environment and R2D3 agent for a set number of episodes', 'construct an R2D3 agent with a network, target network, demonstration dataset, and replay parameters']
```

Usage

```
{'build_r2d3_agent': 'build an R2D3 agent that mixes demonstrations with actor experience using a recurrent network', 'create_replay_server': 'create a Reverb replay server with a uniform sampler and FIFO remover for sequence data', 'combine_datasets': 'combine a Reverb replay dataset with a demonstration dataset using sample_from_datasets with a ratio', 'run_sequence_from_episode': 'run the sequence_from_episode function to produce Reverb-like sequences from full episode trajectories', 'update_checkpoints': 'update the R2D3 agent and save snapshots and checkpoints for the learner and network'}
```

## File: google-deepmind_acme/acme/agents/tf/r2d3/agent_test.py

Prompts

```
['build an R2D3 agent that mixes demonstrations with actor experience using a recurrent network', 'create a Reverb replay server with a uniform sampler and FIFO remover for sequence data', 'combine a Reverb replay dataset with a demonstration dataset using sample_from_datasets with a ratio', 'run the sequence_from_episode function to produce Reverb-like sequences from full episode trajectories', 'update the R2D3 agent and save snapshots and checkpoints for the learner and network', 'test the R2D3 agent by running it in a fake discrete environment for multiple episodes', 'build a SimpleNetwork RNNCore subclass with LSTM and MLP layers for action prediction', 'create a DemonstrationRecorder to record environment timesteps and actions as demonstration episodes', 'run an acme EnvironmentLoop with a fake environment and R2D3 agent for a set number of episodes', 'construct an R2D3 agent with a network, target network, demonstration dataset, and replay parameters']
```

Usage

```
{'test_r2d3_agent': 'test the R2D3 agent by running it in a fake discrete environment for multiple episodes', 'build_simple_rnn_network': 'build a SimpleNetwork RNNCore subclass with LSTM and MLP layers for action prediction', 'create_demonstration_recorder': 'create a DemonstrationRecorder to record environment timesteps and actions as demonstration episodes', 'run_environment_loop': 'run an acme EnvironmentLoop with a fake environment and R2D3 agent for a set number of episodes', 'construct_r2d3_agent': 'construct an R2D3 agent with a network, target network, demonstration dataset, and replay parameters'}
```

