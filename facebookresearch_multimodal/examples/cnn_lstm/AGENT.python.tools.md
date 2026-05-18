# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/cnn_lstm/cnn_encoder.py

Prompts

```
['build a CNN encoder that stacks Conv2d, MaxPool2d, and BatchNorm2d layers for image encoding', 'create a forward pass through the CNN encoder to flatten a batch of image tensors', 'test the CNNEncoder constructor with matching input_dims, output_dims, and kernel_sizes lists', 'review the CNNEncoder class to verify each layer uses Conv2d, LeakyReLU, MaxPool2d, and BatchNorm2d', 'refactor the CNNEncoder to use configurable padding instead of kernel_size divided by two', 'build a multimodal classifier using CNN for images and LSTM for text with LateFusion', 'create a LateFusion model with CNN image encoder and LSTM text encoder for classification', 'build a multimodal encoder combining CNNEncoder and LSTMEncoder with ConcatFusionModule', 'create an MLP classifier with ReLU activation and BatchNorm1d normalization for raw scores', 'review the cnn_lstm_classifier builder function and its CNN and LSTM encoder parameters', 'build a bidirectional LSTM encoder with an embedding layer for sequence encoding', 'create an nn.Embedding layer with a specified vocab size and embedding dimension', 'run the LSTM forward pass on a batch of input sequence tensors', 'test the LSTMEncoder class by passing input tensors and verifying output shape', 'review the LSTMEncoder forward method that concatenates bidirectional hidden states']
```

Usage

```
{'build_CNNEncoder': 'build a CNN encoder that stacks Conv2d, MaxPool2d, and BatchNorm2d layers for image encoding', 'create_CNNEncoder_forward': 'create a forward pass through the CNN encoder to flatten a batch of image tensors', 'test_CNNEncoder_init': 'test the CNNEncoder constructor with matching input_dims, output_dims, and kernel_sizes lists', 'review_CNNEncoder_layers': 'review the CNNEncoder class to verify each layer uses Conv2d, LeakyReLU, MaxPool2d, and BatchNorm2d', 'refactor_CNNEncoder_padding': 'refactor the CNNEncoder to use configurable padding instead of kernel_size divided by two'}
```

## File: facebookresearch_multimodal/examples/cnn_lstm/cnn_lstm.py

Prompts

```
['build a CNN encoder that stacks Conv2d, MaxPool2d, and BatchNorm2d layers for image encoding', 'create a forward pass through the CNN encoder to flatten a batch of image tensors', 'test the CNNEncoder constructor with matching input_dims, output_dims, and kernel_sizes lists', 'review the CNNEncoder class to verify each layer uses Conv2d, LeakyReLU, MaxPool2d, and BatchNorm2d', 'refactor the CNNEncoder to use configurable padding instead of kernel_size divided by two', 'build a multimodal classifier using CNN for images and LSTM for text with LateFusion', 'create a LateFusion model with CNN image encoder and LSTM text encoder for classification', 'build a multimodal encoder combining CNNEncoder and LSTMEncoder with ConcatFusionModule', 'create an MLP classifier with ReLU activation and BatchNorm1d normalization for raw scores', 'review the cnn_lstm_classifier builder function and its CNN and LSTM encoder parameters', 'build a bidirectional LSTM encoder with an embedding layer for sequence encoding', 'create an nn.Embedding layer with a specified vocab size and embedding dimension', 'run the LSTM forward pass on a batch of input sequence tensors', 'test the LSTMEncoder class by passing input tensors and verifying output shape', 'review the LSTMEncoder forward method that concatenates bidirectional hidden states']
```

Usage

```
{'build_cnn_lstm_classifier': 'build a multimodal classifier using CNN for images and LSTM for text with LateFusion', 'create_late_fusion_model': 'create a LateFusion model with CNN image encoder and LSTM text encoder for classification', 'build_multimodal_encoder': 'build a multimodal encoder combining CNNEncoder and LSTMEncoder with ConcatFusionModule', 'create_mlp_classifier': 'create an MLP classifier with ReLU activation and BatchNorm1d normalization for raw scores', 'review_cnn_lstm_classifier': 'review the cnn_lstm_classifier builder function and its CNN and LSTM encoder parameters'}
```

## File: facebookresearch_multimodal/examples/cnn_lstm/lstm_encoder.py

Prompts

```
['build a CNN encoder that stacks Conv2d, MaxPool2d, and BatchNorm2d layers for image encoding', 'create a forward pass through the CNN encoder to flatten a batch of image tensors', 'test the CNNEncoder constructor with matching input_dims, output_dims, and kernel_sizes lists', 'review the CNNEncoder class to verify each layer uses Conv2d, LeakyReLU, MaxPool2d, and BatchNorm2d', 'refactor the CNNEncoder to use configurable padding instead of kernel_size divided by two', 'build a multimodal classifier using CNN for images and LSTM for text with LateFusion', 'create a LateFusion model with CNN image encoder and LSTM text encoder for classification', 'build a multimodal encoder combining CNNEncoder and LSTMEncoder with ConcatFusionModule', 'create an MLP classifier with ReLU activation and BatchNorm1d normalization for raw scores', 'review the cnn_lstm_classifier builder function and its CNN and LSTM encoder parameters', 'build a bidirectional LSTM encoder with an embedding layer for sequence encoding', 'create an nn.Embedding layer with a specified vocab size and embedding dimension', 'run the LSTM forward pass on a batch of input sequence tensors', 'test the LSTMEncoder class by passing input tensors and verifying output shape', 'review the LSTMEncoder forward method that concatenates bidirectional hidden states']
```

Usage

```
{'build_lstm_encoder': 'build a bidirectional LSTM encoder with an embedding layer for sequence encoding', 'create_embedding_layer': 'create an nn.Embedding layer with a specified vocab size and embedding dimension', 'run_lstm_forward': 'run the LSTM forward pass on a batch of input sequence tensors', 'test_lstm_encoder': 'test the LSTMEncoder class by passing input tensors and verifying output shape', 'review_lstm_encoder_forward': 'review the LSTMEncoder forward method that concatenates bidirectional hidden states'}
```

