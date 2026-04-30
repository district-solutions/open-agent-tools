# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glpn/convert_glpn_to_pytorch.py

Prompts

```
['convert a GLPN PyTorch checkpoint to HuggingFace transformers format using argparse CLI', 'rename state dict keys from original GLPN implementation to HuggingFace GLPNForDepthEstimation format', 'split combined key-value matrices into separate key and value weights in the state dict', 'download a COCO validation image for verifying converted model output', 'summarize the GLPN checkpoint conversion script that transforms PyTorch checkpoints to HuggingFace format', 'create a GLPNImageProcessor instance with custom size_divisor for depth estimation preprocessing', 'run GLPNImageProcessor preprocess to resize, rescale, and normalize input images for depth estimation', 'run GLPNImageProcessor resize to down-size image dimensions to multiples of size_divisor', 'run GLPNImageProcessor post_process_depth_estimation to resize predicted depth maps to target image sizes', 'test GLPNImageProcessorKwargs type definition for configurable size_divisor parameter', 'create a GLPNImageProcessorPil instance with custom size_divisor for depth estimation preprocessing', 'build image resize that rounds height and width down to the closest multiple of size_divisor', 'run image preprocessing pipeline with resize, rescale, and normalize for GLPN depth estimation', 'post process depth estimation outputs by resizing predicted depth maps to target image sizes', 'validate and filter preprocess kwargs by removing unused size parameters for size_divisor-based resize', 'build a GLPN depth estimation model for predicting depth maps from input images', 'create a GLPN encoder that extracts hierarchical features from image patches using overlapping embeddings and transformer blocks', 'run forward pass on GLPNForDepthEstimation to predict depth maps with optional loss computation using SiLogLoss', 'build a GLPN decoder that fuses local and global features via selective feature fusion and upsampling stages', 'test GLPNEfficientSelfAttention with sequence reduction for efficient self-attention on spatial tokens']
```

Usage

```
{'convert_glpn_checkpoint': 'convert a GLPN PyTorch checkpoint to HuggingFace transformers format using argparse CLI', 'rename_keys': 'rename state dict keys from original GLPN implementation to HuggingFace GLPNForDepthEstimation format', 'read_in_k_v': 'split combined key-value matrices into separate key and value weights in the state dict', 'prepare_img': 'download a COCO validation image for verifying converted model output', 'summarize_convert_glpn_checkpoint': 'summarize the GLPN checkpoint conversion script that transforms PyTorch checkpoints to HuggingFace format'}
```

## File: huggingface_transformers/src/transformers/models/glpn/image_processing_glpn.py

Prompts

```
['convert a GLPN PyTorch checkpoint to HuggingFace transformers format using argparse CLI', 'rename state dict keys from original GLPN implementation to HuggingFace GLPNForDepthEstimation format', 'split combined key-value matrices into separate key and value weights in the state dict', 'download a COCO validation image for verifying converted model output', 'summarize the GLPN checkpoint conversion script that transforms PyTorch checkpoints to HuggingFace format', 'create a GLPNImageProcessor instance with custom size_divisor for depth estimation preprocessing', 'run GLPNImageProcessor preprocess to resize, rescale, and normalize input images for depth estimation', 'run GLPNImageProcessor resize to down-size image dimensions to multiples of size_divisor', 'run GLPNImageProcessor post_process_depth_estimation to resize predicted depth maps to target image sizes', 'test GLPNImageProcessorKwargs type definition for configurable size_divisor parameter', 'create a GLPNImageProcessorPil instance with custom size_divisor for depth estimation preprocessing', 'build image resize that rounds height and width down to the closest multiple of size_divisor', 'run image preprocessing pipeline with resize, rescale, and normalize for GLPN depth estimation', 'post process depth estimation outputs by resizing predicted depth maps to target image sizes', 'validate and filter preprocess kwargs by removing unused size parameters for size_divisor-based resize', 'build a GLPN depth estimation model for predicting depth maps from input images', 'create a GLPN encoder that extracts hierarchical features from image patches using overlapping embeddings and transformer blocks', 'run forward pass on GLPNForDepthEstimation to predict depth maps with optional loss computation using SiLogLoss', 'build a GLPN decoder that fuses local and global features via selective feature fusion and upsampling stages', 'test GLPNEfficientSelfAttention with sequence reduction for efficient self-attention on spatial tokens']
```

Usage

```
{'create_glpn_image_processor': 'create a GLPNImageProcessor instance with custom size_divisor for depth estimation preprocessing', 'run_glpn_preprocess': 'run GLPNImageProcessor preprocess to resize, rescale, and normalize input images for depth estimation', 'run_glpn_resize': 'run GLPNImageProcessor resize to down-size image dimensions to multiples of size_divisor', 'run_glpn_post_process_depth_estimation': 'run GLPNImageProcessor post_process_depth_estimation to resize predicted depth maps to target image sizes', 'test_glpn_image_processor_kwargs': 'test GLPNImageProcessorKwargs type definition for configurable size_divisor parameter'}
```

