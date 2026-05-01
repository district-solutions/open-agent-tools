# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/aya_vision/test_modeling_aya_vision.py

Prompts

```
['run the AyaVisionModelTest suite to verify model configuration and common behavior', 'run the AyaVisionIntegrationTest suite to validate forward pass and generation outputs', 'create an AyaVisionConfig with custom text and vision config parameters for the model', 'test text generation with AyaVisionForConditionalGeneration using chat templates and image inputs', 'test batched multi-image generation with AyaVisionForConditionalGeneration across multiple inputs', 'test the AyaVisionProcessor class using the ProcessorTesterMixin and unittest framework', 'test the _get_num_multimodal_tokens method to verify image token and patch counts for multiple image sizes', 'test batched processing of interleaved images and text using apply_chat_template with torch tensors', 'configure an image processor with resize, rescale, normalize, and RGB conversion settings for AyaVision', 'load a pretrained tokenizer from the AyaVision model with left padding enabled']
```

Usage

```
{'test_aya_vision_model': 'run the AyaVisionModelTest suite to verify model configuration and common behavior', 'test_aya_vision_integration': 'run the AyaVisionIntegrationTest suite to validate forward pass and generation outputs', 'create_aya_vision_config': 'create an AyaVisionConfig with custom text and vision config parameters for the model', 'test_aya_vision_generation': 'test text generation with AyaVisionForConditionalGeneration using chat templates and image inputs', 'test_aya_vision_batched_multi_image': 'test batched multi-image generation with AyaVisionForConditionalGeneration across multiple inputs'}
```

## File: huggingface_transformers/tests/models/aya_vision/test_processing_aya_vision.py

Prompts

```
['run the AyaVisionModelTest suite to verify model configuration and common behavior', 'run the AyaVisionIntegrationTest suite to validate forward pass and generation outputs', 'create an AyaVisionConfig with custom text and vision config parameters for the model', 'test text generation with AyaVisionForConditionalGeneration using chat templates and image inputs', 'test batched multi-image generation with AyaVisionForConditionalGeneration across multiple inputs', 'test the AyaVisionProcessor class using the ProcessorTesterMixin and unittest framework', 'test the _get_num_multimodal_tokens method to verify image token and patch counts for multiple image sizes', 'test batched processing of interleaved images and text using apply_chat_template with torch tensors', 'configure an image processor with resize, rescale, normalize, and RGB conversion settings for AyaVision', 'load a pretrained tokenizer from the AyaVision model with left padding enabled']
```

Usage

```
{'test_aya_vision_processor': 'test the AyaVisionProcessor class using the ProcessorTesterMixin and unittest framework', 'test_get_num_vision_tokens': 'test the _get_num_multimodal_tokens method to verify image token and patch counts for multiple image sizes', 'test_process_interleaved_images_videos': 'test batched processing of interleaved images and text using apply_chat_template with torch tensors', 'setup_image_processor': 'configure an image processor with resize, rescale, normalize, and RGB conversion settings for AyaVision', 'setup_tokenizer': 'load a pretrained tokenizer from the AyaVision model with left padding enabled'}
```

