# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/qwen3_vl/modeling_qwen3_vl.py

Prompts

```
['create a Qwen3VLForConditionalGeneration model for multimodal image and video understanding', 'run inference with Qwen3VLForConditionalGeneration on images and text to generate descriptions', 'build a Qwen3VLVisionModel that processes image and video pixel values into visual embeddings', 'compute 3D multimodal RoPE position IDs for Qwen3VL text model with vision tokens', 'generate autoregressive text output from Qwen3VL causal language model with visual context', 'build a Qwen3-VL conditional generation model for vision-language tasks with image and video input support', 'create a Qwen3VL processor that tokenizes text with image and video placeholders and returns batch features', 'run a Qwen3-VL forward pass that processes text, images, and videos with deepstack visual embeddings', 'configure a Qwen3-VL model with vision and text sub-configs including rotary embeddings and positional encoding', 'generate text from a Qwen3-VL model using cached past key values and expanded visual inputs for beam search', 'process images, videos, and text input into model-ready BatchFeature with token IDs and pixel values', 'calculate frame timestamps from frame indices, video FPS, and temporal patch size for video processing', 'get the number of placeholder tokens needed for given image and video sizes', 'post-process and decode generated model outputs into readable text strings', 'create a Qwen3VLVideoProcessor instance for preprocessing video inputs for Qwen3-VL models', 'run smart_resize to compute optimal video dimensions respecting pixel limits and temporal factors', 'sample video frames uniformly from a video given metadata with a target frame count or fps', 'preprocess a batch of video tensors by resizing, patchifying, and producing pixel_values_videos with grid dimensions', 'build pixel_values_videos and video_grid_thw tensors ready for Qwen3-VL model inference']
```

Usage

