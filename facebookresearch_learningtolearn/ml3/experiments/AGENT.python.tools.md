# Agent Python Tools

- repo: facebookresearch/learningtolearn
- repo_uri: https://github.com/facebookresearch/learningtolearn

## File: facebookresearch_learningtolearn/ml3/experiments/run_mbrl_reacher_exp.py

Prompts

```
['run the MBRL reacher experiment training loop with random babbling data collection and meta-training', 'run the MBRL reacher experiment test mode to evaluate learned policy against a target goal', 'create a Task_loss callable that computes endpoint distance, trajectory distance, and action regularization loss', 'run random babbling to collect state-action trajectory data from a ReacherSimulation environment', 'test the learned ML3 loss function by optimizing a reacher policy against a target joint configuration', 'run meta training for the shaped sine model with configurable outer iterations and task count', 'test the ML3 loss on a shaped sine model with a fixed frequency test set', 'generate a batch of random sinusoid samples with configurable frequency and input ranges', 'create a callable task loss function that computes MSE on outputs or shaped thetas', 'save and load the shaped sine model state dict to and from a PyTorch checkpoint file']
```

Usage

```
{'run_mbrl_reacher_train': 'run the MBRL reacher experiment training loop with random babbling data collection and meta-training', 'run_mbrl_reacher_test': 'run the MBRL reacher experiment test mode to evaluate learned policy against a target goal', 'create_task_loss': 'create a Task_loss callable that computes endpoint distance, trajectory distance, and action regularization loss', 'run_random_babbling': 'run random babbling to collect state-action trajectory data from a ReacherSimulation environment', 'test_ml3_loss_reacher': 'test the learned ML3 loss function by optimizing a reacher policy against a target joint configuration'}
```

## File: facebookresearch_learningtolearn/ml3/experiments/run_shaped_sine_exp.py

Prompts

```
['run the MBRL reacher experiment training loop with random babbling data collection and meta-training', 'run the MBRL reacher experiment test mode to evaluate learned policy against a target goal', 'create a Task_loss callable that computes endpoint distance, trajectory distance, and action regularization loss', 'run random babbling to collect state-action trajectory data from a ReacherSimulation environment', 'test the learned ML3 loss function by optimizing a reacher policy against a target joint configuration', 'run meta training for the shaped sine model with configurable outer iterations and task count', 'test the ML3 loss on a shaped sine model with a fixed frequency test set', 'generate a batch of random sinusoid samples with configurable frequency and input ranges', 'create a callable task loss function that computes MSE on outputs or shaped thetas', 'save and load the shaped sine model state dict to and from a PyTorch checkpoint file']
```

Usage

```
{'run_meta_train_shaped_sine': 'run meta training for the shaped sine model with configurable outer iterations and task count', 'run_test_ml3_loss_shaped_sine': 'test the ML3 loss on a shaped sine model with a fixed frequency test set', 'generate_sinusoid_batch': 'generate a batch of random sinusoid samples with configurable frequency and input ranges', 'create_task_loss_callable': 'create a callable task loss function that computes MSE on outputs or shaped thetas', 'save_and_load_shaped_sine_model': 'save and load the shaped sine model state dict to and from a PyTorch checkpoint file'}
```

