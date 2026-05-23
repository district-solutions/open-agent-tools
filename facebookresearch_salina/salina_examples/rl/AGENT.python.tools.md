# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/atari_wrappers.py

Prompts

```
['create an Atari gym environment with NoopResetEnv and MaxAndSkipEnv wrappers applied', 'configure an Atari environment with DeepMind-style wrappers including frame stacking and reward clipping', 'wrap a gym environment to convert image observation shape to PyTorch channel-first format', 'stack the last k frames of an Atari environment into a single observation for temporal context', 'warp Atari frames to 84x84 grayscale images as done in the DeepMind Nature paper']
```

Usage

```
{'make_atari_env': 'create an Atari gym environment with NoopResetEnv and MaxAndSkipEnv wrappers applied', 'wrap_deepmind_env': 'configure an Atari environment with DeepMind-style wrappers including frame stacking and reward clipping', 'wrap_pytorch_env': 'wrap a gym environment to convert image observation shape to PyTorch channel-first format', 'use_FrameStack_wrapper': 'stack the last k frames of an Atari environment into a single observation for temporal context', 'use_WarpFrame_wrapper': 'warp Atari frames to 84x84 grayscale images as done in the DeepMind Nature paper'}
```

