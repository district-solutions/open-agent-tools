# Agent Python Tools

- repo: facebookresearch/ai4animationpy
- repo_uri: https://github.com/facebookresearch/ai4animationpy

## File: facebookresearch_ai4animationpy/ai4animation/AI/Library/Blocks.py

Prompts

```
['build a 3-layer LinearBlock neural network module with configurable input, hidden, and output sizes', 'build a 3-layer FiLMLinearBlock neural network module conditioned on external FiLM parameters', 'build a RegularizedFiLMLinearBlock that returns regularization outputs during training and predictions during inference', 'review the LinearBlock forward pass that chains three LinearLayer modules sequentially', 'review the RegularizedFiLMLinearBlock forward method that conditionally returns regularization outputs when in training mode', 'build a LinearLayer module with configurable input size, output size, dropout, and activation function', 'build a FiLMLayer module that applies feature-wise linear modulation using scale and shift parameters', 'build a FiLMLinearLayer module that combines FiLM modulation with a linear transformation layer', 'build a VariationalLayer module that samples from a learned distribution and computes KL divergence', 'build a CodebookLayer module that performs Gumbel-Softmax sampling or softmax over class embeddings', 'apply softmax normalization to a logits tensor with a specified number of classes', 'apply soft Gumbel-softmax sampling to logits with configurable temperature for differentiable relaxation', 'apply hard Gumbel-softmax sampling to logits using the straight-through estimator for discrete one-hot output', 'apply Gumbel-softmax sampling to logits using a custom noise tensor instead of random noise', 'review how changing the temperature parameter affects the sharpness of Gumbel-softmax output distributions', 'create a RunningStatistics module to compute running mean and standard deviation for a given dimension', 'update the RunningStatistics module with new tensor data to incrementally compute mean and variance', 'normalize a PyTorch tensor using the RunningStatistics mean and standard deviation', 'denormalize a PyTorch tensor back to original scale using RunningStatistics mean and standard deviation', 'clear the RunningStatistics state to reset the running mean and variance counters']
```

Usage

```
{'build_linearblock': 'build a 3-layer LinearBlock neural network module with configurable input, hidden, and output sizes', 'build_filmlinearblock': 'build a 3-layer FiLMLinearBlock neural network module conditioned on external FiLM parameters', 'build_regularizedfilmlinearblock': 'build a RegularizedFiLMLinearBlock that returns regularization outputs during training and predictions during inference', 'review_linearblock_forward': 'review the LinearBlock forward pass that chains three LinearLayer modules sequentially', 'review_regularizedfilmlinearblock_training': 'review the RegularizedFiLMLinearBlock forward method that conditionally returns regularization outputs when in training mode'}
```

## File: facebookresearch_ai4animationpy/ai4animation/AI/Library/Layers.py

Prompts

```
['build a 3-layer LinearBlock neural network module with configurable input, hidden, and output sizes', 'build a 3-layer FiLMLinearBlock neural network module conditioned on external FiLM parameters', 'build a RegularizedFiLMLinearBlock that returns regularization outputs during training and predictions during inference', 'review the LinearBlock forward pass that chains three LinearLayer modules sequentially', 'review the RegularizedFiLMLinearBlock forward method that conditionally returns regularization outputs when in training mode', 'build a LinearLayer module with configurable input size, output size, dropout, and activation function', 'build a FiLMLayer module that applies feature-wise linear modulation using scale and shift parameters', 'build a FiLMLinearLayer module that combines FiLM modulation with a linear transformation layer', 'build a VariationalLayer module that samples from a learned distribution and computes KL divergence', 'build a CodebookLayer module that performs Gumbel-Softmax sampling or softmax over class embeddings', 'apply softmax normalization to a logits tensor with a specified number of classes', 'apply soft Gumbel-softmax sampling to logits with configurable temperature for differentiable relaxation', 'apply hard Gumbel-softmax sampling to logits using the straight-through estimator for discrete one-hot output', 'apply Gumbel-softmax sampling to logits using a custom noise tensor instead of random noise', 'review how changing the temperature parameter affects the sharpness of Gumbel-softmax output distributions', 'create a RunningStatistics module to compute running mean and standard deviation for a given dimension', 'update the RunningStatistics module with new tensor data to incrementally compute mean and variance', 'normalize a PyTorch tensor using the RunningStatistics mean and standard deviation', 'denormalize a PyTorch tensor back to original scale using RunningStatistics mean and standard deviation', 'clear the RunningStatistics state to reset the running mean and variance counters']
```

Usage

```
{'build_LinearLayer': 'build a LinearLayer module with configurable input size, output size, dropout, and activation function', 'build_FiLMLayer': 'build a FiLMLayer module that applies feature-wise linear modulation using scale and shift parameters', 'build_FiLMLinearLayer': 'build a FiLMLinearLayer module that combines FiLM modulation with a linear transformation layer', 'build_VariationalLayer': 'build a VariationalLayer module that samples from a learned distribution and computes KL divergence', 'build_CodebookLayer': 'build a CodebookLayer module that performs Gumbel-Softmax sampling or softmax over class embeddings'}
```

