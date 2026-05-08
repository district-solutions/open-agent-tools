# Agent Python Tools

- repo: facebookresearch/higher
- repo_uri: https://github.com/facebookresearch/higher

## File: facebookresearch_higher/examples/deep-energy-mnist.py

Prompts

```
['run the MNIST classification example using SPEN mode with unrolled energy networks', 'run the MNIST classification example using ICNN mode with convex energy constraints', 'create an EnergyNet module that computes energy E(x, y) using LeNet-style conv and FC layers', 'create an UnrollEnergy module that unrolls gradient descent over the energy function using higher', 'train the energy network model on MNIST data with cross-entropy loss and ICNN weight projection', 'run the MAML few-shot Omniglot classification training loop with configurable n-way k-shot parameters', 'train a PyTorch model using higher.innerloop_ctx for differentiable inner-loop gradient steps on support sets', 'test the MAML model on few-shot Omniglot tasks with inner-loop adaptation and report accuracy', 'plot train and test accuracy curves over epochs and save as a PNG file', 'create a PyTorch nn.Module that flattens input tensors to 2D for use in sequential networks']
```

Usage

```
{'run_deep_energy_mnist_spen': 'run the MNIST classification example using SPEN mode with unrolled energy networks', 'run_deep_energy_mnist_icnn': 'run the MNIST classification example using ICNN mode with convex energy constraints', 'create_EnergyNet': 'create an EnergyNet module that computes energy E(x, y) using LeNet-style conv and FC layers', 'create_UnrollEnergy': 'create an UnrollEnergy module that unrolls gradient descent over the energy function using higher', 'train_EnergyNet': 'train the energy network model on MNIST data with cross-entropy loss and ICNN weight projection'}
```

## File: facebookresearch_higher/examples/maml-omniglot.py

Prompts

```
['run the MNIST classification example using SPEN mode with unrolled energy networks', 'run the MNIST classification example using ICNN mode with convex energy constraints', 'create an EnergyNet module that computes energy E(x, y) using LeNet-style conv and FC layers', 'create an UnrollEnergy module that unrolls gradient descent over the energy function using higher', 'train the energy network model on MNIST data with cross-entropy loss and ICNN weight projection', 'run the MAML few-shot Omniglot classification training loop with configurable n-way k-shot parameters', 'train a PyTorch model using higher.innerloop_ctx for differentiable inner-loop gradient steps on support sets', 'test the MAML model on few-shot Omniglot tasks with inner-loop adaptation and report accuracy', 'plot train and test accuracy curves over epochs and save as a PNG file', 'create a PyTorch nn.Module that flattens input tensors to 2D for use in sequential networks']
```

Usage

```
{'run_maml_omniglot_training': 'run the MAML few-shot Omniglot classification training loop with configurable n-way k-shot parameters', 'train_inner_loop_adaptation': 'train a PyTorch model using higher.innerloop_ctx for differentiable inner-loop gradient steps on support sets', 'test_maml_few_shot_accuracy': 'test the MAML model on few-shot Omniglot tasks with inner-loop adaptation and report accuracy', 'plot_training_accuracy_curves': 'plot train and test accuracy curves over epochs and save as a PNG file', 'create_flatten_module': 'create a PyTorch nn.Module that flattens input tensors to 2D for use in sequential networks'}
```

