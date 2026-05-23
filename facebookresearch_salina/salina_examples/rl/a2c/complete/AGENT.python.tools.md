# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/a2c/complete/a2c.py

Prompts

```
['run the A2C reinforcement learning training loop with multi-process environment agents and GAE advantage estimation', 'create an NRemoteAgent with multiple worker processes for parallel environment data acquisition in Salina', 'wrap an A2C agent with TemporalAgent to compute action probabilities and critic values over timesteps', 'compute Generalized Advantage Estimation using salina rl functional with critic values, rewards, and done masks', 'run the Hydra-configured main entry point that instantiates the A2C agent and starts multi-process training', 'build an A2C agent with MLP policy and critic networks for a given gym environment', 'create a recurrent A2C agent pipeline with shared GRU for policy and critic', 'create a recurrent A2C agent pipeline with separate GRUs for policy and critic', 'build an A2C agent with a dueling CNN for Atari environment reinforcement learning', 'test the masked_tensor function to combine two tensors using a boolean mask']
```

Usage

```
{'run_a2c_training': 'run the A2C reinforcement learning training loop with multi-process environment agents and GAE advantage estimation', 'run_NRemoteAgent_create': 'create an NRemoteAgent with multiple worker processes for parallel environment data acquisition in Salina', 'run_TemporalAgent': 'wrap an A2C agent with TemporalAgent to compute action probabilities and critic values over timesteps', 'run_RLF_gae': 'compute Generalized Advantage Estimation using salina rl functional with critic values, rewards, and done masks', 'run_main_entry': 'run the Hydra-configured main entry point that instantiates the A2C agent and starts multi-process training'}
```

## File: facebookresearch_salina/salina_examples/rl/a2c/complete/agents.py

Prompts

```
['run the A2C reinforcement learning training loop with multi-process environment agents and GAE advantage estimation', 'create an NRemoteAgent with multiple worker processes for parallel environment data acquisition in Salina', 'wrap an A2C agent with TemporalAgent to compute action probabilities and critic values over timesteps', 'compute Generalized Advantage Estimation using salina rl functional with critic values, rewards, and done masks', 'run the Hydra-configured main entry point that instantiates the A2C agent and starts multi-process training', 'build an A2C agent with MLP policy and critic networks for a given gym environment', 'create a recurrent A2C agent pipeline with shared GRU for policy and critic', 'create a recurrent A2C agent pipeline with separate GRUs for policy and critic', 'build an A2C agent with a dueling CNN for Atari environment reinforcement learning', 'test the masked_tensor function to combine two tensors using a boolean mask']
```

Usage

```
{'build_A2CMLPAgent': 'build an A2C agent with MLP policy and critic networks for a given gym environment', 'create_a2c_recurrent': 'create a recurrent A2C agent pipeline with shared GRU for policy and critic', 'create_a2c_recurrent_sep': 'create a recurrent A2C agent pipeline with separate GRUs for policy and critic', 'build_A2CAtariAgent': 'build an A2C agent with a dueling CNN for Atari environment reinforcement learning', 'test_masked_tensor': 'test the masked_tensor function to combine two tensors using a boolean mask'}
```

