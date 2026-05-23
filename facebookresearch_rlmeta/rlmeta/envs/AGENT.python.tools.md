# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/rlmeta/envs/atari_wrapper.py

Prompts

```
['create an Atari environment with preprocessing, frame stacking, and reward clipping for a given game', 'build an Atari environment with sticky actions enabled by setting repeat action probability to 0.25', 'create an AtariWrapperFactory instance to produce multiple Atari environments with shared configuration', 'test the Atari environment by verifying that frame stacking wraps observations with the specified number of frames', 'review the AtariPreprocessing wrapper configuration including screen size, grayscale, and terminal on life loss settings', 'create a subclass of Env that implements reset, step, and close methods for a custom RL environment', 'implement the reset method in an Env subclass to initialize state and return a TimeStep', 'implement the step method in an Env subclass to apply an action and return the resulting TimeStep', 'implement the close method in an Env subclass to release environment resources', 'create an EnvFactory instance to instantiate Env subclasses with configurable constructor arguments', 'create a GymWrapper instance wrapping a gym environment with an optional observation function', 'reset the GymWrapper environment with an optional seed and return a TimeStep', 'step the GymWrapper environment with an Action and return the resulting TimeStep', 'close the underlying gym environment through the GymWrapper', 'review the GymWrapper action_space, observation_space, reward_range, and metadata properties']
```

Usage

```
{'create_atari_env': 'create an Atari environment with preprocessing, frame stacking, and reward clipping for a given game', 'build_atari_env_with_sticky_actions': 'build an Atari environment with sticky actions enabled by setting repeat action probability to 0.25', 'create_atari_wrapper_factory': 'create an AtariWrapperFactory instance to produce multiple Atari environments with shared configuration', 'test_atari_env_frame_stacking': 'test the Atari environment by verifying that frame stacking wraps observations with the specified number of frames', 'review_atari_preprocessing': 'review the AtariPreprocessing wrapper configuration including screen size, grayscale, and terminal on life loss settings'}
```

## File: facebookresearch_rlmeta/rlmeta/envs/env.py

Prompts

```
['create an Atari environment with preprocessing, frame stacking, and reward clipping for a given game', 'build an Atari environment with sticky actions enabled by setting repeat action probability to 0.25', 'create an AtariWrapperFactory instance to produce multiple Atari environments with shared configuration', 'test the Atari environment by verifying that frame stacking wraps observations with the specified number of frames', 'review the AtariPreprocessing wrapper configuration including screen size, grayscale, and terminal on life loss settings', 'create a subclass of Env that implements reset, step, and close methods for a custom RL environment', 'implement the reset method in an Env subclass to initialize state and return a TimeStep', 'implement the step method in an Env subclass to apply an action and return the resulting TimeStep', 'implement the close method in an Env subclass to release environment resources', 'create an EnvFactory instance to instantiate Env subclasses with configurable constructor arguments', 'create a GymWrapper instance wrapping a gym environment with an optional observation function', 'reset the GymWrapper environment with an optional seed and return a TimeStep', 'step the GymWrapper environment with an Action and return the resulting TimeStep', 'close the underlying gym environment through the GymWrapper', 'review the GymWrapper action_space, observation_space, reward_range, and metadata properties']
```

Usage

```
{'create_env_subclass': 'create a subclass of Env that implements reset, step, and close methods for a custom RL environment', 'implement_env_reset': 'implement the reset method in an Env subclass to initialize state and return a TimeStep', 'implement_env_step': 'implement the step method in an Env subclass to apply an action and return the resulting TimeStep', 'implement_env_close': 'implement the close method in an Env subclass to release environment resources', 'use_envfactory': 'create an EnvFactory instance to instantiate Env subclasses with configurable constructor arguments'}
```

## File: facebookresearch_rlmeta/rlmeta/envs/gym_wrapper.py

Prompts

```
['create an Atari environment with preprocessing, frame stacking, and reward clipping for a given game', 'build an Atari environment with sticky actions enabled by setting repeat action probability to 0.25', 'create an AtariWrapperFactory instance to produce multiple Atari environments with shared configuration', 'test the Atari environment by verifying that frame stacking wraps observations with the specified number of frames', 'review the AtariPreprocessing wrapper configuration including screen size, grayscale, and terminal on life loss settings', 'create a subclass of Env that implements reset, step, and close methods for a custom RL environment', 'implement the reset method in an Env subclass to initialize state and return a TimeStep', 'implement the step method in an Env subclass to apply an action and return the resulting TimeStep', 'implement the close method in an Env subclass to release environment resources', 'create an EnvFactory instance to instantiate Env subclasses with configurable constructor arguments', 'create a GymWrapper instance wrapping a gym environment with an optional observation function', 'reset the GymWrapper environment with an optional seed and return a TimeStep', 'step the GymWrapper environment with an Action and return the resulting TimeStep', 'close the underlying gym environment through the GymWrapper', 'review the GymWrapper action_space, observation_space, reward_range, and metadata properties']
```

Usage

```
{'create_GymWrapper': 'create a GymWrapper instance wrapping a gym environment with an optional observation function', 'reset_GymWrapper': 'reset the GymWrapper environment with an optional seed and return a TimeStep', 'step_GymWrapper': 'step the GymWrapper environment with an Action and return the resulting TimeStep', 'close_GymWrapper': 'close the underlying gym environment through the GymWrapper', 'review_GymWrapper_properties': 'review the GymWrapper action_space, observation_space, reward_range, and metadata properties'}
```

