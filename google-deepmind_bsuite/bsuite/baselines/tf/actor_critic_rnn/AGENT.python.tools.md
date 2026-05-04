# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/tf/actor_critic_rnn/agent.py

Prompts

```
['build a recurrent actor-critic RL agent using ActorCriticRNN with a custom PolicyValueRNN network and Adam optimizer', 'create a PolicyValueRNN network with MLP torso, LSTM core, policy head, and value head for reinforcement learning', 'run the default_agent factory function to initialize an ActorCriticRNN agent with default hyperparameters like discount 0.99 and td_lambda 0.9', 'test the select_action method of ActorCriticRNN to sample actions from the softmax policy given a dm_env timestep', 'review the update method of ActorCriticRNN that appends transitions to a buffer and performs TD-lambda SGD updates', 'run an actor-critic RNN agent on a bsuite environment and log results to CSV', 'run a single bsuite experiment by passing a bsuite_id flag to the run function', 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'configure an ActorCriticRNN agent with Adam optimizer, discount, and TD lambda parameters', 'test the actor_critic_rnn agent by running it for 5 episodes across bsuite environments', 'run an experiment using the default agent with a bsuite environment for a set number of episodes', 'load a bsuite environment from its ID string using bsuite.load_from_id', 'create a default actor_critic_rnn agent using observation and action specs from the environment', 'review the RunTest class that parameterizes agent training tests across bsuite sweep environments']
```

Usage

```
{'build_recurrent_actor_critic_agent': 'build a recurrent actor-critic RL agent using ActorCriticRNN with a custom PolicyValueRNN network and Adam optimizer', 'create_policy_value_rnn_network': 'create a PolicyValueRNN network with MLP torso, LSTM core, policy head, and value head for reinforcement learning', 'run_default_agent_factory': 'run the default_agent factory function to initialize an ActorCriticRNN agent with default hyperparameters like discount 0.99 and td_lambda 0.9', 'test_select_action_method': 'test the select_action method of ActorCriticRNN to sample actions from the softmax policy given a dm_env timestep', 'review_update_method': 'review the update method of ActorCriticRNN that appends transitions to a buffer and performs TD-lambda SGD updates'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/actor_critic_rnn/run.py

Prompts

```
['build a recurrent actor-critic RL agent using ActorCriticRNN with a custom PolicyValueRNN network and Adam optimizer', 'create a PolicyValueRNN network with MLP torso, LSTM core, policy head, and value head for reinforcement learning', 'run the default_agent factory function to initialize an ActorCriticRNN agent with default hyperparameters like discount 0.99 and td_lambda 0.9', 'test the select_action method of ActorCriticRNN to sample actions from the softmax policy given a dm_env timestep', 'review the update method of ActorCriticRNN that appends transitions to a buffer and performs TD-lambda SGD updates', 'run an actor-critic RNN agent on a bsuite environment and log results to CSV', 'run a single bsuite experiment by passing a bsuite_id flag to the run function', 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'configure an ActorCriticRNN agent with Adam optimizer, discount, and TD lambda parameters', 'test the actor_critic_rnn agent by running it for 5 episodes across bsuite environments', 'run an experiment using the default agent with a bsuite environment for a set number of episodes', 'load a bsuite environment from its ID string using bsuite.load_from_id', 'create a default actor_critic_rnn agent using observation and action specs from the environment', 'review the RunTest class that parameterizes agent training tests across bsuite sweep environments']
```

Usage

```
{'run_actor_critic_on_bsuite_env': 'run an actor-critic RNN agent on a bsuite environment and log results to CSV', 'run_single_experiment': 'run a single bsuite experiment by passing a bsuite_id flag to the run function', 'run_sweep_multiprocess': 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'create_policy_value_rnn_network': 'create a PolicyValueRNN network with configurable hidden layers and action space size', 'configure_actor_critic_rnn_agent': 'configure an ActorCriticRNN agent with Adam optimizer, discount, and TD lambda parameters'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/actor_critic_rnn/run_test.py

Prompts

```
['build a recurrent actor-critic RL agent using ActorCriticRNN with a custom PolicyValueRNN network and Adam optimizer', 'create a PolicyValueRNN network with MLP torso, LSTM core, policy head, and value head for reinforcement learning', 'run the default_agent factory function to initialize an ActorCriticRNN agent with default hyperparameters like discount 0.99 and td_lambda 0.9', 'test the select_action method of ActorCriticRNN to sample actions from the softmax policy given a dm_env timestep', 'review the update method of ActorCriticRNN that appends transitions to a buffer and performs TD-lambda SGD updates', 'run an actor-critic RNN agent on a bsuite environment and log results to CSV', 'run a single bsuite experiment by passing a bsuite_id flag to the run function', 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'configure an ActorCriticRNN agent with Adam optimizer, discount, and TD lambda parameters', 'test the actor_critic_rnn agent by running it for 5 episodes across bsuite environments', 'run an experiment using the default agent with a bsuite environment for a set number of episodes', 'load a bsuite environment from its ID string using bsuite.load_from_id', 'create a default actor_critic_rnn agent using observation and action specs from the environment', 'review the RunTest class that parameterizes agent training tests across bsuite sweep environments']
```

Usage

```
{'test_run_actor_critic_rnn': 'test the actor_critic_rnn agent by running it for 5 episodes across bsuite environments', 'run_experiment_with_agent': 'run an experiment using the default agent with a bsuite environment for a set number of episodes', 'load_bsuite_environment': 'load a bsuite environment from its ID string using bsuite.load_from_id', 'create_default_agent': 'create a default actor_critic_rnn agent using observation and action specs from the environment', 'review_RunTest_class': 'review the RunTest class that parameterizes agent training tests across bsuite sweep environments'}
```

