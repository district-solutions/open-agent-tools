# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/llava_next_video/test_modeling_llava_next_video.py

Prompts

```
['test the LlavaNextVideoForConditionalGenerationModelTest class that verifies model forward pass, config, and generation behavior', 'test the LlavaNextVideo model with different vision_feature_layer configurations including int, list, and nested list values', 'test that the model raises ValueError when image features and image tokens do not match in batch and multi-image cases', 'run the LlavaNextVideoForConditionalGenerationIntegrationTest with batched video and image inputs using 4-bit quantization', 'test training with gradient checkpointing for LlavaNextVideo model (currently xfail due to missing gradients)', 'test the LlavaNextVideoProcessor to count multimodal tokens for multiple image sizes', 'test that the LlavaNextVideoProcessor chat template is saved and loaded correctly', 'test the LlavaNextVideoProcessor image token filling with non-square images', 'review the LlavaNextVideoProcessorTest class and its test methods for processor validation', 'summarize the LlavaNextVideoProcessor processor dictionary configuration including chat template and patch size', 'build a LlavaNextVideoVideoProcessor with resize, center crop, and normalization settings', 'test the LlavaNextVideoVideoProcessor has do_resize, size, do_center_crop, and do_normalize attributes', 'test creating a LlavaNextVideoVideoProcessor from a config dict with override kwargs', 'create a LlavaNextVideoProcessingTester to prepare video inputs and processor configuration dicts', 'prepare batched video inputs with configurable frames, channels, and resolution for testing']
```

Usage

```
{'test_modeling_llava_next_video': 'test the LlavaNextVideoForConditionalGenerationModelTest class that verifies model forward pass, config, and generation behavior', 'test_vision_feature_layers': 'test the LlavaNextVideo model with different vision_feature_layer configurations including int, list, and nested list values', 'test_mismatching_num_image_tokens': 'test that the model raises ValueError when image features and image tokens do not match in batch and multi-image cases', 'run_integration_test_batched': 'run the LlavaNextVideoForConditionalGenerationIntegrationTest with batched video and image inputs using 4-bit quantization', 'test_training_gradient_checkpointing': 'test training with gradient checkpointing for LlavaNextVideo model (currently xfail due to missing gradients)'}
```

## File: huggingface_transformers/tests/models/llava_next_video/test_processing_llava_next_video.py

Prompts

```
['test the LlavaNextVideoForConditionalGenerationModelTest class that verifies model forward pass, config, and generation behavior', 'test the LlavaNextVideo model with different vision_feature_layer configurations including int, list, and nested list values', 'test that the model raises ValueError when image features and image tokens do not match in batch and multi-image cases', 'run the LlavaNextVideoForConditionalGenerationIntegrationTest with batched video and image inputs using 4-bit quantization', 'test training with gradient checkpointing for LlavaNextVideo model (currently xfail due to missing gradients)', 'test the LlavaNextVideoProcessor to count multimodal tokens for multiple image sizes', 'test that the LlavaNextVideoProcessor chat template is saved and loaded correctly', 'test the LlavaNextVideoProcessor image token filling with non-square images', 'review the LlavaNextVideoProcessorTest class and its test methods for processor validation', 'summarize the LlavaNextVideoProcessor processor dictionary configuration including chat template and patch size', 'build a LlavaNextVideoVideoProcessor with resize, center crop, and normalization settings', 'test the LlavaNextVideoVideoProcessor has do_resize, size, do_center_crop, and do_normalize attributes', 'test creating a LlavaNextVideoVideoProcessor from a config dict with override kwargs', 'create a LlavaNextVideoProcessingTester to prepare video inputs and processor configuration dicts', 'prepare batched video inputs with configurable frames, channels, and resolution for testing']
```

Usage

```
{'test_get_num_vision_tokens': 'test the LlavaNextVideoProcessor to count multimodal tokens for multiple image sizes', 'test_chat_template_is_saved': 'test that the LlavaNextVideoProcessor chat template is saved and loaded correctly', 'test_image_token_filling': 'test the LlavaNextVideoProcessor image token filling with non-square images', 'review_LlavaNextVideoProcessorTest': 'review the LlavaNextVideoProcessorTest class and its test methods for processor validation', 'summarize_prepare_processor_dict': 'summarize the LlavaNextVideoProcessor processor dictionary configuration including chat template and patch size'}
```

## File: huggingface_transformers/tests/models/llava_next_video/test_video_processing_llava_next_video.py

Prompts

```
['test the LlavaNextVideoForConditionalGenerationModelTest class that verifies model forward pass, config, and generation behavior', 'test the LlavaNextVideo model with different vision_feature_layer configurations including int, list, and nested list values', 'test that the model raises ValueError when image features and image tokens do not match in batch and multi-image cases', 'run the LlavaNextVideoForConditionalGenerationIntegrationTest with batched video and image inputs using 4-bit quantization', 'test training with gradient checkpointing for LlavaNextVideo model (currently xfail due to missing gradients)', 'test the LlavaNextVideoProcessor to count multimodal tokens for multiple image sizes', 'test that the LlavaNextVideoProcessor chat template is saved and loaded correctly', 'test the LlavaNextVideoProcessor image token filling with non-square images', 'review the LlavaNextVideoProcessorTest class and its test methods for processor validation', 'summarize the LlavaNextVideoProcessor processor dictionary configuration including chat template and patch size', 'build a LlavaNextVideoVideoProcessor with resize, center crop, and normalization settings', 'test the LlavaNextVideoVideoProcessor has do_resize, size, do_center_crop, and do_normalize attributes', 'test creating a LlavaNextVideoVideoProcessor from a config dict with override kwargs', 'create a LlavaNextVideoProcessingTester to prepare video inputs and processor configuration dicts', 'prepare batched video inputs with configurable frames, channels, and resolution for testing']
```

Usage

```
{'build_llava_next_video_processor': 'build a LlavaNextVideoVideoProcessor with resize, center crop, and normalization settings', 'test_video_processor_properties': 'test the LlavaNextVideoVideoProcessor has do_resize, size, do_center_crop, and do_normalize attributes', 'test_video_processor_from_dict': 'test creating a LlavaNextVideoVideoProcessor from a config dict with override kwargs', 'create_video_processing_tester': 'create a LlavaNextVideoProcessingTester to prepare video inputs and processor configuration dicts', 'prepare_video_inputs': 'prepare batched video inputs with configurable frames, channels, and resolution for testing'}
```

