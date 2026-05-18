# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/algos/ppo/r_mappo/algorithm/rMAPPOPolicy.py

Prompts

```
['create an R_MAPPOPolicy instance with actor and critic networks for multi-agent PPO training', 'get actions and value predictions from the R_MAPPOPolicy using centralized and local observations', 'evaluate action log probabilities and entropy for actor network updates in R_MAPPOPolicy', 'decay the learning rates of actor and critic optimizers linearly over training episodes', 'compute actions from the actor network using local observations and RNN states', 'build an R_Actor network for MAPPO with MLP base and optional RNN layers given observation and action spaces', 'build an R_Critic network for MAPPO with centralized observations and optional PopArt value normalization', 'run the R_Actor forward pass to compute actions and log probabilities from observations and RNN states', 'run the R_Critic forward pass to compute value function predictions from centralized observations and RNN states', 'test the R_Actor evaluate_actions method to compute log probabilities and entropy for given actions']
```

Usage

```
{'create_R_MAPPOPolicy': 'create an R_MAPPOPolicy instance with actor and critic networks for multi-agent PPO training', 'get_actions_R_MAPPOPolicy': 'get actions and value predictions from the R_MAPPOPolicy using centralized and local observations', 'evaluate_actions_R_MAPPOPolicy': 'evaluate action log probabilities and entropy for actor network updates in R_MAPPOPolicy', 'lr_decay_R_MAPPOPolicy': 'decay the learning rates of actor and critic optimizers linearly over training episodes', 'act_R_MAPPOPolicy': 'compute actions from the actor network using local observations and RNN states'}
```

## File: facebookresearch_nocturne/algos/ppo/r_mappo/algorithm/r_actor_critic.py

Prompts

```
['create an R_MAPPOPolicy instance with actor and critic networks for multi-agent PPO training', 'get actions and value predictions from the R_MAPPOPolicy using centralized and local observations', 'evaluate action log probabilities and entropy for actor network updates in R_MAPPOPolicy', 'decay the learning rates of actor and critic optimizers linearly over training episodes', 'compute actions from the actor network using local observations and RNN states', 'build an R_Actor network for MAPPO with MLP base and optional RNN layers given observation and action spaces', 'build an R_Critic network for MAPPO with centralized observations and optional PopArt value normalization', 'run the R_Actor forward pass to compute actions and log probabilities from observations and RNN states', 'run the R_Critic forward pass to compute value function predictions from centralized observations and RNN states', 'test the R_Actor evaluate_actions method to compute log probabilities and entropy for given actions']
```

Usage

```
{'build_R_Actor_network': 'build an R_Actor network for MAPPO with MLP base and optional RNN layers given observation and action spaces', 'build_R_Critic_network': 'build an R_Critic network for MAPPO with centralized observations and optional PopArt value normalization', 'run_R_Actor_forward': 'run the R_Actor forward pass to compute actions and log probabilities from observations and RNN states', 'run_R_Critic_forward': 'run the R_Critic forward pass to compute value function predictions from centralized observations and RNN states', 'test_R_Actor_evaluate_actions': 'test the R_Actor evaluate_actions method to compute log probabilities and entropy for given actions'}
```