## File: facebookresearch_ai4animationpy/ai4animation/AI/Library/Manifolds.py

Prompts

```
['build a 3-layer LinearBlock neural network module with configurable input, hidden, and output sizes', 'build a 3-layer FiLMLinearBlock neural network module conditioned on external FiLM parameters', 'build a RegularizedFiLMLinearBlock that returns regularization outputs during training and predictions during inference', 'review the LinearBlock forward pass that chains three LinearLayer modules sequentially', 'review the RegularizedFiLMLinearBlock forward method that conditionally returns regularization outputs when in training mode', 'build a LinearLayer module with configurable input size, output size, dropout, and activation function', 'build a FiLMLayer module that applies feature-wise linear modulation using scale and shift parameters', 'build a FiLMLinearLayer module that combines FiLM modulation with a linear transformation layer', 'build a VariationalLayer module that samples from a learned distribution and computes KL divergence', 'build a CodebookLayer module that performs Gumbel-Softmax sampling or softmax over class embeddings', 'apply softmax normalization to a logits tensor with a specified number of classes', 'apply soft Gumbel-softmax sampling to logits with configurable temperature for differentiable relaxation', 'apply hard Gumbel-softmax sampling to logits using the straight-through estimator for discrete one-hot output', 'apply Gumbel-softmax sampling to logits using a custom noise tensor instead of random noise', 'review how changing the temperature parameter affects the sharpness of Gumbel-softmax output distributions', 'create a RunningStatistics module to compute running mean and standard deviation for a given dimension', 'update the RunningStatistics module with new tensor data to incrementally compute mean and variance', 'normalize a PyTorch tensor using the RunningStatistics mean and standard deviation', 'denormalize a PyTorch tensor back to original scale using RunningStatistics mean and standard deviation', 'clear the RunningStatistics state to reset the running mean and variance counters']
```

Usage

```
{'apply_softmax_to_logits': 'apply softmax normalization to a logits tensor with a specified number of classes', 'apply_gumbel_softmax_soft': 'apply soft Gumbel-softmax sampling to logits with configurable temperature for differentiable relaxation', 'apply_gumbel_softmax_hard': 'apply hard Gumbel-softmax sampling to logits using the straight-through estimator for discrete one-hot output', 'apply_gumbel_with_custom_noise': 'apply Gumbel-softmax sampling to logits using a custom noise tensor instead of random noise', 'review_gumbel_temperature_effect': 'review how changing the temperature parameter affects the sharpness of Gumbel-softmax output distributions'}
```

## File: facebookresearch_ai4animationpy/ai4animation/AI/Library/Statistics.py

Prompts

```
['build a 3-layer LinearBlock neural network module with configurable input, hidden, and output sizes', 'build a 3-layer FiLMLinearBlock neural network module conditioned on external FiLM parameters', 'build a RegularizedFiLMLinearBlock that returns regularization outputs during training and predictions during inference', 'review the LinearBlock forward pass that chains three LinearLayer modules sequentially', 'review the RegularizedFiLMLinearBlock forward method that conditionally returns regularization outputs when in training mode', 'build a LinearLayer module with configurable input size, output size, dropout, and activation function', 'build a FiLMLayer module that applies feature-wise linear modulation using scale and shift parameters', 'build a FiLMLinearLayer module that combines FiLM modulation with a linear transformation layer', 'build a VariationalLayer module that samples from a learned distribution and computes KL divergence', 'build a CodebookLayer module that performs Gumbel-Softmax sampling or softmax over class embeddings', 'apply softmax normalization to a logits tensor with a specified number of classes', 'apply soft Gumbel-softmax sampling to logits with configurable temperature for differentiable relaxation', 'apply hard Gumbel-softmax sampling to logits using the straight-through estimator for discrete one-hot output', 'apply Gumbel-softmax sampling to logits using a custom noise tensor instead of random noise', 'review how changing the temperature parameter affects the sharpness of Gumbel-softmax output distributions', 'create a RunningStatistics module to compute running mean and standard deviation for a given dimension', 'update the RunningStatistics module with new tensor data to incrementally compute mean and variance', 'normalize a PyTorch tensor using the RunningStatistics mean and standard deviation', 'denormalize a PyTorch tensor back to original scale using RunningStatistics mean and standard deviation', 'clear the RunningStatistics state to reset the running mean and variance counters']
```

Usage

```
{'create_running_statistics': 'create a RunningStatistics module to compute running mean and standard deviation for a given dimension', 'update_running_statistics': 'update the RunningStatistics module with new tensor data to incrementally compute mean and variance', 'normalize_tensor': 'normalize a PyTorch tensor using the RunningStatistics mean and standard deviation', 'denormalize_tensor': 'denormalize a PyTorch tensor back to original scale using RunningStatistics mean and standard deviation', 'clear_running_statistics': 'clear the RunningStatistics state to reset the running mean and variance counters'}
```

