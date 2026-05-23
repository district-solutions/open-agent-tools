# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/sam2/modeling/backbones/hieradet.py

Prompts

```
['build a Hiera backbone model with configurable stages, window sizes, and global attention blocks for SAM2', 'create a MultiScaleAttention module that performs scaled dot product attention with optional query pooling for downsampling', 'create a MultiScaleBlock transformer block with windowed attention, MLP, and skip connections for hierarchical feature extraction', 'run the Hiera model forward pass to extract multi-scale feature maps from an input image tensor', 'review the do_pool utility function that applies pooling and normalization to tensors with channel-last layout', 'build an ImageEncoder with a trunk backbone and FpnNeck to extract vision features from images', 'run the ImageEncoder forward pass on a tensor sample to get vision features and positional encodings', 'create an FpnNeck with position encoding and a backbone channel list for feature pyramid processing', 'run the FpnNeck forward pass on a list of feature tensors to get multi-scale outputs and positions', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the output', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition function by partitioning a tensor and verifying the output shape', 'test the window_unpartition function by reversing a partition and verifying the original tensor is recovered']
```

Usage

```
{'build_hieradet_backbone': 'build a Hiera backbone model with configurable stages, window sizes, and global attention blocks for SAM2', 'create_multiscale_attention': 'create a MultiScaleAttention module that performs scaled dot product attention with optional query pooling for downsampling', 'create_multiscale_block': 'create a MultiScaleBlock transformer block with windowed attention, MLP, and skip connections for hierarchical feature extraction', 'run_hieradet_forward': 'run the Hiera model forward pass to extract multi-scale feature maps from an input image tensor', 'review_do_pool': 'review the do_pool utility function that applies pooling and normalization to tensors with channel-last layout'}
```

## File: facebookresearch_sam2/sam2/modeling/backbones/image_encoder.py

Prompts

```
['build a Hiera backbone model with configurable stages, window sizes, and global attention blocks for SAM2', 'create a MultiScaleAttention module that performs scaled dot product attention with optional query pooling for downsampling', 'create a MultiScaleBlock transformer block with windowed attention, MLP, and skip connections for hierarchical feature extraction', 'run the Hiera model forward pass to extract multi-scale feature maps from an input image tensor', 'review the do_pool utility function that applies pooling and normalization to tensors with channel-last layout', 'build an ImageEncoder with a trunk backbone and FpnNeck to extract vision features from images', 'run the ImageEncoder forward pass on a tensor sample to get vision features and positional encodings', 'create an FpnNeck with position encoding and a backbone channel list for feature pyramid processing', 'run the FpnNeck forward pass on a list of feature tensors to get multi-scale outputs and positions', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the output', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition function by partitioning a tensor and verifying the output shape', 'test the window_unpartition function by reversing a partition and verifying the original tensor is recovered']
```

Usage

```
{'build_image_encoder': 'build an ImageEncoder with a trunk backbone and FpnNeck to extract vision features from images', 'run_image_encoder_forward': 'run the ImageEncoder forward pass on a tensor sample to get vision features and positional encodings', 'create_fpn_neck': 'create an FpnNeck with position encoding and a backbone channel list for feature pyramid processing', 'run_fpn_neck_forward': 'run the FpnNeck forward pass on a list of feature tensors to get multi-scale outputs and positions', 'review_image_encoder_scalp': 'review the ImageEncoder scalp parameter to discard lowest resolution features from the output'}
```

## File: facebookresearch_sam2/sam2/modeling/backbones/utils.py

Prompts

```
['build a Hiera backbone model with configurable stages, window sizes, and global attention blocks for SAM2', 'create a MultiScaleAttention module that performs scaled dot product attention with optional query pooling for downsampling', 'create a MultiScaleBlock transformer block with windowed attention, MLP, and skip connections for hierarchical feature extraction', 'run the Hiera model forward pass to extract multi-scale feature maps from an input image tensor', 'review the do_pool utility function that applies pooling and normalization to tensors with channel-last layout', 'build an ImageEncoder with a trunk backbone and FpnNeck to extract vision features from images', 'run the ImageEncoder forward pass on a tensor sample to get vision features and positional encodings', 'create an FpnNeck with position encoding and a backbone channel list for feature pyramid processing', 'run the FpnNeck forward pass on a list of feature tensors to get multi-scale outputs and positions', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the output', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition function by partitioning a tensor and verifying the output shape', 'test the window_unpartition function by reversing a partition and verifying the original tensor is recovered']
```

Usage

```
{'build_window_partition': 'build a python module to partition a tensor into non-overlapping windows with padding', 'build_window_unpartition': 'build a python module to unpartition windows back into the original tensor shape', 'create_patch_embed': 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test_window_partition': 'test the window_partition function by partitioning a tensor and verifying the output shape', 'test_window_unpartition': 'test the window_unpartition function by reversing a partition and verifying the original tensor is recovered'}
```

