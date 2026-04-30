# Agent Python Tools

- repo: huggingface/candle
- repo_uri: https://github.com/huggingface/candle

## File: huggingface_candle/candle-examples/examples/reinforcement-learning/atari_wrappers.py

Prompts

```
['wrap a gymnasium Atari environment with DeepMind-style preprocessing wrappers including frame skipping and reward clipping', 'create a factory thunk that builds a single wrapped Atari environment with a given seed and rank', 'create a vectorized subprocess environment for parallel Atari training with a specified number of processes', 'build a vectorized environment that runs multiple gym environments in separate subprocesses for parallel sampling', 'create a gymnasium wrapper that stacks k consecutive frames across the channel axis for temporal observation']
```

Usage

```
{'wrap_deepmind': 'wrap a gymnasium Atari environment with DeepMind-style preprocessing wrappers including frame skipping and reward clipping', 'make_env': 'create a factory thunk that builds a single wrapped Atari environment with a given seed and rank', 'make': 'create a vectorized subprocess environment for parallel Atari training with a specified number of processes', 'SubprocVecEnv': 'build a vectorized environment that runs multiple gym environments in separate subprocesses for parallel sampling', 'FrameStack': 'create a gymnasium wrapper that stacks k consecutive frames across the channel axis for temporal observation'}
```

