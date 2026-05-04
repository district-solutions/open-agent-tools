# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rts/game_TD/game.py

Prompts

```
['run the Loader class to initialize minirts game environment with actor and train specs', 'create an actor specification with input keys s, base_hp_level, last_r, and terminal', 'create a training specification with input keys rv, pi, s, base_hp_level, a, last_r, V, terminal', 'register an actor callback function that returns zero actions for the game environment', 'run the game controller loop for n iterations and compute FPS timing statistics', 'build a MiniRTSNet convolutional neural network model with configurable batch normalization and activation functions', 'build a Model_ActorCritic reinforcement learning model with policy and value heads for action selection', 'test the Model_ActorCritic model by running a forward pass on an identity matrix input', 'review the MiniRTSNet forward pass that applies four convolutional layers with optional batch normalization', 'refactor the Models dictionary registry to map actor_critic key to Model_ActorCritic and ActorCritic classes']
```

Usage

```
{'run_loader_minirts': 'run the Loader class to initialize minirts game environment with actor and train specs', 'create_actor_spec': 'create an actor specification with input keys s, base_hp_level, last_r, and terminal', 'create_train_spec': 'create a training specification with input keys rv, pi, s, base_hp_level, a, last_r, V, terminal', 'register_actor_callback': 'register an actor callback function that returns zero actions for the game environment', 'run_gc_loop': 'run the game controller loop for n iterations and compute FPS timing statistics'}
```

## File: facebookresearch_elf/rts/game_TD/model.py

Prompts

```
['run the Loader class to initialize minirts game environment with actor and train specs', 'create an actor specification with input keys s, base_hp_level, last_r, and terminal', 'create a training specification with input keys rv, pi, s, base_hp_level, a, last_r, V, terminal', 'register an actor callback function that returns zero actions for the game environment', 'run the game controller loop for n iterations and compute FPS timing statistics', 'build a MiniRTSNet convolutional neural network model with configurable batch normalization and activation functions', 'build a Model_ActorCritic reinforcement learning model with policy and value heads for action selection', 'test the Model_ActorCritic model by running a forward pass on an identity matrix input', 'review the MiniRTSNet forward pass that applies four convolutional layers with optional batch normalization', 'refactor the Models dictionary registry to map actor_critic key to Model_ActorCritic and ActorCritic classes']
```

Usage

```
{'build_MiniRTSNet': 'build a MiniRTSNet convolutional neural network model with configurable batch normalization and activation functions', 'build_Model_ActorCritic': 'build a Model_ActorCritic reinforcement learning model with policy and value heads for action selection', 'test_Model_ActorCritic': 'test the Model_ActorCritic model by running a forward pass on an identity matrix input', 'review_MiniRTSNet_forward': 'review the MiniRTSNet forward pass that applies four convolutional layers with optional batch normalization', 'refactor_Models_registry': 'refactor the Models dictionary registry to map actor_critic key to Model_ActorCritic and ActorCritic classes'}
```

