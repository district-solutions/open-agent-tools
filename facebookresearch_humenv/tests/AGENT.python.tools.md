# Agent Python Tools

- repo: facebookresearch/humenv
- repo_uri: https://github.com/facebookresearch/humenv

## File: facebookresearch_humenv/tests/test_collect_episode.py

Prompts

```
['test the rollout function with a single StepEnv and FakeAgent for episode collection', 'test the rollout function with SyncVectorEnv running multiple StepEnv instances in parallel', 'test the rollout function with AsyncVectorEnv running multiple StepEnv instances asynchronously', 'create a StepEnv gymnasium environment with configurable goal, horizon, and initial state', 'create a FakeAgent that returns constant action values for one or multiple environments', 'test HumEnv initialization with HeadstandReward and MoveAndRaiseArmsReward across Default, Fall, and DefaultAndFall state inits', 'test stepping HumEnv for 30 timesteps with random 69-dim actions and verify observations are returned', 'test HumEnv wrapped with FlattenObservation to ensure flattened observation space works correctly', 'review the test_initalization parametrized test function that validates HumEnv setup with multiple reward and state combinations', 'summarize the test_humenv module that tests HumEnv environment initialization and stepping with various reward functions', 'test the make_humenv function with parametrized num_envs, vectorization_mode, seed, and state_init configurations', 'run make_humenv with sync vectorization mode and FlattenObservation wrapper to create a parallel environment', 'run make_humenv with async vectorization mode to create a parallel environment for multiple agents', 'test the humenv environment reset and step loop with sampled actions across multiple environments', 'test humenv environment with Default or Fall state initialization and validate observation consistency']
```

Usage

```
{'test_single_env_rollout': 'test the rollout function with a single StepEnv and FakeAgent for episode collection', 'test_parallel_sync_env_rollout': 'test the rollout function with SyncVectorEnv running multiple StepEnv instances in parallel', 'test_parallel_async_env_rollout': 'test the rollout function with AsyncVectorEnv running multiple StepEnv instances asynchronously', 'create_StepEnv_gymnasium_env': 'create a StepEnv gymnasium environment with configurable goal, horizon, and initial state', 'create_FakeAgent_for_testing': 'create a FakeAgent that returns constant action values for one or multiple environments'}
```

## File: facebookresearch_humenv/tests/test_humenv.py

Prompts

```
['test the rollout function with a single StepEnv and FakeAgent for episode collection', 'test the rollout function with SyncVectorEnv running multiple StepEnv instances in parallel', 'test the rollout function with AsyncVectorEnv running multiple StepEnv instances asynchronously', 'create a StepEnv gymnasium environment with configurable goal, horizon, and initial state', 'create a FakeAgent that returns constant action values for one or multiple environments', 'test HumEnv initialization with HeadstandReward and MoveAndRaiseArmsReward across Default, Fall, and DefaultAndFall state inits', 'test stepping HumEnv for 30 timesteps with random 69-dim actions and verify observations are returned', 'test HumEnv wrapped with FlattenObservation to ensure flattened observation space works correctly', 'review the test_initalization parametrized test function that validates HumEnv setup with multiple reward and state combinations', 'summarize the test_humenv module that tests HumEnv environment initialization and stepping with various reward functions', 'test the make_humenv function with parametrized num_envs, vectorization_mode, seed, and state_init configurations', 'run make_humenv with sync vectorization mode and FlattenObservation wrapper to create a parallel environment', 'run make_humenv with async vectorization mode to create a parallel environment for multiple agents', 'test the humenv environment reset and step loop with sampled actions across multiple environments', 'test humenv environment with Default or Fall state initialization and validate observation consistency']
```

Usage

```
{'test_HumEnv_initialization': 'test HumEnv initialization with HeadstandReward and MoveAndRaiseArmsReward across Default, Fall, and DefaultAndFall state inits', 'test_HumEnv_step_loop': 'test stepping HumEnv for 30 timesteps with random 69-dim actions and verify observations are returned', 'test_HumEnv_with_FlattenObservation': 'test HumEnv wrapped with FlattenObservation to ensure flattened observation space works correctly', 'review_test_initalization': 'review the test_initalization parametrized test function that validates HumEnv setup with multiple reward and state combinations', 'summarize_test_humenv': 'summarize the test_humenv module that tests HumEnv environment initialization and stepping with various reward functions'}
```

## File: facebookresearch_humenv/tests/test_make_humenv.py

Prompts

```
['test the rollout function with a single StepEnv and FakeAgent for episode collection', 'test the rollout function with SyncVectorEnv running multiple StepEnv instances in parallel', 'test the rollout function with AsyncVectorEnv running multiple StepEnv instances asynchronously', 'create a StepEnv gymnasium environment with configurable goal, horizon, and initial state', 'create a FakeAgent that returns constant action values for one or multiple environments', 'test HumEnv initialization with HeadstandReward and MoveAndRaiseArmsReward across Default, Fall, and DefaultAndFall state inits', 'test stepping HumEnv for 30 timesteps with random 69-dim actions and verify observations are returned', 'test HumEnv wrapped with FlattenObservation to ensure flattened observation space works correctly', 'review the test_initalization parametrized test function that validates HumEnv setup with multiple reward and state combinations', 'summarize the test_humenv module that tests HumEnv environment initialization and stepping with various reward functions', 'test the make_humenv function with parametrized num_envs, vectorization_mode, seed, and state_init configurations', 'run make_humenv with sync vectorization mode and FlattenObservation wrapper to create a parallel environment', 'run make_humenv with async vectorization mode to create a parallel environment for multiple agents', 'test the humenv environment reset and step loop with sampled actions across multiple environments', 'test humenv environment with Default or Fall state initialization and validate observation consistency']
```

Usage

```
{'test_make_humenv': 'test the make_humenv function with parametrized num_envs, vectorization_mode, seed, and state_init configurations', 'run_make_humenv_sync': 'run make_humenv with sync vectorization mode and FlattenObservation wrapper to create a parallel environment', 'run_make_humenv_async': 'run make_humenv with async vectorization mode to create a parallel environment for multiple agents', 'test_humenv_reset_step': 'test the humenv environment reset and step loop with sampled actions across multiple environments', 'test_humenv_state_init': 'test humenv environment with Default or Fall state initialization and validate observation consistency'}
```

