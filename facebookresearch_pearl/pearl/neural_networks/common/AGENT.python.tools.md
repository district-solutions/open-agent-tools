# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/neural_networks/common/epistemic_neural_networks.py

Prompts

```
['build an MLPWithPrior model with prior regularization for Bayesian neural network inference', 'build an Ensemble epistemic neural network with multiple particles to model posterior distributions', 'build an Epinet model combining a trainable epinet and fixed priornet for epistemic uncertainty', 'review the Priornet class that maintains an ensemble of randomly initialized frozen models', 'test the EpistemicNeuralNetwork abstract base class forward method signature and contract', 'build a residual network by wrapping layers with ResidualWrapper in a Sequential model', 'create a ResidualWrapper instance that wraps a single nn.Module for residual connections', 'test the ResidualWrapper forward pass to verify it returns input plus module output', 'review the ResidualWrapper constructor to confirm it stores the wrapped module as an attribute', 'summarize the ResidualWrapper class which adds residual skip connections to any nn.Module', 'build an MLP neural network module with configurable hidden layers, batch norm, and skip connections', 'build a convolutional neural network block with configurable kernel sizes, strides, and batch normalization', 'run forward pass on multiple models and stack their outputs as a tensor', 'soft update a target network parameters using a source network with tau interpolation factor', 'compute the flattened output dimension of a CNN model given input shape parameters', 'create a VanillaValueNetwork with specified input_dim and hidden_dims for value estimation', 'create a CNNValueNetwork with convolutional and MLP blocks for image-based value estimation', 'run forward pass on VanillaValueNetwork to compute scalar value from input tensor', 'run forward pass on CNNValueNetwork to compute value from image tensor input', 'initialize VanillaValueNetwork linear layer weights using Xavier normal initialization']
```

Usage

```
{'build_MLPWithPrior': 'build an MLPWithPrior model with prior regularization for Bayesian neural network inference', 'build_Ensemble': 'build an Ensemble epistemic neural network with multiple particles to model posterior distributions', 'build_Epinet': 'build an Epinet model combining a trainable epinet and fixed priornet for epistemic uncertainty', 'review_Priornet': 'review the Priornet class that maintains an ensemble of randomly initialized frozen models', 'test_EpistemicNeuralNetwork': 'test the EpistemicNeuralNetwork abstract base class forward method signature and contract'}
```

## File: facebookresearch_pearl/pearl/neural_networks/common/residual_wrapper.py

Prompts

```
['build an MLPWithPrior model with prior regularization for Bayesian neural network inference', 'build an Ensemble epistemic neural network with multiple particles to model posterior distributions', 'build an Epinet model combining a trainable epinet and fixed priornet for epistemic uncertainty', 'review the Priornet class that maintains an ensemble of randomly initialized frozen models', 'test the EpistemicNeuralNetwork abstract base class forward method signature and contract', 'build a residual network by wrapping layers with ResidualWrapper in a Sequential model', 'create a ResidualWrapper instance that wraps a single nn.Module for residual connections', 'test the ResidualWrapper forward pass to verify it returns input plus module output', 'review the ResidualWrapper constructor to confirm it stores the wrapped module as an attribute', 'summarize the ResidualWrapper class which adds residual skip connections to any nn.Module', 'build an MLP neural network module with configurable hidden layers, batch norm, and skip connections', 'build a convolutional neural network block with configurable kernel sizes, strides, and batch normalization', 'run forward pass on multiple models and stack their outputs as a tensor', 'soft update a target network parameters using a source network with tau interpolation factor', 'compute the flattened output dimension of a CNN model given input shape parameters', 'create a VanillaValueNetwork with specified input_dim and hidden_dims for value estimation', 'create a CNNValueNetwork with convolutional and MLP blocks for image-based value estimation', 'run forward pass on VanillaValueNetwork to compute scalar value from input tensor', 'run forward pass on CNNValueNetwork to compute value from image tensor input', 'initialize VanillaValueNetwork linear layer weights using Xavier normal initialization']
```

Usage

```
{'build_residual_network': 'build a residual network by wrapping layers with ResidualWrapper in a Sequential model', 'create_ResidualWrapper': 'create a ResidualWrapper instance that wraps a single nn.Module for residual connections', 'test_ResidualWrapper_forward': 'test the ResidualWrapper forward pass to verify it returns input plus module output', 'review_ResidualWrapper_init': 'review the ResidualWrapper constructor to confirm it stores the wrapped module as an attribute', 'summarize_ResidualWrapper': 'summarize the ResidualWrapper class which adds residual skip connections to any nn.Module'}
```

