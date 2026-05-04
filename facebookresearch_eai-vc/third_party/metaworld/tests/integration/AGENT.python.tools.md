# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/metaworld/tests/integration/test_memory_usage.py

Prompts

```
['build a Meta-World environment, step it 10 times with 150 max path length, then close it', 'build and step all Meta-World environment classes in a list sequentially', 'test that each Meta-World V1 environment uses less than 250MB of memory', 'test that the average memory usage across all V1 environments is under 60MB per env', 'test that instantiating the reach-v1 environment uses less than 250MB of memory', 'test all ML1 benchmark environments by verifying train and test task uniqueness and environment stability', 'test the ML10 benchmark suite by validating train and test environment task randomization and positions', 'test the ML45 benchmark suite by checking train and test environment observations and target positions', 'test the MT10 multitask benchmark by verifying train environment task uniqueness with no test tasks', 'test the MT50 multitask benchmark by validating 50 unique environments and their target positions', 'test all Meta-World goal-hidden V2 environments for consistent target positions across resets and seeds', 'test all Meta-World goal-observable V2 environments for consistent target positions across resets and seeds', 'test that goal-observable environments produce matching goals with same seed and different goals with different seeds', 'test that goal-hidden environments produce matching hidden targets with same seed and different targets with different seeds', 'run pytest on test_single_goal_envs.py to validate Meta-World goal environment seeding and target consistency']
```

Usage

```
{'build_and_step': 'build a Meta-World environment, step it 10 times with 150 max path length, then close it', 'build_and_step_all': 'build and step all Meta-World environment classes in a list sequentially', 'test_max_memory_usage': 'test that each Meta-World V1 environment uses less than 250MB of memory', 'test_avg_memory_usage': 'test that the average memory usage across all V1 environments is under 60MB per env', 'test_from_task_memory_usage': 'test that instantiating the reach-v1 environment uses less than 250MB of memory'}
```

## File: facebookresearch_eai-vc/third_party/metaworld/tests/integration/test_new_api.py

Prompts

```
['build a Meta-World environment, step it 10 times with 150 max path length, then close it', 'build and step all Meta-World environment classes in a list sequentially', 'test that each Meta-World V1 environment uses less than 250MB of memory', 'test that the average memory usage across all V1 environments is under 60MB per env', 'test that instantiating the reach-v1 environment uses less than 250MB of memory', 'test all ML1 benchmark environments by verifying train and test task uniqueness and environment stability', 'test the ML10 benchmark suite by validating train and test environment task randomization and positions', 'test the ML45 benchmark suite by checking train and test environment observations and target positions', 'test the MT10 multitask benchmark by verifying train environment task uniqueness with no test tasks', 'test the MT50 multitask benchmark by validating 50 unique environments and their target positions', 'test all Meta-World goal-hidden V2 environments for consistent target positions across resets and seeds', 'test all Meta-World goal-observable V2 environments for consistent target positions across resets and seeds', 'test that goal-observable environments produce matching goals with same seed and different goals with different seeds', 'test that goal-hidden environments produce matching hidden targets with same seed and different targets with different seeds', 'run pytest on test_single_goal_envs.py to validate Meta-World goal environment seeding and target consistency']
```

Usage

```
{'test_ml1_benchmark': 'test all ML1 benchmark environments by verifying train and test task uniqueness and environment stability', 'test_ml10_benchmark': 'test the ML10 benchmark suite by validating train and test environment task randomization and positions', 'test_ml45_benchmark': 'test the ML45 benchmark suite by checking train and test environment observations and target positions', 'test_mt10_benchmark': 'test the MT10 multitask benchmark by verifying train environment task uniqueness with no test tasks', 'test_mt50_benchmark': 'test the MT50 multitask benchmark by validating 50 unique environments and their target positions'}
```

## File: facebookresearch_eai-vc/third_party/metaworld/tests/integration/test_single_goal_envs.py

Prompts

```
['build a Meta-World environment, step it 10 times with 150 max path length, then close it', 'build and step all Meta-World environment classes in a list sequentially', 'test that each Meta-World V1 environment uses less than 250MB of memory', 'test that the average memory usage across all V1 environments is under 60MB per env', 'test that instantiating the reach-v1 environment uses less than 250MB of memory', 'test all ML1 benchmark environments by verifying train and test task uniqueness and environment stability', 'test the ML10 benchmark suite by validating train and test environment task randomization and positions', 'test the ML45 benchmark suite by checking train and test environment observations and target positions', 'test the MT10 multitask benchmark by verifying train environment task uniqueness with no test tasks', 'test the MT50 multitask benchmark by validating 50 unique environments and their target positions', 'test all Meta-World goal-hidden V2 environments for consistent target positions across resets and seeds', 'test all Meta-World goal-observable V2 environments for consistent target positions across resets and seeds', 'test that goal-observable environments produce matching goals with same seed and different goals with different seeds', 'test that goal-hidden environments produce matching hidden targets with same seed and different targets with different seeds', 'run pytest on test_single_goal_envs.py to validate Meta-World goal environment seeding and target consistency']
```

Usage

```
{'test_hidden_goal_envs': 'test all Meta-World goal-hidden V2 environments for consistent target positions across resets and seeds', 'test_observable_goal_envs': 'test all Meta-World goal-observable V2 environments for consistent target positions across resets and seeds', 'test_seeding_observable': 'test that goal-observable environments produce matching goals with same seed and different goals with different seeds', 'test_seeding_hidden': 'test that goal-hidden environments produce matching hidden targets with same seed and different targets with different seeds', 'run_test_single_goal_envs': 'run pytest on test_single_goal_envs.py to validate Meta-World goal environment seeding and target consistency'}
```

