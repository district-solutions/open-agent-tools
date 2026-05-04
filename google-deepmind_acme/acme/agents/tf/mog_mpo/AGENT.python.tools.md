# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/mog_mpo/agent_distributed.py

Prompts

```
['build a distributed MoG MPO agent topology using DistributedMoGMPO with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the MoG MPO agent', 'create a MoGMPOLearner with online and target networks connected to a Reverb dataset', 'create a FeedForwardActor with stochastic sampling policy and N-step transition adder for data collection', 'create an evaluator with a stochastic mean head policy network for evaluation runs', 'build a MoGMPOLearner instance with policy and critic networks for distributional MPO training', 'create a PolicyEvaluationConfig dataclass to set stochastic policy evaluation and value sample count', 'run a single learning step on the MoGMPOLearner that updates critic and policy networks', 'review the MoGMPOLearner target network update logic that copies online variables periodically', 'summarize the MoGMPOLearner step method that computes critic and policy losses with gradient clipping', 'build a python module that calls make_default_networks with an environment spec to create policy and critic networks', 'create a policy network using LayerNormMLP and MultivariateNormalDiagHead for a reinforcement learning agent', 'create a critic network using CriticMultiplexer and GaussianMixtureHead for value estimation', 'review the make_default_networks function to understand how it constructs policy and critic networks', 'refactor the make_default_networks function to support custom layer sizes or different network heads']
```

Usage

```
{'build_distributed_mog_mpo_agent': 'build a distributed MoG MPO agent topology using DistributedMoGMPO with environment and network factories', 'create_replay_storage': 'create a Reverb replay table with uniform sampling and FIFO removal for the MoG MPO agent', 'create_learner_component': 'create a MoGMPOLearner with online and target networks connected to a Reverb dataset', 'create_actor_component': 'create a FeedForwardActor with stochastic sampling policy and N-step transition adder for data collection', 'create_evaluator_component': 'create an evaluator with a stochastic mean head policy network for evaluation runs'}
```

## File: google-deepmind_acme/acme/agents/tf/mog_mpo/learning.py

Prompts

```
['build a distributed MoG MPO agent topology using DistributedMoGMPO with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the MoG MPO agent', 'create a MoGMPOLearner with online and target networks connected to a Reverb dataset', 'create a FeedForwardActor with stochastic sampling policy and N-step transition adder for data collection', 'create an evaluator with a stochastic mean head policy network for evaluation runs', 'build a MoGMPOLearner instance with policy and critic networks for distributional MPO training', 'create a PolicyEvaluationConfig dataclass to set stochastic policy evaluation and value sample count', 'run a single learning step on the MoGMPOLearner that updates critic and policy networks', 'review the MoGMPOLearner target network update logic that copies online variables periodically', 'summarize the MoGMPOLearner step method that computes critic and policy losses with gradient clipping', 'build a python module that calls make_default_networks with an environment spec to create policy and critic networks', 'create a policy network using LayerNormMLP and MultivariateNormalDiagHead for a reinforcement learning agent', 'create a critic network using CriticMultiplexer and GaussianMixtureHead for value estimation', 'review the make_default_networks function to understand how it constructs policy and critic networks', 'refactor the make_default_networks function to support custom layer sizes or different network heads']
```

Usage

```
{'build_mogmpo_learner': 'build a MoGMPOLearner instance with policy and critic networks for distributional MPO training', 'create_policy_evaluation_config': 'create a PolicyEvaluationConfig dataclass to set stochastic policy evaluation and value sample count', 'run_learner_step': 'run a single learning step on the MoGMPOLearner that updates critic and policy networks', 'review_target_network_update': 'review the MoGMPOLearner target network update logic that copies online variables periodically', 'summarize_mogmpo_step': 'summarize the MoGMPOLearner step method that computes critic and policy losses with gradient clipping'}
```

## File: google-deepmind_acme/acme/agents/tf/mog_mpo/networks.py

Prompts

```
['build a distributed MoG MPO agent topology using DistributedMoGMPO with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the MoG MPO agent', 'create a MoGMPOLearner with online and target networks connected to a Reverb dataset', 'create a FeedForwardActor with stochastic sampling policy and N-step transition adder for data collection', 'create an evaluator with a stochastic mean head policy network for evaluation runs', 'build a MoGMPOLearner instance with policy and critic networks for distributional MPO training', 'create a PolicyEvaluationConfig dataclass to set stochastic policy evaluation and value sample count', 'run a single learning step on the MoGMPOLearner that updates critic and policy networks', 'review the MoGMPOLearner target network update logic that copies online variables periodically', 'summarize the MoGMPOLearner step method that computes critic and policy losses with gradient clipping', 'build a python module that calls make_default_networks with an environment spec to create policy and critic networks', 'create a policy network using LayerNormMLP and MultivariateNormalDiagHead for a reinforcement learning agent', 'create a critic network using CriticMultiplexer and GaussianMixtureHead for value estimation', 'review the make_default_networks function to understand how it constructs policy and critic networks', 'refactor the make_default_networks function to support custom layer sizes or different network heads']
```

Usage

```
{'build_mog_mpo_networks': 'build a python module that calls make_default_networks with an environment spec to create policy and critic networks', 'create_policy_network': 'create a policy network using LayerNormMLP and MultivariateNormalDiagHead for a reinforcement learning agent', 'create_critic_network': 'create a critic network using CriticMultiplexer and GaussianMixtureHead for value estimation', 'review_make_default_networks': 'review the make_default_networks function to understand how it constructs policy and critic networks', 'refactor_network_architecture': 'refactor the make_default_networks function to support custom layer sizes or different network heads'}
```

