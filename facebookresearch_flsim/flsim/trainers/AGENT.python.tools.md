# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/trainers/async_trainer.py

Prompts

```
['build a python module to create an AsyncTrainer for asynchronous federated learning with a model and config', 'run asynchronous federated training with a data provider, metrics reporter, and total number of users', 'train a single async client and aggregate its update into the global model', 'review the AsyncTrainerConfig dataclass to understand aggregator, weight, and staleness settings', 'summarize the AsyncTrainer class implementing async federated averaging with reconstructed gradients', 'create a PrivateSyncTrainer instance with an IFLModel and cuda enabled for differential privacy training', 'train a PrivateSyncTrainer with a data provider, metrics reporter, and total number of users', 'create a DPClient for a given dataset id using create_or_get_client_for_data in PrivateSyncTrainer', 'calculate sample level and user level DP epsilon metrics after aggregation using calc_post_aggregation_train_metrics', 'configure a PrivateSyncTrainerConfig dataclass with DPClientConfig for sample-level DP and DPRoundReducerConfig for user-level DP', 'run synchronous federated learning training with FedAvg on a model using SyncTrainer.train()', 'select clients for each training round using SyncTrainer._client_selection with dropout rate', 'create or get a training client for a given dataset ID using SyncTrainer.create_or_get_client_for_data()', 'calculate differential privacy metrics for user-level and sample-level DP using SyncTrainer._calc_privacy_metrics()', 'report post-epoch client-side evaluation metrics using SyncTrainer._report_post_epoch_client_metrics()', 'build a subclass of FLTrainer that implements the abstract train method for federated learning', 'test the FLTrainer base class by calling test with a data provider and metrics reporter', 'review the FLTrainerConfig dataclass to understand epochs, eval frequency, and personalization settings', 'run evaluation on eval users by calling _maybe_run_evaluation with a timeline and data provider', 'summarize the FLTrainer methods for training, testing, evaluation, and metrics reporting in federated learning']
```

Usage

```
{'build_async_fl_trainer': 'build a python module to create an AsyncTrainer for asynchronous federated learning with a model and config', 'run_async_training': 'run asynchronous federated training with a data provider, metrics reporter, and total number of users', 'train_and_update_global_model': 'train a single async client and aggregate its update into the global model', 'review_async_trainer_config': 'review the AsyncTrainerConfig dataclass to understand aggregator, weight, and staleness settings', 'summarize_async_trainer_class': 'summarize the AsyncTrainer class implementing async federated averaging with reconstructed gradients'}
```

## File: facebookresearch_flsim/flsim/trainers/private_sync_trainer.py

Prompts

```
['build a python module to create an AsyncTrainer for asynchronous federated learning with a model and config', 'run asynchronous federated training with a data provider, metrics reporter, and total number of users', 'train a single async client and aggregate its update into the global model', 'review the AsyncTrainerConfig dataclass to understand aggregator, weight, and staleness settings', 'summarize the AsyncTrainer class implementing async federated averaging with reconstructed gradients', 'create a PrivateSyncTrainer instance with an IFLModel and cuda enabled for differential privacy training', 'train a PrivateSyncTrainer with a data provider, metrics reporter, and total number of users', 'create a DPClient for a given dataset id using create_or_get_client_for_data in PrivateSyncTrainer', 'calculate sample level and user level DP epsilon metrics after aggregation using calc_post_aggregation_train_metrics', 'configure a PrivateSyncTrainerConfig dataclass with DPClientConfig for sample-level DP and DPRoundReducerConfig for user-level DP', 'run synchronous federated learning training with FedAvg on a model using SyncTrainer.train()', 'select clients for each training round using SyncTrainer._client_selection with dropout rate', 'create or get a training client for a given dataset ID using SyncTrainer.create_or_get_client_for_data()', 'calculate differential privacy metrics for user-level and sample-level DP using SyncTrainer._calc_privacy_metrics()', 'report post-epoch client-side evaluation metrics using SyncTrainer._report_post_epoch_client_metrics()', 'build a subclass of FLTrainer that implements the abstract train method for federated learning', 'test the FLTrainer base class by calling test with a data provider and metrics reporter', 'review the FLTrainerConfig dataclass to understand epochs, eval frequency, and personalization settings', 'run evaluation on eval users by calling _maybe_run_evaluation with a timeline and data provider', 'summarize the FLTrainer methods for training, testing, evaluation, and metrics reporting in federated learning']
```

Usage

```
{'create_private_sync_trainer': 'create a PrivateSyncTrainer instance with an IFLModel and cuda enabled for differential privacy training', 'train_private_sync_trainer': 'train a PrivateSyncTrainer with a data provider, metrics reporter, and total number of users', 'create_dp_client_for_data': 'create a DPClient for a given dataset id using create_or_get_client_for_data in PrivateSyncTrainer', 'calc_post_aggregation_train_metrics': 'calculate sample level and user level DP epsilon metrics after aggregation using calc_post_aggregation_train_metrics', 'configure_private_sync_trainer_config': 'configure a PrivateSyncTrainerConfig dataclass with DPClientConfig for sample-level DP and DPRoundReducerConfig for user-level DP'}
```

