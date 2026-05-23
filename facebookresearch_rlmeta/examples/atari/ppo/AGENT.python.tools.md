# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/examples/atari/ppo/atari_ppo_model.py

Prompts

```
['create an AtariPPOModel with the NatureCNN backbone for a given number of discrete actions', 'create an AtariPPOModel with the ImpalaCNN backbone for a given number of discrete actions', 'run the forward pass of AtariPPOModel to get log probabilities and value estimates from observations', 'call the act method of AtariPPOModel to select actions with optional deterministic policy support', 'review the AtariPPOModel class and its use of NatureCNN or ImpalaCNN backbones with a discrete actor-critic head', 'build an Atari PPO RND model with NatureCNN or ImpalaCNN backbone for a given number of actions', 'create a forward pass through the Atari PPO RND model to get log probabilities and value estimates', 'test the act method to select actions using greedy or sampled policy based on deterministic flag', 'review the intrinsic_reward method that computes RND prediction error for curiosity-driven exploration', 'refactor the rnd_loss method that computes mean squared error between target and predictor networks']
```

Usage

```
{'create_atari_ppo_model_nature': 'create an AtariPPOModel with the NatureCNN backbone for a given number of discrete actions', 'create_atari_ppo_model_impala': 'create an AtariPPOModel with the ImpalaCNN backbone for a given number of discrete actions', 'forward_atari_ppo_model': 'run the forward pass of AtariPPOModel to get log probabilities and value estimates from observations', 'act_atari_ppo_model': 'call the act method of AtariPPOModel to select actions with optional deterministic policy support', 'review_atari_ppo_model': 'review the AtariPPOModel class and its use of NatureCNN or ImpalaCNN backbones with a discrete actor-critic head'}
```

## File: facebookresearch_rlmeta/examples/atari/ppo/atari_ppo_rnd_model.py

Prompts

```
['create an AtariPPOModel with the NatureCNN backbone for a given number of discrete actions', 'create an AtariPPOModel with the ImpalaCNN backbone for a given number of discrete actions', 'run the forward pass of AtariPPOModel to get log probabilities and value estimates from observations', 'call the act method of AtariPPOModel to select actions with optional deterministic policy support', 'review the AtariPPOModel class and its use of NatureCNN or ImpalaCNN backbones with a discrete actor-critic head', 'build an Atari PPO RND model with NatureCNN or ImpalaCNN backbone for a given number of actions', 'create a forward pass through the Atari PPO RND model to get log probabilities and value estimates', 'test the act method to select actions using greedy or sampled policy based on deterministic flag', 'review the intrinsic_reward method that computes RND prediction error for curiosity-driven exploration', 'refactor the rnd_loss method that computes mean squared error between target and predictor networks']
```

Usage

```
{'build_atari_ppo_rnd_model': 'build an Atari PPO RND model with NatureCNN or ImpalaCNN backbone for a given number of actions', 'create_forward_pass': 'create a forward pass through the Atari PPO RND model to get log probabilities and value estimates', 'test_act_method': 'test the act method to select actions using greedy or sampled policy based on deterministic flag', 'review_intrinsic_reward': 'review the intrinsic_reward method that computes RND prediction error for curiosity-driven exploration', 'refactor_rnd_loss': 'refactor the rnd_loss method that computes mean squared error between target and predictor networks'}
```

