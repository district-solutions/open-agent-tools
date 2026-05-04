# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/agents/learning/base.py

Prompts

```
['create a callable that builds a PyTorch optimizer from parameters and a learning rate', 'create a subclass of BaseLearning that implements the abstract train_step method', 'add a named optimizer with a learning rate and optional gradient clipping to a BaseLearning instance', 'get all trainable parameters from a BaseLearning module by calling trainable_parameters', 'save and load the combined module and optimizer state dict of a BaseLearning instance', 'create an ObservationLoss instance with a configurable weight for observation reconstruction loss', 'create a RewardLoss instance with a configurable weight for reward prediction loss', 'create a KLLoss with alpha, beta, and free_nats hyperparameters for posterior-prior KL divergence', 'run a VariationalModelLearning train_step on experience replay data with a DenoisedMDP world model', 'compute the total weighted loss and per-term losses from observation, reward, and KL components', "create a ValueModel for state-value prediction using a world model's belief and state sizes", "create a Q-function ValueModel that takes actions as input using a world model's actor action size", 'build a Dreamer-style actor-critic learner that backpropagates through imagined dynamics to update policy and value', 'run a Soft Actor-Critic training step with twin Q-networks, entropy regularization, and Polyak target updates', 'apply an in-place Polyak soft update to smoothly interpolate target network parameters toward main parameters']
```

Usage

```
{'create_optimizer_ctor_callable': 'create a callable that builds a PyTorch optimizer from parameters and a learning rate', 'create_base_learning_subclass': 'create a subclass of BaseLearning that implements the abstract train_step method', 'add_optimizer_to_learning': 'add a named optimizer with a learning rate and optional gradient clipping to a BaseLearning instance', 'get_trainable_parameters': 'get all trainable parameters from a BaseLearning module by calling trainable_parameters', 'save_and_load_state_dict': 'save and load the combined module and optimizer state dict of a BaseLearning instance'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/agents/learning/model.py

Prompts

```
['create a callable that builds a PyTorch optimizer from parameters and a learning rate', 'create a subclass of BaseLearning that implements the abstract train_step method', 'add a named optimizer with a learning rate and optional gradient clipping to a BaseLearning instance', 'get all trainable parameters from a BaseLearning module by calling trainable_parameters', 'save and load the combined module and optimizer state dict of a BaseLearning instance', 'create an ObservationLoss instance with a configurable weight for observation reconstruction loss', 'create a RewardLoss instance with a configurable weight for reward prediction loss', 'create a KLLoss with alpha, beta, and free_nats hyperparameters for posterior-prior KL divergence', 'run a VariationalModelLearning train_step on experience replay data with a DenoisedMDP world model', 'compute the total weighted loss and per-term losses from observation, reward, and KL components', "create a ValueModel for state-value prediction using a world model's belief and state sizes", "create a Q-function ValueModel that takes actions as input using a world model's actor action size", 'build a Dreamer-style actor-critic learner that backpropagates through imagined dynamics to update policy and value', 'run a Soft Actor-Critic training step with twin Q-networks, entropy regularization, and Polyak target updates', 'apply an in-place Polyak soft update to smoothly interpolate target network parameters toward main parameters']
```

Usage

```
{'create_observation_loss': 'create an ObservationLoss instance with a configurable weight for observation reconstruction loss', 'create_reward_loss': 'create a RewardLoss instance with a configurable weight for reward prediction loss', 'create_kl_loss': 'create a KLLoss with alpha, beta, and free_nats hyperparameters for posterior-prior KL divergence', 'run_variational_model_training': 'run a VariationalModelLearning train_step on experience replay data with a DenoisedMDP world model', 'compute_variational_losses': 'compute the total weighted loss and per-term losses from observation, reward, and KL components'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/agents/learning/policy.py

Prompts

```
['create a callable that builds a PyTorch optimizer from parameters and a learning rate', 'create a subclass of BaseLearning that implements the abstract train_step method', 'add a named optimizer with a learning rate and optional gradient clipping to a BaseLearning instance', 'get all trainable parameters from a BaseLearning module by calling trainable_parameters', 'save and load the combined module and optimizer state dict of a BaseLearning instance', 'create an ObservationLoss instance with a configurable weight for observation reconstruction loss', 'create a RewardLoss instance with a configurable weight for reward prediction loss', 'create a KLLoss with alpha, beta, and free_nats hyperparameters for posterior-prior KL divergence', 'run a VariationalModelLearning train_step on experience replay data with a DenoisedMDP world model', 'compute the total weighted loss and per-term losses from observation, reward, and KL components', "create a ValueModel for state-value prediction using a world model's belief and state sizes", "create a Q-function ValueModel that takes actions as input using a world model's actor action size", 'build a Dreamer-style actor-critic learner that backpropagates through imagined dynamics to update policy and value', 'run a Soft Actor-Critic training step with twin Q-networks, entropy regularization, and Polyak target updates', 'apply an in-place Polyak soft update to smoothly interpolate target network parameters toward main parameters']
```

Usage

```
{'create_value_model': "create a ValueModel for state-value prediction using a world model's belief and state sizes", 'create_q_model': "create a Q-function ValueModel that takes actions as input using a world model's actor action size", 'build_dynamics_backprop_actor_critic': 'build a Dreamer-style actor-critic learner that backpropagates through imagined dynamics to update policy and value', 'run_sac_training_step': 'run a Soft Actor-Critic training step with twin Q-networks, entropy regularization, and Polyak target updates', 'apply_polyak_update': 'apply an in-place Polyak soft update to smoothly interpolate target network parameters toward main parameters'}
```