## File: huggingface_transformers/src/transformers/models/glpn/image_processing_pil_glpn.py

Prompts

```
['convert a GLPN PyTorch checkpoint to HuggingFace transformers format using argparse CLI', 'rename state dict keys from original GLPN implementation to HuggingFace GLPNForDepthEstimation format', 'split combined key-value matrices into separate key and value weights in the state dict', 'download a COCO validation image for verifying converted model output', 'summarize the GLPN checkpoint conversion script that transforms PyTorch checkpoints to HuggingFace format', 'create a GLPNImageProcessor instance with custom size_divisor for depth estimation preprocessing', 'run GLPNImageProcessor preprocess to resize, rescale, and normalize input images for depth estimation', 'run GLPNImageProcessor resize to down-size image dimensions to multiples of size_divisor', 'run GLPNImageProcessor post_process_depth_estimation to resize predicted depth maps to target image sizes', 'test GLPNImageProcessorKwargs type definition for configurable size_divisor parameter', 'create a GLPNImageProcessorPil instance with custom size_divisor for depth estimation preprocessing', 'build image resize that rounds height and width down to the closest multiple of size_divisor', 'run image preprocessing pipeline with resize, rescale, and normalize for GLPN depth estimation', 'post process depth estimation outputs by resizing predicted depth maps to target image sizes', 'validate and filter preprocess kwargs by removing unused size parameters for size_divisor-based resize', 'build a GLPN depth estimation model for predicting depth maps from input images', 'create a GLPN encoder that extracts hierarchical features from image patches using overlapping embeddings and transformer blocks', 'run forward pass on GLPNForDepthEstimation to predict depth maps with optional loss computation using SiLogLoss', 'build a GLPN decoder that fuses local and global features via selective feature fusion and upsampling stages', 'test GLPNEfficientSelfAttention with sequence reduction for efficient self-attention on spatial tokens']
```

Usage

```
{'create_image_processor_glpn': 'create a GLPNImageProcessorPil instance with custom size_divisor for depth estimation preprocessing', 'build_image_resize_divisor': 'build image resize that rounds height and width down to the closest multiple of size_divisor', 'run_image_preprocess_pipeline': 'run image preprocessing pipeline with resize, rescale, and normalize for GLPN depth estimation', 'post_process_depth_estimation': 'post process depth estimation outputs by resizing predicted depth maps to target image sizes', 'validate_preprocess_kwargs': 'validate and filter preprocess kwargs by removing unused size parameters for size_divisor-based resize'}
```

## File: huggingface_transformers/src/transformers/models/glpn/modeling_glpn.py

Prompts

```
['convert a GLPN PyTorch checkpoint to HuggingFace transformers format using argparse CLI', 'rename state dict keys from original GLPN implementation to HuggingFace GLPNForDepthEstimation format', 'split combined key-value matrices into separate key and value weights in the state dict', 'download a COCO validation image for verifying converted model output', 'summarize the GLPN checkpoint conversion script that transforms PyTorch checkpoints to HuggingFace format', 'create a GLPNImageProcessor instance with custom size_divisor for depth estimation preprocessing', 'run GLPNImageProcessor preprocess to resize, rescale, and normalize input images for depth estimation', 'run GLPNImageProcessor resize to down-size image dimensions to multiples of size_divisor', 'run GLPNImageProcessor post_process_depth_estimation to resize predicted depth maps to target image sizes', 'test GLPNImageProcessorKwargs type definition for configurable size_divisor parameter', 'create a GLPNImageProcessorPil instance with custom size_divisor for depth estimation preprocessing', 'build image resize that rounds height and width down to the closest multiple of size_divisor', 'run image preprocessing pipeline with resize, rescale, and normalize for GLPN depth estimation', 'post process depth estimation outputs by resizing predicted depth maps to target image sizes', 'validate and filter preprocess kwargs by removing unused size parameters for size_divisor-based resize', 'build a GLPN depth estimation model for predicting depth maps from input images', 'create a GLPN encoder that extracts hierarchical features from image patches using overlapping embeddings and transformer blocks', 'run forward pass on GLPNForDepthEstimation to predict depth maps with optional loss computation using SiLogLoss', 'build a GLPN decoder that fuses local and global features via selective feature fusion and upsampling stages', 'test GLPNEfficientSelfAttention with sequence reduction for efficient self-attention on spatial tokens']
```

Usage

```
{'build_depth_estimation_model': 'build a GLPN depth estimation model for predicting depth maps from input images', 'create_encoder_encoder_features': 'create a GLPN encoder that extracts hierarchical features from image patches using overlapping embeddings and transformer blocks', 'run_depth_prediction_forward': 'run forward pass on GLPNForDepthEstimation to predict depth maps with optional loss computation using SiLogLoss', 'build_decoder_fuse_features': 'build a GLPN decoder that fuses local and global features via selective feature fusion and upsampling stages', 'test_attention_sequence_reduction': 'test GLPNEfficientSelfAttention with sequence reduction for efficient self-attention on spatial tokens'}
```

