# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glm_ocr/modeling_glm_ocr.py

Prompts

```
['run GlmOcrForConditionalGeneration to generate text from input images and text prompts', 'run GlmOcrModel forward pass to process multimodal inputs with images, videos, and text tokens', 'extract image features from pixel values using GlmOcrModel.get_image_features method', 'extract video features from pixel values using GlmOcrModel.get_video_features method', 'compute 3D multimodal RoPE position ids for vision and text tokens using GlmOcrModel.compute_3d_position_ids', 'create a GlmOcrConfig with custom vision and text settings for the GLM-OCR model', 'build a GlmOcrVisionModel that processes image hidden states with rotary position embeddings and patch merging', 'build a GlmOcrTextModel decoder with custom attention and RMS norm for language generation', 'create a GlmOcrForConditionalGeneration model that combines vision and text for OCR tasks', 'build a GlmOcrVisionAttention module with QKV projection, RMS norm, rotary embeddings, and flash attention support']
```

Usage

```
{'run_glm_ocr_conditional_generation': 'run GlmOcrForConditionalGeneration to generate text from input images and text prompts', 'run_glm_ocr_forward_pass': 'run GlmOcrModel forward pass to process multimodal inputs with images, videos, and text tokens', 'extract_image_features': 'extract image features from pixel values using GlmOcrModel.get_image_features method', 'extract_video_features': 'extract video features from pixel values using GlmOcrModel.get_video_features method', 'compute_3d_position_ids': 'compute 3D multimodal RoPE position ids for vision and text tokens using GlmOcrModel.compute_3d_position_ids'}
```

## File: huggingface_transformers/src/transformers/models/glm_ocr/modular_glm_ocr.py

Prompts

```
['run GlmOcrForConditionalGeneration to generate text from input images and text prompts', 'run GlmOcrModel forward pass to process multimodal inputs with images, videos, and text tokens', 'extract image features from pixel values using GlmOcrModel.get_image_features method', 'extract video features from pixel values using GlmOcrModel.get_video_features method', 'compute 3D multimodal RoPE position ids for vision and text tokens using GlmOcrModel.compute_3d_position_ids', 'create a GlmOcrConfig with custom vision and text settings for the GLM-OCR model', 'build a GlmOcrVisionModel that processes image hidden states with rotary position embeddings and patch merging', 'build a GlmOcrTextModel decoder with custom attention and RMS norm for language generation', 'create a GlmOcrForConditionalGeneration model that combines vision and text for OCR tasks', 'build a GlmOcrVisionAttention module with QKV projection, RMS norm, rotary embeddings, and flash attention support']
```

Usage

```
{'create_glm_ocr_config': 'create a GlmOcrConfig with custom vision and text settings for the GLM-OCR model', 'build_glm_ocr_vision_model': 'build a GlmOcrVisionModel that processes image hidden states with rotary position embeddings and patch merging', 'build_glm_ocr_text_model': 'build a GlmOcrTextModel decoder with custom attention and RMS norm for language generation', 'create_glm_ocr_conditional_model': 'create a GlmOcrForConditionalGeneration model that combines vision and text for OCR tasks', 'build_glm_ocr_vision_attention': 'build a GlmOcrVisionAttention module with QKV projection, RMS norm, rotary embeddings, and flash attention support'}
```

