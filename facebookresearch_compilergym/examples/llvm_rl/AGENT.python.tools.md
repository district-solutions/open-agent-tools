# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/llvm_rl/info.py

Prompts

```
['run the train command to summarize RL training logs with reward metrics and test results', 'run the test command to print test set results with instruction count and object size reduction', 'run the test command with latex formatting to output reduction metrics in dollar-sign notation', 'review the models_from_paths function to load Model objects from a list of log directory paths', 'summarize the train command output showing episodes, training time, and geomean rewards in a psql table', 'create a ClampedReward wrapper to clamp RL reward signals within a bounded range with optional leakiness', 'create an AutophaseNormalizedFeatures wrapper to normalize and clip LLVM observation features to the range 0 to 1', 'create a ConcatActionsHistogram wrapper to concatenate a histogram of previous actions to each observation', 'create an AutophaseActionSpace wrapper to constrain the LLVM action space to the 42 flags used in the Autophase paper', 'review the ClampedReward convert_reward method to understand how out-of-range rewards are clamped with leakiness']
```

Usage

```
{'run_train_summary': 'run the train command to summarize RL training logs with reward metrics and test results', 'run_test_summary': 'run the test command to print test set results with instruction count and object size reduction', 'run_test_latex': 'run the test command with latex formatting to output reduction metrics in dollar-sign notation', 'review_models_from_paths': 'review the models_from_paths function to load Model objects from a list of log directory paths', 'summarize_train_command': 'summarize the train command output showing episodes, training time, and geomean rewards in a psql table'}
```

## File: facebookresearch_compilergym/examples/llvm_rl/wrappers.py

Prompts

```
['run the train command to summarize RL training logs with reward metrics and test results', 'run the test command to print test set results with instruction count and object size reduction', 'run the test command with latex formatting to output reduction metrics in dollar-sign notation', 'review the models_from_paths function to load Model objects from a list of log directory paths', 'summarize the train command output showing episodes, training time, and geomean rewards in a psql table', 'create a ClampedReward wrapper to clamp RL reward signals within a bounded range with optional leakiness', 'create an AutophaseNormalizedFeatures wrapper to normalize and clip LLVM observation features to the range 0 to 1', 'create a ConcatActionsHistogram wrapper to concatenate a histogram of previous actions to each observation', 'create an AutophaseActionSpace wrapper to constrain the LLVM action space to the 42 flags used in the Autophase paper', 'review the ClampedReward convert_reward method to understand how out-of-range rewards are clamped with leakiness']
```

Usage

```
{'create_clamped_reward_wrapper': 'create a ClampedReward wrapper to clamp RL reward signals within a bounded range with optional leakiness', 'create_autophase_normalized_features_wrapper': 'create an AutophaseNormalizedFeatures wrapper to normalize and clip LLVM observation features to the range 0 to 1', 'create_concat_actions_histogram_wrapper': 'create a ConcatActionsHistogram wrapper to concatenate a histogram of previous actions to each observation', 'create_autophase_action_space_wrapper': 'create an AutophaseActionSpace wrapper to constrain the LLVM action space to the 42 flags used in the Autophase paper', 'review_clamped_reward_convert_reward': 'review the ClampedReward convert_reward method to understand how out-of-range rewards are clamped with leakiness'}
```

