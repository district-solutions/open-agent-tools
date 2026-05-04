# Agent Python Tools

- repo: google-deepmind/distributionshiftframework
- repo_uri: https://github.com/google-deepmind/distribution_shift_framework

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/classification/config.py

Prompts

```
['get a training ConfigDict for a classification experiment with options like dataset_name, model, algorithm, and batch_size', 'parse a comma-separated key=value option string into a typed dictionary with defaults and validation', 'get a learning algorithm config and hyperparameter sweep for algorithms like IRM, DANN, CORAL, or SagNet', 'get a ResNet18 model config with learning rate sweep for a given number of classes and optional resize', 'get an MLP model config with configurable layers, hidden size, and learning rate sweep for classification', 'run one training step of the classification experiment with generator and discriminator updates', 'evaluate the classification model on test data and compute top1 accuracy metrics', 'run domain adaptation using an adaptor function on test data with a specified number of steps', 'build a learner function that computes logits and loss for a classification batch with optional adversarial training', 'refactor the Experiment update function to modify generator and discriminator parameter update logic', 'test training a classification experiment with CORAL, DANN, ERM, IRM, or SagNet algorithms on dsprites or shapes3d datasets', 'run parameterized tests across multiple algorithms, datasets, and test cases like ood, lowdata, and correlated lowdata', 'set up the test module by disabling JAX optimizations to speed up test execution', 'tear down the test module by restoring JAX config values to their previous state', 'review the ExperimentLibTest class that parameterizes training tests across algorithms, datasets, and test cases']
```

Usage

```
{'get_config': 'get a training ConfigDict for a classification experiment with options like dataset_name, model, algorithm, and batch_size', 'parse_options': 'parse a comma-separated key=value option string into a typed dictionary with defaults and validation', 'get_learner': 'get a learning algorithm config and hyperparameter sweep for algorithms like IRM, DANN, CORAL, or SagNet', 'get_resnet18_config': 'get a ResNet18 model config with learning rate sweep for a given number of classes and optional resize', 'get_mlp_config': 'get an MLP model config with configurable layers, hidden size, and learning rate sweep for classification'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/classification/experiment_lib.py

Prompts

```
['get a training ConfigDict for a classification experiment with options like dataset_name, model, algorithm, and batch_size', 'parse a comma-separated key=value option string into a typed dictionary with defaults and validation', 'get a learning algorithm config and hyperparameter sweep for algorithms like IRM, DANN, CORAL, or SagNet', 'get a ResNet18 model config with learning rate sweep for a given number of classes and optional resize', 'get an MLP model config with configurable layers, hidden size, and learning rate sweep for classification', 'run one training step of the classification experiment with generator and discriminator updates', 'evaluate the classification model on test data and compute top1 accuracy metrics', 'run domain adaptation using an adaptor function on test data with a specified number of steps', 'build a learner function that computes logits and loss for a classification batch with optional adversarial training', 'refactor the Experiment update function to modify generator and discriminator parameter update logic', 'test training a classification experiment with CORAL, DANN, ERM, IRM, or SagNet algorithms on dsprites or shapes3d datasets', 'run parameterized tests across multiple algorithms, datasets, and test cases like ood, lowdata, and correlated lowdata', 'set up the test module by disabling JAX optimizations to speed up test execution', 'tear down the test module by restoring JAX config values to their previous state', 'review the ExperimentLibTest class that parameterizes training tests across algorithms, datasets, and test cases']
```

Usage

```
{'run_Experiment_step': 'run one training step of the classification experiment with generator and discriminator updates', 'run_Experiment_evaluate': 'evaluate the classification model on test data and compute top1 accuracy metrics', 'run_Experiment_adapt_fn': 'run domain adaptation using an adaptor function on test data with a specified number of steps', 'build_Experiment_learner_fn': 'build a learner function that computes logits and loss for a classification batch with optional adversarial training', 'refactor_Experiment_update_func': 'refactor the Experiment update function to modify generator and discriminator parameter update logic'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/classification/experiment_lib_test.py

Prompts

```
['get a training ConfigDict for a classification experiment with options like dataset_name, model, algorithm, and batch_size', 'parse a comma-separated key=value option string into a typed dictionary with defaults and validation', 'get a learning algorithm config and hyperparameter sweep for algorithms like IRM, DANN, CORAL, or SagNet', 'get a ResNet18 model config with learning rate sweep for a given number of classes and optional resize', 'get an MLP model config with configurable layers, hidden size, and learning rate sweep for classification', 'run one training step of the classification experiment with generator and discriminator updates', 'evaluate the classification model on test data and compute top1 accuracy metrics', 'run domain adaptation using an adaptor function on test data with a specified number of steps', 'build a learner function that computes logits and loss for a classification batch with optional adversarial training', 'refactor the Experiment update function to modify generator and discriminator parameter update logic', 'test training a classification experiment with CORAL, DANN, ERM, IRM, or SagNet algorithms on dsprites or shapes3d datasets', 'run parameterized tests across multiple algorithms, datasets, and test cases like ood, lowdata, and correlated lowdata', 'set up the test module by disabling JAX optimizations to speed up test execution', 'tear down the test module by restoring JAX config values to their previous state', 'review the ExperimentLibTest class that parameterizes training tests across algorithms, datasets, and test cases']
```

Usage

```
{'test_train_experiment': 'test training a classification experiment with CORAL, DANN, ERM, IRM, or SagNet algorithms on dsprites or shapes3d datasets', 'run_parameterized_tests': 'run parameterized tests across multiple algorithms, datasets, and test cases like ood, lowdata, and correlated lowdata', 'setUpModule_jax_config': 'set up the test module by disabling JAX optimizations to speed up test execution', 'tearDownModule_jax_config': 'tear down the test module by restoring JAX config values to their previous state', 'review_ExperimentLibTest': 'review the ExperimentLibTest class that parameterizes training tests across algorithms, datasets, and test cases'}
```

