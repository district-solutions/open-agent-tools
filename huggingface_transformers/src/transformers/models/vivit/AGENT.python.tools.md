# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vivit/convert_vivit_flax_to_pytorch.py

Prompts

```
['convert a Flax ViViT checkpoint to PyTorch and save the model and processor to an output path', 'download a ViViT Flax checkpoint from Google Storage to a local file path', 'get a VivitConfig for Kinetics-400 video classification with 400 output labels', 'transform a Flax ViViT state dict into a PyTorch state dict with correct weight transposes', 'get a VivitImageProcessor configured to match the original Scenic ViViT preprocessing pipeline', 'build a VivitImageProcessor instance to preprocess video frames for the ViViT model with custom resize and crop settings', 'create a preprocessed batch of video frames with pixel_values resized, cropped, rescaled, and normalized for ViViT input', 'resize a single video frame to a target size while preserving aspect ratio using bilinear resampling', 'rescale image pixel values by a scale factor with optional offset to produce values in [-1, 1]', 'preprocess a single image through resize, center crop, rescale, and normalize steps for ViViT model input', 'create a ViViT model for video classification with a linear head on the CLS token output', 'build a ViViT model forward pass that converts video pixel values into transformer embeddings and pooled output', 'test ViViT embeddings with bicubic position encoding interpolation for higher resolution video inputs', 'review the ViViT self-attention mechanism that computes query, key, value projections with configurable attention heads', 'summarize the ViViT encoder layer with pre-layernorm, self-attention, and feed-forward residual connections']
```

Usage

```
{'convert_flax_to_pytorch': 'convert a Flax ViViT checkpoint to PyTorch and save the model and processor to an output path', 'download_vivit_checkpoint': 'download a ViViT Flax checkpoint from Google Storage to a local file path', 'get_vivit_config': 'get a VivitConfig for Kinetics-400 video classification with 400 output labels', 'transform_flax_state_to_pytorch': 'transform a Flax ViViT state dict into a PyTorch state dict with correct weight transposes', 'get_vivit_processor': 'get a VivitImageProcessor configured to match the original Scenic ViViT preprocessing pipeline'}
```

## File: huggingface_transformers/src/transformers/models/vivit/image_processing_vivit.py

Prompts

```
['convert a Flax ViViT checkpoint to PyTorch and save the model and processor to an output path', 'download a ViViT Flax checkpoint from Google Storage to a local file path', 'get a VivitConfig for Kinetics-400 video classification with 400 output labels', 'transform a Flax ViViT state dict into a PyTorch state dict with correct weight transposes', 'get a VivitImageProcessor configured to match the original Scenic ViViT preprocessing pipeline', 'build a VivitImageProcessor instance to preprocess video frames for the ViViT model with custom resize and crop settings', 'create a preprocessed batch of video frames with pixel_values resized, cropped, rescaled, and normalized for ViViT input', 'resize a single video frame to a target size while preserving aspect ratio using bilinear resampling', 'rescale image pixel values by a scale factor with optional offset to produce values in [-1, 1]', 'preprocess a single image through resize, center crop, rescale, and normalize steps for ViViT model input', 'create a ViViT model for video classification with a linear head on the CLS token output', 'build a ViViT model forward pass that converts video pixel values into transformer embeddings and pooled output', 'test ViViT embeddings with bicubic position encoding interpolation for higher resolution video inputs', 'review the ViViT self-attention mechanism that computes query, key, value projections with configurable attention heads', 'summarize the ViViT encoder layer with pre-layernorm, self-attention, and feed-forward residual connections']
```

Usage

```
{'build_vivit_image_processor': 'build a VivitImageProcessor instance to preprocess video frames for the ViViT model with custom resize and crop settings', 'create_preprocess_videos': 'create a preprocessed batch of video frames with pixel_values resized, cropped, rescaled, and normalized for ViViT input', 'resize_image_vivit': 'resize a single video frame to a target size while preserving aspect ratio using bilinear resampling', 'rescale_image_vivit': 'rescale image pixel values by a scale factor with optional offset to produce values in [-1, 1]', 'preprocess_single_image_vivit': 'preprocess a single image through resize, center crop, rescale, and normalize steps for ViViT model input'}
```

## File: huggingface_transformers/src/transformers/models/vivit/modeling_vivit.py

Prompts

```
['convert a Flax ViViT checkpoint to PyTorch and save the model and processor to an output path', 'download a ViViT Flax checkpoint from Google Storage to a local file path', 'get a VivitConfig for Kinetics-400 video classification with 400 output labels', 'transform a Flax ViViT state dict into a PyTorch state dict with correct weight transposes', 'get a VivitImageProcessor configured to match the original Scenic ViViT preprocessing pipeline', 'build a VivitImageProcessor instance to preprocess video frames for the ViViT model with custom resize and crop settings', 'create a preprocessed batch of video frames with pixel_values resized, cropped, rescaled, and normalized for ViViT input', 'resize a single video frame to a target size while preserving aspect ratio using bilinear resampling', 'rescale image pixel values by a scale factor with optional offset to produce values in [-1, 1]', 'preprocess a single image through resize, center crop, rescale, and normalize steps for ViViT model input', 'create a ViViT model for video classification with a linear head on the CLS token output', 'build a ViViT model forward pass that converts video pixel values into transformer embeddings and pooled output', 'test ViViT embeddings with bicubic position encoding interpolation for higher resolution video inputs', 'review the ViViT self-attention mechanism that computes query, key, value projections with configurable attention heads', 'summarize the ViViT encoder layer with pre-layernorm, self-attention, and feed-forward residual connections']
```

Usage

```
{'create_vivit_video_classification': 'create a ViViT model for video classification with a linear head on the CLS token output', 'build_vivit_model_forward': 'build a ViViT model forward pass that converts video pixel values into transformer embeddings and pooled output', 'test_vivit_embeddings_interpolation': 'test ViViT embeddings with bicubic position encoding interpolation for higher resolution video inputs', 'review_vivit_self_attention': 'review the ViViT self-attention mechanism that computes query, key, value projections with configurable attention heads', 'summarize_vivit_encoder_layer': 'summarize the ViViT encoder layer with pre-layernorm, self-attention, and feed-forward residual connections'}
```

