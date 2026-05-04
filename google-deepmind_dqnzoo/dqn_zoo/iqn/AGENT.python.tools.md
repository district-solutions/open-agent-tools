# Agent Python Tools

- repo: google-deepmind/dqnzoo
- repo_uri: https://github.com/google-deepmind/dqn_zoo

## File: google-deepmind_dqnzoo/dqn_zoo/iqn/agent.py

Prompts

```
['create an Implicit Quantile Network agent with epsilon-greedy exploration and replay buffer for reinforcement learning', 'create an IQN epsilon-greedy actor that selects actions from a pre-trained network with given parameters', 'run a single environment step with the IQN agent to select an action and optionally learn from replay', 'serialize the IQN agent state including network parameters, optimizer state, and replay buffer for checkpointing', 'sample uniform tau quantile values between zero and one for IQN Q-value distribution estimation', 'run the IQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'build an IQN Atari network using networks.iqn_atari_network with a given number of actions and tau latent dimension', 'create an IQN training agent with a preprocessor, network, optimizer, replay buffer, and exploration schedule', 'create an IQN epsilon greedy evaluation agent with a network, exploration epsilon, and tau samples', 'run an Atari environment loop using parts.run_loop with a train or eval agent and max frames per episode', 'run the IQN Atari test suite that trains an agent on the Pong environment', 'test the run_atari.main function with minimal training frames and iterations on Pong', 'run the RunAtariTest test case to verify the IQN agent can execute with default Atari flags', 'review the RunAtariTest class and its flag configuration for replay capacity, batch size, and tau sampling', 'refactor the RunAtariTest test_can_run_agent method to adjust tau latent dim and sample policy values']
```

Usage

```
{'create_IQN_agent': 'create an Implicit Quantile Network agent with epsilon-greedy exploration and replay buffer for reinforcement learning', 'create_IqnEpsilonGreedyActor': 'create an IQN epsilon-greedy actor that selects actions from a pre-trained network with given parameters', 'run_IQN_step': 'run a single environment step with the IQN agent to select an action and optionally learn from replay', 'serialize_IQN_state': 'serialize the IQN agent state including network parameters, optimizer state, and replay buffer for checkpointing', 'sample_tau_values': 'sample uniform tau quantile values between zero and one for IQN Q-value distribution estimation'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/iqn/run_atari.py

Prompts

```
['create an Implicit Quantile Network agent with epsilon-greedy exploration and replay buffer for reinforcement learning', 'create an IQN epsilon-greedy actor that selects actions from a pre-trained network with given parameters', 'run a single environment step with the IQN agent to select an action and optionally learn from replay', 'serialize the IQN agent state including network parameters, optimizer state, and replay buffer for checkpointing', 'sample uniform tau quantile values between zero and one for IQN Q-value distribution estimation', 'run the IQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'build an IQN Atari network using networks.iqn_atari_network with a given number of actions and tau latent dimension', 'create an IQN training agent with a preprocessor, network, optimizer, replay buffer, and exploration schedule', 'create an IQN epsilon greedy evaluation agent with a network, exploration epsilon, and tau samples', 'run an Atari environment loop using parts.run_loop with a train or eval agent and max frames per episode', 'run the IQN Atari test suite that trains an agent on the Pong environment', 'test the run_atari.main function with minimal training frames and iterations on Pong', 'run the RunAtariTest test case to verify the IQN agent can execute with default Atari flags', 'review the RunAtariTest class and its flag configuration for replay capacity, batch size, and tau sampling', 'refactor the RunAtariTest test_can_run_agent method to adjust tau latent dim and sample policy values']
```

Usage

```
{'run_iqn_atari_training': 'run the IQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'build_iqn_atari_network': 'build an IQN Atari network using networks.iqn_atari_network with a given number of actions and tau latent dimension', 'create_iqn_agent': 'create an IQN training agent with a preprocessor, network, optimizer, replay buffer, and exploration schedule', 'create_iqn_eval_agent': 'create an IQN epsilon greedy evaluation agent with a network, exploration epsilon, and tau samples', 'run_atari_environment_loop': 'run an Atari environment loop using parts.run_loop with a train or eval agent and max frames per episode'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/iqn/run_atari_test.py

Prompts

```
['create an Implicit Quantile Network agent with epsilon-greedy exploration and replay buffer for reinforcement learning', 'create an IQN epsilon-greedy actor that selects actions from a pre-trained network with given parameters', 'run a single environment step with the IQN agent to select an action and optionally learn from replay', 'serialize the IQN agent state including network parameters, optimizer state, and replay buffer for checkpointing', 'sample uniform tau quantile values between zero and one for IQN Q-value distribution estimation', 'run the IQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'build an IQN Atari network using networks.iqn_atari_network with a given number of actions and tau latent dimension', 'create an IQN training agent with a preprocessor, network, optimizer, replay buffer, and exploration schedule', 'create an IQN epsilon greedy evaluation agent with a network, exploration epsilon, and tau samples', 'run an Atari environment loop using parts.run_loop with a train or eval agent and max frames per episode', 'run the IQN Atari test suite that trains an agent on the Pong environment', 'test the run_atari.main function with minimal training frames and iterations on Pong', 'run the RunAtariTest test case to verify the IQN agent can execute with default Atari flags', 'review the RunAtariTest class and its flag configuration for replay capacity, batch size, and tau sampling', 'refactor the RunAtariTest test_can_run_agent method to adjust tau latent dim and sample policy values']
```

Usage

```
{'test_iqn_agent_on_atari_pong': 'run the IQN Atari test suite that trains an agent on the Pong environment', 'test_run_atari_main': 'test the run_atari.main function with minimal training frames and iterations on Pong', 'run_iqn_atari_test': 'run the RunAtariTest test case to verify the IQN agent can execute with default Atari flags', 'review_run_atari_test_flags': 'review the RunAtariTest class and its flag configuration for replay capacity, batch size, and tau sampling', 'refactor_iqn_test_parameters': 'refactor the RunAtariTest test_can_run_agent method to adjust tau latent dim and sample policy values'}
```

