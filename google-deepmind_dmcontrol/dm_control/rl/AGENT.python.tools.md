# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/rl/control.py

Prompts

```
['create a physics-based reinforcement learning Environment with a custom Physics and Task instance', 'step the Environment with an action array and return the resulting TimeStep', 'flatten multiple observation arrays into a single concatenated numpy array', 'compute the number of physics timesteps per control timestep given both durations', 'reset the Environment to start a new episode and return the first TimeStep', 'test the dm_control Environment class by running EnvironmentTest with mocked physics and task', 'test the Environment timeout behavior with parameterized physics and control timestep values', 'test the compute_n_steps function with parameterized control and physics timestep pairs', 'test the Environment flat_observation feature that concatenates multimodal observations into a single array', 'test the Environment control_timestep calculation derived from physics timestep and n_sub_steps']
```

Usage

```
{'create_environment': 'create a physics-based reinforcement learning Environment with a custom Physics and Task instance', 'step_environment': 'step the Environment with an action array and return the resulting TimeStep', 'flatten_observation': 'flatten multiple observation arrays into a single concatenated numpy array', 'compute_n_steps': 'compute the number of physics timesteps per control timestep given both durations', 'reset_environment': 'reset the Environment to start a new episode and return the first TimeStep'}
```

## File: google-deepmind_dmcontrol/dm_control/rl/control_test.py

Prompts

```
['create a physics-based reinforcement learning Environment with a custom Physics and Task instance', 'step the Environment with an action array and return the resulting TimeStep', 'flatten multiple observation arrays into a single concatenated numpy array', 'compute the number of physics timesteps per control timestep given both durations', 'reset the Environment to start a new episode and return the first TimeStep', 'test the dm_control Environment class by running EnvironmentTest with mocked physics and task', 'test the Environment timeout behavior with parameterized physics and control timestep values', 'test the compute_n_steps function with parameterized control and physics timestep pairs', 'test the Environment flat_observation feature that concatenates multimodal observations into a single array', 'test the Environment control_timestep calculation derived from physics timestep and n_sub_steps']
```

Usage

```
{'test_control_environment': 'test the dm_control Environment class by running EnvironmentTest with mocked physics and task', 'test_environment_timeout': 'test the Environment timeout behavior with parameterized physics and control timestep values', 'test_compute_n_steps': 'test the compute_n_steps function with parameterized control and physics timestep pairs', 'test_flatten_observations': 'test the Environment flat_observation feature that concatenates multimodal observations into a single array', 'test_control_timestep': 'test the Environment control_timestep calculation derived from physics timestep and n_sub_steps'}
```

