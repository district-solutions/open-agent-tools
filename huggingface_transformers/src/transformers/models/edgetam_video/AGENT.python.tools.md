# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/edgetam_video/convert_edgetam_video_to_hf.py

Prompts

```
['convert an EdgeTAM checkpoint to HuggingFace transformers format and save locally', 'build an EdgeTamVideoConfig with RepViT backbone and default prompt encoder and mask decoder settings', 'transform original SAM checkpoint keys to HuggingFace-compatible state dictionary keys', 'test the converted model with a sample image and point prompts to verify output scores', 'upload the converted model and processor to a HuggingFace Hub repository', 'run EdgeTamVideoModel forward to segment objects in a video frame using point or mask prompts', 'propagate EdgeTamVideoModel through video frames to track objects across the entire sequence', 'build an EdgeTamVideoInferenceSession to manage video inference state, caching, and object tracking', 'create prompt embeddings from input points, boxes, or masks using EdgeTamVideoPromptEncoder', 'get image embeddings from pixel values using the vision encoder and FPN feature maps', 'create an EdgeTamVideoModel instance with EdgeTamVideoConfig for video object segmentation', 'encode predicted masks into memory features for conditioning future frames in video tracking', 'fuse current frame vision features with memory from previous frames for object tracking', 'build a spatial perceiver resampler that downsamples vision features into 1D and 2D latent tokens']
```

Usage

```
{'convert_edgetam_checkpoint': 'convert an EdgeTAM checkpoint to HuggingFace transformers format and save locally', 'get_config': 'build an EdgeTamVideoConfig with RepViT backbone and default prompt encoder and mask decoder settings', 'replace_keys': 'transform original SAM checkpoint keys to HuggingFace-compatible state dictionary keys', 'run_sanity_check': 'test the converted model with a sample image and point prompts to verify output scores', 'push_to_hub': 'upload the converted model and processor to a HuggingFace Hub repository'}
```

## File: huggingface_transformers/src/transformers/models/edgetam_video/modeling_edgetam_video.py

Prompts

```
['convert an EdgeTAM checkpoint to HuggingFace transformers format and save locally', 'build an EdgeTamVideoConfig with RepViT backbone and default prompt encoder and mask decoder settings', 'transform original SAM checkpoint keys to HuggingFace-compatible state dictionary keys', 'test the converted model with a sample image and point prompts to verify output scores', 'upload the converted model and processor to a HuggingFace Hub repository', 'run EdgeTamVideoModel forward to segment objects in a video frame using point or mask prompts', 'propagate EdgeTamVideoModel through video frames to track objects across the entire sequence', 'build an EdgeTamVideoInferenceSession to manage video inference state, caching, and object tracking', 'create prompt embeddings from input points, boxes, or masks using EdgeTamVideoPromptEncoder', 'get image embeddings from pixel values using the vision encoder and FPN feature maps', 'create an EdgeTamVideoModel instance with EdgeTamVideoConfig for video object segmentation', 'encode predicted masks into memory features for conditioning future frames in video tracking', 'fuse current frame vision features with memory from previous frames for object tracking', 'build a spatial perceiver resampler that downsamples vision features into 1D and 2D latent tokens']
```

Usage

```
{'run_video_object_segmentation': 'run EdgeTamVideoModel forward to segment objects in a video frame using point or mask prompts', 'propagate_video_tracking': 'propagate EdgeTamVideoModel through video frames to track objects across the entire sequence', 'build_inference_session': 'build an EdgeTamVideoInferenceSession to manage video inference state, caching, and object tracking', 'create_prompt_embeddings': 'create prompt embeddings from input points, boxes, or masks using EdgeTamVideoPromptEncoder', 'get_image_embeddings': 'get image embeddings from pixel values using the vision encoder and FPN feature maps'}
```

## File: huggingface_transformers/src/transformers/models/edgetam_video/modular_edgetam_video.py

Prompts

```
['convert an EdgeTAM checkpoint to HuggingFace transformers format and save locally', 'build an EdgeTamVideoConfig with RepViT backbone and default prompt encoder and mask decoder settings', 'transform original SAM checkpoint keys to HuggingFace-compatible state dictionary keys', 'test the converted model with a sample image and point prompts to verify output scores', 'upload the converted model and processor to a HuggingFace Hub repository', 'run EdgeTamVideoModel forward to segment objects in a video frame using point or mask prompts', 'propagate EdgeTamVideoModel through video frames to track objects across the entire sequence', 'build an EdgeTamVideoInferenceSession to manage video inference state, caching, and object tracking', 'create prompt embeddings from input points, boxes, or masks using EdgeTamVideoPromptEncoder', 'get image embeddings from pixel values using the vision encoder and FPN feature maps', 'create an EdgeTamVideoModel instance with EdgeTamVideoConfig for video object segmentation', 'encode predicted masks into memory features for conditioning future frames in video tracking', 'fuse current frame vision features with memory from previous frames for object tracking', 'build a spatial perceiver resampler that downsamples vision features into 1D and 2D latent tokens']
```

Usage

```
{'create_edgetam_video_model': 'create an EdgeTamVideoModel instance with EdgeTamVideoConfig for video object segmentation', 'run_video_object_segmentation': 'run video object segmentation on frames with point and mask prompts via EdgeTamVideoModel.forward', 'encode_new_memory': 'encode predicted masks into memory features for conditioning future frames in video tracking', 'prepare_memory_conditioned_features': 'fuse current frame vision features with memory from previous frames for object tracking', 'build_perceiver_resampler': 'build a spatial perceiver resampler that downsamples vision features into 1D and 2D latent tokens'}
```

