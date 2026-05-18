# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/agent/common/envs/tasks.py

Prompts

```
['create a MiniHack or NLE environment instance from command-line flags with optional CounterWrapper', 'check if a given environment class is a subclass of MiniHack', 'lookup an environment class by string key from the ENVS registry dictionary', 'create a MiniHack environment wrapped with CounterWrapper for state tracking', 'create an NLE environment like NetHackStaircase with max_episode_steps and character settings', 'create a CounterWrapper around a gym environment to track state visits using coordinates or ones mode', 'create a CropWrapper around a gym environment to crop TTY observations to a fixed window around the cursor', 'create a PrevWrapper around a gym environment to inject the previous reward and action into observations', 'create a CachedEnvWrapper with multiple environments and background threads to prefetch resets for faster episode turnover', 'review the CounterWrapper, CropWrapper, PrevWrapper, and CachedEnvWrapper classes to understand their Gym wrapper behavior and observation modifications']
```

Usage

```
{'create_env_from_flags': 'create a MiniHack or NLE environment instance from command-line flags with optional CounterWrapper', 'check_env_is_minihack': 'check if a given environment class is a subclass of MiniHack', 'lookup_env_class': 'lookup an environment class by string key from the ENVS registry dictionary', 'create_env_with_counter': 'create a MiniHack environment wrapped with CounterWrapper for state tracking', 'create_nle_env': 'create an NLE environment like NetHackStaircase with max_episode_steps and character settings'}
```

## File: facebookresearch_minihack/minihack/agent/common/envs/wrapper.py

Prompts

```
['create a MiniHack or NLE environment instance from command-line flags with optional CounterWrapper', 'check if a given environment class is a subclass of MiniHack', 'lookup an environment class by string key from the ENVS registry dictionary', 'create a MiniHack environment wrapped with CounterWrapper for state tracking', 'create an NLE environment like NetHackStaircase with max_episode_steps and character settings', 'create a CounterWrapper around a gym environment to track state visits using coordinates or ones mode', 'create a CropWrapper around a gym environment to crop TTY observations to a fixed window around the cursor', 'create a PrevWrapper around a gym environment to inject the previous reward and action into observations', 'create a CachedEnvWrapper with multiple environments and background threads to prefetch resets for faster episode turnover', 'review the CounterWrapper, CropWrapper, PrevWrapper, and CachedEnvWrapper classes to understand their Gym wrapper behavior and observation modifications']
```

Usage

```
{'create_counterwrapper': 'create a CounterWrapper around a gym environment to track state visits using coordinates or ones mode', 'create_cropwrapper': 'create a CropWrapper around a gym environment to crop TTY observations to a fixed window around the cursor', 'create_prevwrapper': 'create a PrevWrapper around a gym environment to inject the previous reward and action into observations', 'create_cachedenvwrapper': 'create a CachedEnvWrapper with multiple environments and background threads to prefetch resets for faster episode turnover', 'review_wrapper_classes': 'review the CounterWrapper, CropWrapper, PrevWrapper, and CachedEnvWrapper classes to understand their Gym wrapper behavior and observation modifications'}
```

