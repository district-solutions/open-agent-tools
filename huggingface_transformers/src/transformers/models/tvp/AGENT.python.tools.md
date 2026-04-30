# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/tvp/image_processing_pil_tvp.py

Prompts

```
['build a TvpImageProcessorPil instance to preprocess video frames with resize, crop, normalize, pad, and channel flip', 'run the TvpImageProcessorPil preprocess method on video frames to produce batched pixel values', 'resize a numpy image to longest edge using aspect ratio preservation for TVP preprocessing', 'pad a numpy image to a target size with configurable mode and constant fill values', 'flip channel order from RGB to BGR on a numpy image array with channel dimension first', 'preprocess video frames with TvpImageProcessor using resize, center crop, rescale, pad, and normalize', 'resize an image tensor to a specified size while maintaining aspect ratio using longest edge', 'flip the channel order of video frames from RGB to BGR format', 'create TvpImageProcessorKwargs with custom do_flip_channel_order, constant_values, and pad_mode settings', 'create a TvpForVideoGrounding model with text and video inputs to predict temporal video grounding logits', 'run TvpModel forward pass with input_ids and pixel_values to get pooled hidden states and attention outputs', 'compute IoU, distance, and duration losses for video grounding predictions using TvpLoss criterion', 'build a TvpEncoder with stacked TvpEncodeLayers for self-attention over text and visual embeddings', 'review TvpVisualInputEmbedding with 2D positional embeddings and temporal mean pooling for video frame processing', 'create a TvpProcessor instance with an image processor and tokenizer for video-text processing', 'initialize TvpProcessorKwargs with text_kwargs defaults for truncation, padding, and token type ids', 'post-process video grounding logits and video duration to compute start and end timestamps', 'build a video grounding pipeline using TvpProcessor to preprocess inputs and post-process model outputs', 'test the TvpProcessor.post_process_video_grounding method with sample logits and video duration']
```

Usage

```
{'build_tvp_image_processor': 'build a TvpImageProcessorPil instance to preprocess video frames with resize, crop, normalize, pad, and channel flip', 'run_tvp_preprocess': 'run the TvpImageProcessorPil preprocess method on video frames to produce batched pixel values', 'resize_tvp_image': 'resize a numpy image to longest edge using aspect ratio preservation for TVP preprocessing', 'pad_tvp_image': 'pad a numpy image to a target size with configurable mode and constant fill values', 'flip_tvp_channels': 'flip channel order from RGB to BGR on a numpy image array with channel dimension first'}
```

## File: huggingface_transformers/src/transformers/models/tvp/image_processing_tvp.py

Prompts

```
['build a TvpImageProcessorPil instance to preprocess video frames with resize, crop, normalize, pad, and channel flip', 'run the TvpImageProcessorPil preprocess method on video frames to produce batched pixel values', 'resize a numpy image to longest edge using aspect ratio preservation for TVP preprocessing', 'pad a numpy image to a target size with configurable mode and constant fill values', 'flip channel order from RGB to BGR on a numpy image array with channel dimension first', 'preprocess video frames with TvpImageProcessor using resize, center crop, rescale, pad, and normalize', 'resize an image tensor to a specified size while maintaining aspect ratio using longest edge', 'flip the channel order of video frames from RGB to BGR format', 'create TvpImageProcessorKwargs with custom do_flip_channel_order, constant_values, and pad_mode settings', 'create a TvpForVideoGrounding model with text and video inputs to predict temporal video grounding logits', 'run TvpModel forward pass with input_ids and pixel_values to get pooled hidden states and attention outputs', 'compute IoU, distance, and duration losses for video grounding predictions using TvpLoss criterion', 'build a TvpEncoder with stacked TvpEncodeLayers for self-attention over text and visual embeddings', 'review TvpVisualInputEmbedding with 2D positional embeddings and temporal mean pooling for video frame processing', 'create a TvpProcessor instance with an image processor and tokenizer for video-text processing', 'initialize TvpProcessorKwargs with text_kwargs defaults for truncation, padding, and token type ids', 'post-process video grounding logits and video duration to compute start and end timestamps', 'build a video grounding pipeline using TvpProcessor to preprocess inputs and post-process model outputs', 'test the TvpProcessor.post_process_video_grounding method with sample logits and video duration']
```

Usage

```
{'build_tvp_image_processor': 'build a TvpImageProcessor instance to preprocess video frames for the TVP model', 'preprocess_videos_tvp': 'preprocess video frames with TvpImageProcessor using resize, center crop, rescale, pad, and normalize', 'resize_image_tvp': 'resize an image tensor to a specified size while maintaining aspect ratio using longest edge', 'flip_channel_order_rgb_to_bgr': 'flip the channel order of video frames from RGB to BGR format', 'create_tvp_image_processor_kwargs': 'create TvpImageProcessorKwargs with custom do_flip_channel_order, constant_values, and pad_mode settings'}
```

