# Agent Python Tools

- repo: facebookresearch/edgetam
- repo_uri: https://github.com/facebookresearch/edgetam

## File: facebookresearch_edgetam/sam2/modeling/backbones/hieradet.py

Prompts

```
['build a Hiera hierarchical vision transformer backbone with configurable stages, window sizes, and global attention blocks', 'create a MultiScaleBlock transformer block with multi-scale attention, MLP, and optional Q pooling for stage transitions', 'create a MultiScaleAttention module with QKV projection, optional Q pooling, and scaled dot-product attention', 'run the Hiera backbone forward pass on an image tensor to extract multi-scale feature maps', 'review the do_pool utility function that applies pooling and normalization with tensor format conversion', 'build a python module to create an ImageEncoder with a trunk backbone and FpnNeck for vision feature extraction', 'run the ImageEncoder forward pass on a tensor sample to extract vision features and positional encodings', 'create a Feature Pyramid Network neck module with configurable interpolation model and fusion type for multi-scale features', 'run the FpnNeck forward pass on a list of feature tensors to produce multi-scale outputs with positional encoding', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the backbone FPN output', 'create a TimmBackbone instance with a model name and feature layer tuple', 'build a forward pass through the TimmBackbone body and return feature tensors', 'test the TimmBackbone initialization with pretrained TIMM model and feature indices', 'review the TimmBackbone channel_list property that extracts reversed channel counts from feature info', 'summarize the TimmBackbone class that wraps TIMM pretrained models as feature extraction backbones', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition and window_unpartition functions with a sample tensor round trip', 'review the PatchEmbed forward method that applies a conv2d projection and permutes to B H W C']
```

Usage

```
{'build_Hiera_backbone': 'build a Hiera hierarchical vision transformer backbone with configurable stages, window sizes, and global attention blocks', 'create_MultiScaleBlock': 'create a MultiScaleBlock transformer block with multi-scale attention, MLP, and optional Q pooling for stage transitions', 'create_MultiScaleAttention': 'create a MultiScaleAttention module with QKV projection, optional Q pooling, and scaled dot-product attention', 'run_Hiera_forward': 'run the Hiera backbone forward pass on an image tensor to extract multi-scale feature maps', 'review_do_pool': 'review the do_pool utility function that applies pooling and normalization with tensor format conversion'}
```

## File: facebookresearch_edgetam/sam2/modeling/backbones/image_encoder.py

Prompts

```
['build a Hiera hierarchical vision transformer backbone with configurable stages, window sizes, and global attention blocks', 'create a MultiScaleBlock transformer block with multi-scale attention, MLP, and optional Q pooling for stage transitions', 'create a MultiScaleAttention module with QKV projection, optional Q pooling, and scaled dot-product attention', 'run the Hiera backbone forward pass on an image tensor to extract multi-scale feature maps', 'review the do_pool utility function that applies pooling and normalization with tensor format conversion', 'build a python module to create an ImageEncoder with a trunk backbone and FpnNeck for vision feature extraction', 'run the ImageEncoder forward pass on a tensor sample to extract vision features and positional encodings', 'create a Feature Pyramid Network neck module with configurable interpolation model and fusion type for multi-scale features', 'run the FpnNeck forward pass on a list of feature tensors to produce multi-scale outputs with positional encoding', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the backbone FPN output', 'create a TimmBackbone instance with a model name and feature layer tuple', 'build a forward pass through the TimmBackbone body and return feature tensors', 'test the TimmBackbone initialization with pretrained TIMM model and feature indices', 'review the TimmBackbone channel_list property that extracts reversed channel counts from feature info', 'summarize the TimmBackbone class that wraps TIMM pretrained models as feature extraction backbones', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition and window_unpartition functions with a sample tensor round trip', 'review the PatchEmbed forward method that applies a conv2d projection and permutes to B H W C']
```

Usage

```
{'build_image_encoder': 'build a python module to create an ImageEncoder with a trunk backbone and FpnNeck for vision feature extraction', 'run_image_encoder_forward': 'run the ImageEncoder forward pass on a tensor sample to extract vision features and positional encodings', 'create_fpn_neck': 'create a Feature Pyramid Network neck module with configurable interpolation model and fusion type for multi-scale features', 'run_fpn_neck_forward': 'run the FpnNeck forward pass on a list of feature tensors to produce multi-scale outputs with positional encoding', 'review_image_encoder_scalp': 'review the ImageEncoder scalp parameter to discard lowest resolution features from the backbone FPN output'}
```

