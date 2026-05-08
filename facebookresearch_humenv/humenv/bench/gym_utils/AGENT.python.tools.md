# Agent Python Tools

- repo: facebookresearch/humenv
- repo_uri: https://github.com/facebookresearch/humenv

## File: facebookresearch_humenv/humenv/bench/gym_utils/episodes.py

Prompts

```
['create an Episode object and initialise it with an observation and info dictionary', 'add a transition step with observation, reward, action, terminated, truncated, and info to an Episode', 'get the stored episode data as a dictionary of numpy arrays from an Episode object', 'create a CollectEpisodes object to track multiple ongoing episodes across a batch of parallel environments', 'retrieve the list of completed episodes and their returns and lengths from a CollectEpisodes object', 'run a rollout of an agent in a single gymnasium environment for a specified number of episodes', 'run a rollout of an agent in a vectorized gymnasium environment collecting episodes in parallel', 'run a rollout of an agent with an optional torch tensor context across episodes', 'review the rollout function that dispatches to single or parallel environment rollout strategies', 'test the single environment rollout function that collects returns and lengths per episode']
```

Usage

```
{'create_episode': 'create an Episode object and initialise it with an observation and info dictionary', 'add_step_to_episode': 'add a transition step with observation, reward, action, terminated, truncated, and info to an Episode', 'get_episode_data': 'get the stored episode data as a dictionary of numpy arrays from an Episode object', 'collect_episodes_batch': 'create a CollectEpisodes object to track multiple ongoing episodes across a batch of parallel environments', 'retrieve_completed_episodes': 'retrieve the list of completed episodes and their returns and lengths from a CollectEpisodes object'}
```

## File: facebookresearch_humenv/humenv/bench/gym_utils/rollouts.py

Prompts

```
['create an Episode object and initialise it with an observation and info dictionary', 'add a transition step with observation, reward, action, terminated, truncated, and info to an Episode', 'get the stored episode data as a dictionary of numpy arrays from an Episode object', 'create a CollectEpisodes object to track multiple ongoing episodes across a batch of parallel environments', 'retrieve the list of completed episodes and their returns and lengths from a CollectEpisodes object', 'run a rollout of an agent in a single gymnasium environment for a specified number of episodes', 'run a rollout of an agent in a vectorized gymnasium environment collecting episodes in parallel', 'run a rollout of an agent with an optional torch tensor context across episodes', 'review the rollout function that dispatches to single or parallel environment rollout strategies', 'test the single environment rollout function that collects returns and lengths per episode']
```

Usage

```
{'run_rollout_single_env': 'run a rollout of an agent in a single gymnasium environment for a specified number of episodes', 'run_rollout_parallel_env': 'run a rollout of an agent in a vectorized gymnasium environment collecting episodes in parallel', 'run_rollout_with_context': 'run a rollout of an agent with an optional torch tensor context across episodes', 'review_rollout_dispatch': 'review the rollout function that dispatches to single or parallel environment rollout strategies', 'test_single_env_rollout': 'test the single environment rollout function that collects returns and lengths per episode'}
```

