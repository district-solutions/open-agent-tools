# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/patterns/specializing_config/example.py

Prompts

```
['run the experiment function that prints the resolved Hydra config as YAML using OmegaConf', 'run the experiment overriding the dataset config group to cifar10 via command-line arguments', 'run the experiment overriding the model config group to resnet via command-line arguments', 'run the experiment with both dataset and model overrides to trigger the optional dataset_model specialization config', 'review the experiment function decorated with hydra.main to understand the specializing config pattern with optional group resolution']
```

Usage

```
{'run_experiment_with_hydra_config': 'run the experiment function that prints the resolved Hydra config as YAML using OmegaConf', 'run_experiment_with_dataset_override': 'run the experiment overriding the dataset config group to cifar10 via command-line arguments', 'run_experiment_with_model_override': 'run the experiment overriding the model config group to resnet via command-line arguments', 'run_experiment_with_dataset_model_specialization': 'run the experiment with both dataset and model overrides to trigger the optional dataset_model specialization config', 'review_experiment_hydra_main': 'review the experiment function decorated with hydra.main to understand the specializing config pattern with optional group resolution'}
```

