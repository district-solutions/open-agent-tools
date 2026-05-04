# Agent Python Tools

- repo: google-deepmind/dmnevis
- repo_uri: https://github.com/google-deepmind/dm_nevis

## File: google-deepmind_dmnevis/experiments_jax/experiment.py

Prompts

```
['run a launchpad benchmarking program using an ExperimentConfig with learner and stream settings', 'construct a typed ExperimentConfig from an ml_collections ConfigDict with stream and learner fields', 'create an ExperimentConfig dataclass with resume checkpoint path, stream config, and learner config', 'create a LearnerConfig dataclass with a MetaLearnerBuilderFn and ml_collections ConfigDict', 'create a StreamConfig dataclass with a stream constructor callable and keyword arguments mapping', 'run the BaselineTest parameterized test suite to verify experiment runs and finishes for all configs', 'test that experiment.run_program completes successfully given a config dict from finetuning_prev or finetuning_dknn', 'review the BaselineTest class and its parameterized test method for experiment validation', 'summarize the CONFIGS_TO_TEST list containing finetuning_learner and finetuning_dknn_learner test configurations', 'refactor the experiment test to add additional config modules or test cases to CONFIGS_TO_TEST']
```

Usage

```
{'run_experiment_program': 'run a launchpad benchmarking program using an ExperimentConfig with learner and stream settings', 'config_from_config_dict': 'construct a typed ExperimentConfig from an ml_collections ConfigDict with stream and learner fields', 'create_experiment_config': 'create an ExperimentConfig dataclass with resume checkpoint path, stream config, and learner config', 'create_learner_config': 'create a LearnerConfig dataclass with a MetaLearnerBuilderFn and ml_collections ConfigDict', 'create_stream_config': 'create a StreamConfig dataclass with a stream constructor callable and keyword arguments mapping'}
```

## File: google-deepmind_dmnevis/experiments_jax/experiment_test.py

Prompts

```
['run a launchpad benchmarking program using an ExperimentConfig with learner and stream settings', 'construct a typed ExperimentConfig from an ml_collections ConfigDict with stream and learner fields', 'create an ExperimentConfig dataclass with resume checkpoint path, stream config, and learner config', 'create a LearnerConfig dataclass with a MetaLearnerBuilderFn and ml_collections ConfigDict', 'create a StreamConfig dataclass with a stream constructor callable and keyword arguments mapping', 'run the BaselineTest parameterized test suite to verify experiment runs and finishes for all configs', 'test that experiment.run_program completes successfully given a config dict from finetuning_prev or finetuning_dknn', 'review the BaselineTest class and its parameterized test method for experiment validation', 'summarize the CONFIGS_TO_TEST list containing finetuning_learner and finetuning_dknn_learner test configurations', 'refactor the experiment test to add additional config modules or test cases to CONFIGS_TO_TEST']
```

Usage

```
{'run_experiment_test': 'run the BaselineTest parameterized test suite to verify experiment runs and finishes for all configs', 'test_experiment_runs_and_finishes': 'test that experiment.run_program completes successfully given a config dict from finetuning_prev or finetuning_dknn', 'review_BaselineTest': 'review the BaselineTest class and its parameterized test method for experiment validation', 'summarize_CONFIGS_TO_TEST': 'summarize the CONFIGS_TO_TEST list containing finetuning_learner and finetuning_dknn_learner test configurations', 'refactor_experiment_test': 'refactor the experiment test to add additional config modules or test cases to CONFIGS_TO_TEST'}
```

