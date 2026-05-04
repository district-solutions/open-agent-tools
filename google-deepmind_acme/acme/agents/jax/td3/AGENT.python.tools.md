# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/td3/builder.py

Prompts

```
['build a TD3 learner with Adam optimizers and optional gradient clipping for policy updates', 'build a TD3 actor with a feed-forward policy and CPU-based variable client', 'build Reverb replay tables with uniform sampling and FIFO removal for TD3 training', 'build a dataset iterator from a Reverb client for TD3 learning with configurable batch size', 'build a TD3 behavior policy with configurable exploration noise sigma for training or evaluation', 'create a TrainingState namedtuple holding policy, critic, and optimizer parameters for TD3 training', 'run the policy loss computation using DPG loss with optional behavior cloning regularization', 'run the critic loss computation using TD error with twin critic minimum for target Q values', 'run a single update step that updates critics every step and policy every delay steps with Polyak averaging', 'build a TD3 actor and twin critic networks from an environment spec using make_networks', 'create a noisy behavior policy from TD3 networks using get_default_behavior_policy with a sigma parameter', 'review the TD3Networks dataclass containing policy_network, critic_network, twin_critic_network, and add_policy_noise fields', 'refactor make_networks to customize hidden_layer_sizes for the LayerNormMLP actor and critic networks', 'summarize the add_policy_noise function that clips Gaussian noise and adds it to target policy actions']
```

Usage

```
{'build_td3_learner': 'build a TD3 learner with Adam optimizers and optional gradient clipping for policy updates', 'build_td3_actor': 'build a TD3 actor with a feed-forward policy and CPU-based variable client', 'build_replay_tables': 'build Reverb replay tables with uniform sampling and FIFO removal for TD3 training', 'build_dataset_iterator': 'build a dataset iterator from a Reverb client for TD3 learning with configurable batch size', 'build_td3_policy': 'build a TD3 behavior policy with configurable exploration noise sigma for training or evaluation'}
```

## File: google-deepmind_acme/acme/agents/jax/td3/learning.py

Prompts

```
['build a TD3 learner with Adam optimizers and optional gradient clipping for policy updates', 'build a TD3 actor with a feed-forward policy and CPU-based variable client', 'build Reverb replay tables with uniform sampling and FIFO removal for TD3 training', 'build a dataset iterator from a Reverb client for TD3 learning with configurable batch size', 'build a TD3 behavior policy with configurable exploration noise sigma for training or evaluation', 'create a TrainingState namedtuple holding policy, critic, and optimizer parameters for TD3 training', 'run the policy loss computation using DPG loss with optional behavior cloning regularization', 'run the critic loss computation using TD error with twin critic minimum for target Q values', 'run a single update step that updates critics every step and policy every delay steps with Polyak averaging', 'build a TD3 actor and twin critic networks from an environment spec using make_networks', 'create a noisy behavior policy from TD3 networks using get_default_behavior_policy with a sigma parameter', 'review the TD3Networks dataclass containing policy_network, critic_network, twin_critic_network, and add_policy_noise fields', 'refactor make_networks to customize hidden_layer_sizes for the LayerNormMLP actor and critic networks', 'summarize the add_policy_noise function that clips Gaussian noise and adds it to target policy actions']
```

Usage

```
{'build_td3_learner': 'build a TD3Learner with policy and twin critic networks for continuous control reinforcement learning', 'create_training_state': 'create a TrainingState namedtuple holding policy, critic, and optimizer parameters for TD3 training', 'run_policy_loss': 'run the policy loss computation using DPG loss with optional behavior cloning regularization', 'run_critic_loss': 'run the critic loss computation using TD error with twin critic minimum for target Q values', 'run_update_step': 'run a single update step that updates critics every step and policy every delay steps with Polyak averaging'}
```

## File: google-deepmind_acme/acme/agents/jax/td3/networks.py

Prompts

```
['build a TD3 learner with Adam optimizers and optional gradient clipping for policy updates', 'build a TD3 actor with a feed-forward policy and CPU-based variable client', 'build Reverb replay tables with uniform sampling and FIFO removal for TD3 training', 'build a dataset iterator from a Reverb client for TD3 learning with configurable batch size', 'build a TD3 behavior policy with configurable exploration noise sigma for training or evaluation', 'create a TrainingState namedtuple holding policy, critic, and optimizer parameters for TD3 training', 'run the policy loss computation using DPG loss with optional behavior cloning regularization', 'run the critic loss computation using TD error with twin critic minimum for target Q values', 'run a single update step that updates critics every step and policy every delay steps with Polyak averaging', 'build a TD3 actor and twin critic networks from an environment spec using make_networks', 'create a noisy behavior policy from TD3 networks using get_default_behavior_policy with a sigma parameter', 'review the TD3Networks dataclass containing policy_network, critic_network, twin_critic_network, and add_policy_noise fields', 'refactor make_networks to customize hidden_layer_sizes for the LayerNormMLP actor and critic networks', 'summarize the add_policy_noise function that clips Gaussian noise and adds it to target policy actions']
```

Usage

```
{'build_td3_networks': 'build a TD3 actor and twin critic networks from an environment spec using make_networks', 'create_behavior_policy': 'create a noisy behavior policy from TD3 networks using get_default_behavior_policy with a sigma parameter', 'review_td3networks_dataclass': 'review the TD3Networks dataclass containing policy_network, critic_network, twin_critic_network, and add_policy_noise fields', 'refactor_make_networks': 'refactor make_networks to customize hidden_layer_sizes for the LayerNormMLP actor and critic networks', 'summarize_add_policy_noise': 'summarize the add_policy_noise function that clips Gaussian noise and adds it to target policy actions'}
```

