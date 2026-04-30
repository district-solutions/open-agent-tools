# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mobilenet_v1/configuration_mobilenet_v1.py

Prompts

```
['create a MobileNetV1Config instance with default configuration for mobilenet_v1_1.0_224', 'configure MobileNetV1Config with custom image_size, depth_multiplier, and min_depth parameters', 'validate MobileNetV1Config architecture by calling validate_architecture method', 'initialize a MobileNetV1Model using a MobileNetV1Config configuration instance', 'access the model configuration via model.config attribute after model initialization', 'convert a TensorFlow MobileNetV1 checkpoint to a PyTorch model and save to a directory', 'build a mapping dictionary from TensorFlow weight names to PyTorch model parameters', 'load TensorFlow checkpoint weights into a PyTorch MobileNetV1 model', 'get a MobileNetV1 configuration from a model name string with depth multiplier and image size', 'run the CLI script to convert a TensorFlow MobileNetV1 checkpoint to PyTorch format', 'build a MobileNetV1 model with feature extraction and optional pooling layer', 'create a MobileNetV1 model for image classification with a linear classifier head', 'run a forward pass on a MobileNetV1 model with pixel values and return hidden states', 'test MobileNetV1 image classification with labels to compute classification loss', 'review the TensorFlow-style SAME padding function for convolution layers']
```

Usage

```
{'create_MobileNetV1Config': 'create a MobileNetV1Config instance with default configuration for mobilenet_v1_1.0_224', 'configure_MobileNetV1Config_parameters': 'configure MobileNetV1Config with custom image_size, depth_multiplier, and min_depth parameters', 'validate_MobileNetV1Config_architecture': 'validate MobileNetV1Config architecture by calling validate_architecture method', 'initialize_MobileNetV1Model_with_config': 'initialize a MobileNetV1Model using a MobileNetV1Config configuration instance', 'access_MobileNetV1Model_config': 'access the model configuration via model.config attribute after model initialization'}
```

## File: huggingface_transformers/src/transformers/models/mobilenet_v1/convert_original_tf_checkpoint_to_pytorch.py

Prompts

```
['create a MobileNetV1Config instance with default configuration for mobilenet_v1_1.0_224', 'configure MobileNetV1Config with custom image_size, depth_multiplier, and min_depth parameters', 'validate MobileNetV1Config architecture by calling validate_architecture method', 'initialize a MobileNetV1Model using a MobileNetV1Config configuration instance', 'access the model configuration via model.config attribute after model initialization', 'convert a TensorFlow MobileNetV1 checkpoint to a PyTorch model and save to a directory', 'build a mapping dictionary from TensorFlow weight names to PyTorch model parameters', 'load TensorFlow checkpoint weights into a PyTorch MobileNetV1 model', 'get a MobileNetV1 configuration from a model name string with depth multiplier and image size', 'run the CLI script to convert a TensorFlow MobileNetV1 checkpoint to PyTorch format', 'build a MobileNetV1 model with feature extraction and optional pooling layer', 'create a MobileNetV1 model for image classification with a linear classifier head', 'run a forward pass on a MobileNetV1 model with pixel values and return hidden states', 'test MobileNetV1 image classification with labels to compute classification loss', 'review the TensorFlow-style SAME padding function for convolution layers']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow MobileNetV1 checkpoint to a PyTorch model and save to a directory', 'build_tf_to_pytorch_map': 'build a mapping dictionary from TensorFlow weight names to PyTorch model parameters', 'load_tf_weights_in_mobilenet_v1': 'load TensorFlow checkpoint weights into a PyTorch MobileNetV1 model', 'get_mobilenet_v1_config': 'get a MobileNetV1 configuration from a model name string with depth multiplier and image size', 'run_cli_convert': 'run the CLI script to convert a TensorFlow MobileNetV1 checkpoint to PyTorch format'}
```

## File: huggingface_transformers/src/transformers/models/mobilenet_v1/modeling_mobilenet_v1.py

Prompts

```
['create a MobileNetV1Config instance with default configuration for mobilenet_v1_1.0_224', 'configure MobileNetV1Config with custom image_size, depth_multiplier, and min_depth parameters', 'validate MobileNetV1Config architecture by calling validate_architecture method', 'initialize a MobileNetV1Model using a MobileNetV1Config configuration instance', 'access the model configuration via model.config attribute after model initialization', 'convert a TensorFlow MobileNetV1 checkpoint to a PyTorch model and save to a directory', 'build a mapping dictionary from TensorFlow weight names to PyTorch model parameters', 'load TensorFlow checkpoint weights into a PyTorch MobileNetV1 model', 'get a MobileNetV1 configuration from a model name string with depth multiplier and image size', 'run the CLI script to convert a TensorFlow MobileNetV1 checkpoint to PyTorch format', 'build a MobileNetV1 model with feature extraction and optional pooling layer', 'create a MobileNetV1 model for image classification with a linear classifier head', 'run a forward pass on a MobileNetV1 model with pixel values and return hidden states', 'test MobileNetV1 image classification with labels to compute classification loss', 'review the TensorFlow-style SAME padding function for convolution layers']
```

Usage

```
{'build_mobilenetv1_model': 'build a MobileNetV1 model with feature extraction and optional pooling layer', 'create_image_classification_model': 'create a MobileNetV1 model for image classification with a linear classifier head', 'run_model_forward_pass': 'run a forward pass on a MobileNetV1 model with pixel values and return hidden states', 'test_image_classification_loss': 'test MobileNetV1 image classification with labels to compute classification loss', 'review_tf_padding_function': 'review the TensorFlow-style SAME padding function for convolution layers'}
```

