# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/trainers/tests/test_async_trainer.py

Prompts

```
['test that async FL training with SGD produces the same model as non-FL training for single and multiple users', 'test that async FL training with FedAdam produces the same model as non-FL training for single and multiple users', 'test that local learning rate normalization with equal weighting produces the same model update as linear weighting without normalization', 'test that async training metrics are reported only on training_end events and verify the order of reported num_examples', 'test async training with a Gaussian timeout simulator to verify trained examples stay within the timeout limit', 'run the pytest test suite for async trainer example and staleness weight configurations', 'test linear sqrt log10 and equal example weight configs against non-FL SGD training equivalence', 'test that default equal example weights produce identical models regardless of data replication factor', 'test threshold staleness weight config that zeroes updates with staleness greater than the cutoff', 'test polynomial staleness weight config where weight decays as 1 over staleness plus one', 'create a data provider for FL training with a dummy alphabet dataset and specified users', 'train a sync async or non-FL model to compare against FedBuff results', 'create a FedBuff aggregator config from an existing async or sync server config', 'compare FedBuff trained model against sync async or non-FL trained model for equivalence', 'run pytest to verify FedBuff with SGD produces the same model as non-FL training', 'test creating a SyncTrainer from a JSON or YAML config file with a dummy FL model', 'test creating an AsyncTrainer from a JSON or YAML config file and verify DP aggregator is private', 'test that FL training with one user per round produces equivalent results to non-FL SGD training', 'test client overselection with dropout rate and timeout simulator to verify training equivalence', 'test tensorboard metrics reporting for training, aggregation, and eval stages across multiple epochs']
```

Usage

```
{'test_async_fl_sgd_equivalence': 'test that async FL training with SGD produces the same model as non-FL training for single and multiple users', 'test_async_fl_adam_equivalence': 'test that async FL training with FedAdam produces the same model as non-FL training for single and multiple users', 'test_local_lr_normalization': 'test that local learning rate normalization with equal weighting produces the same model update as linear weighting without normalization', 'test_async_training_metrics_reporting': 'test that async training metrics are reported only on training_end events and verify the order of reported num_examples', 'test_async_training_with_timeout': 'test async training with a Gaussian timeout simulator to verify trained examples stay within the timeout limit'}
```

## File: facebookresearch_flsim/flsim/trainers/tests/test_async_trainer_weights.py

Prompts

```
['test that async FL training with SGD produces the same model as non-FL training for single and multiple users', 'test that async FL training with FedAdam produces the same model as non-FL training for single and multiple users', 'test that local learning rate normalization with equal weighting produces the same model update as linear weighting without normalization', 'test that async training metrics are reported only on training_end events and verify the order of reported num_examples', 'test async training with a Gaussian timeout simulator to verify trained examples stay within the timeout limit', 'run the pytest test suite for async trainer example and staleness weight configurations', 'test linear sqrt log10 and equal example weight configs against non-FL SGD training equivalence', 'test that default equal example weights produce identical models regardless of data replication factor', 'test threshold staleness weight config that zeroes updates with staleness greater than the cutoff', 'test polynomial staleness weight config where weight decays as 1 over staleness plus one', 'create a data provider for FL training with a dummy alphabet dataset and specified users', 'train a sync async or non-FL model to compare against FedBuff results', 'create a FedBuff aggregator config from an existing async or sync server config', 'compare FedBuff trained model against sync async or non-FL trained model for equivalence', 'run pytest to verify FedBuff with SGD produces the same model as non-FL training', 'test creating a SyncTrainer from a JSON or YAML config file with a dummy FL model', 'test creating an AsyncTrainer from a JSON or YAML config file and verify DP aggregator is private', 'test that FL training with one user per round produces equivalent results to non-FL SGD training', 'test client overselection with dropout rate and timeout simulator to verify training equivalence', 'test tensorboard metrics reporting for training, aggregation, and eval stages across multiple epochs']
```

Usage

```
{'run_async_trainer_weight_tests': 'run the pytest test suite for async trainer example and staleness weight configurations', 'test_linear_example_weights': 'test linear sqrt log10 and equal example weight configs against non-FL SGD training equivalence', 'test_default_example_weights': 'test that default equal example weights produce identical models regardless of data replication factor', 'test_threshold_staleness_weights': 'test threshold staleness weight config that zeroes updates with staleness greater than the cutoff', 'test_polynomial_staleness_weights': 'test polynomial staleness weight config where weight decays as 1 over staleness plus one'}
```

## File: facebookresearch_flsim/flsim/trainers/tests/test_fedbuff.py

