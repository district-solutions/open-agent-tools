# Agent Python Tools

- repo: facebookresearch/adversarial-continual-learning
- repo_uri: https://github.com/facebookresearch/adversarial-continual-learning

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/acl.py

Prompts

```
['train an ACL continual learning model on a task dataset with adversarial discriminator training', 'evaluate an ACL model on a data loader and return task accuracy and loss metrics', 'test an ACL model on a data loader and return accuracy and loss results', 'run inference with an ACL model on a data loader and return task accuracy and loss', 'compute the difference loss between two feature tensors using L2 normalized cosine similarity', 'run the adversarial continual learning training loop across multiple tasks using a config file', 'run the main entry point to execute multiple training runs with different random seeds', 'test a trained ACL model on all tasks by loading a checkpoint and running inference', 'run the ACL experiment by passing a YAML config file via the --config argument', 'run evaluation on a trained model by swapping the shared module and testing across tasks', 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save and print continual learning accuracy matrices, backward transfer, and logs to a pickle file', 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', 'get a deep copy of a PyTorch model state dict for saving or comparison']
```

Usage

```
{'train_ACL_model': 'train an ACL continual learning model on a task dataset with adversarial discriminator training', 'evaluate_ACL_model': 'evaluate an ACL model on a data loader and return task accuracy and loss metrics', 'test_ACL_model': 'test an ACL model on a data loader and return accuracy and loss results', 'run_ACL_inference': 'run inference with an ACL model on a data loader and return task accuracy and loss', 'compute_DiffLoss': 'compute the difference loss between two feature tensors using L2 normalized cosine similarity'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/main.py

Prompts

```
['train an ACL continual learning model on a task dataset with adversarial discriminator training', 'evaluate an ACL model on a data loader and return task accuracy and loss metrics', 'test an ACL model on a data loader and return accuracy and loss results', 'run inference with an ACL model on a data loader and return task accuracy and loss', 'compute the difference loss between two feature tensors using L2 normalized cosine similarity', 'run the adversarial continual learning training loop across multiple tasks using a config file', 'run the main entry point to execute multiple training runs with different random seeds', 'test a trained ACL model on all tasks by loading a checkpoint and running inference', 'run the ACL experiment by passing a YAML config file via the --config argument', 'run evaluation on a trained model by swapping the shared module and testing across tasks', 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save and print continual learning accuracy matrices, backward transfer, and logs to a pickle file', 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', 'get a deep copy of a PyTorch model state dict for saving or comparison']
```

Usage

```
{'run_ACL_training': 'run the adversarial continual learning training loop across multiple tasks using a config file', 'run_main_entry': 'run the main entry point to execute multiple training runs with different random seeds', 'test_trained_model': 'test a trained ACL model on all tasks by loading a checkpoint and running inference', 'run_ACL_with_config': 'run the ACL experiment by passing a YAML config file via the --config argument', 'run_ACL_evaluation': 'run evaluation on a trained model by swapping the shared module and testing across tasks'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/utils.py

Prompts

```
['train an ACL continual learning model on a task dataset with adversarial discriminator training', 'evaluate an ACL model on a data loader and return task accuracy and loss metrics', 'test an ACL model on a data loader and return accuracy and loss results', 'run inference with an ACL model on a data loader and return task accuracy and loss', 'compute the difference loss between two feature tensors using L2 normalized cosine similarity', 'run the adversarial continual learning training loop across multiple tasks using a config file', 'run the main entry point to execute multiple training runs with different random seeds', 'test a trained ACL model on all tasks by loading a checkpoint and running inference', 'run the ACL experiment by passing a YAML config file via the --config argument', 'run evaluation on a trained model by swapping the shared module and testing across tasks', 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save and print continual learning accuracy matrices, backward transfer, and logs to a pickle file', 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', 'get a deep copy of a PyTorch model state dict for saving or comparison']
```

Usage

```
{'compute_conv_output_size': 'compute the output size of a convolutional layer given input size, kernel, stride, padding, and dilation', 'human_format': 'format a number into a human-readable string with K, M, G, T, or P suffixes', 'save_print_log': 'save and print continual learning accuracy matrices, backward transfer, and logs to a pickle file', 'print_log_acc_bwt': 'print continual learning accuracy and backward transfer metrics then save results with a unique run ID', 'get_model': 'get a deep copy of a PyTorch model state dict for saving or comparison'}
```

