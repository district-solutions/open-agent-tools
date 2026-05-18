# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/cnn_lstm/tests/test_cnn_encoder.py

Prompts

```
['test the CNNEncoder class with a single convolutional layer and verify output tensor values', 'test the CNNEncoder class with multiple stacked convolutional layers and verify output tensor values', 'test the CNNEncoder constructor raises AssertionError when input_dims, output_dims, or kernel_sizes have mismatched lengths', 'test the CNNEncoder forward pass with manually set fixed weight and bias parameters', 'test the CNNEncoder class can be compiled with torch.jit.script and produces identical output', 'test the cnn_lstm_classifier forward pass with image and text inputs to verify output shape', 'build a multimodal classifier using cnn_lstm_classifier with CNN image encoder and LSTM text encoder', 'create pytest fixtures for text tensor and image tensor inputs for CNN LSTM testing', 'review the cnn_lstm_classifier builder function that composes CNN, LSTM, and MLP into a LateFusion model', 'run pytest tests for the CNN LSTM multimodal classifier module to validate forward pass output dimensions', 'test the LSTMEncoder class with a bidirectional LSTM and embedding layer using PyTorch', 'create an LSTMEncoder fixture with vocab size 80, embedding dim 20, and hidden size 50', 'test the LSTMEncoder forward pass to verify output tensor size is 1x100', 'review the LSTMEncoder class that stacks an LSTM on an embedding layer for sequence encoding', 'run the pytest test for LSTMEncoder to validate bidirectional LSTM output dimensions']
```

Usage

```
{'test_CNNEncoder_single_layer': 'test the CNNEncoder class with a single convolutional layer and verify output tensor values', 'test_CNNEncoder_multiple_layer': 'test the CNNEncoder class with multiple stacked convolutional layers and verify output tensor values', 'test_CNNEncoder_invalid_args': 'test the CNNEncoder constructor raises AssertionError when input_dims, output_dims, or kernel_sizes have mismatched lengths', 'test_CNNEncoder_fixed_weights': 'test the CNNEncoder forward pass with manually set fixed weight and bias parameters', 'test_CNNEncoder_scripting': 'test the CNNEncoder class can be compiled with torch.jit.script and produces identical output'}
```

## File: facebookresearch_multimodal/examples/cnn_lstm/tests/test_cnn_lstm.py

Prompts

```
['test the CNNEncoder class with a single convolutional layer and verify output tensor values', 'test the CNNEncoder class with multiple stacked convolutional layers and verify output tensor values', 'test the CNNEncoder constructor raises AssertionError when input_dims, output_dims, or kernel_sizes have mismatched lengths', 'test the CNNEncoder forward pass with manually set fixed weight and bias parameters', 'test the CNNEncoder class can be compiled with torch.jit.script and produces identical output', 'test the cnn_lstm_classifier forward pass with image and text inputs to verify output shape', 'build a multimodal classifier using cnn_lstm_classifier with CNN image encoder and LSTM text encoder', 'create pytest fixtures for text tensor and image tensor inputs for CNN LSTM testing', 'review the cnn_lstm_classifier builder function that composes CNN, LSTM, and MLP into a LateFusion model', 'run pytest tests for the CNN LSTM multimodal classifier module to validate forward pass output dimensions', 'test the LSTMEncoder class with a bidirectional LSTM and embedding layer using PyTorch', 'create an LSTMEncoder fixture with vocab size 80, embedding dim 20, and hidden size 50', 'test the LSTMEncoder forward pass to verify output tensor size is 1x100', 'review the LSTMEncoder class that stacks an LSTM on an embedding layer for sequence encoding', 'run the pytest test for LSTMEncoder to validate bidirectional LSTM output dimensions']
```

Usage

```
{'test_cnn_lstm_forward': 'test the cnn_lstm_classifier forward pass with image and text inputs to verify output shape', 'build_cnn_lstm_classifier': 'build a multimodal classifier using cnn_lstm_classifier with CNN image encoder and LSTM text encoder', 'create_cnn_lstm_test_fixtures': 'create pytest fixtures for text tensor and image tensor inputs for CNN LSTM testing', 'review_cnn_lstm_classifier': 'review the cnn_lstm_classifier builder function that composes CNN, LSTM, and MLP into a LateFusion model', 'run_cnn_lstm_tests': 'run pytest tests for the CNN LSTM multimodal classifier module to validate forward pass output dimensions'}
```

## File: facebookresearch_multimodal/examples/cnn_lstm/tests/test_lstm_encoder.py

Prompts

```
['test the CNNEncoder class with a single convolutional layer and verify output tensor values', 'test the CNNEncoder class with multiple stacked convolutional layers and verify output tensor values', 'test the CNNEncoder constructor raises AssertionError when input_dims, output_dims, or kernel_sizes have mismatched lengths', 'test the CNNEncoder forward pass with manually set fixed weight and bias parameters', 'test the CNNEncoder class can be compiled with torch.jit.script and produces identical output', 'test the cnn_lstm_classifier forward pass with image and text inputs to verify output shape', 'build a multimodal classifier using cnn_lstm_classifier with CNN image encoder and LSTM text encoder', 'create pytest fixtures for text tensor and image tensor inputs for CNN LSTM testing', 'review the cnn_lstm_classifier builder function that composes CNN, LSTM, and MLP into a LateFusion model', 'run pytest tests for the CNN LSTM multimodal classifier module to validate forward pass output dimensions', 'test the LSTMEncoder class with a bidirectional LSTM and embedding layer using PyTorch', 'create an LSTMEncoder fixture with vocab size 80, embedding dim 20, and hidden size 50', 'test the LSTMEncoder forward pass to verify output tensor size is 1x100', 'review the LSTMEncoder class that stacks an LSTM on an embedding layer for sequence encoding', 'run the pytest test for LSTMEncoder to validate bidirectional LSTM output dimensions']
```

Usage

```
{'test_LSTMEncoder': 'test the LSTMEncoder class with a bidirectional LSTM and embedding layer using PyTorch', 'create_LSTMEncoder_fixture': 'create an LSTMEncoder fixture with vocab size 80, embedding dim 20, and hidden size 50', 'test_LSTMEncoder_forward': 'test the LSTMEncoder forward pass to verify output tensor size is 1x100', 'review_LSTMEncoder_class': 'review the LSTMEncoder class that stacks an LSTM on an embedding layer for sequence encoding', 'run_LSTMEncoder_test': 'run the pytest test for LSTMEncoder to validate bidirectional LSTM output dimensions'}
```

