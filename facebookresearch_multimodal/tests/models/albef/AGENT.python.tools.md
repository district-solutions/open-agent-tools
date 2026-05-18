# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/models/albef/test_albef.py

Prompts

```
['test the ALBEFModel by running forward pass with image and text tensors', 'test the ALBEFModelWithSimilarity by computing image-to-text and text-to-image similarity scores', 'test the ALBEFSimilarity dataclass by verifying similarity tensor outputs for i2t and t2i', 'test the TransformerCrossAttentionLayer by running forward pass with prenorm and postnorm configurations', 'test the momentum_update utility by verifying momentum-weighted parameter updates between model and momentum model', 'test the ALBEFVisionEncoder by passing a random 4x4 RGB image tensor and verifying output values', 'test the ALBEFVisionEncoder with a 3D tensor to verify it raises an IndexError for invalid input length', 'test the ALBEFVisionEncoder with a 1-channel image to verify it raises a RuntimeError for wrong channels', 'test the ALBEFVisionEncoder with a 5x4 image to verify it raises an AssertionError for wrong image height', 'test the ALBEFVisionEncoder with a 4x3 image to verify it raises an AssertionError for wrong image width', 'test the ALBEFMultimodalEncoder forward pass with image and text embeddings and attention masks', 'test that ALBEFMultimodalEncoder raises RuntimeError when image hidden size does not match expected size', 'test that ALBEFMultimodalEncoder raises RuntimeError when text hidden size does not match expected size', 'test that ALBEFMultimodalEncoder raises RuntimeError when image and text batch sizes do not match', 'create a pytest fixture that initializes ALBEFMultimodalEncoder with a fixed hidden size and attention heads']
```

Usage

```
{'test_ALBEFModel': 'test the ALBEFModel by running forward pass with image and text tensors', 'test_ALBEFModelWithSimilarity': 'test the ALBEFModelWithSimilarity by computing image-to-text and text-to-image similarity scores', 'test_ALBEFSimilarity': 'test the ALBEFSimilarity dataclass by verifying similarity tensor outputs for i2t and t2i', 'test_TransformerCrossAttentionLayer': 'test the TransformerCrossAttentionLayer by running forward pass with prenorm and postnorm configurations', 'test_momentum_update': 'test the momentum_update utility by verifying momentum-weighted parameter updates between model and momentum model'}
```

## File: facebookresearch_multimodal/tests/models/albef/test_image_encoder.py

Prompts

```
['test the ALBEFModel by running forward pass with image and text tensors', 'test the ALBEFModelWithSimilarity by computing image-to-text and text-to-image similarity scores', 'test the ALBEFSimilarity dataclass by verifying similarity tensor outputs for i2t and t2i', 'test the TransformerCrossAttentionLayer by running forward pass with prenorm and postnorm configurations', 'test the momentum_update utility by verifying momentum-weighted parameter updates between model and momentum model', 'test the ALBEFVisionEncoder by passing a random 4x4 RGB image tensor and verifying output values', 'test the ALBEFVisionEncoder with a 3D tensor to verify it raises an IndexError for invalid input length', 'test the ALBEFVisionEncoder with a 1-channel image to verify it raises a RuntimeError for wrong channels', 'test the ALBEFVisionEncoder with a 5x4 image to verify it raises an AssertionError for wrong image height', 'test the ALBEFVisionEncoder with a 4x3 image to verify it raises an AssertionError for wrong image width', 'test the ALBEFMultimodalEncoder forward pass with image and text embeddings and attention masks', 'test that ALBEFMultimodalEncoder raises RuntimeError when image hidden size does not match expected size', 'test that ALBEFMultimodalEncoder raises RuntimeError when text hidden size does not match expected size', 'test that ALBEFMultimodalEncoder raises RuntimeError when image and text batch sizes do not match', 'create a pytest fixture that initializes ALBEFMultimodalEncoder with a fixed hidden size and attention heads']
```

Usage

```
{'test_ALBEFVisionEncoder_vision_transformer': 'test the ALBEFVisionEncoder by passing a random 4x4 RGB image tensor and verifying output values', 'test_ALBEFVisionEncoder_invalid_input_length': 'test the ALBEFVisionEncoder with a 3D tensor to verify it raises an IndexError for invalid input length', 'test_ALBEFVisionEncoder_invalid_channel_dim': 'test the ALBEFVisionEncoder with a 1-channel image to verify it raises a RuntimeError for wrong channels', 'test_ALBEFVisionEncoder_invalid_image_height': 'test the ALBEFVisionEncoder with a 5x4 image to verify it raises an AssertionError for wrong image height', 'test_ALBEFVisionEncoder_invalid_image_width': 'test the ALBEFVisionEncoder with a 4x3 image to verify it raises an AssertionError for wrong image width'}
```

## File: facebookresearch_multimodal/tests/models/albef/test_multimodal_encoder.py

Prompts

```
['test the ALBEFModel by running forward pass with image and text tensors', 'test the ALBEFModelWithSimilarity by computing image-to-text and text-to-image similarity scores', 'test the ALBEFSimilarity dataclass by verifying similarity tensor outputs for i2t and t2i', 'test the TransformerCrossAttentionLayer by running forward pass with prenorm and postnorm configurations', 'test the momentum_update utility by verifying momentum-weighted parameter updates between model and momentum model', 'test the ALBEFVisionEncoder by passing a random 4x4 RGB image tensor and verifying output values', 'test the ALBEFVisionEncoder with a 3D tensor to verify it raises an IndexError for invalid input length', 'test the ALBEFVisionEncoder with a 1-channel image to verify it raises a RuntimeError for wrong channels', 'test the ALBEFVisionEncoder with a 5x4 image to verify it raises an AssertionError for wrong image height', 'test the ALBEFVisionEncoder with a 4x3 image to verify it raises an AssertionError for wrong image width', 'test the ALBEFMultimodalEncoder forward pass with image and text embeddings and attention masks', 'test that ALBEFMultimodalEncoder raises RuntimeError when image hidden size does not match expected size', 'test that ALBEFMultimodalEncoder raises RuntimeError when text hidden size does not match expected size', 'test that ALBEFMultimodalEncoder raises RuntimeError when image and text batch sizes do not match', 'create a pytest fixture that initializes ALBEFMultimodalEncoder with a fixed hidden size and attention heads']
```

Usage

```
{'test_multimodal_encoder_forward_pass': 'test the ALBEFMultimodalEncoder forward pass with image and text embeddings and attention masks', 'test_invalid_image_hidden_size': 'test that ALBEFMultimodalEncoder raises RuntimeError when image hidden size does not match expected size', 'test_invalid_text_hidden_size': 'test that ALBEFMultimodalEncoder raises RuntimeError when text hidden size does not match expected size', 'test_not_matching_input_batch_size': 'test that ALBEFMultimodalEncoder raises RuntimeError when image and text batch sizes do not match', 'create_multimodal_encoder_fixture': 'create a pytest fixture that initializes ALBEFMultimodalEncoder with a fixed hidden size and attention heads'}
```

