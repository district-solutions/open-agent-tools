# Agent Python Tools

- repo: google-deepmind/discorl
- repo_uri: https://github.com/google-deepmind/disco_rl

## File: google-deepmind_discorl/disco_rl/environments/base.py

Prompts

```
['implement a subclass of Environment that overrides step to advance environment state given actions', 'implement a subclass of Environment that overrides reset to initialize episodes with an RNG key', 'implement a subclass of Environment that overrides single_observation_spec to return observation type specs', 'implement a subclass of Environment that overrides single_action_spec to return action type specs', 'call batched_action_spec on an Environment subclass to get the action spec broadcast across the batch size', 'create a SingleStreamCatch environment with config settings for rows, columns, and random seed', 'run a step on the SingleStreamCatch environment by passing an action integer to move the paddle', 'reset the SingleStreamCatch environment to start a new episode with a randomized ball position', 'build a batched CatchEnvironment wrapping multiple SingleStreamCatch instances with a specified batch size', 'get the default ConfigDict for CatchEnvironment with 8x8 grid and random seed 1', 'create a CatchJittableEnvironment with a given batch size and env_settings ConfigDict', 'get the default ConfigDict for the Catch environment with rows and columns set to 8', 'run a step on _SingleStreamCatch to advance the ball and move the paddle by action', 'render the current Catch environment state as a JAX array grid showing ball and paddle positions', 'check if the Catch state is terminal and compute the reward based on ball and paddle alignment']
```

Usage

```
{'implement_environment_step': 'implement a subclass of Environment that overrides step to advance environment state given actions', 'implement_environment_reset': 'implement a subclass of Environment that overrides reset to initialize episodes with an RNG key', 'implement_environment_observation_spec': 'implement a subclass of Environment that overrides single_observation_spec to return observation type specs', 'implement_environment_action_spec': 'implement a subclass of Environment that overrides single_action_spec to return action type specs', 'use_batched_action_spec': 'call batched_action_spec on an Environment subclass to get the action spec broadcast across the batch size'}
```

## File: google-deepmind_discorl/disco_rl/environments/catch.py

Prompts

```
['implement a subclass of Environment that overrides step to advance environment state given actions', 'implement a subclass of Environment that overrides reset to initialize episodes with an RNG key', 'implement a subclass of Environment that overrides single_observation_spec to return observation type specs', 'implement a subclass of Environment that overrides single_action_spec to return action type specs', 'call batched_action_spec on an Environment subclass to get the action spec broadcast across the batch size', 'create a SingleStreamCatch environment with config settings for rows, columns, and random seed', 'run a step on the SingleStreamCatch environment by passing an action integer to move the paddle', 'reset the SingleStreamCatch environment to start a new episode with a randomized ball position', 'build a batched CatchEnvironment wrapping multiple SingleStreamCatch instances with a specified batch size', 'get the default ConfigDict for CatchEnvironment with 8x8 grid and random seed 1', 'create a CatchJittableEnvironment with a given batch size and env_settings ConfigDict', 'get the default ConfigDict for the Catch environment with rows and columns set to 8', 'run a step on _SingleStreamCatch to advance the ball and move the paddle by action', 'render the current Catch environment state as a JAX array grid showing ball and paddle positions', 'check if the Catch state is terminal and compute the reward based on ball and paddle alignment']
```

Usage

```
{'create_SingleStreamCatch_env': 'create a SingleStreamCatch environment with config settings for rows, columns, and random seed', 'run_SingleStreamCatch_step': 'run a step on the SingleStreamCatch environment by passing an action integer to move the paddle', 'reset_SingleStreamCatch_episode': 'reset the SingleStreamCatch environment to start a new episode with a randomized ball position', 'build_CatchEnvironment_batched': 'build a batched CatchEnvironment wrapping multiple SingleStreamCatch instances with a specified batch size', 'get_config_default': 'get the default ConfigDict for CatchEnvironment with 8x8 grid and random seed 1'}
```

## File: google-deepmind_discorl/disco_rl/environments/jittable_envs.py

Prompts

```
['implement a subclass of Environment that overrides step to advance environment state given actions', 'implement a subclass of Environment that overrides reset to initialize episodes with an RNG key', 'implement a subclass of Environment that overrides single_observation_spec to return observation type specs', 'implement a subclass of Environment that overrides single_action_spec to return action type specs', 'call batched_action_spec on an Environment subclass to get the action spec broadcast across the batch size', 'create a SingleStreamCatch environment with config settings for rows, columns, and random seed', 'run a step on the SingleStreamCatch environment by passing an action integer to move the paddle', 'reset the SingleStreamCatch environment to start a new episode with a randomized ball position', 'build a batched CatchEnvironment wrapping multiple SingleStreamCatch instances with a specified batch size', 'get the default ConfigDict for CatchEnvironment with 8x8 grid and random seed 1', 'create a CatchJittableEnvironment with a given batch size and env_settings ConfigDict', 'get the default ConfigDict for the Catch environment with rows and columns set to 8', 'run a step on _SingleStreamCatch to advance the ball and move the paddle by action', 'render the current Catch environment state as a JAX array grid showing ball and paddle positions', 'check if the Catch state is terminal and compute the reward based on ball and paddle alignment']
```

Usage

```
{'create_catch_jittable_environment': 'create a CatchJittableEnvironment with a given batch size and env_settings ConfigDict', 'get_catch_config': 'get the default ConfigDict for the Catch environment with rows and columns set to 8', 'run_single_stream_catch_step': 'run a step on _SingleStreamCatch to advance the ball and move the paddle by action', 'render_catch_state': 'render the current Catch environment state as a JAX array grid showing ball and paddle positions', 'check_catch_terminal_reward': 'check if the Catch state is terminal and compute the reward based on ball and paddle alignment'}
```

