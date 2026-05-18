# Agent Python Tools

- repo: facebookresearch/neural-light-fields
- repo_uri: https://github.com/facebookresearch/neural-light-fields

## File: facebookresearch_neural-light-fields/baselines/third_party/evaluation/elpips/elpips.py

Prompts

```
['create a Config instance to set E-LPIPS metric type, dropout, offset, flip, scale, and color randomization options', 'call set_scale_levels on a Config to set the number of scale levels and their inverse-square probabilities', 'call validate on a Config to assert metric type, color mode, and scale probabilities are consistent', 'call sample_ensemble with a Config to sample random offset, flip, swap, color, and scale transformation parameters', 'call forward on a Metric instance to evaluate perceptual distances between image and reference tensors', 'build a SqueezeNet 1.1 network and run forward pass to extract 7 ReLU feature maps', 'build a VGG16 network and run forward pass to extract 5 ReLU feature maps', 'create a trainable SqueezeNet or VGG16 network by setting trainable=True in the constructor', 'review the Network base class _conv method to understand dropout and convolution logic', 'summarize the SqueezeNet fire_module method that combines squeeze 1x1 and expand 1x1 plus 3x3 convolutions', 'create a PNetLin instance using VGG16 as the pretrained network for perceptual similarity', 'create a PNetLin instance using SqueezeNet 1.1 as the pretrained network for perceptual similarity', 'compute perceptual distances between two NHWC image tensors using the PNetLin forward method', 'normalize a tensor to unit length along the depth feature dimension using normalize_tensor', 'create a trainable PNetLin instance with lpips or net weights enabled for fine-tuning', 'build a TensorFlow graph using switch_case_cond to chain conditional branches with a default case', 'build a TensorFlow tensor using switch_case_where to select values from multiple condition-effect pairs', 'test the np_dtype function to convert a TensorFlow dtype to its NumPy equivalent', 'test the f32_to_dtype function to cast a TensorFlow tensor from float32 to another dtype', 'test the for_each function to apply a callable to each element of a tuple or single value']
```

Usage

```
{'create_Config': 'create a Config instance to set E-LPIPS metric type, dropout, offset, flip, scale, and color randomization options', 'call_set_scale_levels': 'call set_scale_levels on a Config to set the number of scale levels and their inverse-square probabilities', 'call_validate': 'call validate on a Config to assert metric type, color mode, and scale probabilities are consistent', 'call_sample_ensemble': 'call sample_ensemble with a Config to sample random offset, flip, swap, color, and scale transformation parameters', 'call_Metric_forward': 'call forward on a Metric instance to evaluate perceptual distances between image and reference tensors'}
```

## File: facebookresearch_neural-light-fields/baselines/third_party/evaluation/elpips/networks.py

Prompts

```
['create a Config instance to set E-LPIPS metric type, dropout, offset, flip, scale, and color randomization options', 'call set_scale_levels on a Config to set the number of scale levels and their inverse-square probabilities', 'call validate on a Config to assert metric type, color mode, and scale probabilities are consistent', 'call sample_ensemble with a Config to sample random offset, flip, swap, color, and scale transformation parameters', 'call forward on a Metric instance to evaluate perceptual distances between image and reference tensors', 'build a SqueezeNet 1.1 network and run forward pass to extract 7 ReLU feature maps', 'build a VGG16 network and run forward pass to extract 5 ReLU feature maps', 'create a trainable SqueezeNet or VGG16 network by setting trainable=True in the constructor', 'review the Network base class _conv method to understand dropout and convolution logic', 'summarize the SqueezeNet fire_module method that combines squeeze 1x1 and expand 1x1 plus 3x3 convolutions', 'create a PNetLin instance using VGG16 as the pretrained network for perceptual similarity', 'create a PNetLin instance using SqueezeNet 1.1 as the pretrained network for perceptual similarity', 'compute perceptual distances between two NHWC image tensors using the PNetLin forward method', 'normalize a tensor to unit length along the depth feature dimension using normalize_tensor', 'create a trainable PNetLin instance with lpips or net weights enabled for fine-tuning', 'build a TensorFlow graph using switch_case_cond to chain conditional branches with a default case', 'build a TensorFlow tensor using switch_case_where to select values from multiple condition-effect pairs', 'test the np_dtype function to convert a TensorFlow dtype to its NumPy equivalent', 'test the f32_to_dtype function to cast a TensorFlow tensor from float32 to another dtype', 'test the for_each function to apply a callable to each element of a tuple or single value']
```

Usage

```
{'build_squeezenet_forward': 'build a SqueezeNet 1.1 network and run forward pass to extract 7 ReLU feature maps', 'build_vgg16_forward': 'build a VGG16 network and run forward pass to extract 5 ReLU feature maps', 'create_trainable_network': 'create a trainable SqueezeNet or VGG16 network by setting trainable=True in the constructor', 'review_network_conv': 'review the Network base class _conv method to understand dropout and convolution logic', 'summarize_fire_module': 'summarize the SqueezeNet fire_module method that combines squeeze 1x1 and expand 1x1 plus 3x3 convolutions'}
```