## File: huggingface_transformers/src/transformers/models/tvp/modeling_tvp.py

Prompts

```
['build a TvpImageProcessorPil instance to preprocess video frames with resize, crop, normalize, pad, and channel flip', 'run the TvpImageProcessorPil preprocess method on video frames to produce batched pixel values', 'resize a numpy image to longest edge using aspect ratio preservation for TVP preprocessing', 'pad a numpy image to a target size with configurable mode and constant fill values', 'flip channel order from RGB to BGR on a numpy image array with channel dimension first', 'preprocess video frames with TvpImageProcessor using resize, center crop, rescale, pad, and normalize', 'resize an image tensor to a specified size while maintaining aspect ratio using longest edge', 'flip the channel order of video frames from RGB to BGR format', 'create TvpImageProcessorKwargs with custom do_flip_channel_order, constant_values, and pad_mode settings', 'create a TvpForVideoGrounding model with text and video inputs to predict temporal video grounding logits', 'run TvpModel forward pass with input_ids and pixel_values to get pooled hidden states and attention outputs', 'compute IoU, distance, and duration losses for video grounding predictions using TvpLoss criterion', 'build a TvpEncoder with stacked TvpEncodeLayers for self-attention over text and visual embeddings', 'review TvpVisualInputEmbedding with 2D positional embeddings and temporal mean pooling for video frame processing', 'create a TvpProcessor instance with an image processor and tokenizer for video-text processing', 'initialize TvpProcessorKwargs with text_kwargs defaults for truncation, padding, and token type ids', 'post-process video grounding logits and video duration to compute start and end timestamps', 'build a video grounding pipeline using TvpProcessor to preprocess inputs and post-process model outputs', 'test the TvpProcessor.post_process_video_grounding method with sample logits and video duration']
```

Usage

```
{'create_tvp_for_video_grounding': 'create a TvpForVideoGrounding model with text and video inputs to predict temporal video grounding logits', 'run_tvp_model_forward': 'run TvpModel forward pass with input_ids and pixel_values to get pooled hidden states and attention outputs', 'compute_tvp_loss': 'compute IoU, distance, and duration losses for video grounding predictions using TvpLoss criterion', 'build_tvp_encoder': 'build a TvpEncoder with stacked TvpEncodeLayers for self-attention over text and visual embeddings', 'review_tvp_visual_input_embedding': 'review TvpVisualInputEmbedding with 2D positional embeddings and temporal mean pooling for video frame processing'}
```

## File: huggingface_transformers/src/transformers/models/tvp/processing_tvp.py

Prompts

```
['build a TvpImageProcessorPil instance to preprocess video frames with resize, crop, normalize, pad, and channel flip', 'run the TvpImageProcessorPil preprocess method on video frames to produce batched pixel values', 'resize a numpy image to longest edge using aspect ratio preservation for TVP preprocessing', 'pad a numpy image to a target size with configurable mode and constant fill values', 'flip channel order from RGB to BGR on a numpy image array with channel dimension first', 'preprocess video frames with TvpImageProcessor using resize, center crop, rescale, pad, and normalize', 'resize an image tensor to a specified size while maintaining aspect ratio using longest edge', 'flip the channel order of video frames from RGB to BGR format', 'create TvpImageProcessorKwargs with custom do_flip_channel_order, constant_values, and pad_mode settings', 'create a TvpForVideoGrounding model with text and video inputs to predict temporal video grounding logits', 'run TvpModel forward pass with input_ids and pixel_values to get pooled hidden states and attention outputs', 'compute IoU, distance, and duration losses for video grounding predictions using TvpLoss criterion', 'build a TvpEncoder with stacked TvpEncodeLayers for self-attention over text and visual embeddings', 'review TvpVisualInputEmbedding with 2D positional embeddings and temporal mean pooling for video frame processing', 'create a TvpProcessor instance with an image processor and tokenizer for video-text processing', 'initialize TvpProcessorKwargs with text_kwargs defaults for truncation, padding, and token type ids', 'post-process video grounding logits and video duration to compute start and end timestamps', 'build a video grounding pipeline using TvpProcessor to preprocess inputs and post-process model outputs', 'test the TvpProcessor.post_process_video_grounding method with sample logits and video duration']
```

Usage

```
{'create_tvp_processor': 'create a TvpProcessor instance with an image processor and tokenizer for video-text processing', 'init_tvp_processor_kwargs': 'initialize TvpProcessorKwargs with text_kwargs defaults for truncation, padding, and token type ids', 'post_process_video_grounding': 'post-process video grounding logits and video duration to compute start and end timestamps', 'build_tvp_processor_pipeline': 'build a video grounding pipeline using TvpProcessor to preprocess inputs and post-process model outputs', 'test_tvp_processor_post_process': 'test the TvpProcessor.post_process_video_grounding method with sample logits and video duration'}
```

