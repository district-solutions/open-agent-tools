# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/depth/models/depther/base.py

Prompts

```
['build a python module that subclasses BaseDepther to implement a custom depth estimation model', 'test the BaseDepther forward_train method by passing images and metadata for training', 'test the BaseDepther forward_test method with augmented image batches for inference', 'review the BaseDepther train_step method to understand loss parsing and logging during training', 'summarize the BaseDepther _parse_losses static method that aggregates and reduces loss tensors for distributed training', 'build a DepthEncoderDecoder model with a backbone, decode head, and optional neck for monocular depth estimation', 'run forward training on input images with ground truth depth to compute loss components', 'run sliding window inference with overlap to predict depth maps on large images', 'run simple test inference on a single image to produce a depth prediction map', 'run test with multiple augmented images and average their depth predictions for robust estimation']
```

Usage

```
{'build_DepthEstimator_subclass': 'build a python module that subclasses BaseDepther to implement a custom depth estimation model', 'test_forward_train': 'test the BaseDepther forward_train method by passing images and metadata for training', 'test_forward_test': 'test the BaseDepther forward_test method with augmented image batches for inference', 'review_train_step': 'review the BaseDepther train_step method to understand loss parsing and logging during training', 'summarize_parse_losses': 'summarize the BaseDepther _parse_losses static method that aggregates and reduces loss tensors for distributed training'}
```

## File: facebookresearch_dinov2/dinov2/eval/depth/models/depther/encoder_decoder.py

Prompts

```
['build a python module that subclasses BaseDepther to implement a custom depth estimation model', 'test the BaseDepther forward_train method by passing images and metadata for training', 'test the BaseDepther forward_test method with augmented image batches for inference', 'review the BaseDepther train_step method to understand loss parsing and logging during training', 'summarize the BaseDepther _parse_losses static method that aggregates and reduces loss tensors for distributed training', 'build a DepthEncoderDecoder model with a backbone, decode head, and optional neck for monocular depth estimation', 'run forward training on input images with ground truth depth to compute loss components', 'run sliding window inference with overlap to predict depth maps on large images', 'run simple test inference on a single image to produce a depth prediction map', 'run test with multiple augmented images and average their depth predictions for robust estimation']
```

Usage

```
{'build_depth_encoder_decoder': 'build a DepthEncoderDecoder model with a backbone, decode head, and optional neck for monocular depth estimation', 'run_forward_train': 'run forward training on input images with ground truth depth to compute loss components', 'run_slide_inference': 'run sliding window inference with overlap to predict depth maps on large images', 'run_simple_test': 'run simple test inference on a single image to produce a depth prediction map', 'run_aug_test': 'run test with multiple augmented images and average their depth predictions for robust estimation'}
```

