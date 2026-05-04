# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/utils/timing/training_duration_distribution.py

Prompts

```
['create a PerExampleGaussianDurationDistribution to compute training duration scaled by number of examples', 'create a PerUserGaussianDurationDistribution to sample per-user training duration from a bounded Gaussian', 'create a PerUserHalfNormalDurationDistribution to sample per-user training duration from a half-normal distribution', 'create a PerUserUniformDurationDistribution to sample per-user training duration from a uniform distribution', 'create a DurationDistributionFromList to return predetermined training durations from a fixed list for testing', 'estimate training time for both SyncFL and AsyncFL given users, rounds, epochs, and a duration distribution', 'calculate the total synchronous federated learning training time accounting for straggler effects per round', 'compute the maximum completion time for a single FL round to model the straggler effect', 'calculate the total asynchronous federated learning training time assuming clients start at a linear rate', 'element-wise sum two lists of floats to compute training end times from start times and durations']
```

Usage

```
{'create_per_example_gaussian_duration': 'create a PerExampleGaussianDurationDistribution to compute training duration scaled by number of examples', 'create_per_user_gaussian_duration': 'create a PerUserGaussianDurationDistribution to sample per-user training duration from a bounded Gaussian', 'create_per_user_half_normal_duration': 'create a PerUserHalfNormalDurationDistribution to sample per-user training duration from a half-normal distribution', 'create_per_user_uniform_duration': 'create a PerUserUniformDurationDistribution to sample per-user training duration from a uniform distribution', 'create_duration_from_list': 'create a DurationDistributionFromList to return predetermined training durations from a fixed list for testing'}
```

## File: facebookresearch_flsim/flsim/utils/timing/training_time_estimator.py

Prompts

```
['create a PerExampleGaussianDurationDistribution to compute training duration scaled by number of examples', 'create a PerUserGaussianDurationDistribution to sample per-user training duration from a bounded Gaussian', 'create a PerUserHalfNormalDurationDistribution to sample per-user training duration from a half-normal distribution', 'create a PerUserUniformDurationDistribution to sample per-user training duration from a uniform distribution', 'create a DurationDistributionFromList to return predetermined training durations from a fixed list for testing', 'estimate training time for both SyncFL and AsyncFL given users, rounds, epochs, and a duration distribution', 'calculate the total synchronous federated learning training time accounting for straggler effects per round', 'compute the maximum completion time for a single FL round to model the straggler effect', 'calculate the total asynchronous federated learning training time assuming clients start at a linear rate', 'element-wise sum two lists of floats to compute training end times from start times and durations']
```

Usage

```
{'get_training_time': 'estimate training time for both SyncFL and AsyncFL given users, rounds, epochs, and a duration distribution', 'SyncTrainingTimeEstimator_training_time': 'calculate the total synchronous federated learning training time accounting for straggler effects per round', 'SyncTrainingTimeEstimator_round_completion_time': 'compute the maximum completion time for a single FL round to model the straggler effect', 'AsyncTrainingTimeEstimator_training_time': 'calculate the total asynchronous federated learning training time assuming clients start at a linear rate', 'AsyncTrainingTimeEstimator_list_sum': 'element-wise sum two lists of floats to compute training end times from start times and durations'}
```

