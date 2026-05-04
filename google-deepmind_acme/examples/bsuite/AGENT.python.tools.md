# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/examples/bsuite/run_impala.py

Prompts

```
['run IMPALA agent on a bsuite environment like deep_sea and record results to CSV', 'create a DeepRNN network with MLP, LSTM, and PolicyValueHead for a given action spec', 'build an IMPALA agent with a network, environment spec, and sequence length parameters', 'run an acme EnvironmentLoop with an agent for a specified number of episodes', 'load a bsuite environment by ID and record results to a CSV directory', 'run MCTS agent on a BSuite environment like deep_sea using acme EnvironmentLoop', 'create a BSuite environment and simulator or MLP model using make_env_and_model', 'build a Sonnet MLP network with PolicyValueHead for discrete action spaces', 'construct an MCTS agent with a model, network, and Adam optimizer']
```

Usage

```
{'run_impala_on_bsuite': 'run IMPALA agent on a bsuite environment like deep_sea and record results to CSV', 'create_make_network': 'create a DeepRNN network with MLP, LSTM, and PolicyValueHead for a given action spec', 'build_impala_agent': 'build an IMPALA agent with a network, environment spec, and sequence length parameters', 'run_environment_loop': 'run an acme EnvironmentLoop with an agent for a specified number of episodes', 'load_bsuite_environment': 'load a bsuite environment by ID and record results to a CSV directory'}
```

## File: google-deepmind_acme/examples/bsuite/run_mcts.py

Prompts

```
['run IMPALA agent on a bsuite environment like deep_sea and record results to CSV', 'create a DeepRNN network with MLP, LSTM, and PolicyValueHead for a given action spec', 'build an IMPALA agent with a network, environment spec, and sequence length parameters', 'run an acme EnvironmentLoop with an agent for a specified number of episodes', 'load a bsuite environment by ID and record results to a CSV directory', 'run MCTS agent on a BSuite environment like deep_sea using acme EnvironmentLoop', 'create a BSuite environment and simulator or MLP model using make_env_and_model', 'build a Sonnet MLP network with PolicyValueHead for discrete action spaces', 'construct an MCTS agent with a model, network, and Adam optimizer']
```

Usage

```
{'run_mcts_on_bsuite': 'run MCTS agent on a BSuite environment like deep_sea using acme EnvironmentLoop', 'create_env_and_model': 'create a BSuite environment and simulator or MLP model using make_env_and_model', 'build_network_policy_value': 'build a Sonnet MLP network with PolicyValueHead for discrete action spaces', 'construct_mcts_agent': 'construct an MCTS agent with a model, network, and Adam optimizer', 'run_environment_loop': 'run an acme EnvironmentLoop for a specified number of episodes with an MCTS agent'}
```