```
{'create_qwen3vl_conditional_model': 'create a Qwen3VLForConditionalGeneration model for multimodal image and video understanding', 'run_qwen3vl_inference': 'run inference with Qwen3VLForConditionalGeneration on images and text to generate descriptions', 'build_qwen3vl_vision_encoder': 'build a Qwen3VLVisionModel that processes image and video pixel values into visual embeddings', 'compute_qwen3vl_position_embeddings': 'compute 3D multimodal RoPE position IDs for Qwen3VL text model with vision tokens', 'generate_qwen3vl_output': 'generate autoregressive text output from Qwen3VL causal language model with visual context'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_vl/modular_qwen3_vl.py

Prompts

```
['create a Qwen3VLForConditionalGeneration model for multimodal image and video understanding', 'run inference with Qwen3VLForConditionalGeneration on images and text to generate descriptions', 'build a Qwen3VLVisionModel that processes image and video pixel values into visual embeddings', 'compute 3D multimodal RoPE position IDs for Qwen3VL text model with vision tokens', 'generate autoregressive text output from Qwen3VL causal language model with visual context', 'build a Qwen3-VL conditional generation model for vision-language tasks with image and video input support', 'create a Qwen3VL processor that tokenizes text with image and video placeholders and returns batch features', 'run a Qwen3-VL forward pass that processes text, images, and videos with deepstack visual embeddings', 'configure a Qwen3-VL model with vision and text sub-configs including rotary embeddings and positional encoding', 'generate text from a Qwen3-VL model using cached past key values and expanded visual inputs for beam search', 'process images, videos, and text input into model-ready BatchFeature with token IDs and pixel values', 'calculate frame timestamps from frame indices, video FPS, and temporal patch size for video processing', 'get the number of placeholder tokens needed for given image and video sizes', 'post-process and decode generated model outputs into readable text strings', 'create a Qwen3VLVideoProcessor instance for preprocessing video inputs for Qwen3-VL models', 'run smart_resize to compute optimal video dimensions respecting pixel limits and temporal factors', 'sample video frames uniformly from a video given metadata with a target frame count or fps', 'preprocess a batch of video tensors by resizing, patchifying, and producing pixel_values_videos with grid dimensions', 'build pixel_values_videos and video_grid_thw tensors ready for Qwen3-VL model inference']
```

Usage

```
{'build_qwen3vl_conditional_generation_model': 'build a Qwen3-VL conditional generation model for vision-language tasks with image and video input support', 'create_qwen3vl_processor': 'create a Qwen3VL processor that tokenizes text with image and video placeholders and returns batch features', 'run_qwen3vl_forward_pass': 'run a Qwen3-VL forward pass that processes text, images, and videos with deepstack visual embeddings', 'configure_qwen3vl_model': 'configure a Qwen3-VL model with vision and text sub-configs including rotary embeddings and positional encoding', 'generate_qwen3vl_text': 'generate text from a Qwen3-VL model using cached past key values and expanded visual inputs for beam search'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_vl/processing_qwen3_vl.py

Prompts

```
['create a Qwen3VLForConditionalGeneration model for multimodal image and video understanding', 'run inference with Qwen3VLForConditionalGeneration on images and text to generate descriptions', 'build a Qwen3VLVisionModel that processes image and video pixel values into visual embeddings', 'compute 3D multimodal RoPE position IDs for Qwen3VL text model with vision tokens', 'generate autoregressive text output from Qwen3VL causal language model with visual context', 'build a Qwen3-VL conditional generation model for vision-language tasks with image and video input support', 'create a Qwen3VL processor that tokenizes text with image and video placeholders and returns batch features', 'run a Qwen3-VL forward pass that processes text, images, and videos with deepstack visual embeddings', 'configure a Qwen3-VL model with vision and text sub-configs including rotary embeddings and positional encoding', 'generate text from a Qwen3-VL model using cached past key values and expanded visual inputs for beam search', 'process images, videos, and text input into model-ready BatchFeature with token IDs and pixel values', 'calculate frame timestamps from frame indices, video FPS, and temporal patch size for video processing', 'get the number of placeholder tokens needed for given image and video sizes', 'post-process and decode generated model outputs into readable text strings', 'create a Qwen3VLVideoProcessor instance for preprocessing video inputs for Qwen3-VL models', 'run smart_resize to compute optimal video dimensions respecting pixel limits and temporal factors', 'sample video frames uniformly from a video given metadata with a target frame count or fps', 'preprocess a batch of video tensors by resizing, patchifying, and producing pixel_values_videos with grid dimensions', 'build pixel_values_videos and video_grid_thw tensors ready for Qwen3-VL model inference']
```

Usage

```
{'create_qwen3vl_processor': 'create a Qwen3VLProcessor instance with image_processor, tokenizer, and optional video_processor', 'process_multimodal_input': 'process images, videos, and text input into model-ready BatchFeature with token IDs and pixel values', 'calculate_video_timestamps': 'calculate frame timestamps from frame indices, video FPS, and temporal patch size for video processing', 'get_multimodal_token_count': 'get the number of placeholder tokens needed for given image and video sizes', 'post_process_generated_text': 'post-process and decode generated model outputs into readable text strings'}
```

## File: huggingface_transformers/src/transformers/models/qwen3_vl/video_processing_qwen3_vl.py

Prompts

```
['create a Qwen3VLForConditionalGeneration model for multimodal image and video understanding', 'run inference with Qwen3VLForConditionalGeneration on images and text to generate descriptions', 'build a Qwen3VLVisionModel that processes image and video pixel values into visual embeddings', 'compute 3D multimodal RoPE position IDs for Qwen3VL text model with vision tokens', 'generate autoregressive text output from Qwen3VL causal language model with visual context', 'build a Qwen3-VL conditional generation model for vision-language tasks with image and video input support', 'create a Qwen3VL processor that tokenizes text with image and video placeholders and returns batch features', 'run a Qwen3-VL forward pass that processes text, images, and videos with deepstack visual embeddings', 'configure a Qwen3-VL model with vision and text sub-configs including rotary embeddings and positional encoding', 'generate text from a Qwen3-VL model using cached past key values and expanded visual inputs for beam search', 'process images, videos, and text input into model-ready BatchFeature with token IDs and pixel values', 'calculate frame timestamps from frame indices, video FPS, and temporal patch size for video processing', 'get the number of placeholder tokens needed for given image and video sizes', 'post-process and decode generated model outputs into readable text strings', 'create a Qwen3VLVideoProcessor instance for preprocessing video inputs for Qwen3-VL models', 'run smart_resize to compute optimal video dimensions respecting pixel limits and temporal factors', 'sample video frames uniformly from a video given metadata with a target frame count or fps', 'preprocess a batch of video tensors by resizing, patchifying, and producing pixel_values_videos with grid dimensions', 'build pixel_values_videos and video_grid_thw tensors ready for Qwen3-VL model inference']
```

Usage

```
{'create_video_processor': 'create a Qwen3VLVideoProcessor instance for preprocessing video inputs for Qwen3-VL models', 'run_smart_resize': 'run smart_resize to compute optimal video dimensions respecting pixel limits and temporal factors', 'sample_video_frames': 'sample video frames uniformly from a video given metadata with a target frame count or fps', 'preprocess_videos': 'preprocess a batch of video tensors by resizing, patchifying, and producing pixel_values_videos with grid dimensions', 'build_video_input_tensors': 'build pixel_values_videos and video_grid_thw tensors ready for Qwen3-VL model inference'}
```

