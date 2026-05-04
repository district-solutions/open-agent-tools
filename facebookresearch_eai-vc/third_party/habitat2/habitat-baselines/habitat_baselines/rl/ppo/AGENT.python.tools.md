# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ppo/cpc_aux_loss.py

Prompts

```
['build a CPCA auxiliary loss module for action-conditional contrastive predictive coding in embodied AI', 'create an action-conditioned forward modeling loss module using LSTM to predict future states from action sequences', 'test the masked_index_select function to select tensor indices with validity masking and fill values', 'review the masked_mean function that computes the mean of a tensor for valid locations specified by a boolean mask', 'refactor the CPCA predictor network layers to adjust hidden size or add new activation functions', 'build a PointNavBaselinePolicy from a DictConfig with observation and action spaces for PPO training', 'create a NetPolicy with a custom net, action space, and optional auxiliary loss configuration', 'run the PointNavBaselineNet forward pass with observations, RNN hidden states, masks, and goal sensors', 'evaluate actions with NetPolicy.evaluate_actions to get value, log probs, entropy, and auxiliary loss results', 'review the CriticHead class which uses an orthogonal-initialized linear layer for value estimation', 'build a PPO agent from a config dict and NetPolicy actor-critic using PPO.from_config', 'run the PPO update loop on RolloutStorage to compute advantages and perform gradient steps', 'create a PPO instance with Adam or AdamW optimizer supporting separate encoder and policy learning rates', 'review the PPO get_advantages method that computes and normalizes advantage estimates from rollout returns', 'refactor the PPO before_step method to customize gradient clipping and distributed all-reduce behavior', 'train a PPO agent on Habitat navigation tasks using the PPOTrainer train method', 'evaluate a saved PPO checkpoint on test episodes using the _eval_checkpoint method', 'save the current PPO agent state and config to a checkpoint file', 'load a PPO agent checkpoint from a file path and return its state dict', 'setup the actor critic network and PPO agent from config using _setup_actor_critic_agent']
```

Usage

