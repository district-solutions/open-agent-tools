# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/deprecated/sac/agent.py

Prompts

```
['create a SACPolicy network with given observation dim, action dim, and hidden size', 'create a SACQ critic network with given observation dim, action dim, and hidden size', 'run a SACAgent step to sample actions from a Gaussian policy model', 'create a DiagGaussianActor that constrains log_std and applies tanh to mean', 'create a SquashedNormal distribution by applying TanhTransform to a base Normal distribution', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment using Hydra config', 'create a GymEnvInf or GymEnv wrapper for training or evaluation with configurable episode steps and seed', 'create an SACAgent instance with a given policy and optional action dimension', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys', 'review the Experiment class that extends SAC and creates SACPolicy and SACQ models with weight initialization', 'run the SAC algorithm training loop with replay buffer and soft target updates', 'create a ReplayBuffer instance to store and sample transitions for off-policy learning', 'review the SAC get_q_loss method that computes twin Q-network loss with target network bootstrapping', 'review the SAC get_policy_loss method that computes entropy-regularized policy loss using reparameterization', 'test the SAC soft_update_params method that performs tau-weighted parameter interpolation between networks']
```

Usage

```
{'create_SACPolicy': 'create a SACPolicy network with given observation dim, action dim, and hidden size', 'create_SACQ': 'create a SACQ critic network with given observation dim, action dim, and hidden size', 'run_SACAgent': 'run a SACAgent step to sample actions from a Gaussian policy model', 'create_DiagGaussianActor': 'create a DiagGaussianActor that constrains log_std and applies tanh to mean', 'create_SquashedNormal': 'create a SquashedNormal distribution by applying TanhTransform to a base Normal distribution'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/sac/run_cartpole.py

Prompts

```
['create a SACPolicy network with given observation dim, action dim, and hidden size', 'create a SACQ critic network with given observation dim, action dim, and hidden size', 'run a SACAgent step to sample actions from a Gaussian policy model', 'create a DiagGaussianActor that constrains log_std and applies tanh to mean', 'create a SquashedNormal distribution by applying TanhTransform to a base Normal distribution', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment using Hydra config', 'create a GymEnvInf or GymEnv wrapper for training or evaluation with configurable episode steps and seed', 'create an SACAgent instance with a given policy and optional action dimension', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys', 'review the Experiment class that extends SAC and creates SACPolicy and SACQ models with weight initialization', 'run the SAC algorithm training loop with replay buffer and soft target updates', 'create a ReplayBuffer instance to store and sample transitions for off-policy learning', 'review the SAC get_q_loss method that computes twin Q-network loss with target network bootstrapping', 'review the SAC get_policy_loss method that computes entropy-regularized policy loss using reparameterization', 'test the SAC soft_update_params method that performs tau-weighted parameter interpolation between networks']
```

Usage

```
{'run_sac_cartpole_experiment': 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment using Hydra config', 'create_env_for_training': 'create a GymEnvInf or GymEnv wrapper for training or evaluation with configurable episode steps and seed', 'create_sac_agent': 'create an SACAgent instance with a given policy and optional action dimension', 'flatten_hydra_config': 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys', 'review_Experiment_class': 'review the Experiment class that extends SAC and creates SACPolicy and SACQ models with weight initialization'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/sac/sac.py

Prompts

```
['create a SACPolicy network with given observation dim, action dim, and hidden size', 'create a SACQ critic network with given observation dim, action dim, and hidden size', 'run a SACAgent step to sample actions from a Gaussian policy model', 'create a DiagGaussianActor that constrains log_std and applies tanh to mean', 'create a SquashedNormal distribution by applying TanhTransform to a base Normal distribution', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment using Hydra config', 'create a GymEnvInf or GymEnv wrapper for training or evaluation with configurable episode steps and seed', 'create an SACAgent instance with a given policy and optional action dimension', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys', 'review the Experiment class that extends SAC and creates SACPolicy and SACQ models with weight initialization', 'run the SAC algorithm training loop with replay buffer and soft target updates', 'create a ReplayBuffer instance to store and sample transitions for off-policy learning', 'review the SAC get_q_loss method that computes twin Q-network loss with target network bootstrapping', 'review the SAC get_policy_loss method that computes entropy-regularized policy loss using reparameterization', 'test the SAC soft_update_params method that performs tau-weighted parameter interpolation between networks']
```

Usage

```
{'run_SAC_training': 'run the SAC algorithm training loop with replay buffer and soft target updates', 'create_ReplayBuffer': 'create a ReplayBuffer instance to store and sample transitions for off-policy learning', 'review_SAC_get_q_loss': 'review the SAC get_q_loss method that computes twin Q-network loss with target network bootstrapping', 'review_SAC_get_policy_loss': 'review the SAC get_policy_loss method that computes entropy-regularized policy loss using reparameterization', 'test_SAC_soft_update': 'test the SAC soft_update_params method that performs tau-weighted parameter interpolation between networks'}
```

