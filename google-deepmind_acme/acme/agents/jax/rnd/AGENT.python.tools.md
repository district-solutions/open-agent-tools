# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/rnd/builder.py

Prompts

```
['build an RNDBuilder instance with an RL agent and RND config for random network distillation', 'create an RND learner by calling make_learner with networks, dataset, and environment spec', 'create replay tables for the RND agent using make_replay_tables with environment spec and policy', 'create a feed-forward policy from RND networks using make_policy with environment spec', 'create an RND actor using make_actor with a policy, environment spec, and optional variable source', 'build an RNDLearner instance with a direct RL learner factory, replay iterator, and optimizer', 'run a single RND training update step on transitions using the predictor network and optimizer', 'compute the MSE loss between predictor and target network outputs for RND training', 'create an RNDTrainingState namedtuple holding optimizer state, predictor params, target params, and step count', 'save and restore the full RND learner state including rewarder and direct RL learner states', 'build RND target and predictor networks using make_networks with an environment spec and layer sizes', 'compute the intrinsic RND reward for a transition using predictor and target network parameters', 'create a reward function combining intrinsic prediction error and extrinsic reward with configurable coefficients', 'review the RNDNetworks dataclass container holding target network, predictor network, and reward computation function', 'summarize how rnd_reward_fn computes mean squared error between predictor and target outputs as intrinsic reward']
```

Usage

```
{'build_RNDBuilder': 'build an RNDBuilder instance with an RL agent and RND config for random network distillation', 'create_make_learner': 'create an RND learner by calling make_learner with networks, dataset, and environment spec', 'create_make_replay_tables': 'create replay tables for the RND agent using make_replay_tables with environment spec and policy', 'create_make_policy': 'create a feed-forward policy from RND networks using make_policy with environment spec', 'create_make_actor': 'create an RND actor using make_actor with a policy, environment spec, and optional variable source'}
```

## File: google-deepmind_acme/acme/agents/jax/rnd/learning.py

Prompts

```
['build an RNDBuilder instance with an RL agent and RND config for random network distillation', 'create an RND learner by calling make_learner with networks, dataset, and environment spec', 'create replay tables for the RND agent using make_replay_tables with environment spec and policy', 'create a feed-forward policy from RND networks using make_policy with environment spec', 'create an RND actor using make_actor with a policy, environment spec, and optional variable source', 'build an RNDLearner instance with a direct RL learner factory, replay iterator, and optimizer', 'run a single RND training update step on transitions using the predictor network and optimizer', 'compute the MSE loss between predictor and target network outputs for RND training', 'create an RNDTrainingState namedtuple holding optimizer state, predictor params, target params, and step count', 'save and restore the full RND learner state including rewarder and direct RL learner states', 'build RND target and predictor networks using make_networks with an environment spec and layer sizes', 'compute the intrinsic RND reward for a transition using predictor and target network parameters', 'create a reward function combining intrinsic prediction error and extrinsic reward with configurable coefficients', 'review the RNDNetworks dataclass container holding target network, predictor network, and reward computation function', 'summarize how rnd_reward_fn computes mean squared error between predictor and target outputs as intrinsic reward']
```

Usage

```
{'build_rnd_learner': 'build an RNDLearner instance with a direct RL learner factory, replay iterator, and optimizer', 'run_rnd_update_step': 'run a single RND training update step on transitions using the predictor network and optimizer', 'compute_rnd_loss': 'compute the MSE loss between predictor and target network outputs for RND training', 'create_rnd_training_state': 'create an RNDTrainingState namedtuple holding optimizer state, predictor params, target params, and step count', 'save_restore_rnd_learner': 'save and restore the full RND learner state including rewarder and direct RL learner states'}
```

## File: google-deepmind_acme/acme/agents/jax/rnd/networks.py

Prompts

```
['build an RNDBuilder instance with an RL agent and RND config for random network distillation', 'create an RND learner by calling make_learner with networks, dataset, and environment spec', 'create replay tables for the RND agent using make_replay_tables with environment spec and policy', 'create a feed-forward policy from RND networks using make_policy with environment spec', 'create an RND actor using make_actor with a policy, environment spec, and optional variable source', 'build an RNDLearner instance with a direct RL learner factory, replay iterator, and optimizer', 'run a single RND training update step on transitions using the predictor network and optimizer', 'compute the MSE loss between predictor and target network outputs for RND training', 'create an RNDTrainingState namedtuple holding optimizer state, predictor params, target params, and step count', 'save and restore the full RND learner state including rewarder and direct RL learner states', 'build RND target and predictor networks using make_networks with an environment spec and layer sizes', 'compute the intrinsic RND reward for a transition using predictor and target network parameters', 'create a reward function combining intrinsic prediction error and extrinsic reward with configurable coefficients', 'review the RNDNetworks dataclass container holding target network, predictor network, and reward computation function', 'summarize how rnd_reward_fn computes mean squared error between predictor and target outputs as intrinsic reward']
```

Usage

```
{'build_rnd_networks': 'build RND target and predictor networks using make_networks with an environment spec and layer sizes', 'compute_rnd_reward': 'compute the intrinsic RND reward for a transition using predictor and target network parameters', 'create_rnd_reward_fn': 'create a reward function combining intrinsic prediction error and extrinsic reward with configurable coefficients', 'review_RNDNetworks_dataclass': 'review the RNDNetworks dataclass container holding target network, predictor network, and reward computation function', 'summarize_rnd_reward_fn': 'summarize how rnd_reward_fn computes mean squared error between predictor and target outputs as intrinsic reward'}
```