## File: facebookresearch_pearl/pearl/neural_networks/common/utils.py

Prompts

```
['build an MLPWithPrior model with prior regularization for Bayesian neural network inference', 'build an Ensemble epistemic neural network with multiple particles to model posterior distributions', 'build an Epinet model combining a trainable epinet and fixed priornet for epistemic uncertainty', 'review the Priornet class that maintains an ensemble of randomly initialized frozen models', 'test the EpistemicNeuralNetwork abstract base class forward method signature and contract', 'build a residual network by wrapping layers with ResidualWrapper in a Sequential model', 'create a ResidualWrapper instance that wraps a single nn.Module for residual connections', 'test the ResidualWrapper forward pass to verify it returns input plus module output', 'review the ResidualWrapper constructor to confirm it stores the wrapped module as an attribute', 'summarize the ResidualWrapper class which adds residual skip connections to any nn.Module', 'build an MLP neural network module with configurable hidden layers, batch norm, and skip connections', 'build a convolutional neural network block with configurable kernel sizes, strides, and batch normalization', 'run forward pass on multiple models and stack their outputs as a tensor', 'soft update a target network parameters using a source network with tau interpolation factor', 'compute the flattened output dimension of a CNN model given input shape parameters', 'create a VanillaValueNetwork with specified input_dim and hidden_dims for value estimation', 'create a CNNValueNetwork with convolutional and MLP blocks for image-based value estimation', 'run forward pass on VanillaValueNetwork to compute scalar value from input tensor', 'run forward pass on CNNValueNetwork to compute value from image tensor input', 'initialize VanillaValueNetwork linear layer weights using Xavier normal initialization']
```

Usage

```
{'build_mlp_block': 'build an MLP neural network module with configurable hidden layers, batch norm, and skip connections', 'build_conv_block': 'build a convolutional neural network block with configurable kernel sizes, strides, and batch normalization', 'run_ensemble_forward': 'run forward pass on multiple models and stack their outputs as a tensor', 'update_target_network': 'soft update a target network parameters using a source network with tau interpolation factor', 'compute_cnn_output_dim': 'compute the flattened output dimension of a CNN model given input shape parameters'}
```

## File: facebookresearch_pearl/pearl/neural_networks/common/value_networks.py

Prompts

```
['build an MLPWithPrior model with prior regularization for Bayesian neural network inference', 'build an Ensemble epistemic neural network with multiple particles to model posterior distributions', 'build an Epinet model combining a trainable epinet and fixed priornet for epistemic uncertainty', 'review the Priornet class that maintains an ensemble of randomly initialized frozen models', 'test the EpistemicNeuralNetwork abstract base class forward method signature and contract', 'build a residual network by wrapping layers with ResidualWrapper in a Sequential model', 'create a ResidualWrapper instance that wraps a single nn.Module for residual connections', 'test the ResidualWrapper forward pass to verify it returns input plus module output', 'review the ResidualWrapper constructor to confirm it stores the wrapped module as an attribute', 'summarize the ResidualWrapper class which adds residual skip connections to any nn.Module', 'build an MLP neural network module with configurable hidden layers, batch norm, and skip connections', 'build a convolutional neural network block with configurable kernel sizes, strides, and batch normalization', 'run forward pass on multiple models and stack their outputs as a tensor', 'soft update a target network parameters using a source network with tau interpolation factor', 'compute the flattened output dimension of a CNN model given input shape parameters', 'create a VanillaValueNetwork with specified input_dim and hidden_dims for value estimation', 'create a CNNValueNetwork with convolutional and MLP blocks for image-based value estimation', 'run forward pass on VanillaValueNetwork to compute scalar value from input tensor', 'run forward pass on CNNValueNetwork to compute value from image tensor input', 'initialize VanillaValueNetwork linear layer weights using Xavier normal initialization']
```

Usage

```
{'create_vanilla_value_network': 'create a VanillaValueNetwork with specified input_dim and hidden_dims for value estimation', 'create_cnn_value_network': 'create a CNNValueNetwork with convolutional and MLP blocks for image-based value estimation', 'run_vanilla_forward': 'run forward pass on VanillaValueNetwork to compute scalar value from input tensor', 'run_cnn_forward': 'run forward pass on CNNValueNetwork to compute value from image tensor input', 'init_vanilla_xavier': 'initialize VanillaValueNetwork linear layer weights using Xavier normal initialization'}
```

