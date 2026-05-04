# Agent Python Tools

- repo: facebookresearch/adversarial-continual-learning
- repo_uri: https://github.com/facebookresearch/adversarial-continual-learning

## File: facebookresearch_adversarial-continual-learning/src/acl.py

Prompts

```
['train the ACL model on a continual learning task with adversarial and difference loss regularization', 'evaluate the ACL model on a data loader and return task accuracy and discriminator accuracy metrics', 'test the ACL model on a test data loader and return loss and accuracy results', 'create a DiffLoss module that computes orthogonality loss between two sets of normalized feature embeddings', 'save the ACL model and discriminator state dicts as checkpoint files for a given task ID', 'run an adversarial continual learning experiment on MNIST5, CIFAR100, or MiniImageNet datasets', 'run the training loop across multiple tasks and test accuracy after each task', 'run multiple experimental runs with different random seeds and report average accuracy and forgetting', 'run t-SNE embedding extraction for MiniImageNet tasks to visualize in TensorBoard', 'run an ACL experiment by loading a YAML config file via the --config argument', 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save and print continual learning accuracy matrices and backward transfer metrics to a pickle file', 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', "get a deep copy of a PyTorch model's state dictionary for checkpointing"]
```

Usage

```
{'train_ACL_model': 'train the ACL model on a continual learning task with adversarial and difference loss regularization', 'eval_ACL_model': 'evaluate the ACL model on a data loader and return task accuracy and discriminator accuracy metrics', 'test_ACL_model': 'test the ACL model on a test data loader and return loss and accuracy results', 'create_DiffLoss_module': 'create a DiffLoss module that computes orthogonality loss between two sets of normalized feature embeddings', 'save_ACL_checkpoints': 'save the ACL model and discriminator state dicts as checkpoint files for a given task ID'}
```

## File: facebookresearch_adversarial-continual-learning/src/main.py

Prompts

```
['train the ACL model on a continual learning task with adversarial and difference loss regularization', 'evaluate the ACL model on a data loader and return task accuracy and discriminator accuracy metrics', 'test the ACL model on a test data loader and return loss and accuracy results', 'create a DiffLoss module that computes orthogonality loss between two sets of normalized feature embeddings', 'save the ACL model and discriminator state dicts as checkpoint files for a given task ID', 'run an adversarial continual learning experiment on MNIST5, CIFAR100, or MiniImageNet datasets', 'run the training loop across multiple tasks and test accuracy after each task', 'run multiple experimental runs with different random seeds and report average accuracy and forgetting', 'run t-SNE embedding extraction for MiniImageNet tasks to visualize in TensorBoard', 'run an ACL experiment by loading a YAML config file via the --config argument', 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save and print continual learning accuracy matrices and backward transfer metrics to a pickle file', 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', "get a deep copy of a PyTorch model's state dictionary for checkpointing"]
```

Usage

```
{'run_acl_experiment': 'run an adversarial continual learning experiment on MNIST5, CIFAR100, or MiniImageNet datasets', 'run_train_and_test_loop': 'run the training loop across multiple tasks and test accuracy after each task', 'run_multiple_seeds': 'run multiple experimental runs with different random seeds and report average accuracy and forgetting', 'run_tsne_embeddings': 'run t-SNE embedding extraction for MiniImageNet tasks to visualize in TensorBoard', 'run_config_experiment': 'run an ACL experiment by loading a YAML config file via the --config argument'}
```

## File: facebookresearch_adversarial-continual-learning/src/utils.py

Prompts

```
['train the ACL model on a continual learning task with adversarial and difference loss regularization', 'evaluate the ACL model on a data loader and return task accuracy and discriminator accuracy metrics', 'test the ACL model on a test data loader and return loss and accuracy results', 'create a DiffLoss module that computes orthogonality loss between two sets of normalized feature embeddings', 'save the ACL model and discriminator state dicts as checkpoint files for a given task ID', 'run an adversarial continual learning experiment on MNIST5, CIFAR100, or MiniImageNet datasets', 'run the training loop across multiple tasks and test accuracy after each task', 'run multiple experimental runs with different random seeds and report average accuracy and forgetting', 'run t-SNE embedding extraction for MiniImageNet tasks to visualize in TensorBoard', 'run an ACL experiment by loading a YAML config file via the --config argument', 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save and print continual learning accuracy matrices and backward transfer metrics to a pickle file', 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', "get a deep copy of a PyTorch model's state dictionary for checkpointing"]
```

Usage

```
{'compute_conv_output_size': 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'human_format': 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save_print_log': 'save and print continual learning accuracy matrices and backward transfer metrics to a pickle file', 'print_log_acc_bwt': 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', 'get_model': "get a deep copy of a PyTorch model's state dictionary for checkpointing"}
```

