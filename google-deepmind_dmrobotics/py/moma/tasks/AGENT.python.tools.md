# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/moma/tasks/run_loop.py

Prompts

```
['run an agent in a DM-env environment with observers for up to max_steps', 'start a new episode by resetting the environment and validating the first timestep', 'fix a timestep by filling in missing reward or discount values from the environment spec', 'notify all observers of episode begin, step, and end events during the run loop', 'ensure an agent action contains no NaN values before stepping the environment', 'test that run_loop.run sends agent actions to the environment in the correct order across episodes', 'test that run_loop.run delivers FIRST, MID, LAST timestep types to the agent in sequence', 'test that run_loop.run notifies observers on begin_episode, step, and end_episode callbacks', 'review the SpyEnv mock environment class that cycles through FIRST, MID, LAST step types for testing', 'review the SpyObserver class that records begin_episode, step, and end_episode notifications for verification']
```

Usage

```
{'run_agent_in_environment': 'run an agent in a DM-env environment with observers for up to max_steps', 'start_new_episode': 'start a new episode by resetting the environment and validating the first timestep', 'fix_timestep_reward_discount': 'fix a timestep by filling in missing reward or discount values from the environment spec', 'observe_episode_lifecycle': 'notify all observers of episode begin, step, and end events during the run loop', 'ensure_no_nans_in_action': 'ensure an agent action contains no NaN values before stepping the environment'}
```

## File: google-deepmind_dmrobotics/py/moma/tasks/run_loop_test.py

Prompts

```
['run an agent in a DM-env environment with observers for up to max_steps', 'start a new episode by resetting the environment and validating the first timestep', 'fix a timestep by filling in missing reward or discount values from the environment spec', 'notify all observers of episode begin, step, and end events during the run loop', 'ensure an agent action contains no NaN values before stepping the environment', 'test that run_loop.run sends agent actions to the environment in the correct order across episodes', 'test that run_loop.run delivers FIRST, MID, LAST timestep types to the agent in sequence', 'test that run_loop.run notifies observers on begin_episode, step, and end_episode callbacks', 'review the SpyEnv mock environment class that cycles through FIRST, MID, LAST step types for testing', 'review the SpyObserver class that records begin_episode, step, and end_episode notifications for verification']
```

Usage

```
{'test_run_loop_actions': 'test that run_loop.run sends agent actions to the environment in the correct order across episodes', 'test_run_loop_timesteps': 'test that run_loop.run delivers FIRST, MID, LAST timestep types to the agent in sequence', 'test_run_loop_observers': 'test that run_loop.run notifies observers on begin_episode, step, and end_episode callbacks', 'review_spyenv': 'review the SpyEnv mock environment class that cycles through FIRST, MID, LAST step types for testing', 'review_spyobserver': 'review the SpyObserver class that records begin_episode, step, and end_episode notifications for verification'}
```

