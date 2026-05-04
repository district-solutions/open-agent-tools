# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/iqn/learning.py

Prompts

```
['build an IQNLearner instance with an IQN network, target network, discount, and replay dataset', 'run a single SGD training step on the IQNLearner that updates network weights and priorities', 'review the IQNLearner _loss_and_fetches method to understand how quantile regression loss is computed', 'refactor the IQNLearner target network periodic update logic to support soft updates with tau', 'summarize the _index_embs_with_actions function that slices embedding tensors using sparse boolean masks', 'test the IQN learner by building a network, creating a learner, and running a single step', 'create a torso network using sonnet Sequential with Flatten and MLP layers for intermediate representations', 'create a head network using sonnet MLP to output Q-values for a given number of actions', 'build an IQNNetwork with a torso, head, latent dimension, and quantile sample count for distributional RL']
```

Usage

```
{'build_iqn_learner': 'build an IQNLearner instance with an IQN network, target network, discount, and replay dataset', 'run_iqn_learner_step': 'run a single SGD training step on the IQNLearner that updates network weights and priorities', 'review_iqn_loss_computation': 'review the IQNLearner _loss_and_fetches method to understand how quantile regression loss is computed', 'refactor_iqn_target_network_update': 'refactor the IQNLearner target network periodic update logic to support soft updates with tau', 'summarize_index_embs_with_actions': 'summarize the _index_embs_with_actions function that slices embedding tensors using sparse boolean masks'}
```

## File: google-deepmind_acme/acme/agents/tf/iqn/learning_test.py

Prompts

```
['build an IQNLearner instance with an IQN network, target network, discount, and replay dataset', 'run a single SGD training step on the IQNLearner that updates network weights and priorities', 'review the IQNLearner _loss_and_fetches method to understand how quantile regression loss is computed', 'refactor the IQNLearner target network periodic update logic to support soft updates with tau', 'summarize the _index_embs_with_actions function that slices embedding tensors using sparse boolean masks', 'test the IQN learner by building a network, creating a learner, and running a single step', 'create a torso network using sonnet Sequential with Flatten and MLP layers for intermediate representations', 'create a head network using sonnet MLP to output Q-values for a given number of actions', 'build an IQNNetwork with a torso, head, latent dimension, and quantile sample count for distributional RL']
```

Usage

```
{'test_iqn_learner_full_pipeline': 'test the IQN learner by building a network, creating a learner, and running a single step', 'create_torso_network': 'create a torso network using sonnet Sequential with Flatten and MLP layers for intermediate representations', 'create_head_network': 'create a head network using sonnet MLP to output Q-values for a given number of actions', 'build_iqn_network': 'build an IQNNetwork with a torso, head, latent dimension, and quantile sample count for distributional RL', 'run_iqn_learner_step': 'run a single learning step of the IQN learner and verify step counts and state updates'}
```

