# Agent Python Tools

- repo: facebookresearch/clevr-iep
- repo_uri: https://github.com/facebookresearch/clevr-iep

## File: facebookresearch_clevr-iep/iep/models/baselines.py

Prompts

```
['build a CNN feature extractor with optional residual blocks and max pooling for image features', 'build a multi-layer perceptron classifier with optional batch normalization and dropout layers', 'create an LSTM encoder that embeds token sequences and extracts the last non-null hidden state', 'create a stacked attention module that computes attention maps between image features and question vectors', 'create a CNN-LSTM model with stacked attention for visual question answering on CLEVR datasets', 'build a ResidualBlock with configurable batch norm and residual connections for a CNN model', 'create a GlobalAveragePool layer to collapse spatial dimensions of a feature tensor', 'create a Flatten layer to reshape a tensor into a 2D batch by features matrix', 'test the ResidualBlock forward pass with a sample input tensor and verify output shape', 'refactor the ResidualBlock to toggle batch normalization on or off via the with_batchnorm flag', 'build a ModuleNet neural network model with a stem, function modules, and classifier for visual reasoning', 'create a ConcatBlock module that concatenates two tensors along depth and projects them through a residual block', 'build a stem feature extractor with configurable Conv2d layers, batch normalization, and ReLU activations', 'build a classifier with optional projection, downsampling, fully connected layers, and dropout for answer prediction', 'run the ModuleNet forward pass with image features and a program to produce classification logits', 'build a Seq2Seq LSTM encoder-decoder model with configurable vocab sizes and hidden dimensions', 'create a forward pass through the Seq2Seq encoder to get hidden state representations', 'test the Seq2Seq decoder to sample output sequences token by token with argmax', 'run reinforce sampling with temperature control and backward pass for reward-based training', 'review the Seq2Seq compute_loss method that masks padding tokens and shifts targets by one timestep']
```

Usage

```
{'build_cnn': 'build a CNN feature extractor with optional residual blocks and max pooling for image features', 'build_mlp': 'build a multi-layer perceptron classifier with optional batch normalization and dropout layers', 'create_LstmEncoder': 'create an LSTM encoder that embeds token sequences and extracts the last non-null hidden state', 'create_StackedAttention': 'create a stacked attention module that computes attention maps between image features and question vectors', 'create_CnnLstmSaModel': 'create a CNN-LSTM model with stacked attention for visual question answering on CLEVR datasets'}
```

## File: facebookresearch_clevr-iep/iep/models/layers.py

Prompts

```
['build a CNN feature extractor with optional residual blocks and max pooling for image features', 'build a multi-layer perceptron classifier with optional batch normalization and dropout layers', 'create an LSTM encoder that embeds token sequences and extracts the last non-null hidden state', 'create a stacked attention module that computes attention maps between image features and question vectors', 'create a CNN-LSTM model with stacked attention for visual question answering on CLEVR datasets', 'build a ResidualBlock with configurable batch norm and residual connections for a CNN model', 'create a GlobalAveragePool layer to collapse spatial dimensions of a feature tensor', 'create a Flatten layer to reshape a tensor into a 2D batch by features matrix', 'test the ResidualBlock forward pass with a sample input tensor and verify output shape', 'refactor the ResidualBlock to toggle batch normalization on or off via the with_batchnorm flag', 'build a ModuleNet neural network model with a stem, function modules, and classifier for visual reasoning', 'create a ConcatBlock module that concatenates two tensors along depth and projects them through a residual block', 'build a stem feature extractor with configurable Conv2d layers, batch normalization, and ReLU activations', 'build a classifier with optional projection, downsampling, fully connected layers, and dropout for answer prediction', 'run the ModuleNet forward pass with image features and a program to produce classification logits', 'build a Seq2Seq LSTM encoder-decoder model with configurable vocab sizes and hidden dimensions', 'create a forward pass through the Seq2Seq encoder to get hidden state representations', 'test the Seq2Seq decoder to sample output sequences token by token with argmax', 'run reinforce sampling with temperature control and backward pass for reward-based training', 'review the Seq2Seq compute_loss method that masks padding tokens and shifts targets by one timestep']
```

Usage

```
{'build_residual_block': 'build a ResidualBlock with configurable batch norm and residual connections for a CNN model', 'create_global_average_pool': 'create a GlobalAveragePool layer to collapse spatial dimensions of a feature tensor', 'create_flatten_layer': 'create a Flatten layer to reshape a tensor into a 2D batch by features matrix', 'test_residual_block_forward': 'test the ResidualBlock forward pass with a sample input tensor and verify output shape', 'refactor_residual_block_batchnorm': 'refactor the ResidualBlock to toggle batch normalization on or off via the with_batchnorm flag'}
```

