# Agent Python Tools

- repo: google-deepmind/dmnevis
- repo_uri: https://github.com/google-deepmind/dm_nevis

## File: google-deepmind_dmnevis/dm_nevis/benchmarker/learners/learner_interface.py

Prompts

```
['create a Learner NamedTuple with init, train, and predict function protocols for a new ML model', 'combine two ResourceUsage dataclasses to accumulate floating point operations and peak parameter counts', 'build a TrainFn protocol that trains a learner state given a TrainingEvent and checkpoint function', 'create a Predictions NamedTuple pairing an input MiniBatch with the model output from a learner', 'implement an InitFn protocol that initializes and returns a new LearnerState for benchmarking']
```

Usage

```
{'create_learner': 'create a Learner NamedTuple with init, train, and predict function protocols for a new ML model', 'combine_resource_usage': 'combine two ResourceUsage dataclasses to accumulate floating point operations and peak parameter counts', 'build_train_fn': 'build a TrainFn protocol that trains a learner state given a TrainingEvent and checkpoint function', 'create_predictions': 'create a Predictions NamedTuple pairing an input MiniBatch with the model output from a learner', 'implement_init_fn': 'implement an InitFn protocol that initializes and returns a new LearnerState for benchmarking'}
```

