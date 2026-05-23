# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/utils/scripts/cb_benchmark/cb_benchmark_config.py

Prompts

```
['build a NeuralBandit policy learner and SquareCBExploration config for a contextual bandit environment', 'build a NeuralLinearBandit policy learner and UCBExploration config with a tunable alpha parameter', 'build a NeuralLinearBandit policy learner and ThompsonSamplingExploration config for a contextual bandit environment', 'build an offline evaluation config with no exploration for a contextual bandit environment', 'build a NeuralBandit policy learner and FastCBExploration config for a contextual bandit environment', 'run contextual bandit algorithms on UCI benchmark environments and save regret results to CSV', 'run online evaluation of a PearlAgent in an SLCBEnvironment over N steps and return cumulative regrets', 'train a PearlAgent on data collected by acting with a uniform random policy in an environment', 'run offline evaluation by training a NeuralBandit on uniform-policy data and evaluating regret over steps', 'run online evaluation by training a policy learner with exploration and collecting regret over T steps']
```

Usage

```
{'build_neural_squarecb_config': 'build a NeuralBandit policy learner and SquareCBExploration config for a contextual bandit environment', 'build_neural_lin_ucb_config': 'build a NeuralLinearBandit policy learner and UCBExploration config with a tunable alpha parameter', 'build_neural_lin_ts_config': 'build a NeuralLinearBandit policy learner and ThompsonSamplingExploration config for a contextual bandit environment', 'build_offline_eval_config': 'build an offline evaluation config with no exploration for a contextual bandit environment', 'build_neural_fastcb_config': 'build a NeuralBandit policy learner and FastCBExploration config for a contextual bandit environment'}
```

## File: facebookresearch_pearl/pearl/utils/scripts/cb_benchmark/run_cb_benchmarks.py

Prompts

```
['build a NeuralBandit policy learner and SquareCBExploration config for a contextual bandit environment', 'build a NeuralLinearBandit policy learner and UCBExploration config with a tunable alpha parameter', 'build a NeuralLinearBandit policy learner and ThompsonSamplingExploration config for a contextual bandit environment', 'build an offline evaluation config with no exploration for a contextual bandit environment', 'build a NeuralBandit policy learner and FastCBExploration config for a contextual bandit environment', 'run contextual bandit algorithms on UCI benchmark environments and save regret results to CSV', 'run online evaluation of a PearlAgent in an SLCBEnvironment over N steps and return cumulative regrets', 'train a PearlAgent on data collected by acting with a uniform random policy in an environment', 'run offline evaluation by training a NeuralBandit on uniform-policy data and evaluating regret over steps', 'run online evaluation by training a policy learner with exploration and collecting regret over T steps']
```

Usage

```
{'run_cb_benchmarks': 'run contextual bandit algorithms on UCI benchmark environments and save regret results to CSV', 'online_evaluation': 'run online evaluation of a PearlAgent in an SLCBEnvironment over N steps and return cumulative regrets', 'train_via_uniform_data': 'train a PearlAgent on data collected by acting with a uniform random policy in an environment', 'run_experiments_offline': 'run offline evaluation by training a NeuralBandit on uniform-policy data and evaluating regret over steps', 'run_experiments_online': 'run online evaluation by training a policy learner with exploration and collecting regret over T steps'}
```

