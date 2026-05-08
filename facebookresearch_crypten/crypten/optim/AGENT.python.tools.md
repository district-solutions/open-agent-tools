# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/optim/optimizer.py

Prompts

```
['create an Optimizer instance to optimize CrypTensor parameters in a CrypTen model', 'add a new parameter group with tensors and options to an existing Optimizer', 'zero all optimizer gradients by setting them to None for lower memory footprint', 'zero all optimizer gradients by subtracting them from themselves instead of setting to None', 'review the Optimizer base class adapted from torch.optim.Optimizer to work with CrypTensors', 'create an SGD optimizer with a learning rate and momentum for model parameters', 'create an SGD optimizer with Nesterov momentum enabled for accelerated convergence', 'create an SGD optimizer with L2 weight decay regularization for model parameters', 'create an SGD optimizer with gradient thresholding to prevent gradient explosion', 'run a single optimization step on the SGD optimizer to update model parameters']
```

Usage

```
{'create_optimizer_for_cryptensors': 'create an Optimizer instance to optimize CrypTensor parameters in a CrypTen model', 'add_param_group_to_optimizer': 'add a new parameter group with tensors and options to an existing Optimizer', 'zero_grad_set_to_none': 'zero all optimizer gradients by setting them to None for lower memory footprint', 'zero_grad_set_to_zero': 'zero all optimizer gradients by subtracting them from themselves instead of setting to None', 'review_optimizer_base_class': 'review the Optimizer base class adapted from torch.optim.Optimizer to work with CrypTensors'}
```

## File: facebookresearch_crypten/crypten/optim/sgd.py

Prompts

```
['create an Optimizer instance to optimize CrypTensor parameters in a CrypTen model', 'add a new parameter group with tensors and options to an existing Optimizer', 'zero all optimizer gradients by setting them to None for lower memory footprint', 'zero all optimizer gradients by subtracting them from themselves instead of setting to None', 'review the Optimizer base class adapted from torch.optim.Optimizer to work with CrypTensors', 'create an SGD optimizer with a learning rate and momentum for model parameters', 'create an SGD optimizer with Nesterov momentum enabled for accelerated convergence', 'create an SGD optimizer with L2 weight decay regularization for model parameters', 'create an SGD optimizer with gradient thresholding to prevent gradient explosion', 'run a single optimization step on the SGD optimizer to update model parameters']
```

Usage

```
{'create_SGD_optimizer': 'create an SGD optimizer with a learning rate and momentum for model parameters', 'create_SGD_with_nesterov': 'create an SGD optimizer with Nesterov momentum enabled for accelerated convergence', 'create_SGD_with_weight_decay': 'create an SGD optimizer with L2 weight decay regularization for model parameters', 'create_SGD_with_grad_threshold': 'create an SGD optimizer with gradient thresholding to prevent gradient explosion', 'run_SGD_step': 'run a single optimization step on the SGD optimizer to update model parameters'}
```

