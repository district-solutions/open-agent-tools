# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/notebooks/_src/plot_ensembling.py

Prompts

```
['build a simple CNN model with two conv layers and two fully connected layers for MNIST classification', 'create an ensemble by stacking parameters from multiple models using combine_state_for_ensemble from functorch', 'run vmap on an ensemble of models with different minibatches for each model to vectorize predictions', 'run vmap with in_dims set to None to apply the same minibatch across all ensemble models', 'review the SimpleCNN forward pass which applies conv layers, ReLU, max pooling, and fully connected layers', 'compute the Jacobian of a neural network function using functorch jacrev with reverse-mode autodiff', 'compute the Jacobian of a neural network function using functorch jacfwd with forward-mode autodiff', 'compute the Hessian matrix of a prediction function using functorch hessian for second-order derivatives', 'compute batched Jacobians by composing vmap with jacrev over a batch of input tensors', 'compute batched Hessians by composing vmap with hessian over a batch of input tensors', 'create a SimpleCNN model with two conv layers and two fully connected layers for MNIST classification', 'compute the gradient for a single data sample using autograd and the model parameters', 'compute per-sample gradients for an entire batch of data by iterating over each sample', 'compute the loss for a single sample using a functional model with explicit params and buffers', 'use functorch vmap and grad to efficiently compute per-sample gradients across a batch of data']
```

Usage

```
{'build_SimpleCNN': 'build a simple CNN model with two conv layers and two fully connected layers for MNIST classification', 'create_combine_state_for_ensemble': 'create an ensemble by stacking parameters from multiple models using combine_state_for_ensemble from functorch', 'run_vmap_ensemble_different_minibatches': 'run vmap on an ensemble of models with different minibatches for each model to vectorize predictions', 'run_vmap_ensemble_same_minibatch': 'run vmap with in_dims set to None to apply the same minibatch across all ensemble models', 'review_SimpleCNN_forward': 'review the SimpleCNN forward pass which applies conv layers, ReLU, max pooling, and fully connected layers'}
```

## File: facebookresearch_torchdim/third_party/functorch/notebooks/_src/plot_jacobians_and_hessians.py

Prompts

```
['build a simple CNN model with two conv layers and two fully connected layers for MNIST classification', 'create an ensemble by stacking parameters from multiple models using combine_state_for_ensemble from functorch', 'run vmap on an ensemble of models with different minibatches for each model to vectorize predictions', 'run vmap with in_dims set to None to apply the same minibatch across all ensemble models', 'review the SimpleCNN forward pass which applies conv layers, ReLU, max pooling, and fully connected layers', 'compute the Jacobian of a neural network function using functorch jacrev with reverse-mode autodiff', 'compute the Jacobian of a neural network function using functorch jacfwd with forward-mode autodiff', 'compute the Hessian matrix of a prediction function using functorch hessian for second-order derivatives', 'compute batched Jacobians by composing vmap with jacrev over a batch of input tensors', 'compute batched Hessians by composing vmap with hessian over a batch of input tensors', 'create a SimpleCNN model with two conv layers and two fully connected layers for MNIST classification', 'compute the gradient for a single data sample using autograd and the model parameters', 'compute per-sample gradients for an entire batch of data by iterating over each sample', 'compute the loss for a single sample using a functional model with explicit params and buffers', 'use functorch vmap and grad to efficiently compute per-sample gradients across a batch of data']
```

Usage

```
{'compute_jacobian_with_jacrev': 'compute the Jacobian of a neural network function using functorch jacrev with reverse-mode autodiff', 'compute_jacobian_with_jacfwd': 'compute the Jacobian of a neural network function using functorch jacfwd with forward-mode autodiff', 'compute_hessian_with_hessian': 'compute the Hessian matrix of a prediction function using functorch hessian for second-order derivatives', 'compute_batch_jacobian_with_vmap': 'compute batched Jacobians by composing vmap with jacrev over a batch of input tensors', 'compute_batch_hessian_with_vmap': 'compute batched Hessians by composing vmap with hessian over a batch of input tensors'}
```

## File: facebookresearch_torchdim/third_party/functorch/notebooks/_src/plot_per_sample_gradients.py

Prompts

```
['build a simple CNN model with two conv layers and two fully connected layers for MNIST classification', 'create an ensemble by stacking parameters from multiple models using combine_state_for_ensemble from functorch', 'run vmap on an ensemble of models with different minibatches for each model to vectorize predictions', 'run vmap with in_dims set to None to apply the same minibatch across all ensemble models', 'review the SimpleCNN forward pass which applies conv layers, ReLU, max pooling, and fully connected layers', 'compute the Jacobian of a neural network function using functorch jacrev with reverse-mode autodiff', 'compute the Jacobian of a neural network function using functorch jacfwd with forward-mode autodiff', 'compute the Hessian matrix of a prediction function using functorch hessian for second-order derivatives', 'compute batched Jacobians by composing vmap with jacrev over a batch of input tensors', 'compute batched Hessians by composing vmap with hessian over a batch of input tensors', 'create a SimpleCNN model with two conv layers and two fully connected layers for MNIST classification', 'compute the gradient for a single data sample using autograd and the model parameters', 'compute per-sample gradients for an entire batch of data by iterating over each sample', 'compute the loss for a single sample using a functional model with explicit params and buffers', 'use functorch vmap and grad to efficiently compute per-sample gradients across a batch of data']
```

Usage

```
{'create_SimpleCNN': 'create a SimpleCNN model with two conv layers and two fully connected layers for MNIST classification', 'compute_grad_single_sample': 'compute the gradient for a single data sample using autograd and the model parameters', 'compute_sample_grads_batch': 'compute per-sample gradients for an entire batch of data by iterating over each sample', 'compute_loss_functional_model': 'compute the loss for a single sample using a functional model with explicit params and buffers', 'vmap_per_sample_gradients': 'use functorch vmap and grad to efficiently compute per-sample gradients across a batch of data'}
```

