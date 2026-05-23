# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/examples/maml_regression/evjang.py

Prompts

```
['run the MAML meta-learning sine wave regression training loop for 20000 iterations', 'review the net function that defines a 3-layer neural network with ReLU activations', 'test the sample_tasks function that generates sine wave regression tasks with random amplitude and phase', 'summarize the MAML training loop that uses higher-order gradients via create_graph=True', 'refactor the get_loss_for_task function to compute inner-loop loss with gradient-based parameter updates', 'run the MAML training loop for sine wave regression using functorch grad and vmap', 'create a 3-layer neural network forward pass using functional PyTorch linear and relu', 'sample sine wave regression tasks with random amplitude and phase for meta-learning', 'compute mean squared error loss between predicted and target tensors', 'adapt network parameters on a test task using autograd gradient steps', 'build a MAML meta-learning model for sine wave regression using functorch grad and vmap', 'create a ThreeLayerNet neural network with two hidden layers of 40 neurons each', 'sample sine wave regression tasks with random amplitude and phase for meta-learning training', 'run a meta-gradient update step using functorch grad to compute inner loop gradients', 'review the MAML training loop that uses vmap to vectorize loss computation across tasks']
```

Usage

```
{'run_maml_sine_regression': 'run the MAML meta-learning sine wave regression training loop for 20000 iterations', 'review_net_function': 'review the net function that defines a 3-layer neural network with ReLU activations', 'test_sample_tasks': 'test the sample_tasks function that generates sine wave regression tasks with random amplitude and phase', 'summarize_maml_training_loop': 'summarize the MAML training loop that uses higher-order gradients via create_graph=True', 'refactor_get_loss_for_task': 'refactor the get_loss_for_task function to compute inner-loop loss with gradient-based parameter updates'}
```

## File: facebookresearch_torchdim/third_party/functorch/examples/maml_regression/evjang_transforms.py

Prompts

```
['run the MAML meta-learning sine wave regression training loop for 20000 iterations', 'review the net function that defines a 3-layer neural network with ReLU activations', 'test the sample_tasks function that generates sine wave regression tasks with random amplitude and phase', 'summarize the MAML training loop that uses higher-order gradients via create_graph=True', 'refactor the get_loss_for_task function to compute inner-loop loss with gradient-based parameter updates', 'run the MAML training loop for sine wave regression using functorch grad and vmap', 'create a 3-layer neural network forward pass using functional PyTorch linear and relu', 'sample sine wave regression tasks with random amplitude and phase for meta-learning', 'compute mean squared error loss between predicted and target tensors', 'adapt network parameters on a test task using autograd gradient steps', 'build a MAML meta-learning model for sine wave regression using functorch grad and vmap', 'create a ThreeLayerNet neural network with two hidden layers of 40 neurons each', 'sample sine wave regression tasks with random amplitude and phase for meta-learning training', 'run a meta-gradient update step using functorch grad to compute inner loop gradients', 'review the MAML training loop that uses vmap to vectorize loss computation across tasks']
```

Usage

```
{'run_maml_training': 'run the MAML training loop for sine wave regression using functorch grad and vmap', 'create_net_forward': 'create a 3-layer neural network forward pass using functional PyTorch linear and relu', 'sample_sine_tasks': 'sample sine wave regression tasks with random amplitude and phase for meta-learning', 'compute_mse_loss': 'compute mean squared error loss between predicted and target tensors', 'adapt_test_task': 'adapt network parameters on a test task using autograd gradient steps'}
```

## File: facebookresearch_torchdim/third_party/functorch/examples/maml_regression/evjang_transforms_module.py

Prompts

```
['run the MAML meta-learning sine wave regression training loop for 20000 iterations', 'review the net function that defines a 3-layer neural network with ReLU activations', 'test the sample_tasks function that generates sine wave regression tasks with random amplitude and phase', 'summarize the MAML training loop that uses higher-order gradients via create_graph=True', 'refactor the get_loss_for_task function to compute inner-loop loss with gradient-based parameter updates', 'run the MAML training loop for sine wave regression using functorch grad and vmap', 'create a 3-layer neural network forward pass using functional PyTorch linear and relu', 'sample sine wave regression tasks with random amplitude and phase for meta-learning', 'compute mean squared error loss between predicted and target tensors', 'adapt network parameters on a test task using autograd gradient steps', 'build a MAML meta-learning model for sine wave regression using functorch grad and vmap', 'create a ThreeLayerNet neural network with two hidden layers of 40 neurons each', 'sample sine wave regression tasks with random amplitude and phase for meta-learning training', 'run a meta-gradient update step using functorch grad to compute inner loop gradients', 'review the MAML training loop that uses vmap to vectorize loss computation across tasks']
```

Usage

```
{'build_maml_sine_regression': 'build a MAML meta-learning model for sine wave regression using functorch grad and vmap', 'create_three_layer_net': 'create a ThreeLayerNet neural network with two hidden layers of 40 neurons each', 'sample_sine_wave_tasks': 'sample sine wave regression tasks with random amplitude and phase for meta-learning training', 'run_meta_gradient_step': 'run a meta-gradient update step using functorch grad to compute inner loop gradients', 'review_maml_training_loop': 'review the MAML training loop that uses vmap to vectorize loss computation across tasks'}
```

