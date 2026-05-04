# Agent Python Tools

- repo: google-deepmind/ai-safety-gridworlds
- repo_uri: https://github.com/google-deepmind/ai-safety-gridworlds

## File: google-deepmind_ai-safety-gridworlds/ai_safety_gridworlds/demonstrations/demonstrations.py

Prompts

```
['get demonstrations for a named environment like boat_race or island_navigation', 'list all environment names that have available demonstrations', 'replay a demonstration by setting the seed and stepping through actions in sequence', 'access demonstration metadata including seed, episode_return, safety_performance, and terminates fields', 'check if a given environment name has demonstrations available before calling get_demonstrations', 'run the DemonstrationsTest suite to replay all environment demonstrations and verify returns', 'test that get_demonstrations raises ValueError for an unavailable environment name', 'test demonstrations across all environments by replaying action sequences and checking safety performance', 'run an action sequence in a gridworld environment and accumulate episode return', 'check the environment termination reason against INTERRUPTED or MAX_STEPS conditions']
```

Usage

```
{'get_demonstrations_for_environment': 'get demonstrations for a named environment like boat_race or island_navigation', 'list_environment_names': 'list all environment names that have available demonstrations', 'replay_demonstration_actions': 'replay a demonstration by setting the seed and stepping through actions in sequence', 'access_demonstration_metadata': 'access demonstration metadata including seed, episode_return, safety_performance, and terminates fields', 'check_environment_has_demonstrations': 'check if a given environment name has demonstrations available before calling get_demonstrations'}
```

## File: google-deepmind_ai-safety-gridworlds/ai_safety_gridworlds/demonstrations/demonstrations_test.py

Prompts

```
['get demonstrations for a named environment like boat_race or island_navigation', 'list all environment names that have available demonstrations', 'replay a demonstration by setting the seed and stepping through actions in sequence', 'access demonstration metadata including seed, episode_return, safety_performance, and terminates fields', 'check if a given environment name has demonstrations available before calling get_demonstrations', 'run the DemonstrationsTest suite to replay all environment demonstrations and verify returns', 'test that get_demonstrations raises ValueError for an unavailable environment name', 'test demonstrations across all environments by replaying action sequences and checking safety performance', 'run an action sequence in a gridworld environment and accumulate episode return', 'check the environment termination reason against INTERRUPTED or MAX_STEPS conditions']
```

Usage

```
{'run_demonstrations_test': 'run the DemonstrationsTest suite to replay all environment demonstrations and verify returns', 'test_get_demonstrations_unavailable': 'test that get_demonstrations raises ValueError for an unavailable environment name', 'test_demonstrations_parameterized': 'test demonstrations across all environments by replaying action sequences and checking safety performance', 'run_env_action_sequence': 'run an action sequence in a gridworld environment and accumulate episode return', 'check_termination_reason': 'check the environment termination reason against INTERRUPTED or MAX_STEPS conditions'}
```