## File: facebookresearch_edgetam/sam2/modeling/backbones/timm.py

Prompts

```
['build a Hiera hierarchical vision transformer backbone with configurable stages, window sizes, and global attention blocks', 'create a MultiScaleBlock transformer block with multi-scale attention, MLP, and optional Q pooling for stage transitions', 'create a MultiScaleAttention module with QKV projection, optional Q pooling, and scaled dot-product attention', 'run the Hiera backbone forward pass on an image tensor to extract multi-scale feature maps', 'review the do_pool utility function that applies pooling and normalization with tensor format conversion', 'build a python module to create an ImageEncoder with a trunk backbone and FpnNeck for vision feature extraction', 'run the ImageEncoder forward pass on a tensor sample to extract vision features and positional encodings', 'create a Feature Pyramid Network neck module with configurable interpolation model and fusion type for multi-scale features', 'run the FpnNeck forward pass on a list of feature tensors to produce multi-scale outputs with positional encoding', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the backbone FPN output', 'create a TimmBackbone instance with a model name and feature layer tuple', 'build a forward pass through the TimmBackbone body and return feature tensors', 'test the TimmBackbone initialization with pretrained TIMM model and feature indices', 'review the TimmBackbone channel_list property that extracts reversed channel counts from feature info', 'summarize the TimmBackbone class that wraps TIMM pretrained models as feature extraction backbones', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition and window_unpartition functions with a sample tensor round trip', 'review the PatchEmbed forward method that applies a conv2d projection and permutes to B H W C']
```

Usage

```
{'create_TimmBackbone': 'create a TimmBackbone instance with a model name and feature layer tuple', 'build_TimmBackbone_forward': 'build a forward pass through the TimmBackbone body and return feature tensors', 'test_TimmBackbone_init': 'test the TimmBackbone initialization with pretrained TIMM model and feature indices', 'review_TimmBackbone_channel_list': 'review the TimmBackbone channel_list property that extracts reversed channel counts from feature info', 'summarize_TimmBackbone': 'summarize the TimmBackbone class that wraps TIMM pretrained models as feature extraction backbones'}
```

## File: facebookresearch_edgetam/sam2/modeling/backbones/utils.py

Prompts

```
['build a Hiera hierarchical vision transformer backbone with configurable stages, window sizes, and global attention blocks', 'create a MultiScaleBlock transformer block with multi-scale attention, MLP, and optional Q pooling for stage transitions', 'create a MultiScaleAttention module with QKV projection, optional Q pooling, and scaled dot-product attention', 'run the Hiera backbone forward pass on an image tensor to extract multi-scale feature maps', 'review the do_pool utility function that applies pooling and normalization with tensor format conversion', 'build a python module to create an ImageEncoder with a trunk backbone and FpnNeck for vision feature extraction', 'run the ImageEncoder forward pass on a tensor sample to extract vision features and positional encodings', 'create a Feature Pyramid Network neck module with configurable interpolation model and fusion type for multi-scale features', 'run the FpnNeck forward pass on a list of feature tensors to produce multi-scale outputs with positional encoding', 'review the ImageEncoder scalp parameter to discard lowest resolution features from the backbone FPN output', 'create a TimmBackbone instance with a model name and feature layer tuple', 'build a forward pass through the TimmBackbone body and return feature tensors', 'test the TimmBackbone initialization with pretrained TIMM model and feature indices', 'review the TimmBackbone channel_list property that extracts reversed channel counts from feature info', 'summarize the TimmBackbone class that wraps TIMM pretrained models as feature extraction backbones', 'build a python module to partition a tensor into non-overlapping windows with padding', 'build a python module to unpartition windows back into the original tensor shape', 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test the window_partition and window_unpartition functions with a sample tensor round trip', 'review the PatchEmbed forward method that applies a conv2d projection and permutes to B H W C']
```

Usage

```
{'build_window_partition': 'build a python module to partition a tensor into non-overlapping windows with padding', 'build_window_unpartition': 'build a python module to unpartition windows back into the original tensor shape', 'create_patch_embed': 'create a PatchEmbed module that converts an image to patch embeddings using a convolutional layer', 'test_window_partition_unpartition': 'test the window_partition and window_unpartition functions with a sample tensor round trip', 'review_PatchEmbed_forward': 'review the PatchEmbed forward method that applies a conv2d projection and permutes to B H W C'}
```