## File: facebookresearch_flsim/flsim/trainers/sync_trainer.py

Prompts

```
['build a python module to create an AsyncTrainer for asynchronous federated learning with a model and config', 'run asynchronous federated training with a data provider, metrics reporter, and total number of users', 'train a single async client and aggregate its update into the global model', 'review the AsyncTrainerConfig dataclass to understand aggregator, weight, and staleness settings', 'summarize the AsyncTrainer class implementing async federated averaging with reconstructed gradients', 'create a PrivateSyncTrainer instance with an IFLModel and cuda enabled for differential privacy training', 'train a PrivateSyncTrainer with a data provider, metrics reporter, and total number of users', 'create a DPClient for a given dataset id using create_or_get_client_for_data in PrivateSyncTrainer', 'calculate sample level and user level DP epsilon metrics after aggregation using calc_post_aggregation_train_metrics', 'configure a PrivateSyncTrainerConfig dataclass with DPClientConfig for sample-level DP and DPRoundReducerConfig for user-level DP', 'run synchronous federated learning training with FedAvg on a model using SyncTrainer.train()', 'select clients for each training round using SyncTrainer._client_selection with dropout rate', 'create or get a training client for a given dataset ID using SyncTrainer.create_or_get_client_for_data()', 'calculate differential privacy metrics for user-level and sample-level DP using SyncTrainer._calc_privacy_metrics()', 'report post-epoch client-side evaluation metrics using SyncTrainer._report_post_epoch_client_metrics()', 'build a subclass of FLTrainer that implements the abstract train method for federated learning', 'test the FLTrainer base class by calling test with a data provider and metrics reporter', 'review the FLTrainerConfig dataclass to understand epochs, eval frequency, and personalization settings', 'run evaluation on eval users by calling _maybe_run_evaluation with a timeline and data provider', 'summarize the FLTrainer methods for training, testing, evaluation, and metrics reporting in federated learning']
```

Usage

```
{'train_sync_fl_model': 'run synchronous federated learning training with FedAvg on a model using SyncTrainer.train()', 'select_clients_for_round': 'select clients for each training round using SyncTrainer._client_selection with dropout rate', 'create_client_for_data': 'create or get a training client for a given dataset ID using SyncTrainer.create_or_get_client_for_data()', 'calculate_privacy_metrics': 'calculate differential privacy metrics for user-level and sample-level DP using SyncTrainer._calc_privacy_metrics()', 'report_client_metrics': 'report post-epoch client-side evaluation metrics using SyncTrainer._report_post_epoch_client_metrics()'}
```

## File: facebookresearch_flsim/flsim/trainers/trainer_base.py

Prompts

```
['build a python module to create an AsyncTrainer for asynchronous federated learning with a model and config', 'run asynchronous federated training with a data provider, metrics reporter, and total number of users', 'train a single async client and aggregate its update into the global model', 'review the AsyncTrainerConfig dataclass to understand aggregator, weight, and staleness settings', 'summarize the AsyncTrainer class implementing async federated averaging with reconstructed gradients', 'create a PrivateSyncTrainer instance with an IFLModel and cuda enabled for differential privacy training', 'train a PrivateSyncTrainer with a data provider, metrics reporter, and total number of users', 'create a DPClient for a given dataset id using create_or_get_client_for_data in PrivateSyncTrainer', 'calculate sample level and user level DP epsilon metrics after aggregation using calc_post_aggregation_train_metrics', 'configure a PrivateSyncTrainerConfig dataclass with DPClientConfig for sample-level DP and DPRoundReducerConfig for user-level DP', 'run synchronous federated learning training with FedAvg on a model using SyncTrainer.train()', 'select clients for each training round using SyncTrainer._client_selection with dropout rate', 'create or get a training client for a given dataset ID using SyncTrainer.create_or_get_client_for_data()', 'calculate differential privacy metrics for user-level and sample-level DP using SyncTrainer._calc_privacy_metrics()', 'report post-epoch client-side evaluation metrics using SyncTrainer._report_post_epoch_client_metrics()', 'build a subclass of FLTrainer that implements the abstract train method for federated learning', 'test the FLTrainer base class by calling test with a data provider and metrics reporter', 'review the FLTrainerConfig dataclass to understand epochs, eval frequency, and personalization settings', 'run evaluation on eval users by calling _maybe_run_evaluation with a timeline and data provider', 'summarize the FLTrainer methods for training, testing, evaluation, and metrics reporting in federated learning']
```

Usage

```
{'build_FLTrainer_subclass': 'build a subclass of FLTrainer that implements the abstract train method for federated learning', 'test_FLTrainer': 'test the FLTrainer base class by calling test with a data provider and metrics reporter', 'review_FLTrainerConfig': 'review the FLTrainerConfig dataclass to understand epochs, eval frequency, and personalization settings', 'run_FLTrainer_evaluation': 'run evaluation on eval users by calling _maybe_run_evaluation with a timeline and data provider', 'summarize_FLTrainer_methods': 'summarize the FLTrainer methods for training, testing, evaluation, and metrics reporting in federated learning'}
```

