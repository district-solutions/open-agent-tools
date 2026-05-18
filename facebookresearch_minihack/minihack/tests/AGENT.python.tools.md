# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/tests/test_envs.py

Prompts

```
['get all registered MiniHack environment IDs from the Gymnasium registry excluding skipped environments', 'run a random policy rollout for a given number of steps and return the final reward', 'convert an observation dictionary tty_chars array into a readable terminal screen string', 'compare two seeded Gymnasium environments step by step to verify identical rollout outputs', 'test that two MiniHack environments seeded with the same values produce identical observations and rewards', 'test the MiniHack environment works correctly when instantiated inside a multiprocessing subprocess', 'test the MiniHack environment works in the main process then again inside a subprocess', 'run a single step in a MiniHack-Room-15x15-v0 gym environment and return the done flag', 'review the TestEnvSubprocess class that parametrizes tests across fork and spawn multiprocessing contexts', 'summarize the START_METHODS list that filters available multiprocessing start methods for the current platform']
```

Usage

```
{'get_minihack_env_ids': 'get all registered MiniHack environment IDs from the Gymnasium registry excluding skipped environments', 'rollout_env': 'run a random policy rollout for a given number of steps and return the final reward', 'term_screen': 'convert an observation dictionary tty_chars array into a readable terminal screen string', 'compare_rollouts': 'compare two seeded Gymnasium environments step by step to verify identical rollout outputs', 'test_seed_rollout_seeded': 'test that two MiniHack environments seeded with the same values produce identical observations and rewards'}
```

## File: facebookresearch_minihack/minihack/tests/test_system.py

Prompts

```
['get all registered MiniHack environment IDs from the Gymnasium registry excluding skipped environments', 'run a random policy rollout for a given number of steps and return the final reward', 'convert an observation dictionary tty_chars array into a readable terminal screen string', 'compare two seeded Gymnasium environments step by step to verify identical rollout outputs', 'test that two MiniHack environments seeded with the same values produce identical observations and rewards', 'test the MiniHack environment works correctly when instantiated inside a multiprocessing subprocess', 'test the MiniHack environment works in the main process then again inside a subprocess', 'run a single step in a MiniHack-Room-15x15-v0 gym environment and return the done flag', 'review the TestEnvSubprocess class that parametrizes tests across fork and spawn multiprocessing contexts', 'summarize the START_METHODS list that filters available multiprocessing start methods for the current platform']
```

Usage

```
{'test_env_in_subprocess': 'test the MiniHack environment works correctly when instantiated inside a multiprocessing subprocess', 'test_env_before_and_in_subprocess': 'test the MiniHack environment works in the main process then again inside a subprocess', 'run_new_env_one_step': 'run a single step in a MiniHack-Room-15x15-v0 gym environment and return the done flag', 'review_TestEnvSubprocess': 'review the TestEnvSubprocess class that parametrizes tests across fork and spawn multiprocessing contexts', 'summarize_START_METHODS': 'summarize the START_METHODS list that filters available multiprocessing start methods for the current platform'}
```

