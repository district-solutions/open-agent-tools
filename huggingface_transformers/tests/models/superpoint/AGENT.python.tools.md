# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/superpoint/test_image_processing_superpoint.py

Prompts

```
['test the SuperPoint image processor by instantiating it with config dict and verifying do_resize, size, do_rescale, rescale_factor, do_grayscale attributes', 'test creating a SuperPoint image processor from a config dict and overriding size with kwargs to set height and width', 'test that the SuperPoint image processor converts input images to grayscale by verifying all three channels are identical', 'test post-processing keypoint detection output by verifying keypoints are within image bounds and non-negative', 'prepare a synthetic SuperPointKeypointDescriptionOutput with random keypoints, scores, descriptors, and mask for testing', 'test the SuperPointConfig class configuration with common properties', 'test SuperPointForKeypointDetection keypoint detection output shapes and hidden states', 'test SuperPointForKeypointDetection hidden states output across encoder layers', 'test SuperPointForKeypointDetection batching equivalence with stable topk indices', 'test loading SuperPointForKeypointDetection from magic-leap-community/superpoint pretrained model']
```

Usage

```
{'test_image_processing_superpoint': 'test the SuperPoint image processor by instantiating it with config dict and verifying do_resize, size, do_rescale, rescale_factor, do_grayscale attributes', 'test_image_processor_from_dict_with_kwargs': 'test creating a SuperPoint image processor from a config dict and overriding size with kwargs to set height and width', 'test_input_image_properly_converted_to_grayscale': 'test that the SuperPoint image processor converts input images to grayscale by verifying all three channels are identical', 'test_post_processing_keypoint_detection': 'test post-processing keypoint detection output by verifying keypoints are within image bounds and non-negative', 'prepare_keypoint_detection_output': 'prepare a synthetic SuperPointKeypointDescriptionOutput with random keypoints, scores, descriptors, and mask for testing'}
```

## File: huggingface_transformers/tests/models/superpoint/test_modeling_superpoint.py

Prompts

```
['test the SuperPoint image processor by instantiating it with config dict and verifying do_resize, size, do_rescale, rescale_factor, do_grayscale attributes', 'test creating a SuperPoint image processor from a config dict and overriding size with kwargs to set height and width', 'test that the SuperPoint image processor converts input images to grayscale by verifying all three channels are identical', 'test post-processing keypoint detection output by verifying keypoints are within image bounds and non-negative', 'prepare a synthetic SuperPointKeypointDescriptionOutput with random keypoints, scores, descriptors, and mask for testing', 'test the SuperPointConfig class configuration with common properties', 'test SuperPointForKeypointDetection keypoint detection output shapes and hidden states', 'test SuperPointForKeypointDetection hidden states output across encoder layers', 'test SuperPointForKeypointDetection batching equivalence with stable topk indices', 'test loading SuperPointForKeypointDetection from magic-leap-community/superpoint pretrained model']
```

Usage

```
{'test_model_superpoint_config': 'test the SuperPointConfig class configuration with common properties', 'test_model_keypoint_detection': 'test SuperPointForKeypointDetection keypoint detection output shapes and hidden states', 'test_model_hidden_states_output': 'test SuperPointForKeypointDetection hidden states output across encoder layers', 'test_model_batching_equivalence': 'test SuperPointForKeypointDetection batching equivalence with stable topk indices', 'test_model_from_pretrained': 'test loading SuperPointForKeypointDetection from magic-leap-community/superpoint pretrained model'}
```

