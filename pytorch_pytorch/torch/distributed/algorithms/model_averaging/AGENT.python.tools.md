# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/algorithms/model_averaging/averagers.py

Prompts

```
['create a model averager with a process group for distributed all-reduce parameter averaging', 'create a periodic model averager with a period and warmup steps for post-local SGD training', 'average model parameters periodically after warmup using PeriodicModelAverager with DDP', 'test PeriodicModelAverager skips averaging when period is 1 and raises ValueError for invalid period', 'review PeriodicModelAverager.average_parameters to average optimizer parameter groups across processes', 'create a HierarchicalModelAverager with period_group_size_dict and warmup_steps for hierarchical SGD', 'initialize HierarchicalModelAverager with ordered period-to-process-group-size mapping and warmup steps', 'find the correct process group for model averaging at a given training step', 'average model parameters periodically using hierarchical process groups after warmup', 'configure warmup_steps to skip model averaging during initial training iterations', 'get parameters that have gradients from model parameters or optimizer parameter groups for averaging', 'average optimizer parameter groups across distributed processes filtering parameters without gradients', 'test the distributed model averaging utility with a process group and iterator of torch parameters', 'review the average_parameters function that flattens parameters, allreduces, and unpacks averaged values']
```

Usage

```
{'create_ModelAverager': 'create a model averager with a process group for distributed all-reduce parameter averaging', 'create_PeriodicModelAverager': 'create a periodic model averager with a period and warmup steps for post-local SGD training', 'average_parameters_PeriodicModelAverager': 'average model parameters periodically after warmup using PeriodicModelAverager with DDP', 'test_PeriodicModelAverager_period': 'test PeriodicModelAverager skips averaging when period is 1 and raises ValueError for invalid period', 'review_PeriodicModelAverager_average_parameters': 'review PeriodicModelAverager.average_parameters to average optimizer parameter groups across processes'}
```

## File: pytorch_pytorch/torch/distributed/algorithms/model_averaging/hierarchical_model_averager.py

Prompts

```
['create a model averager with a process group for distributed all-reduce parameter averaging', 'create a periodic model averager with a period and warmup steps for post-local SGD training', 'average model parameters periodically after warmup using PeriodicModelAverager with DDP', 'test PeriodicModelAverager skips averaging when period is 1 and raises ValueError for invalid period', 'review PeriodicModelAverager.average_parameters to average optimizer parameter groups across processes', 'create a HierarchicalModelAverager with period_group_size_dict and warmup_steps for hierarchical SGD', 'initialize HierarchicalModelAverager with ordered period-to-process-group-size mapping and warmup steps', 'find the correct process group for model averaging at a given training step', 'average model parameters periodically using hierarchical process groups after warmup', 'configure warmup_steps to skip model averaging during initial training iterations', 'get parameters that have gradients from model parameters or optimizer parameter groups for averaging', 'average optimizer parameter groups across distributed processes filtering parameters without gradients', 'test the distributed model averaging utility with a process group and iterator of torch parameters', 'review the average_parameters function that flattens parameters, allreduces, and unpacks averaged values']
```

Usage

```
{'create_HierarchicalModelAverager': 'create a HierarchicalModelAverager with period_group_size_dict and warmup_steps for hierarchical SGD', 'initialize_HierarchicalModelAverager': 'initialize HierarchicalModelAverager with ordered period-to-process-group-size mapping and warmup steps', 'find_process_group_step': 'find the correct process group for model averaging at a given training step', 'average_parameters_model': 'average model parameters periodically using hierarchical process groups after warmup', 'configure_warmup_steps': 'configure warmup_steps to skip model averaging during initial training iterations'}
```

## File: pytorch_pytorch/torch/distributed/algorithms/model_averaging/utils.py

Prompts

```
['create a model averager with a process group for distributed all-reduce parameter averaging', 'create a periodic model averager with a period and warmup steps for post-local SGD training', 'average model parameters periodically after warmup using PeriodicModelAverager with DDP', 'test PeriodicModelAverager skips averaging when period is 1 and raises ValueError for invalid period', 'review PeriodicModelAverager.average_parameters to average optimizer parameter groups across processes', 'create a HierarchicalModelAverager with period_group_size_dict and warmup_steps for hierarchical SGD', 'initialize HierarchicalModelAverager with ordered period-to-process-group-size mapping and warmup steps', 'find the correct process group for model averaging at a given training step', 'average model parameters periodically using hierarchical process groups after warmup', 'configure warmup_steps to skip model averaging during initial training iterations', 'get parameters that have gradients from model parameters or optimizer parameter groups for averaging', 'average optimizer parameter groups across distributed processes filtering parameters without gradients', 'test the distributed model averaging utility with a process group and iterator of torch parameters', 'review the average_parameters function that flattens parameters, allreduces, and unpacks averaged values']
```

Usage

```
{'average_parameters_model': 'average model parameters across distributed processes using a process group and parameter iterator', 'get_params_with_gradients': 'get parameters that have gradients from model parameters or optimizer parameter groups for averaging', 'average_optimizer_parameter_groups': 'average optimizer parameter groups across distributed processes filtering parameters without gradients', 'test_distributed_average': 'test the distributed model averaging utility with a process group and iterator of torch parameters', 'review_average_parameters': 'review the average_parameters function that flattens parameters, allreduces, and unpacks averaged values'}
```

