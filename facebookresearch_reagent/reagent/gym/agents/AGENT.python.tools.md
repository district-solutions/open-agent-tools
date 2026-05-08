# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/agents/agent.py

Prompts

```
['create an Agent for a gym environment with an optional policy or random fallback', 'create an Agent for a gym environment using a prebuilt serving policy', 'act on a single observation and return the extracted action with log probability', 'call the post transition callback after an environment step with a Transition object', 'call the post episode callback after an episode ends with a Trajectory and info dict', 'create a post-step function that adds transitions to a replay buffer for a gym environment', 'build a replay buffer inserter to log experience transitions after each environment step', 'test the add_replay_buffer_post_step function with a mock gym environment and replay buffer', 'review the add_replay_buffer_post_step function and its closure-based post-step return pattern', 'refactor the replay buffer inserter logic to support custom preprocessing before storing transitions']
```

Usage

```
{'create_agent_for_env': 'create an Agent for a gym environment with an optional policy or random fallback', 'create_agent_with_serving_policy': 'create an Agent for a gym environment using a prebuilt serving policy', 'act_on_observation': 'act on a single observation and return the extracted action with log probability', 'post_step_callback': 'call the post transition callback after an environment step with a Transition object', 'post_episode_callback': 'call the post episode callback after an episode ends with a Trajectory and info dict'}
```

## File: facebookresearch_reagent/reagent/gym/agents/post_step.py

Prompts

```
['create an Agent for a gym environment with an optional policy or random fallback', 'create an Agent for a gym environment using a prebuilt serving policy', 'act on a single observation and return the extracted action with log probability', 'call the post transition callback after an environment step with a Transition object', 'call the post episode callback after an episode ends with a Trajectory and info dict', 'create a post-step function that adds transitions to a replay buffer for a gym environment', 'build a replay buffer inserter to log experience transitions after each environment step', 'test the add_replay_buffer_post_step function with a mock gym environment and replay buffer', 'review the add_replay_buffer_post_step function and its closure-based post-step return pattern', 'refactor the replay buffer inserter logic to support custom preprocessing before storing transitions']
```

Usage

```
{'create_replay_buffer_post_step': 'create a post-step function that adds transitions to a replay buffer for a gym environment', 'build_rl_experience_logger': 'build a replay buffer inserter to log experience transitions after each environment step', 'test_add_replay_buffer_post_step': 'test the add_replay_buffer_post_step function with a mock gym environment and replay buffer', 'review_add_replay_buffer_post_step': 'review the add_replay_buffer_post_step function and its closure-based post-step return pattern', 'refactor_replay_buffer_inserter': 'refactor the replay buffer inserter logic to support custom preprocessing before storing transitions'}
```

