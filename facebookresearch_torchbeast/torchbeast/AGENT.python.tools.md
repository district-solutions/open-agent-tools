# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/torchbeast/atari_wrappers.py

Prompts

```
['create an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers using make_atari', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to transpose image observations from HWC to CHW format for PyTorch', 'stack the last k frames into a single observation using the FrameStack wrapper', 'warp environment frames to 84x84 grayscale using the WarpFrame observation wrapper', 'train a PPO agent on an Atari environment using multiple actors and learner threads', 'test a trained Atari agent by running episodes and logging average returns', 'create a convolutional neural network with optional LSTM for Atari frame-based RL', 'compute the policy gradient loss from logits, actions, and advantages', 'create a DeepMind-wrapped Atari gym environment with frame stacking and PyTorch tensors', 'run the polybeast reinforcement learning agent with learner and environment processes via CLI', 'run the polybeast environment process with a given actor id and flags in a forked process', 'run the polybeast learner process with parsed command line flags in the main process', 'review the main function that parses args and spawns multiprocessing environment and learner processes', 'summarize the polybeast entry point that coordinates learner and environment via multiprocessing', 'run the polybeast environment server with multiple Atari environment processes using unix pipes', 'create a wrapped Atari environment using DeepMind wrappers with frame stacking and PyTorch formatting', 'serve an Atari or Mock environment over a libtorchbeast server at a given address', 'review the Env mock class that provides reset and step methods returning numpy arrays', 'refactor the main function to spawn multiple daemon processes for parallel environment serving', 'train a PolyBeast RL agent using the PyTorch Scalable Agent with configurable actors and learning steps', 'run a forward pass through the Net model to get action, policy logits, and baseline outputs', 'compute the entropy loss as the negative entropy of the policy from logits', 'compute the baseline loss as half the sum of squared advantages']
```

Usage

```
{'make_atari_env': 'create an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers using make_atari', 'wrap_deepmind_env': 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap_pytorch_env': 'wrap an environment to transpose image observations from HWC to CHW format for PyTorch', 'use_FrameStack_wrapper': 'stack the last k frames into a single observation using the FrameStack wrapper', 'use_WarpFrame_wrapper': 'warp environment frames to 84x84 grayscale using the WarpFrame observation wrapper'}
```

## File: facebookresearch_torchbeast/torchbeast/monobeast.py

Prompts

```
['create an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers using make_atari', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to transpose image observations from HWC to CHW format for PyTorch', 'stack the last k frames into a single observation using the FrameStack wrapper', 'warp environment frames to 84x84 grayscale using the WarpFrame observation wrapper', 'train a PPO agent on an Atari environment using multiple actors and learner threads', 'test a trained Atari agent by running episodes and logging average returns', 'create a convolutional neural network with optional LSTM for Atari frame-based RL', 'compute the policy gradient loss from logits, actions, and advantages', 'create a DeepMind-wrapped Atari gym environment with frame stacking and PyTorch tensors', 'run the polybeast reinforcement learning agent with learner and environment processes via CLI', 'run the polybeast environment process with a given actor id and flags in a forked process', 'run the polybeast learner process with parsed command line flags in the main process', 'review the main function that parses args and spawns multiprocessing environment and learner processes', 'summarize the polybeast entry point that coordinates learner and environment via multiprocessing', 'run the polybeast environment server with multiple Atari environment processes using unix pipes', 'create a wrapped Atari environment using DeepMind wrappers with frame stacking and PyTorch formatting', 'serve an Atari or Mock environment over a libtorchbeast server at a given address', 'review the Env mock class that provides reset and step methods returning numpy arrays', 'refactor the main function to spawn multiple daemon processes for parallel environment serving', 'train a PolyBeast RL agent using the PyTorch Scalable Agent with configurable actors and learning steps', 'run a forward pass through the Net model to get action, policy logits, and baseline outputs', 'compute the entropy loss as the negative entropy of the policy from logits', 'compute the baseline loss as half the sum of squared advantages']
```

Usage

```
{'train_atari_agent': 'train a PPO agent on an Atari environment using multiple actors and learner threads', 'test_atari_agent': 'test a trained Atari agent by running episodes and logging average returns', 'create_atari_net': 'create a convolutional neural network with optional LSTM for Atari frame-based RL', 'compute_policy_gradient_loss': 'compute the policy gradient loss from logits, actions, and advantages', 'create_env': 'create a DeepMind-wrapped Atari gym environment with frame stacking and PyTorch tensors'}
```

## File: facebookresearch_torchbeast/torchbeast/polybeast.py

Prompts

```
['create an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers using make_atari', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to transpose image observations from HWC to CHW format for PyTorch', 'stack the last k frames into a single observation using the FrameStack wrapper', 'warp environment frames to 84x84 grayscale using the WarpFrame observation wrapper', 'train a PPO agent on an Atari environment using multiple actors and learner threads', 'test a trained Atari agent by running episodes and logging average returns', 'create a convolutional neural network with optional LSTM for Atari frame-based RL', 'compute the policy gradient loss from logits, actions, and advantages', 'create a DeepMind-wrapped Atari gym environment with frame stacking and PyTorch tensors', 'run the polybeast reinforcement learning agent with learner and environment processes via CLI', 'run the polybeast environment process with a given actor id and flags in a forked process', 'run the polybeast learner process with parsed command line flags in the main process', 'review the main function that parses args and spawns multiprocessing environment and learner processes', 'summarize the polybeast entry point that coordinates learner and environment via multiprocessing', 'run the polybeast environment server with multiple Atari environment processes using unix pipes', 'create a wrapped Atari environment using DeepMind wrappers with frame stacking and PyTorch formatting', 'serve an Atari or Mock environment over a libtorchbeast server at a given address', 'review the Env mock class that provides reset and step methods returning numpy arrays', 'refactor the main function to spawn multiple daemon processes for parallel environment serving', 'train a PolyBeast RL agent using the PyTorch Scalable Agent with configurable actors and learning steps', 'run a forward pass through the Net model to get action, policy logits, and baseline outputs', 'compute the entropy loss as the negative entropy of the policy from logits', 'compute the baseline loss as half the sum of squared advantages']
```

