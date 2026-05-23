# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/neural_networks/sequential_decision_making/actor_networks.py

Prompts

```
['build a VanillaActorNetwork for discrete action spaces that outputs softmax probability distributions over actions', 'build a GaussianActorNetwork that parameterizes continuous actions as a multivariate Gaussian with mean and std outputs', 'build a CNNActorNetwork that processes image inputs through conv layers then outputs discrete action probabilities', 'build a DynamicActionActorNetwork for dynamic action spaces where available actions change per state', 'test the action_scaling function to map normalized actions from [-1,1] to the BoxActionSpace bounds', 'create a VanillaQValueNetwork MLP that estimates Q-values from concatenated state and action tensors', 'create a DuelingQValueNetwork that separates state value and action advantage streams for Q-value estimation', 'create a TwoTowerQValueNetwork with independent state and action feature towers merged before Q-value output', 'create a QuantileQValueNetwork that outputs quantile locations approximating the distribution of Q-values', 'create a CNNQValueNetwork that processes image states through conv layers then concatenates actions for Q-value output', 'build a TwinCritic instance by providing state_dim, action_dim, and hidden_dims to create two Q-value networks', 'build a TwinCritic by passing two pre-constructed QValueNetwork instances as network_instance_1 and network_instance_2', 'get Q-values from both critic networks by calling get_q_values with a state_batch and action_batch tensor', 'review the TwinCritic __init__ to understand how it initializes two critics and applies an init_fn via ModuleList', 'refactor the TwinCritic to accept a custom network_type subclass of QValueNetwork instead of VanillaQValueNetwork']
```

Usage

```
{'build_vanilla_actor_network': 'build a VanillaActorNetwork for discrete action spaces that outputs softmax probability distributions over actions', 'build_gaussian_actor_network': 'build a GaussianActorNetwork that parameterizes continuous actions as a multivariate Gaussian with mean and std outputs', 'build_cnn_actor_network': 'build a CNNActorNetwork that processes image inputs through conv layers then outputs discrete action probabilities', 'build_dynamic_action_actor_network': 'build a DynamicActionActorNetwork for dynamic action spaces where available actions change per state', 'test_action_scaling': 'test the action_scaling function to map normalized actions from [-1,1] to the BoxActionSpace bounds'}
```

## File: facebookresearch_pearl/pearl/neural_networks/sequential_decision_making/q_value_networks.py

Prompts

```
['build a VanillaActorNetwork for discrete action spaces that outputs softmax probability distributions over actions', 'build a GaussianActorNetwork that parameterizes continuous actions as a multivariate Gaussian with mean and std outputs', 'build a CNNActorNetwork that processes image inputs through conv layers then outputs discrete action probabilities', 'build a DynamicActionActorNetwork for dynamic action spaces where available actions change per state', 'test the action_scaling function to map normalized actions from [-1,1] to the BoxActionSpace bounds', 'create a VanillaQValueNetwork MLP that estimates Q-values from concatenated state and action tensors', 'create a DuelingQValueNetwork that separates state value and action advantage streams for Q-value estimation', 'create a TwoTowerQValueNetwork with independent state and action feature towers merged before Q-value output', 'create a QuantileQValueNetwork that outputs quantile locations approximating the distribution of Q-values', 'create a CNNQValueNetwork that processes image states through conv layers then concatenates actions for Q-value output', 'build a TwinCritic instance by providing state_dim, action_dim, and hidden_dims to create two Q-value networks', 'build a TwinCritic by passing two pre-constructed QValueNetwork instances as network_instance_1 and network_instance_2', 'get Q-values from both critic networks by calling get_q_values with a state_batch and action_batch tensor', 'review the TwinCritic __init__ to understand how it initializes two critics and applies an init_fn via ModuleList', 'refactor the TwinCritic to accept a custom network_type subclass of QValueNetwork instead of VanillaQValueNetwork']
```

Usage

```
{'create_VanillaQValueNetwork': 'create a VanillaQValueNetwork MLP that estimates Q-values from concatenated state and action tensors', 'create_DuelingQValueNetwork': 'create a DuelingQValueNetwork that separates state value and action advantage streams for Q-value estimation', 'create_TwoTowerQValueNetwork': 'create a TwoTowerQValueNetwork with independent state and action feature towers merged before Q-value output', 'create_QuantileQValueNetwork': 'create a QuantileQValueNetwork that outputs quantile locations approximating the distribution of Q-values', 'create_CNNQValueNetwork': 'create a CNNQValueNetwork that processes image states through conv layers then concatenates actions for Q-value output'}
```

## File: facebookresearch_pearl/pearl/neural_networks/sequential_decision_making/twin_critic.py

Prompts

```
['build a VanillaActorNetwork for discrete action spaces that outputs softmax probability distributions over actions', 'build a GaussianActorNetwork that parameterizes continuous actions as a multivariate Gaussian with mean and std outputs', 'build a CNNActorNetwork that processes image inputs through conv layers then outputs discrete action probabilities', 'build a DynamicActionActorNetwork for dynamic action spaces where available actions change per state', 'test the action_scaling function to map normalized actions from [-1,1] to the BoxActionSpace bounds', 'create a VanillaQValueNetwork MLP that estimates Q-values from concatenated state and action tensors', 'create a DuelingQValueNetwork that separates state value and action advantage streams for Q-value estimation', 'create a TwoTowerQValueNetwork with independent state and action feature towers merged before Q-value output', 'create a QuantileQValueNetwork that outputs quantile locations approximating the distribution of Q-values', 'create a CNNQValueNetwork that processes image states through conv layers then concatenates actions for Q-value output', 'build a TwinCritic instance by providing state_dim, action_dim, and hidden_dims to create two Q-value networks', 'build a TwinCritic by passing two pre-constructed QValueNetwork instances as network_instance_1 and network_instance_2', 'get Q-values from both critic networks by calling get_q_values with a state_batch and action_batch tensor', 'review the TwinCritic __init__ to understand how it initializes two critics and applies an init_fn via ModuleList', 'refactor the TwinCritic to accept a custom network_type subclass of QValueNetwork instead of VanillaQValueNetwork']
```

Usage

```
{'build_twin_critic_with_dims': 'build a TwinCritic instance by providing state_dim, action_dim, and hidden_dims to create two Q-value networks', 'build_twin_critic_with_instances': 'build a TwinCritic by passing two pre-constructed QValueNetwork instances as network_instance_1 and network_instance_2', 'get_q_values_from_twin_critic': 'get Q-values from both critic networks by calling get_q_values with a state_batch and action_batch tensor', 'review_twin_critic_init': 'review the TwinCritic __init__ to understand how it initializes two critics and applies an init_fn via ModuleList', 'refactor_twin_critic_network_type': 'refactor the TwinCritic to accept a custom network_type subclass of QValueNetwork instead of VanillaQValueNetwork'}
```

