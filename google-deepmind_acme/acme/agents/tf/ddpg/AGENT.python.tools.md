# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/ddpg/agent_distributed.py

Prompts

```
['build a distributed DDPG agent topology with actors, learner, evaluator, and replay using the build method', 'create a Reverb replay table with uniform sampling and FIFO removal for experience storage', 'create a DDPG learner with online and target policy and critic networks for training', 'create a DDPG actor with clipped Gaussian exploration that adds transitions to replay', 'create a DDPG evaluator actor without replay adder for periodic policy evaluation', 'create a DDPG policy and critic network using sonnet sequential layers and action specs', 'run an integration test for the distributed DDPG agent with fake continuous environment', 'build a DistributedDDPG agent with environment factory network factory and replay buffer settings', 'launch the distributed program and step the learner node multiple times', 'review the make_networks function that creates policy critic observation and evaluator networks for DDPG', 'run the DDPG agent test with a fake continuous environment and two episodes', 'run an Acme EnvironmentLoop with a continuous environment and DDPG agent', 'review the make_networks function that builds LayerNormMLP policy and critic networks', 'build a DDPG learner with policy and critic networks for reinforcement learning', 'create a target network update mechanism that periodically copies online network weights', 'run the critic loss computation using temporal difference learning with target Q-values', 'test the policy gradient update with DPG loss and gradient clipping', 'review the DDPG learner step method that performs learning updates and logging']
```

Usage

```
{'build_distributed_ddpg_program': 'build a distributed DDPG agent topology with actors, learner, evaluator, and replay using the build method', 'create_ddpg_replay_table': 'create a Reverb replay table with uniform sampling and FIFO removal for experience storage', 'create_ddpg_learner': 'create a DDPG learner with online and target policy and critic networks for training', 'create_ddpg_actor': 'create a DDPG actor with clipped Gaussian exploration that adds transitions to replay', 'create_ddpg_evaluator': 'create a DDPG evaluator actor without replay adder for periodic policy evaluation'}
```

## File: google-deepmind_acme/acme/agents/tf/ddpg/agent_distributed_test.py

Prompts

```
['build a distributed DDPG agent topology with actors, learner, evaluator, and replay using the build method', 'create a Reverb replay table with uniform sampling and FIFO removal for experience storage', 'create a DDPG learner with online and target policy and critic networks for training', 'create a DDPG actor with clipped Gaussian exploration that adds transitions to replay', 'create a DDPG evaluator actor without replay adder for periodic policy evaluation', 'create a DDPG policy and critic network using sonnet sequential layers and action specs', 'run an integration test for the distributed DDPG agent with fake continuous environment', 'build a DistributedDDPG agent with environment factory network factory and replay buffer settings', 'launch the distributed program and step the learner node multiple times', 'review the make_networks function that creates policy critic observation and evaluator networks for DDPG', 'run the DDPG agent test with a fake continuous environment and two episodes', 'run an Acme EnvironmentLoop with a continuous environment and DDPG agent', 'review the make_networks function that builds LayerNormMLP policy and critic networks', 'build a DDPG learner with policy and critic networks for reinforcement learning', 'create a target network update mechanism that periodically copies online network weights', 'run the critic loss computation using temporal difference learning with target Q-values', 'test the policy gradient update with DPG loss and gradient clipping', 'review the DDPG learner step method that performs learning updates and logging']
```

Usage

```
{'build_ddpg_networks': 'create a DDPG policy and critic network using sonnet sequential layers and action specs', 'test_distributed_ddpg_agent': 'run an integration test for the distributed DDPG agent with fake continuous environment', 'create_ddpg_agent': 'build a DistributedDDPG agent with environment factory network factory and replay buffer settings', 'run_learner_steps': 'launch the distributed program and step the learner node multiple times', 'review_network_factory': 'review the make_networks function that creates policy critic observation and evaluator networks for DDPG'}
```

## File: google-deepmind_acme/acme/agents/tf/ddpg/agent_test.py

Prompts

```
['build a distributed DDPG agent topology with actors, learner, evaluator, and replay using the build method', 'create a Reverb replay table with uniform sampling and FIFO removal for experience storage', 'create a DDPG learner with online and target policy and critic networks for training', 'create a DDPG actor with clipped Gaussian exploration that adds transitions to replay', 'create a DDPG evaluator actor without replay adder for periodic policy evaluation', 'create a DDPG policy and critic network using sonnet sequential layers and action specs', 'run an integration test for the distributed DDPG agent with fake continuous environment', 'build a DistributedDDPG agent with environment factory network factory and replay buffer settings', 'launch the distributed program and step the learner node multiple times', 'review the make_networks function that creates policy critic observation and evaluator networks for DDPG', 'run the DDPG agent test with a fake continuous environment and two episodes', 'run an Acme EnvironmentLoop with a continuous environment and DDPG agent', 'review the make_networks function that builds LayerNormMLP policy and critic networks', 'build a DDPG learner with policy and critic networks for reinforcement learning', 'create a target network update mechanism that periodically copies online network weights', 'run the critic loss computation using temporal difference learning with target Q-values', 'test the policy gradient update with DPG loss and gradient clipping', 'review the DDPG learner step method that performs learning updates and logging']
```

Usage

```
{'build_ddpg_networks': 'create policy and critic Sonnet networks for a DDPG agent using make_networks', 'test_ddpg_agent': 'run the DDPG agent test with a fake continuous environment and two episodes', 'create_ddpg_agent': 'construct a DDPG agent with policy network, critic network, and replay settings', 'run_environment_loop': 'run an Acme EnvironmentLoop with a continuous environment and DDPG agent', 'review_make_networks': 'review the make_networks function that builds LayerNormMLP policy and critic networks'}
```

## File: google-deepmind_acme/acme/agents/tf/ddpg/learning.py

Prompts

```
['build a distributed DDPG agent topology with actors, learner, evaluator, and replay using the build method', 'create a Reverb replay table with uniform sampling and FIFO removal for experience storage', 'create a DDPG learner with online and target policy and critic networks for training', 'create a DDPG actor with clipped Gaussian exploration that adds transitions to replay', 'create a DDPG evaluator actor without replay adder for periodic policy evaluation', 'create a DDPG policy and critic network using sonnet sequential layers and action specs', 'run an integration test for the distributed DDPG agent with fake continuous environment', 'build a DistributedDDPG agent with environment factory network factory and replay buffer settings', 'launch the distributed program and step the learner node multiple times', 'review the make_networks function that creates policy critic observation and evaluator networks for DDPG', 'run the DDPG agent test with a fake continuous environment and two episodes', 'run an Acme EnvironmentLoop with a continuous environment and DDPG agent', 'review the make_networks function that builds LayerNormMLP policy and critic networks', 'build a DDPG learner with policy and critic networks for reinforcement learning', 'create a target network update mechanism that periodically copies online network weights', 'run the critic loss computation using temporal difference learning with target Q-values', 'test the policy gradient update with DPG loss and gradient clipping', 'review the DDPG learner step method that performs learning updates and logging']
```

Usage

```
{'build_ddpg_learner': 'build a DDPG learner with policy and critic networks for reinforcement learning', 'create_target_network_update': 'create a target network update mechanism that periodically copies online network weights', 'run_critic_loss_computation': 'run the critic loss computation using temporal difference learning with target Q-values', 'test_policy_gradient_update': 'test the policy gradient update with DPG loss and gradient clipping', 'review_learner_step': 'review the DDPG learner step method that performs learning updates and logging'}
```

