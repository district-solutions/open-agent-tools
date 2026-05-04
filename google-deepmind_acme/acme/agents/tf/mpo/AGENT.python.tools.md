# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/mpo/agent_distributed.py

Prompts

```
['build a DistributedMPO program topology with actors, learner, evaluator, and replay storage using Launchpad', 'create a Reverb replay table with uniform sampling and FIFO removal for MPO training', 'create an MPOLearner with online and target policy and critic networks for distributed training', 'create a FeedForwardActor with stochastic sampling policy that adds transitions to replay storage', 'create an evaluator with stochastic mean head policy for evaluating the trained MPO agent', 'create policy, critic, observation, and evaluator networks for the MPO agent using make_networks', 'run the distributed MPO agent integration test with a fake continuous environment and two actors', 'launch the distributed program and step the learner five times using launchpad test mode', 'review the make_networks function that builds LayerNormMLP policy and critic networks with Sonnet', 'refactor the DistributedAgentTest to use a different environment factory or adjust replay buffer sizes', 'test the MPO agent by running it in a fake continuous environment for two episodes', 'create policy and critic networks using LayerNormMLP and MultivariateNormalDiagHead for the MPO agent', 'run an acme EnvironmentLoop with the MPO agent and a fake continuous environment', 'construct an MPO agent with policy network, critic network, batch size, and replay settings', 'make an environment spec from a fake continuous environment using acme specs module', 'build an MPO learner with policy and critic networks for reinforcement learning training', 'run a single learning step of the MPO learner to update policy and critic networks', 'create a checkpoint of the MPO learner state including policy, critic, and optimizer variables', 'get the numpy arrays of critic or policy variables from the MPO learner', 'review the MPO learner target network update logic that periodically syncs online to target networks']
```

Usage

```
{'build_distributed_mpo_program': 'build a DistributedMPO program topology with actors, learner, evaluator, and replay storage using Launchpad', 'create_mpo_replay_table': 'create a Reverb replay table with uniform sampling and FIFO removal for MPO training', 'create_mpo_learner': 'create an MPOLearner with online and target policy and critic networks for distributed training', 'create_mpo_actor': 'create a FeedForwardActor with stochastic sampling policy that adds transitions to replay storage', 'create_mpo_evaluator': 'create an evaluator with stochastic mean head policy for evaluating the trained MPO agent'}
```

## File: google-deepmind_acme/acme/agents/tf/mpo/agent_distributed_test.py

Prompts

```
['build a DistributedMPO program topology with actors, learner, evaluator, and replay storage using Launchpad', 'create a Reverb replay table with uniform sampling and FIFO removal for MPO training', 'create an MPOLearner with online and target policy and critic networks for distributed training', 'create a FeedForwardActor with stochastic sampling policy that adds transitions to replay storage', 'create an evaluator with stochastic mean head policy for evaluating the trained MPO agent', 'create policy, critic, observation, and evaluator networks for the MPO agent using make_networks', 'run the distributed MPO agent integration test with a fake continuous environment and two actors', 'launch the distributed program and step the learner five times using launchpad test mode', 'review the make_networks function that builds LayerNormMLP policy and critic networks with Sonnet', 'refactor the DistributedAgentTest to use a different environment factory or adjust replay buffer sizes', 'test the MPO agent by running it in a fake continuous environment for two episodes', 'create policy and critic networks using LayerNormMLP and MultivariateNormalDiagHead for the MPO agent', 'run an acme EnvironmentLoop with the MPO agent and a fake continuous environment', 'construct an MPO agent with policy network, critic network, batch size, and replay settings', 'make an environment spec from a fake continuous environment using acme specs module', 'build an MPO learner with policy and critic networks for reinforcement learning training', 'run a single learning step of the MPO learner to update policy and critic networks', 'create a checkpoint of the MPO learner state including policy, critic, and optimizer variables', 'get the numpy arrays of critic or policy variables from the MPO learner', 'review the MPO learner target network update logic that periodically syncs online to target networks']
```

Usage

```
{'build_mpo_networks': 'create policy, critic, observation, and evaluator networks for the MPO agent using make_networks', 'test_distributed_mpo_agent': 'run the distributed MPO agent integration test with a fake continuous environment and two actors', 'run_learner_steps': 'launch the distributed program and step the learner five times using launchpad test mode', 'review_make_networks_function': 'review the make_networks function that builds LayerNormMLP policy and critic networks with Sonnet', 'refactor_distributed_agent_test': 'refactor the DistributedAgentTest to use a different environment factory or adjust replay buffer sizes'}
```