Usage

```
{'run_polybeast_cli': 'run the polybeast reinforcement learning agent with learner and environment processes via CLI', 'run_env_function': 'run the polybeast environment process with a given actor id and flags in a forked process', 'run_learner_function': 'run the polybeast learner process with parsed command line flags in the main process', 'review_main_function': 'review the main function that parses args and spawns multiprocessing environment and learner processes', 'summarize_polybeast_entry': 'summarize the polybeast entry point that coordinates learner and environment via multiprocessing'}
```

## File: facebookresearch_torchbeast/torchbeast/polybeast_env.py

Prompts

```
['create an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers using make_atari', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to transpose image observations from HWC to CHW format for PyTorch', 'stack the last k frames into a single observation using the FrameStack wrapper', 'warp environment frames to 84x84 grayscale using the WarpFrame observation wrapper', 'train a PPO agent on an Atari environment using multiple actors and learner threads', 'test a trained Atari agent by running episodes and logging average returns', 'create a convolutional neural network with optional LSTM for Atari frame-based RL', 'compute the policy gradient loss from logits, actions, and advantages', 'create a DeepMind-wrapped Atari gym environment with frame stacking and PyTorch tensors', 'run the polybeast reinforcement learning agent with learner and environment processes via CLI', 'run the polybeast environment process with a given actor id and flags in a forked process', 'run the polybeast learner process with parsed command line flags in the main process', 'review the main function that parses args and spawns multiprocessing environment and learner processes', 'summarize the polybeast entry point that coordinates learner and environment via multiprocessing', 'run the polybeast environment server with multiple Atari environment processes using unix pipes', 'create a wrapped Atari environment using DeepMind wrappers with frame stacking and PyTorch formatting', 'serve an Atari or Mock environment over a libtorchbeast server at a given address', 'review the Env mock class that provides reset and step methods returning numpy arrays', 'refactor the main function to spawn multiple daemon processes for parallel environment serving', 'train a PolyBeast RL agent using the PyTorch Scalable Agent with configurable actors and learning steps', 'run a forward pass through the Net model to get action, policy logits, and baseline outputs', 'compute the entropy loss as the negative entropy of the policy from logits', 'compute the baseline loss as half the sum of squared advantages']
```

Usage

```
{'run_polybeast_env_server': 'run the polybeast environment server with multiple Atari environment processes using unix pipes', 'create_env_atari': 'create a wrapped Atari environment using DeepMind wrappers with frame stacking and PyTorch formatting', 'serve_environment': 'serve an Atari or Mock environment over a libtorchbeast server at a given address', 'review_Env_class': 'review the Env mock class that provides reset and step methods returning numpy arrays', 'refactor_main_multiprocessing': 'refactor the main function to spawn multiple daemon processes for parallel environment serving'}
```

## File: facebookresearch_torchbeast/torchbeast/polybeast_learner.py

Prompts

```
['create an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers using make_atari', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to transpose image observations from HWC to CHW format for PyTorch', 'stack the last k frames into a single observation using the FrameStack wrapper', 'warp environment frames to 84x84 grayscale using the WarpFrame observation wrapper', 'train a PPO agent on an Atari environment using multiple actors and learner threads', 'test a trained Atari agent by running episodes and logging average returns', 'create a convolutional neural network with optional LSTM for Atari frame-based RL', 'compute the policy gradient loss from logits, actions, and advantages', 'create a DeepMind-wrapped Atari gym environment with frame stacking and PyTorch tensors', 'run the polybeast reinforcement learning agent with learner and environment processes via CLI', 'run the polybeast environment process with a given actor id and flags in a forked process', 'run the polybeast learner process with parsed command line flags in the main process', 'review the main function that parses args and spawns multiprocessing environment and learner processes', 'summarize the polybeast entry point that coordinates learner and environment via multiprocessing', 'run the polybeast environment server with multiple Atari environment processes using unix pipes', 'create a wrapped Atari environment using DeepMind wrappers with frame stacking and PyTorch formatting', 'serve an Atari or Mock environment over a libtorchbeast server at a given address', 'review the Env mock class that provides reset and step methods returning numpy arrays', 'refactor the main function to spawn multiple daemon processes for parallel environment serving', 'train a PolyBeast RL agent using the PyTorch Scalable Agent with configurable actors and learning steps', 'run a forward pass through the Net model to get action, policy logits, and baseline outputs', 'compute the entropy loss as the negative entropy of the policy from logits', 'compute the baseline loss as half the sum of squared advantages']
```

Usage

```
{'train_polybeast_agent': 'train a PolyBeast RL agent using the PyTorch Scalable Agent with configurable actors and learning steps', 'run_net_forward_pass': 'run a forward pass through the Net model to get action, policy logits, and baseline outputs', 'compute_policy_gradient_loss': 'compute the policy gradient loss using target policy logits, actions, and advantages', 'compute_entropy_loss': 'compute the entropy loss as the negative entropy of the policy from logits', 'compute_baseline_loss': 'compute the baseline loss as half the sum of squared advantages'}
```

