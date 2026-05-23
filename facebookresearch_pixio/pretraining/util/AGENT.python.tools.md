# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/pretraining/util/lr_sched.py

Prompts

```
['build a python module that decays the learning rate with half-cycle cosine annealing after a warmup phase', 'create a function that applies linear warmup followed by cosine learning rate decay for an optimizer', 'test the adjust_learning_rate function to verify correct warmup and cosine decay behavior across epochs', 'refactor the adjust_learning_rate function to support additional learning rate scheduling strategies beyond cosine decay', 'review the adjust_learning_rate function and how it updates optimizer param groups with scaled learning rates', 'create a SmoothedValue instance to track rolling median and global average of training metrics', 'build a MetricLogger to log and print training metrics like loss and accuracy every N iterations', 'initialize distributed training mode by parsing SLURM or ITP environment variables and starting the process group', 'save and load model checkpoints including optimizer state, epoch, and AMP scaler using save_model and load_model', 'compute the mean of a scalar value across all distributed processes using all_reduce_mean', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D parameters from weight decay for a PyTorch model', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional exclusion criteria beyond bias and 1D parameters', 'review the param_groups_weight_decay function and its handling of no_weight_decay_list parameter']
```

Usage

```
{'build_lr_scheduler': 'build a python module that decays the learning rate with half-cycle cosine annealing after a warmup phase', 'create_warmup_cosine_lr': 'create a function that applies linear warmup followed by cosine learning rate decay for an optimizer', 'test_adjust_learning_rate': 'test the adjust_learning_rate function to verify correct warmup and cosine decay behavior across epochs', 'refactor_lr_schedule': 'refactor the adjust_learning_rate function to support additional learning rate scheduling strategies beyond cosine decay', 'review_optimizer_lr_update': 'review the adjust_learning_rate function and how it updates optimizer param groups with scaled learning rates'}
```

## File: facebookresearch_pixio/pretraining/util/misc.py

Prompts

```
['build a python module that decays the learning rate with half-cycle cosine annealing after a warmup phase', 'create a function that applies linear warmup followed by cosine learning rate decay for an optimizer', 'test the adjust_learning_rate function to verify correct warmup and cosine decay behavior across epochs', 'refactor the adjust_learning_rate function to support additional learning rate scheduling strategies beyond cosine decay', 'review the adjust_learning_rate function and how it updates optimizer param groups with scaled learning rates', 'create a SmoothedValue instance to track rolling median and global average of training metrics', 'build a MetricLogger to log and print training metrics like loss and accuracy every N iterations', 'initialize distributed training mode by parsing SLURM or ITP environment variables and starting the process group', 'save and load model checkpoints including optimizer state, epoch, and AMP scaler using save_model and load_model', 'compute the mean of a scalar value across all distributed processes using all_reduce_mean', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D parameters from weight decay for a PyTorch model', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional exclusion criteria beyond bias and 1D parameters', 'review the param_groups_weight_decay function and its handling of no_weight_decay_list parameter']
```

Usage

```
{'create_SmoothedValue': 'create a SmoothedValue instance to track rolling median and global average of training metrics', 'build_MetricLogger': 'build a MetricLogger to log and print training metrics like loss and accuracy every N iterations', 'init_distributed_mode': 'initialize distributed training mode by parsing SLURM or ITP environment variables and starting the process group', 'save_and_load_model': 'save and load model checkpoints including optimizer state, epoch, and AMP scaler using save_model and load_model', 'all_reduce_mean': 'compute the mean of a scalar value across all distributed processes using all_reduce_mean'}
```

## File: facebookresearch_pixio/pretraining/util/optim_factory.py

Prompts

```
['build a python module that decays the learning rate with half-cycle cosine annealing after a warmup phase', 'create a function that applies linear warmup followed by cosine learning rate decay for an optimizer', 'test the adjust_learning_rate function to verify correct warmup and cosine decay behavior across epochs', 'refactor the adjust_learning_rate function to support additional learning rate scheduling strategies beyond cosine decay', 'review the adjust_learning_rate function and how it updates optimizer param groups with scaled learning rates', 'create a SmoothedValue instance to track rolling median and global average of training metrics', 'build a MetricLogger to log and print training metrics like loss and accuracy every N iterations', 'initialize distributed training mode by parsing SLURM or ITP environment variables and starting the process group', 'save and load model checkpoints including optimizer state, epoch, and AMP scaler using save_model and load_model', 'compute the mean of a scalar value across all distributed processes using all_reduce_mean', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D parameters from weight decay for a PyTorch model', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional exclusion criteria beyond bias and 1D parameters', 'review the param_groups_weight_decay function and its handling of no_weight_decay_list parameter']
```

Usage

```
{'build_param_groups_weight_decay': 'build a python module that splits model parameters into weight decay and no decay groups', 'create_optimizer_param_groups': 'create param groups separating bias and 1D parameters from weight decay for a PyTorch model', 'test_param_groups_weight_decay': 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor_param_groups_weight_decay': 'refactor param_groups_weight_decay to support additional exclusion criteria beyond bias and 1D parameters', 'review_param_groups_weight_decay': 'review the param_groups_weight_decay function and its handling of no_weight_decay_list parameter'}
```

