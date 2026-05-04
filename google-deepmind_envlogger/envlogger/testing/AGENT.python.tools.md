# Agent Python Tools

- repo: google-deepmind/envlogger
- repo_uri: https://github.com/google-deepmind/envlogger

## File: google-deepmind_envlogger/envlogger/testing/catch_env.py

Prompts

```
['create a Catch RL environment with configurable rows, columns, and random seed', 'reset the Catch environment to start a new episode with a randomized ball position', 'step the Catch environment with a discrete action to move the paddle left, right, or stay', 'get the BoundedArray observation spec describing the board shape and value range', 'get the DiscreteArray action spec with three available actions for paddle movement']
```

Usage

```
{'create_catch_environment': 'create a Catch RL environment with configurable rows, columns, and random seed', 'reset_catch_episode': 'reset the Catch environment to start a new episode with a randomized ball position', 'step_catch_action': 'step the Catch environment with a discrete action to move the paddle left, right, or stay', 'get_observation_spec': 'get the BoundedArray observation spec describing the board shape and value range', 'get_action_spec': 'get the DiscreteArray action spec with three available actions for paddle movement'}
```