## File: google-deepmind_acme/acme/agents/tf/mpo/agent_test.py

Prompts

```
['build a DistributedMPO program topology with actors, learner, evaluator, and replay storage using Launchpad', 'create a Reverb replay table with uniform sampling and FIFO removal for MPO training', 'create an MPOLearner with online and target policy and critic networks for distributed training', 'create a FeedForwardActor with stochastic sampling policy that adds transitions to replay storage', 'create an evaluator with stochastic mean head policy for evaluating the trained MPO agent', 'create policy, critic, observation, and evaluator networks for the MPO agent using make_networks', 'run the distributed MPO agent integration test with a fake continuous environment and two actors', 'launch the distributed program and step the learner five times using launchpad test mode', 'review the make_networks function that builds LayerNormMLP policy and critic networks with Sonnet', 'refactor the DistributedAgentTest to use a different environment factory or adjust replay buffer sizes', 'test the MPO agent by running it in a fake continuous environment for two episodes', 'create policy and critic networks using LayerNormMLP and MultivariateNormalDiagHead for the MPO agent', 'run an acme EnvironmentLoop with the MPO agent and a fake continuous environment', 'construct an MPO agent with policy network, critic network, batch size, and replay settings', 'make an environment spec from a fake continuous environment using acme specs module', 'build an MPO learner with policy and critic networks for reinforcement learning training', 'run a single learning step of the MPO learner to update policy and critic networks', 'create a checkpoint of the MPO learner state including policy, critic, and optimizer variables', 'get the numpy arrays of critic or policy variables from the MPO learner', 'review the MPO learner target network update logic that periodically syncs online to target networks']
```

Usage

```
{'test_mpo_agent': 'test the MPO agent by running it in a fake continuous environment for two episodes', 'create_policy_and_critic_networks': 'create policy and critic networks using LayerNormMLP and MultivariateNormalDiagHead for the MPO agent', 'run_environment_loop': 'run an acme EnvironmentLoop with the MPO agent and a fake continuous environment', 'construct_mpo_agent': 'construct an MPO agent with policy network, critic network, batch size, and replay settings', 'make_environment_spec': 'make an environment spec from a fake continuous environment using acme specs module'}
```

## File: google-deepmind_acme/acme/agents/tf/mpo/learning.py

Prompts

```
['build a DistributedMPO program topology with actors, learner, evaluator, and replay storage using Launchpad', 'create a Reverb replay table with uniform sampling and FIFO removal for MPO training', 'create an MPOLearner with online and target policy and critic networks for distributed training', 'create a FeedForwardActor with stochastic sampling policy that adds transitions to replay storage', 'create an evaluator with stochastic mean head policy for evaluating the trained MPO agent', 'create policy, critic, observation, and evaluator networks for the MPO agent using make_networks', 'run the distributed MPO agent integration test with a fake continuous environment and two actors', 'launch the distributed program and step the learner five times using launchpad test mode', 'review the make_networks function that builds LayerNormMLP policy and critic networks with Sonnet', 'refactor the DistributedAgentTest to use a different environment factory or adjust replay buffer sizes', 'test the MPO agent by running it in a fake continuous environment for two episodes', 'create policy and critic networks using LayerNormMLP and MultivariateNormalDiagHead for the MPO agent', 'run an acme EnvironmentLoop with the MPO agent and a fake continuous environment', 'construct an MPO agent with policy network, critic network, batch size, and replay settings', 'make an environment spec from a fake continuous environment using acme specs module', 'build an MPO learner with policy and critic networks for reinforcement learning training', 'run a single learning step of the MPO learner to update policy and critic networks', 'create a checkpoint of the MPO learner state including policy, critic, and optimizer variables', 'get the numpy arrays of critic or policy variables from the MPO learner', 'review the MPO learner target network update logic that periodically syncs online to target networks']
```

Usage

```
{'build_mpo_learner': 'build an MPO learner with policy and critic networks for reinforcement learning training', 'run_mpo_learner_step': 'run a single learning step of the MPO learner to update policy and critic networks', 'create_mpo_learner_checkpoint': 'create a checkpoint of the MPO learner state including policy, critic, and optimizer variables', 'get_mpo_learner_variables': 'get the numpy arrays of critic or policy variables from the MPO learner', 'review_mpo_target_network_update': 'review the MPO learner target network update logic that periodically syncs online to target networks'}
```

