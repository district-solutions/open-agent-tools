# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tests/trainers/callbacks/test_logistics.py

Prompts

```
['test the LogisticsCallback on_train_start method to verify train_timer initializes at zero milliseconds', 'test the LogisticsCallback on_update_end method to verify logging behavior with should_log flag', 'test the LogisticsCallback on_validation_start method to verify snapshot_timer initializes at zero milliseconds', 'test the LogisticsCallback on_test_end method to verify finished run message is written to train.log', 'test the SimpleModule forward pass that computes cross entropy loss through a base and classifier network', 'test the LRSchedulerCallback on_update_end method to verify learning rate decreases after each update step', 'create a SimpleModule PyTorch model with base and classifier layers using CrossEntropyLoss for training', 'test the NumbersDataset class that provides a dataset of 1000 sequential integer samples', 'review the LRSchedulerCallback configuration with lr_ratio and lr_steps for step-based learning rate scheduling', 'build an OmegaConf training configuration merging defaults.yaml with lr_scheduler, lr_ratio, and lr_steps settings', 'register a custom callback class with the MMF registry under a named key', 'test that a registered user callback is correctly instantiated from config', 'set up a trainer namespace with config, model, optimizer, and registered callbacks', 'retrieve a registered callback class by its name from the MMF registry', 'merge default YAML config with training callback settings using OmegaConf']
```

Usage

```
{'test_LogisticsCallback_on_train_start': 'test the LogisticsCallback on_train_start method to verify train_timer initializes at zero milliseconds', 'test_LogisticsCallback_on_update_end': 'test the LogisticsCallback on_update_end method to verify logging behavior with should_log flag', 'test_LogisticsCallback_on_validation_start': 'test the LogisticsCallback on_validation_start method to verify snapshot_timer initializes at zero milliseconds', 'test_LogisticsCallback_on_test_end': 'test the LogisticsCallback on_test_end method to verify finished run message is written to train.log', 'test_SimpleModule_forward': 'test the SimpleModule forward pass that computes cross entropy loss through a base and classifier network'}
```

## File: facebookresearch_mmf/tests/trainers/callbacks/test_lr_scheduler.py

Prompts

```
['test the LogisticsCallback on_train_start method to verify train_timer initializes at zero milliseconds', 'test the LogisticsCallback on_update_end method to verify logging behavior with should_log flag', 'test the LogisticsCallback on_validation_start method to verify snapshot_timer initializes at zero milliseconds', 'test the LogisticsCallback on_test_end method to verify finished run message is written to train.log', 'test the SimpleModule forward pass that computes cross entropy loss through a base and classifier network', 'test the LRSchedulerCallback on_update_end method to verify learning rate decreases after each update step', 'create a SimpleModule PyTorch model with base and classifier layers using CrossEntropyLoss for training', 'test the NumbersDataset class that provides a dataset of 1000 sequential integer samples', 'review the LRSchedulerCallback configuration with lr_ratio and lr_steps for step-based learning rate scheduling', 'build an OmegaConf training configuration merging defaults.yaml with lr_scheduler, lr_ratio, and lr_steps settings', 'register a custom callback class with the MMF registry under a named key', 'test that a registered user callback is correctly instantiated from config', 'set up a trainer namespace with config, model, optimizer, and registered callbacks', 'retrieve a registered callback class by its name from the MMF registry', 'merge default YAML config with training callback settings using OmegaConf']
```

Usage

```
{'test_LRSchedulerCallback_on_update_end': 'test the LRSchedulerCallback on_update_end method to verify learning rate decreases after each update step', 'create_SimpleModule_model': 'create a SimpleModule PyTorch model with base and classifier layers using CrossEntropyLoss for training', 'test_NumbersDataset_dataset': 'test the NumbersDataset class that provides a dataset of 1000 sequential integer samples', 'review_LRSchedulerCallback_lr_steps': 'review the LRSchedulerCallback configuration with lr_ratio and lr_steps for step-based learning rate scheduling', 'build_OmegaConf_training_config': 'build an OmegaConf training configuration merging defaults.yaml with lr_scheduler, lr_ratio, and lr_steps settings'}
```

## File: facebookresearch_mmf/tests/trainers/callbacks/test_user_callback.py

Prompts

```
['test the LogisticsCallback on_train_start method to verify train_timer initializes at zero milliseconds', 'test the LogisticsCallback on_update_end method to verify logging behavior with should_log flag', 'test the LogisticsCallback on_validation_start method to verify snapshot_timer initializes at zero milliseconds', 'test the LogisticsCallback on_test_end method to verify finished run message is written to train.log', 'test the SimpleModule forward pass that computes cross entropy loss through a base and classifier network', 'test the LRSchedulerCallback on_update_end method to verify learning rate decreases after each update step', 'create a SimpleModule PyTorch model with base and classifier layers using CrossEntropyLoss for training', 'test the NumbersDataset class that provides a dataset of 1000 sequential integer samples', 'review the LRSchedulerCallback configuration with lr_ratio and lr_steps for step-based learning rate scheduling', 'build an OmegaConf training configuration merging defaults.yaml with lr_scheduler, lr_ratio, and lr_steps settings', 'register a custom callback class with the MMF registry under a named key', 'test that a registered user callback is correctly instantiated from config', 'set up a trainer namespace with config, model, optimizer, and registered callbacks', 'retrieve a registered callback class by its name from the MMF registry', 'merge default YAML config with training callback settings using OmegaConf']
```

Usage

```
{'register_callback_class': 'register a custom callback class with the MMF registry under a named key', 'test_user_callback_instantiation': 'test that a registered user callback is correctly instantiated from config', 'setup_trainer_with_callbacks': 'set up a trainer namespace with config, model, optimizer, and registered callbacks', 'get_callback_class_from_registry': 'retrieve a registered callback class by its name from the MMF registry', 'merge_training_config_with_omegaconf': 'merge default YAML config with training callback settings using OmegaConf'}
```