## File: facebookresearch_clevr-iep/iep/models/module_net.py

Prompts

```
['build a CNN feature extractor with optional residual blocks and max pooling for image features', 'build a multi-layer perceptron classifier with optional batch normalization and dropout layers', 'create an LSTM encoder that embeds token sequences and extracts the last non-null hidden state', 'create a stacked attention module that computes attention maps between image features and question vectors', 'create a CNN-LSTM model with stacked attention for visual question answering on CLEVR datasets', 'build a ResidualBlock with configurable batch norm and residual connections for a CNN model', 'create a GlobalAveragePool layer to collapse spatial dimensions of a feature tensor', 'create a Flatten layer to reshape a tensor into a 2D batch by features matrix', 'test the ResidualBlock forward pass with a sample input tensor and verify output shape', 'refactor the ResidualBlock to toggle batch normalization on or off via the with_batchnorm flag', 'build a ModuleNet neural network model with a stem, function modules, and classifier for visual reasoning', 'create a ConcatBlock module that concatenates two tensors along depth and projects them through a residual block', 'build a stem feature extractor with configurable Conv2d layers, batch normalization, and ReLU activations', 'build a classifier with optional projection, downsampling, fully connected layers, and dropout for answer prediction', 'run the ModuleNet forward pass with image features and a program to produce classification logits', 'build a Seq2Seq LSTM encoder-decoder model with configurable vocab sizes and hidden dimensions', 'create a forward pass through the Seq2Seq encoder to get hidden state representations', 'test the Seq2Seq decoder to sample output sequences token by token with argmax', 'run reinforce sampling with temperature control and backward pass for reward-based training', 'review the Seq2Seq compute_loss method that masks padding tokens and shifts targets by one timestep']
```

Usage

```
{'build_Modulenet': 'build a ModuleNet neural network model with a stem, function modules, and classifier for visual reasoning', 'create_ConcatBlock': 'create a ConcatBlock module that concatenates two tensors along depth and projects them through a residual block', 'build_stem': 'build a stem feature extractor with configurable Conv2d layers, batch normalization, and ReLU activations', 'build_classifier': 'build a classifier with optional projection, downsampling, fully connected layers, and dropout for answer prediction', 'run_Modulenet_forward': 'run the ModuleNet forward pass with image features and a program to produce classification logits'}
```

## File: facebookresearch_clevr-iep/iep/models/seq2seq.py

Prompts

```
['build a CNN feature extractor with optional residual blocks and max pooling for image features', 'build a multi-layer perceptron classifier with optional batch normalization and dropout layers', 'create an LSTM encoder that embeds token sequences and extracts the last non-null hidden state', 'create a stacked attention module that computes attention maps between image features and question vectors', 'create a CNN-LSTM model with stacked attention for visual question answering on CLEVR datasets', 'build a ResidualBlock with configurable batch norm and residual connections for a CNN model', 'create a GlobalAveragePool layer to collapse spatial dimensions of a feature tensor', 'create a Flatten layer to reshape a tensor into a 2D batch by features matrix', 'test the ResidualBlock forward pass with a sample input tensor and verify output shape', 'refactor the ResidualBlock to toggle batch normalization on or off via the with_batchnorm flag', 'build a ModuleNet neural network model with a stem, function modules, and classifier for visual reasoning', 'create a ConcatBlock module that concatenates two tensors along depth and projects them through a residual block', 'build a stem feature extractor with configurable Conv2d layers, batch normalization, and ReLU activations', 'build a classifier with optional projection, downsampling, fully connected layers, and dropout for answer prediction', 'run the ModuleNet forward pass with image features and a program to produce classification logits', 'build a Seq2Seq LSTM encoder-decoder model with configurable vocab sizes and hidden dimensions', 'create a forward pass through the Seq2Seq encoder to get hidden state representations', 'test the Seq2Seq decoder to sample output sequences token by token with argmax', 'run reinforce sampling with temperature control and backward pass for reward-based training', 'review the Seq2Seq compute_loss method that masks padding tokens and shifts targets by one timestep']
```

Usage

```
{'build_seq2seq_model': 'build a Seq2Seq LSTM encoder-decoder model with configurable vocab sizes and hidden dimensions', 'create_encoder_forward_pass': 'create a forward pass through the Seq2Seq encoder to get hidden state representations', 'test_decoder_sampling': 'test the Seq2Seq decoder to sample output sequences token by token with argmax', 'run_reinforce_learning': 'run reinforce sampling with temperature control and backward pass for reward-based training', 'review_compute_loss': 'review the Seq2Seq compute_loss method that masks padding tokens and shifts targets by one timestep'}
```

