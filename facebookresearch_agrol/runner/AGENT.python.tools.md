# Agent Python Tools

- repo: facebookresearch/agrol
- repo_uri: https://github.com/facebookresearch/agrol

## File: facebookresearch_agrol/runner/train_mlp.py

Prompts

```
['run a single training step for an MLP model with motion input and target data', 'run a multistep learning rate update that switches between max and min LR based on iteration', 'create a training step function that computes L2 loss between predicted and target motion data', 'create a multistep LR scheduler that anneals from max_lr to min_lr after a set number of steps', 'refactor the train_step function to support custom loss functions beyond L2 norm', 'run the TrainLoop class to train a diffusion model over multiple epochs with checkpoint saving', 'run the TrainLoop forward_backward method to compute diffusion training losses and perform backpropagation', 'create a TrainLoop instance with model, diffusion, data loader, and training hyperparameters', 'parse the resume step number from a model checkpoint filename like model000123.pt', 'log loss dictionary values and their quantile breakdowns across diffusion timesteps']
```

Usage

```
{'run_train_step': 'run a single training step for an MLP model with motion input and target data', 'run_update_lr_multistep': 'run a multistep learning rate update that switches between max and min LR based on iteration', 'create_train_step': 'create a training step function that computes L2 loss between predicted and target motion data', 'create_update_lr_multistep': 'create a multistep LR scheduler that anneals from max_lr to min_lr after a set number of steps', 'refactor_train_step': 'refactor the train_step function to support custom loss functions beyond L2 norm'}
```

## File: facebookresearch_agrol/runner/training_loop.py

Prompts

```
['run a single training step for an MLP model with motion input and target data', 'run a multistep learning rate update that switches between max and min LR based on iteration', 'create a training step function that computes L2 loss between predicted and target motion data', 'create a multistep LR scheduler that anneals from max_lr to min_lr after a set number of steps', 'refactor the train_step function to support custom loss functions beyond L2 norm', 'run the TrainLoop class to train a diffusion model over multiple epochs with checkpoint saving', 'run the TrainLoop forward_backward method to compute diffusion training losses and perform backpropagation', 'create a TrainLoop instance with model, diffusion, data loader, and training hyperparameters', 'parse the resume step number from a model checkpoint filename like model000123.pt', 'log loss dictionary values and their quantile breakdowns across diffusion timesteps']
```

Usage

```
{'run_TrainLoop_training': 'run the TrainLoop class to train a diffusion model over multiple epochs with checkpoint saving', 'run_TrainLoop_forward_backward': 'run the TrainLoop forward_backward method to compute diffusion training losses and perform backpropagation', 'create_TrainLoop_instance': 'create a TrainLoop instance with model, diffusion, data loader, and training hyperparameters', 'parse_resume_step_from_filename': 'parse the resume step number from a model checkpoint filename like model000123.pt', 'log_loss_dict_quantiles': 'log loss dictionary values and their quantile breakdowns across diffusion timesteps'}
```