Prompts

```
['test that async FL training with SGD produces the same model as non-FL training for single and multiple users', 'test that async FL training with FedAdam produces the same model as non-FL training for single and multiple users', 'test that local learning rate normalization with equal weighting produces the same model update as linear weighting without normalization', 'test that async training metrics are reported only on training_end events and verify the order of reported num_examples', 'test async training with a Gaussian timeout simulator to verify trained examples stay within the timeout limit', 'run the pytest test suite for async trainer example and staleness weight configurations', 'test linear sqrt log10 and equal example weight configs against non-FL SGD training equivalence', 'test that default equal example weights produce identical models regardless of data replication factor', 'test threshold staleness weight config that zeroes updates with staleness greater than the cutoff', 'test polynomial staleness weight config where weight decays as 1 over staleness plus one', 'create a data provider for FL training with a dummy alphabet dataset and specified users', 'train a sync async or non-FL model to compare against FedBuff results', 'create a FedBuff aggregator config from an existing async or sync server config', 'compare FedBuff trained model against sync async or non-FL trained model for equivalence', 'run pytest to verify FedBuff with SGD produces the same model as non-FL training', 'test creating a SyncTrainer from a JSON or YAML config file with a dummy FL model', 'test creating an AsyncTrainer from a JSON or YAML config file and verify DP aggregator is private', 'test that FL training with one user per round produces equivalent results to non-FL SGD training', 'test client overselection with dropout rate and timeout simulator to verify training equivalence', 'test tensorboard metrics reporting for training, aggregation, and eval stages across multiple epochs']
```

Usage

```
{'run_FedBuffTestUtils_get_data_provider': 'create a data provider for FL training with a dummy alphabet dataset and specified users', 'run_FedBuffTestUtils_train_comparable_model': 'train a sync async or non-FL model to compare against FedBuff results', 'run_FedBuffTestUtils_get_fedbuff_aggregator': 'create a FedBuff aggregator config from an existing async or sync server config', 'run_FedBuffTestUtils_compare_fedbuff_same': 'compare FedBuff trained model against sync async or non-FL trained model for equivalence', 'run_TestFedBuff_test_nonfl_fedbuff_same_sgd': 'run pytest to verify FedBuff with SGD produces the same model as non-FL training'}
```

## File: facebookresearch_flsim/flsim/trainers/tests/test_trainer.py

Prompts

```
['test that async FL training with SGD produces the same model as non-FL training for single and multiple users', 'test that async FL training with FedAdam produces the same model as non-FL training for single and multiple users', 'test that local learning rate normalization with equal weighting produces the same model update as linear weighting without normalization', 'test that async training metrics are reported only on training_end events and verify the order of reported num_examples', 'test async training with a Gaussian timeout simulator to verify trained examples stay within the timeout limit', 'run the pytest test suite for async trainer example and staleness weight configurations', 'test linear sqrt log10 and equal example weight configs against non-FL SGD training equivalence', 'test that default equal example weights produce identical models regardless of data replication factor', 'test threshold staleness weight config that zeroes updates with staleness greater than the cutoff', 'test polynomial staleness weight config where weight decays as 1 over staleness plus one', 'create a data provider for FL training with a dummy alphabet dataset and specified users', 'train a sync async or non-FL model to compare against FedBuff results', 'create a FedBuff aggregator config from an existing async or sync server config', 'compare FedBuff trained model against sync async or non-FL trained model for equivalence', 'run pytest to verify FedBuff with SGD produces the same model as non-FL training', 'test creating a SyncTrainer from a JSON or YAML config file with a dummy FL model', 'test creating an AsyncTrainer from a JSON or YAML config file and verify DP aggregator is private', 'test that FL training with one user per round produces equivalent results to non-FL SGD training', 'test client overselection with dropout rate and timeout simulator to verify training equivalence', 'test tensorboard metrics reporting for training, aggregation, and eval stages across multiple epochs']
```

Usage

```
{'test_sync_trainer_creation': 'test creating a SyncTrainer from a JSON or YAML config file with a dummy FL model', 'test_async_trainer_creation': 'test creating an AsyncTrainer from a JSON or YAML config file and verify DP aggregator is private', 'test_training_equivalence': 'test that FL training with one user per round produces equivalent results to non-FL SGD training', 'test_client_overselection': 'test client overselection with dropout rate and timeout simulator to verify training equivalence', 'test_tensorboard_metrics_reporting': 'test tensorboard metrics reporting for training, aggregation, and eval stages across multiple epochs'}
```

