# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rts/game_CF/game.py

Prompts

```
['run the minirts game loop for nIter iterations and measure elapsed time and FPS', 'create a Loader class that extends CommonLoader with minirts and defines actor and train specs', 'register an actor callback function with the game controller using GC.reg_callback', 'get the actor specification dict with input keys s, res, last_r, r0, r1, terminal', 'get the train specification dict with input keys rv, pi, s, res, a, last_r, r0, r1, V, terminal', 'build a MiniRTSNet convolutional neural network model with configurable batch normalization and leaky ReLU', 'run the MiniRTSNet forward pass to extract flattened features from a 20x20 input grid', 'build a Model_ActorCritic that wraps MiniRTSNet with policy and value linear heads for RL', 'run the Model_ActorCritic forward pass to get policy probabilities and value estimates from state input', 'test the Model_ActorCritic model by running a diagonal identity matrix through and printing policy and value outputs']
```

Usage

```
{'run_game_loop': 'run the minirts game loop for nIter iterations and measure elapsed time and FPS', 'create_loader_class': 'create a Loader class that extends CommonLoader with minirts and defines actor and train specs', 'register_actor_callback': 'register an actor callback function with the game controller using GC.reg_callback', 'get_actor_spec': 'get the actor specification dict with input keys s, res, last_r, r0, r1, terminal', 'get_train_spec': 'get the train specification dict with input keys rv, pi, s, res, a, last_r, r0, r1, V, terminal'}
```

## File: facebookresearch_elf/rts/game_CF/model.py

Prompts

```
['run the minirts game loop for nIter iterations and measure elapsed time and FPS', 'create a Loader class that extends CommonLoader with minirts and defines actor and train specs', 'register an actor callback function with the game controller using GC.reg_callback', 'get the actor specification dict with input keys s, res, last_r, r0, r1, terminal', 'get the train specification dict with input keys rv, pi, s, res, a, last_r, r0, r1, V, terminal', 'build a MiniRTSNet convolutional neural network model with configurable batch normalization and leaky ReLU', 'run the MiniRTSNet forward pass to extract flattened features from a 20x20 input grid', 'build a Model_ActorCritic that wraps MiniRTSNet with policy and value linear heads for RL', 'run the Model_ActorCritic forward pass to get policy probabilities and value estimates from state input', 'test the Model_ActorCritic model by running a diagonal identity matrix through and printing policy and value outputs']
```

Usage

```
{'build_MiniRTSNet': 'build a MiniRTSNet convolutional neural network model with configurable batch normalization and leaky ReLU', 'run_MiniRTSNet_forward': 'run the MiniRTSNet forward pass to extract flattened features from a 20x20 input grid', 'build_Model_ActorCritic': 'build a Model_ActorCritic that wraps MiniRTSNet with policy and value linear heads for RL', 'run_Model_ActorCritic_forward': 'run the Model_ActorCritic forward pass to get policy probabilities and value estimates from state input', 'test_Model_ActorCritic': 'test the Model_ActorCritic model by running a diagonal identity matrix through and printing policy and value outputs'}
```