```
{'build_CPCA_auxiliary_loss': 'build a CPCA auxiliary loss module for action-conditional contrastive predictive coding in embodied AI', 'create_ActionConditionedForwardModelingLoss': 'create an action-conditioned forward modeling loss module using LSTM to predict future states from action sequences', 'test_masked_index_select': 'test the masked_index_select function to select tensor indices with validity masking and fill values', 'review_masked_mean': 'review the masked_mean function that computes the mean of a tensor for valid locations specified by a boolean mask', 'refactor_CPCA_predictor': 'refactor the CPCA predictor network layers to adjust hidden size or add new activation functions'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ppo/policy.py

Prompts

```
['build a CPCA auxiliary loss module for action-conditional contrastive predictive coding in embodied AI', 'create an action-conditioned forward modeling loss module using LSTM to predict future states from action sequences', 'test the masked_index_select function to select tensor indices with validity masking and fill values', 'review the masked_mean function that computes the mean of a tensor for valid locations specified by a boolean mask', 'refactor the CPCA predictor network layers to adjust hidden size or add new activation functions', 'build a PointNavBaselinePolicy from a DictConfig with observation and action spaces for PPO training', 'create a NetPolicy with a custom net, action space, and optional auxiliary loss configuration', 'run the PointNavBaselineNet forward pass with observations, RNN hidden states, masks, and goal sensors', 'evaluate actions with NetPolicy.evaluate_actions to get value, log probs, entropy, and auxiliary loss results', 'review the CriticHead class which uses an orthogonal-initialized linear layer for value estimation', 'build a PPO agent from a config dict and NetPolicy actor-critic using PPO.from_config', 'run the PPO update loop on RolloutStorage to compute advantages and perform gradient steps', 'create a PPO instance with Adam or AdamW optimizer supporting separate encoder and policy learning rates', 'review the PPO get_advantages method that computes and normalizes advantage estimates from rollout returns', 'refactor the PPO before_step method to customize gradient clipping and distributed all-reduce behavior', 'train a PPO agent on Habitat navigation tasks using the PPOTrainer train method', 'evaluate a saved PPO checkpoint on test episodes using the _eval_checkpoint method', 'save the current PPO agent state and config to a checkpoint file', 'load a PPO agent checkpoint from a file path and return its state dict', 'setup the actor critic network and PPO agent from config using _setup_actor_critic_agent']
```

Usage

```
{'build_PointNavBaselinePolicy': 'build a PointNavBaselinePolicy from a DictConfig with observation and action spaces for PPO training', 'create_NetPolicy': 'create a NetPolicy with a custom net, action space, and optional auxiliary loss configuration', 'run_PointNavBaselineNet_forward': 'run the PointNavBaselineNet forward pass with observations, RNN hidden states, masks, and goal sensors', 'evaluate_NetPolicy_actions': 'evaluate actions with NetPolicy.evaluate_actions to get value, log probs, entropy, and auxiliary loss results', 'review_CriticHead': 'review the CriticHead class which uses an orthogonal-initialized linear layer for value estimation'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ppo/ppo.py

Prompts

```
['build a CPCA auxiliary loss module for action-conditional contrastive predictive coding in embodied AI', 'create an action-conditioned forward modeling loss module using LSTM to predict future states from action sequences', 'test the masked_index_select function to select tensor indices with validity masking and fill values', 'review the masked_mean function that computes the mean of a tensor for valid locations specified by a boolean mask', 'refactor the CPCA predictor network layers to adjust hidden size or add new activation functions', 'build a PointNavBaselinePolicy from a DictConfig with observation and action spaces for PPO training', 'create a NetPolicy with a custom net, action space, and optional auxiliary loss configuration', 'run the PointNavBaselineNet forward pass with observations, RNN hidden states, masks, and goal sensors', 'evaluate actions with NetPolicy.evaluate_actions to get value, log probs, entropy, and auxiliary loss results', 'review the CriticHead class which uses an orthogonal-initialized linear layer for value estimation', 'build a PPO agent from a config dict and NetPolicy actor-critic using PPO.from_config', 'run the PPO update loop on RolloutStorage to compute advantages and perform gradient steps', 'create a PPO instance with Adam or AdamW optimizer supporting separate encoder and policy learning rates', 'review the PPO get_advantages method that computes and normalizes advantage estimates from rollout returns', 'refactor the PPO before_step method to customize gradient clipping and distributed all-reduce behavior', 'train a PPO agent on Habitat navigation tasks using the PPOTrainer train method', 'evaluate a saved PPO checkpoint on test episodes using the _eval_checkpoint method', 'save the current PPO agent state and config to a checkpoint file', 'load a PPO agent checkpoint from a file path and return its state dict', 'setup the actor critic network and PPO agent from config using _setup_actor_critic_agent']
```

Usage

```
{'build_PPO_from_config': 'build a PPO agent from a config dict and NetPolicy actor-critic using PPO.from_config', 'run_PPO_update': 'run the PPO update loop on RolloutStorage to compute advantages and perform gradient steps', 'create_PPO_optimizer': 'create a PPO instance with Adam or AdamW optimizer supporting separate encoder and policy learning rates', 'review_PPO_get_advantages': 'review the PPO get_advantages method that computes and normalizes advantage estimates from rollout returns', 'refactor_PPO_before_step': 'refactor the PPO before_step method to customize gradient clipping and distributed all-reduce behavior'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ppo/ppo_trainer.py

Prompts

```
['build a CPCA auxiliary loss module for action-conditional contrastive predictive coding in embodied AI', 'create an action-conditioned forward modeling loss module using LSTM to predict future states from action sequences', 'test the masked_index_select function to select tensor indices with validity masking and fill values', 'review the masked_mean function that computes the mean of a tensor for valid locations specified by a boolean mask', 'refactor the CPCA predictor network layers to adjust hidden size or add new activation functions', 'build a PointNavBaselinePolicy from a DictConfig with observation and action spaces for PPO training', 'create a NetPolicy with a custom net, action space, and optional auxiliary loss configuration', 'run the PointNavBaselineNet forward pass with observations, RNN hidden states, masks, and goal sensors', 'evaluate actions with NetPolicy.evaluate_actions to get value, log probs, entropy, and auxiliary loss results', 'review the CriticHead class which uses an orthogonal-initialized linear layer for value estimation', 'build a PPO agent from a config dict and NetPolicy actor-critic using PPO.from_config', 'run the PPO update loop on RolloutStorage to compute advantages and perform gradient steps', 'create a PPO instance with Adam or AdamW optimizer supporting separate encoder and policy learning rates', 'review the PPO get_advantages method that computes and normalizes advantage estimates from rollout returns', 'refactor the PPO before_step method to customize gradient clipping and distributed all-reduce behavior', 'train a PPO agent on Habitat navigation tasks using the PPOTrainer train method', 'evaluate a saved PPO checkpoint on test episodes using the _eval_checkpoint method', 'save the current PPO agent state and config to a checkpoint file', 'load a PPO agent checkpoint from a file path and return its state dict', 'setup the actor critic network and PPO agent from config using _setup_actor_critic_agent']
```

Usage

```
{'train_PPOTrainer': 'train a PPO agent on Habitat navigation tasks using the PPOTrainer train method', 'eval_checkpoint_PPOTrainer': 'evaluate a saved PPO checkpoint on test episodes using the _eval_checkpoint method', 'save_checkpoint_PPOTrainer': 'save the current PPO agent state and config to a checkpoint file', 'load_checkpoint_PPOTrainer': 'load a PPO agent checkpoint from a file path and return its state dict', 'setup_actor_critic_PPOTrainer': 'setup the actor critic network and PPO agent from config using _setup_actor_critic_agent'}
```

