# Agent Python Tools

- repo: facebookresearch/agem
- repo_uri: https://github.com/facebookresearch/agem

## File: facebookresearch_agem/conv_split_awa.py

Prompts

```
['run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test the trained model on a task sequence and compute per-task accuracy', 'parse command line arguments for the split AWA experiment including model and training options', 'save TensorFlow model weights to a checkpoint file in the snapshots directory', 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'save and load TensorFlow model checkpoints to and from disk for resuming training', 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save or load TensorFlow model checkpoints to and from disk directories', 'run the split CUB continual learning experiment with specified architecture and importance method', 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run save or load TensorFlow checkpoint weights for model persistence across training tasks', 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence']
```

Usage

```
{'run_split_awa_experiment': 'run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train_task_sequence': 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test_task_sequence': 'test the trained model on a task sequence and compute per-task accuracy', 'get_arguments': 'parse command line arguments for the split AWA experiment including model and training options', 'save_model_checkpoint': 'save TensorFlow model weights to a checkpoint file in the snapshots directory'}
```

## File: facebookresearch_agem/conv_split_awa_hybrid.py

Prompts

```
['run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test the trained model on a task sequence and compute per-task accuracy', 'parse command line arguments for the split AWA experiment including model and training options', 'save TensorFlow model weights to a checkpoint file in the snapshots directory', 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'save and load TensorFlow model checkpoints to and from disk for resuming training', 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save or load TensorFlow model checkpoints to and from disk directories', 'run the split CUB continual learning experiment with specified architecture and importance method', 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run save or load TensorFlow checkpoint weights for model persistence across training tasks', 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence']
```

Usage

```
{'run_split_awa_hybrid_training': 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'train_task_sequence': 'train a sequence of tasks using LLL methods like A-GEM, EWC, PI, MAS, or RWALK', 'test_task_sequence': 'test the trained model on a task sequence and compute per-task accuracy across all tasks', 'get_arguments': 'parse CLI arguments for architecture, optimizer, learning rate, batch size, and importance method', 'save_load_checkpoints': 'save and load TensorFlow model checkpoints to and from disk for resuming training'}
```

## File: facebookresearch_agem/conv_split_cifar.py

Prompts

```
['run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test the trained model on a task sequence and compute per-task accuracy', 'parse command line arguments for the split AWA experiment including model and training options', 'save TensorFlow model weights to a checkpoint file in the snapshots directory', 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'save and load TensorFlow model checkpoints to and from disk for resuming training', 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save or load TensorFlow model checkpoints to and from disk directories', 'run the split CUB continual learning experiment with specified architecture and importance method', 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run save or load TensorFlow checkpoint weights for model persistence across training tasks', 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence']
```

Usage

```
{'run_split_cifar_training': 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run_train_task_sequence': 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run_test_task_sequence': 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create_get_arguments_parser': 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save_load_model_checkpoints': 'save or load TensorFlow model checkpoints to and from disk directories'}
```

## File: facebookresearch_agem/conv_split_cub.py

Prompts

```
['run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test the trained model on a task sequence and compute per-task accuracy', 'parse command line arguments for the split AWA experiment including model and training options', 'save TensorFlow model weights to a checkpoint file in the snapshots directory', 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'save and load TensorFlow model checkpoints to and from disk for resuming training', 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save or load TensorFlow model checkpoints to and from disk directories', 'run the split CUB continual learning experiment with specified architecture and importance method', 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run save or load TensorFlow checkpoint weights for model persistence across training tasks', 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence']
```

Usage

```
{'run_split_cub_training': 'run the split CUB continual learning experiment with specified architecture and importance method', 'train_task_sequence': 'train a sequence of tasks using LLL methods like EWC, PI, MAS, or A-GEM', 'test_task_sequence': 'test the model accuracy across all previously seen tasks in the sequence', 'get_arguments': 'parse CLI arguments for the split CUB experiment including architecture, optimizer, and model options', 'save_load_checkpoints': 'save or load TensorFlow model checkpoints to and from disk for resuming training'}
```

## File: facebookresearch_agem/conv_split_cub_hybrid.py

Prompts

```
['run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test the trained model on a task sequence and compute per-task accuracy', 'parse command line arguments for the split AWA experiment including model and training options', 'save TensorFlow model weights to a checkpoint file in the snapshots directory', 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'save and load TensorFlow model checkpoints to and from disk for resuming training', 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save or load TensorFlow model checkpoints to and from disk directories', 'run the split CUB continual learning experiment with specified architecture and importance method', 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run save or load TensorFlow checkpoint weights for model persistence across training tasks', 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence']
```

Usage

```
{'run_split_cub_training': 'run the split CUB continual learning experiment with A-GEM, EWC, or other LLL methods via CLI', 'run_train_task_sequence': 'run the lifelong learning task sequence training loop with episodic memory and gradient projection', 'run_test_task_sequence': 'run evaluation across all seen tasks to snapshot accuracy for each task in the sequence', 'run_get_arguments': 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run_save_load_checkpoints': 'run save or load TensorFlow checkpoint weights for model persistence across training tasks'}
```

## File: facebookresearch_agem/fc_permute_mnist.py

Prompts

```
['run a split AWA continual learning experiment with configurable model architecture and optimizer', 'train a lifelong learning model across a sequence of tasks with episodic memory support', 'test the trained model on a task sequence and compute per-task accuracy', 'parse command line arguments for the split AWA experiment including model and training options', 'save TensorFlow model weights to a checkpoint file in the snapshots directory', 'run the split AWA hybrid continual learning experiment with A-GEM or EWC importance methods', 'save and load TensorFlow model checkpoints to and from disk for resuming training', 'run the split CIFAR 100 continual learning experiment with argparse CLI options', 'run the lifelong learning task sequence training loop across multiple tasks and runs', 'run evaluation of model accuracy across all previously seen tasks in the sequence', 'create an argparse CLI parser for split CIFAR experiment hyperparameters and model options', 'save or load TensorFlow model checkpoints to and from disk directories', 'run the split CUB continual learning experiment with specified architecture and importance method', 'run the CLI argument parser to configure architecture, optimizer, learning rate, and importance method', 'run save or load TensorFlow checkpoint weights for model persistence across training tasks', 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence']
```

Usage

```
{'run_permute_mnist_training': 'run the permute MNIST continual learning experiment with EWC or A-GEM importance method via CLI', 'run_cross_validate_permute_mnist': 'run the permute MNIST experiment in cross-validation mode to dump accuracy results to a text file', 'run_single_epoch_training': 'run the permute MNIST training for a single epoch instead of fixed iterations per task', 'review_train_task_sequence': 'review the train_task_sequence function that trains a sequence of tasks using LLL methods like EWC or A-GEM', 'review_test_task_sequence': 'review the test_task_sequence function that evaluates model accuracy across all tasks in the sequence'}
```