## File: facebookresearch_neural-light-fields/baselines/third_party/evaluation/elpips/pnetlin.py

Prompts

```
['create a Config instance to set E-LPIPS metric type, dropout, offset, flip, scale, and color randomization options', 'call set_scale_levels on a Config to set the number of scale levels and their inverse-square probabilities', 'call validate on a Config to assert metric type, color mode, and scale probabilities are consistent', 'call sample_ensemble with a Config to sample random offset, flip, swap, color, and scale transformation parameters', 'call forward on a Metric instance to evaluate perceptual distances between image and reference tensors', 'build a SqueezeNet 1.1 network and run forward pass to extract 7 ReLU feature maps', 'build a VGG16 network and run forward pass to extract 5 ReLU feature maps', 'create a trainable SqueezeNet or VGG16 network by setting trainable=True in the constructor', 'review the Network base class _conv method to understand dropout and convolution logic', 'summarize the SqueezeNet fire_module method that combines squeeze 1x1 and expand 1x1 plus 3x3 convolutions', 'create a PNetLin instance using VGG16 as the pretrained network for perceptual similarity', 'create a PNetLin instance using SqueezeNet 1.1 as the pretrained network for perceptual similarity', 'compute perceptual distances between two NHWC image tensors using the PNetLin forward method', 'normalize a tensor to unit length along the depth feature dimension using normalize_tensor', 'create a trainable PNetLin instance with lpips or net weights enabled for fine-tuning', 'build a TensorFlow graph using switch_case_cond to chain conditional branches with a default case', 'build a TensorFlow tensor using switch_case_where to select values from multiple condition-effect pairs', 'test the np_dtype function to convert a TensorFlow dtype to its NumPy equivalent', 'test the f32_to_dtype function to cast a TensorFlow tensor from float32 to another dtype', 'test the for_each function to apply a callable to each element of a tuple or single value']
```

Usage

```
{'create_PNetLin_vgg': 'create a PNetLin instance using VGG16 as the pretrained network for perceptual similarity', 'create_PNetLin_squeeze': 'create a PNetLin instance using SqueezeNet 1.1 as the pretrained network for perceptual similarity', 'forward_perceptual_distance': 'compute perceptual distances between two NHWC image tensors using the PNetLin forward method', 'normalize_tensor_features': 'normalize a tensor to unit length along the depth feature dimension using normalize_tensor', 'create_PNetLin_trainable': 'create a trainable PNetLin instance with lpips or net weights enabled for fine-tuning'}
```

## File: facebookresearch_neural-light-fields/baselines/third_party/evaluation/elpips/util.py

Prompts

```
['create a Config instance to set E-LPIPS metric type, dropout, offset, flip, scale, and color randomization options', 'call set_scale_levels on a Config to set the number of scale levels and their inverse-square probabilities', 'call validate on a Config to assert metric type, color mode, and scale probabilities are consistent', 'call sample_ensemble with a Config to sample random offset, flip, swap, color, and scale transformation parameters', 'call forward on a Metric instance to evaluate perceptual distances between image and reference tensors', 'build a SqueezeNet 1.1 network and run forward pass to extract 7 ReLU feature maps', 'build a VGG16 network and run forward pass to extract 5 ReLU feature maps', 'create a trainable SqueezeNet or VGG16 network by setting trainable=True in the constructor', 'review the Network base class _conv method to understand dropout and convolution logic', 'summarize the SqueezeNet fire_module method that combines squeeze 1x1 and expand 1x1 plus 3x3 convolutions', 'create a PNetLin instance using VGG16 as the pretrained network for perceptual similarity', 'create a PNetLin instance using SqueezeNet 1.1 as the pretrained network for perceptual similarity', 'compute perceptual distances between two NHWC image tensors using the PNetLin forward method', 'normalize a tensor to unit length along the depth feature dimension using normalize_tensor', 'create a trainable PNetLin instance with lpips or net weights enabled for fine-tuning', 'build a TensorFlow graph using switch_case_cond to chain conditional branches with a default case', 'build a TensorFlow tensor using switch_case_where to select values from multiple condition-effect pairs', 'test the np_dtype function to convert a TensorFlow dtype to its NumPy equivalent', 'test the f32_to_dtype function to cast a TensorFlow tensor from float32 to another dtype', 'test the for_each function to apply a callable to each element of a tuple or single value']
```

Usage

```
{'build_switch_case_cond': 'build a TensorFlow graph using switch_case_cond to chain conditional branches with a default case', 'build_switch_case_where': 'build a TensorFlow tensor using switch_case_where to select values from multiple condition-effect pairs', 'test_np_dtype': 'test the np_dtype function to convert a TensorFlow dtype to its NumPy equivalent', 'test_f32_to_dtype': 'test the f32_to_dtype function to cast a TensorFlow tensor from float32 to another dtype', 'test_for_each': 'test the for_each function to apply a callable to each element of a tuple or single value'}
```

