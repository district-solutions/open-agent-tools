# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/tests/conftest.py

Prompts

```
['test MockBackbone forward pass by passing a 4D image tensor and verifying flattened feature output', 'test MockDiffBackbone forward pass by passing two image tensors and verifying the difference of features', 'test the arange_4d_image pytest fixture by asserting it produces 4D tensors with even spatial dimensions', 'test the arange_4d_image_odd pytest fixture by asserting it produces 4D tensors with odd spatial dimensions', 'review MockBackbone train method override that forces the module to stay in evaluation mode', 'test the SimplifiedGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'test the SimplifiedInverseGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedInverseGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'run pytest on test_layers_gdn.py to validate SimplifiedGDN and SimplifiedInverseGDN layer behavior with parametrized shapes', 'test the DVCCompressionEncoder and DVCCompressionDecoder by encoding and decoding a tensor with GDN enabled or disabled', 'test the DVCMotionCompensationModel by warping an image with dense flow and running the compensation layer', 'test the integrated DVC model by running forward pass on two image tensors and checking residual and flow shapes', 'test the DVC model compress and decompress pipeline by encoding two frames and reconstructing the second frame', 'test the DVCPyramidFlowEstimator by calculating multi-scale optical flow between two image pairs and verifying output shapes', 'create a deterministic PyTorch tensor from a shape using sequential integer values with an optional offset', 'create a normalized deterministic image array from a shape by scaling sequential values to 0-1 range', 'create a normalized random image array from a shape using an optional NumPy random generator', 'write a normalized numpy image array to a file path as PNG or lossless JPEG', 'create a random PyTorch tensor with uniform values from a given shape using an optional random generator']
```

Usage

```
{'test_MockBackbone_forward': 'test MockBackbone forward pass by passing a 4D image tensor and verifying flattened feature output', 'test_MockDiffBackbone_forward': 'test MockDiffBackbone forward pass by passing two image tensors and verifying the difference of features', 'test_arange_4d_image_fixture': 'test the arange_4d_image pytest fixture by asserting it produces 4D tensors with even spatial dimensions', 'test_arange_4d_image_odd_fixture': 'test the arange_4d_image_odd pytest fixture by asserting it produces 4D tensors with odd spatial dimensions', 'review_MockBackbone_train_override': 'review MockBackbone train method override that forces the module to stay in evaluation mode'}
```

## File: facebookresearch_neuralcompression/tests/test_layers_gdn.py

Prompts

```
['test MockBackbone forward pass by passing a 4D image tensor and verifying flattened feature output', 'test MockDiffBackbone forward pass by passing two image tensors and verifying the difference of features', 'test the arange_4d_image pytest fixture by asserting it produces 4D tensors with even spatial dimensions', 'test the arange_4d_image_odd pytest fixture by asserting it produces 4D tensors with odd spatial dimensions', 'review MockBackbone train method override that forces the module to stay in evaluation mode', 'test the SimplifiedGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'test the SimplifiedInverseGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedInverseGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'run pytest on test_layers_gdn.py to validate SimplifiedGDN and SimplifiedInverseGDN layer behavior with parametrized shapes', 'test the DVCCompressionEncoder and DVCCompressionDecoder by encoding and decoding a tensor with GDN enabled or disabled', 'test the DVCMotionCompensationModel by warping an image with dense flow and running the compensation layer', 'test the integrated DVC model by running forward pass on two image tensors and checking residual and flow shapes', 'test the DVC model compress and decompress pipeline by encoding two frames and reconstructing the second frame', 'test the DVCPyramidFlowEstimator by calculating multi-scale optical flow between two image pairs and verifying output shapes', 'create a deterministic PyTorch tensor from a shape using sequential integer values with an optional offset', 'create a normalized deterministic image array from a shape by scaling sequential values to 0-1 range', 'create a normalized random image array from a shape using an optional NumPy random generator', 'write a normalized numpy image array to a file path as PNG or lossless JPEG', 'create a random PyTorch tensor with uniform values from a given shape using an optional random generator']
```

Usage

```
{'test_simplified_gdn_forward': 'test the SimplifiedGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test_simplified_gdn_clamp': 'test the SimplifiedGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'test_simplified_inverse_gdn_forward': 'test the SimplifiedInverseGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test_simplified_inverse_gdn_clamp': 'test the SimplifiedInverseGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'run_gdn_layer_tests': 'run pytest on test_layers_gdn.py to validate SimplifiedGDN and SimplifiedInverseGDN layer behavior with parametrized shapes'}
```

## File: facebookresearch_neuralcompression/tests/test_models.py

Prompts

