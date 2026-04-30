# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/llava_next_video/convert_llava_next_video_weights_to_hf.py

Prompts

```
['convert LLaVA-NeXT-Video checkpoint from original repository to HuggingFace format', 'run the convert_llava_next_video_weights_to_hf CLI with model_id, output path, and push_to_hub flags', 'load original safetensors checkpoint state dict from a model hub repository', 'convert original state dict keys to HuggingFace naming convention and cast to bfloat16', 'convert LLaVA-NeXT-Video model weights, resize token embeddings, and save or push to HuggingFace hub', 'run LLaVA-NeXT-Video inference on a video clip and an image using the conditional generation model', 'create image features from pixel values using the vision tower and multimodal projector', 'create video features from pixel value frames using the vision tower and spatial pooler', 'pack image features from multiple patches into a single tensor with proper grid reshaping', 'generate autoregressive text output from combined image, video, and text inputs with cached KV states', 'create a LLaVA-NeXT-Video model for conditional generation with image and video support', 'build a LlavaNextVideoConfig with vision and text encoder configurations for multimodal processing', 'run video feature extraction from pixel values using the vision tower and spatial pooler', 'process image features through the vision tower, projector, and spatial pooling for multimodal input', 'generate text responses from video and image inputs using the conditional generation forward pass']
```

Usage

```
{'convert_llava_next_video_weights_to_hf': 'convert LLaVA-NeXT-Video checkpoint from original repository to HuggingFace format', 'run_convert_cli': 'run the convert_llava_next_video_weights_to_hf CLI with model_id, output path, and push_to_hub flags', 'load_original_state_dict': 'load original safetensors checkpoint state dict from a model hub repository', 'convert_state_dict_to_hf': 'convert original state dict keys to HuggingFace naming convention and cast to bfloat16', 'convert_llava_to_hf': 'convert LLaVA-NeXT-Video model weights, resize token embeddings, and save or push to HuggingFace hub'}
```

## File: huggingface_transformers/src/transformers/models/llava_next_video/modeling_llava_next_video.py

Prompts

```
['convert LLaVA-NeXT-Video checkpoint from original repository to HuggingFace format', 'run the convert_llava_next_video_weights_to_hf CLI with model_id, output path, and push_to_hub flags', 'load original safetensors checkpoint state dict from a model hub repository', 'convert original state dict keys to HuggingFace naming convention and cast to bfloat16', 'convert LLaVA-NeXT-Video model weights, resize token embeddings, and save or push to HuggingFace hub', 'run LLaVA-NeXT-Video inference on a video clip and an image using the conditional generation model', 'create image features from pixel values using the vision tower and multimodal projector', 'create video features from pixel value frames using the vision tower and spatial pooler', 'pack image features from multiple patches into a single tensor with proper grid reshaping', 'generate autoregressive text output from combined image, video, and text inputs with cached KV states', 'create a LLaVA-NeXT-Video model for conditional generation with image and video support', 'build a LlavaNextVideoConfig with vision and text encoder configurations for multimodal processing', 'run video feature extraction from pixel values using the vision tower and spatial pooler', 'process image features through the vision tower, projector, and spatial pooling for multimodal input', 'generate text responses from video and image inputs using the conditional generation forward pass']
```

Usage

```
{'run_llava_next_video_inference': 'run LLaVA-NeXT-Video inference on a video clip and an image using the conditional generation model', 'create_image_features': 'create image features from pixel values using the vision tower and multimodal projector', 'create_video_features': 'create video features from pixel value frames using the vision tower and spatial pooler', 'pack_image_features': 'pack image features from multiple patches into a single tensor with proper grid reshaping', 'generate_text_from_multimodal_input': 'generate autoregressive text output from combined image, video, and text inputs with cached KV states'}
```

## File: huggingface_transformers/src/transformers/models/llava_next_video/modular_llava_next_video.py

Prompts

```
['convert LLaVA-NeXT-Video checkpoint from original repository to HuggingFace format', 'run the convert_llava_next_video_weights_to_hf CLI with model_id, output path, and push_to_hub flags', 'load original safetensors checkpoint state dict from a model hub repository', 'convert original state dict keys to HuggingFace naming convention and cast to bfloat16', 'convert LLaVA-NeXT-Video model weights, resize token embeddings, and save or push to HuggingFace hub', 'run LLaVA-NeXT-Video inference on a video clip and an image using the conditional generation model', 'create image features from pixel values using the vision tower and multimodal projector', 'create video features from pixel value frames using the vision tower and spatial pooler', 'pack image features from multiple patches into a single tensor with proper grid reshaping', 'generate autoregressive text output from combined image, video, and text inputs with cached KV states', 'create a LLaVA-NeXT-Video model for conditional generation with image and video support', 'build a LlavaNextVideoConfig with vision and text encoder configurations for multimodal processing', 'run video feature extraction from pixel values using the vision tower and spatial pooler', 'process image features through the vision tower, projector, and spatial pooling for multimodal input', 'generate text responses from video and image inputs using the conditional generation forward pass']
```

Usage

```
{'create_llava_next_video_model': 'create a LLaVA-NeXT-Video model for conditional generation with image and video support', 'build_multimodal_config': 'build a LlavaNextVideoConfig with vision and text encoder configurations for multimodal processing', 'run_video_feature_extraction': 'run video feature extraction from pixel values using the vision tower and spatial pooler', 'process_image_features': 'process image features through the vision tower, projector, and spatial pooling for multimodal input', 'generate_text_from_video': 'generate text responses from video and image inputs using the conditional generation forward pass'}
```

