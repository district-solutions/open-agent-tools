# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/depther/base.py

Prompts

```
['build a python module that subclasses BaseDepther to implement a custom depth estimation model', 'test the BaseDepther forward method to verify it dispatches to forward_train or forward_test based on return_loss', 'run the BaseDepther train_step method to process a data batch and return loss and log variables', 'review the BaseDepther _parse_losses static method to understand how it aggregates and reduces losses for distributed training', 'refactor the BaseDepther forward_test method to customize test-time augmentation routing logic', 'build a DepthEncoderDecoder model with a backbone, decode_head, and optional neck for monocular depth estimation', 'extract multi-scale features from input images using the backbone and optional neck network', 'encode input images through the backbone and decode into a depth estimation map with optional rescaling', 'run forward training pass with input images and ground truth depth to compute loss components', 'perform depth inference using sliding-window strategy with configurable crop size and stride for large images']
```

Usage

```
{'build_DepthModel_subclass': 'build a python module that subclasses BaseDepther to implement a custom depth estimation model', 'test_forward_dispatch': 'test the BaseDepther forward method to verify it dispatches to forward_train or forward_test based on return_loss', 'run_train_step': 'run the BaseDepther train_step method to process a data batch and return loss and log variables', 'review_parse_losses': 'review the BaseDepther _parse_losses static method to understand how it aggregates and reduces losses for distributed training', 'refactor_forward_test_aug': 'refactor the BaseDepther forward_test method to customize test-time augmentation routing logic'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/depther/encoder_decoder.py

Prompts

```
['build a python module that subclasses BaseDepther to implement a custom depth estimation model', 'test the BaseDepther forward method to verify it dispatches to forward_train or forward_test based on return_loss', 'run the BaseDepther train_step method to process a data batch and return loss and log variables', 'review the BaseDepther _parse_losses static method to understand how it aggregates and reduces losses for distributed training', 'refactor the BaseDepther forward_test method to customize test-time augmentation routing logic', 'build a DepthEncoderDecoder model with a backbone, decode_head, and optional neck for monocular depth estimation', 'extract multi-scale features from input images using the backbone and optional neck network', 'encode input images through the backbone and decode into a depth estimation map with optional rescaling', 'run forward training pass with input images and ground truth depth to compute loss components', 'perform depth inference using sliding-window strategy with configurable crop size and stride for large images']
```

Usage

```
{'build_depth_encoder_decoder': 'build a DepthEncoderDecoder model with a backbone, decode_head, and optional neck for monocular depth estimation', 'extract_features_from_images': 'extract multi-scale features from input images using the backbone and optional neck network', 'encode_decode_depth_map': 'encode input images through the backbone and decode into a depth estimation map with optional rescaling', 'train_depth_model': 'run forward training pass with input images and ground truth depth to compute loss components', 'inference_depth_sliding_window': 'perform depth inference using sliding-window strategy with configurable crop size and stride for large images'}
```