```
['test MockBackbone forward pass by passing a 4D image tensor and verifying flattened feature output', 'test MockDiffBackbone forward pass by passing two image tensors and verifying the difference of features', 'test the arange_4d_image pytest fixture by asserting it produces 4D tensors with even spatial dimensions', 'test the arange_4d_image_odd pytest fixture by asserting it produces 4D tensors with odd spatial dimensions', 'review MockBackbone train method override that forces the module to stay in evaluation mode', 'test the SimplifiedGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'test the SimplifiedInverseGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedInverseGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'run pytest on test_layers_gdn.py to validate SimplifiedGDN and SimplifiedInverseGDN layer behavior with parametrized shapes', 'test the DVCCompressionEncoder and DVCCompressionDecoder by encoding and decoding a tensor with GDN enabled or disabled', 'test the DVCMotionCompensationModel by warping an image with dense flow and running the compensation layer', 'test the integrated DVC model by running forward pass on two image tensors and checking residual and flow shapes', 'test the DVC model compress and decompress pipeline by encoding two frames and reconstructing the second frame', 'test the DVCPyramidFlowEstimator by calculating multi-scale optical flow between two image pairs and verifying output shapes', 'create a deterministic PyTorch tensor from a shape using sequential integer values with an optional offset', 'create a normalized deterministic image array from a shape by scaling sequential values to 0-1 range', 'create a normalized random image array from a shape using an optional NumPy random generator', 'write a normalized numpy image array to a file path as PNG or lossless JPEG', 'create a random PyTorch tensor with uniform values from a given shape using an optional random generator']
```

Usage

```
{'test_DVCCompressionEncoder_decoder': 'test the DVCCompressionEncoder and DVCCompressionDecoder by encoding and decoding a tensor with GDN enabled or disabled', 'test_DVCMotionCompensationModel': 'test the DVCMotionCompensationModel by warping an image with dense flow and running the compensation layer', 'test_DVC_integrated_forward': 'test the integrated DVC model by running forward pass on two image tensors and checking residual and flow shapes', 'test_DVC_compress_decompress': 'test the DVC model compress and decompress pipeline by encoding two frames and reconstructing the second frame', 'test_DVCPyramidFlowEstimator': 'test the DVCPyramidFlowEstimator by calculating multi-scale optical flow between two image pairs and verifying output shapes'}
```

## File: facebookresearch_neuralcompression/tests/utils.py

Prompts

```
['test MockBackbone forward pass by passing a 4D image tensor and verifying flattened feature output', 'test MockDiffBackbone forward pass by passing two image tensors and verifying the difference of features', 'test the arange_4d_image pytest fixture by asserting it produces 4D tensors with even spatial dimensions', 'test the arange_4d_image_odd pytest fixture by asserting it produces 4D tensors with odd spatial dimensions', 'review MockBackbone train method override that forces the module to stay in evaluation mode', 'test the SimplifiedGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'test the SimplifiedInverseGDN layer forward pass preserves input tensor shape across multiple channel configurations', 'test the SimplifiedInverseGDN layer clamps gamma to zero and beta to beta_min when parameters go negative', 'run pytest on test_layers_gdn.py to validate SimplifiedGDN and SimplifiedInverseGDN layer behavior with parametrized shapes', 'test the DVCCompressionEncoder and DVCCompressionDecoder by encoding and decoding a tensor with GDN enabled or disabled', 'test the DVCMotionCompensationModel by warping an image with dense flow and running the compensation layer', 'test the integrated DVC model by running forward pass on two image tensors and checking residual and flow shapes', 'test the DVC model compress and decompress pipeline by encoding two frames and reconstructing the second frame', 'test the DVCPyramidFlowEstimator by calculating multi-scale optical flow between two image pairs and verifying output shapes', 'create a deterministic PyTorch tensor from a shape using sequential integer values with an optional offset', 'create a normalized deterministic image array from a shape by scaling sequential values to 0-1 range', 'create a normalized random image array from a shape using an optional NumPy random generator', 'write a normalized numpy image array to a file path as PNG or lossless JPEG', 'create a random PyTorch tensor with uniform values from a given shape using an optional random generator']
```

Usage

```
{'create_deterministic_tensor_input': 'create a deterministic PyTorch tensor from a shape using sequential integer values with an optional offset', 'create_deterministic_image': 'create a normalized deterministic image array from a shape by scaling sequential values to 0-1 range', 'create_random_image': 'create a normalized random image array from a shape using an optional NumPy random generator', 'write_image_to_file': 'write a normalized numpy image array to a file path as PNG or lossless JPEG', 'create_random_tensor': 'create a random PyTorch tensor with uniform values from a given shape using an optional random generator'}
```

