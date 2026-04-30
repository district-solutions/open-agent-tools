# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pe_video/modeling_pe_video.py

Prompts

```
['build a PeVideoModel to encode video and text inputs for contrastive learning', 'create a PeVideoEncoder that processes pixel values with patch embedding and transformer layers', 'run forward pass with return_loss to compute video-text contrastive loss', 'get text features from input_ids using the text model and contrastive head', 'get video features from pixel_values_videos using the video encoder and contrastive head', 'create a PeVideoVideoProcessor instance to preprocess video inputs for the PE-Video transformer model', 'sample evenly spaced frame indices from a video given its metadata and target frame count', 'preprocess a batch of variable-length videos and pad them into a single tensor with a padding mask', 'build a video processing pipeline that resamples frames with bilinear interpolation and returns padded pixel tensors', 'review the PeVideoVideoProcessor class that extends BaseVideoProcessor for variable-length video padding']
```

Usage

```
{'build_pe_video_model': 'build a PeVideoModel to encode video and text inputs for contrastive learning', 'create_video_encoder': 'create a PeVideoEncoder that processes pixel values with patch embedding and transformer layers', 'run_contrastive_loss': 'run forward pass with return_loss to compute video-text contrastive loss', 'get_text_features': 'get text features from input_ids using the text model and contrastive head', 'get_video_features': 'get video features from pixel_values_videos using the video encoder and contrastive head'}
```

## File: huggingface_transformers/src/transformers/models/pe_video/modular_pe_video.py

Prompts

```
['build a PeVideoModel to encode video and text inputs for contrastive learning', 'create a PeVideoEncoder that processes pixel values with patch embedding and transformer layers', 'run forward pass with return_loss to compute video-text contrastive loss', 'get text features from input_ids using the text model and contrastive head', 'get video features from pixel_values_videos using the video encoder and contrastive head', 'create a PeVideoVideoProcessor instance to preprocess video inputs for the PE-Video transformer model', 'sample evenly spaced frame indices from a video given its metadata and target frame count', 'preprocess a batch of variable-length videos and pad them into a single tensor with a padding mask', 'build a video processing pipeline that resamples frames with bilinear interpolation and returns padded pixel tensors', 'review the PeVideoVideoProcessor class that extends BaseVideoProcessor for variable-length video padding']
```

Usage

```
{'build_pe_video_model': 'build a PeVideoModel to encode video and text inputs for contrastive learning', 'create_video_encoder': 'create a PeVideoEncoder that processes pixel values with vision encoder and transformer layers', 'get_text_features': 'get text features from input_ids using the text model and contrastive head', 'get_video_features': 'get video features from pixel_values_videos using the video encoder and contrastive head', 'run_contrastive_loss': 'run forward pass with return_loss to compute video-text contrastive loss'}
```

## File: huggingface_transformers/src/transformers/models/pe_video/video_processing_pe_video.py

Prompts

```
['build a PeVideoModel to encode video and text inputs for contrastive learning', 'create a PeVideoEncoder that processes pixel values with patch embedding and transformer layers', 'run forward pass with return_loss to compute video-text contrastive loss', 'get text features from input_ids using the text model and contrastive head', 'get video features from pixel_values_videos using the video encoder and contrastive head', 'create a PeVideoVideoProcessor instance to preprocess video inputs for the PE-Video transformer model', 'sample evenly spaced frame indices from a video given its metadata and target frame count', 'preprocess a batch of variable-length videos and pad them into a single tensor with a padding mask', 'build a video processing pipeline that resamples frames with bilinear interpolation and returns padded pixel tensors', 'review the PeVideoVideoProcessor class that extends BaseVideoProcessor for variable-length video padding']
```

Usage

```
{'create_PeVideoVideoProcessor': 'create a PeVideoVideoProcessor instance to preprocess video inputs for the PE-Video transformer model', 'sample_frames_video': 'sample evenly spaced frame indices from a video given its metadata and target frame count', 'preprocess_videos_tensors': 'preprocess a batch of variable-length videos and pad them into a single tensor with a padding mask', 'build_video_processor_pipeline': 'build a video processing pipeline that resamples frames with bilinear interpolation and returns padded pixel tensors', 'review_PeVideoVideoProcessor': 'review the PeVideoVideoProcessor class that extends BaseVideoProcessor for variable-length video padding'}
```

