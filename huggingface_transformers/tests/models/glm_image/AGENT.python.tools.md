# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/glm_image/test_modeling_glm_image.py

Prompts

```
['test the GlmImageModelTest class that validates GLM-Image model forward pass, training, and generation behavior', 'test the GlmImageConfig class configuration initialization and parameter validation', 'test the GlmImageVisionText2TextModelTester class for image-to-image generation input preparation', 'test the GlmImageIntegrationTest class for text-to-image generation with the zai-org/GLM-Image model', 'test the GlmImageProcessor class for preparing text-to-image and image-to-image inputs with chat templates', 'test the GlmImageProcessor by passing text and PIL images and verifying model input names match', 'test the processor apply_chat_template method with batch messages and verify tokenized output matches tokenizer', 'setup a GlmImageProcessor from the zai-org/GLM-Image model using AutoImageProcessor with custom patch size and pixel limits', 'prepare random 256x256 RGB PIL images with valid aspect ratio for GLM-Image processor testing', 'test that kwargs like padding truncation and max_length are correctly passed through apply_chat_template']
```

Usage

```
{'test_glm_image_model': 'test the GlmImageModelTest class that validates GLM-Image model forward pass, training, and generation behavior', 'test_glm_image_config': 'test the GlmImageConfig class configuration initialization and parameter validation', 'test_image_to_image_generation': 'test the GlmImageVisionText2TextModelTester class for image-to-image generation input preparation', 'test_text_to_image_generation': 'test the GlmImageIntegrationTest class for text-to-image generation with the zai-org/GLM-Image model', 'test_glm_image_processor': 'test the GlmImageProcessor class for preparing text-to-image and image-to-image inputs with chat templates'}
```

## File: huggingface_transformers/tests/models/glm_image/test_processor_glm_image.py

Prompts

```
['test the GlmImageModelTest class that validates GLM-Image model forward pass, training, and generation behavior', 'test the GlmImageConfig class configuration initialization and parameter validation', 'test the GlmImageVisionText2TextModelTester class for image-to-image generation input preparation', 'test the GlmImageIntegrationTest class for text-to-image generation with the zai-org/GLM-Image model', 'test the GlmImageProcessor class for preparing text-to-image and image-to-image inputs with chat templates', 'test the GlmImageProcessor by passing text and PIL images and verifying model input names match', 'test the processor apply_chat_template method with batch messages and verify tokenized output matches tokenizer', 'setup a GlmImageProcessor from the zai-org/GLM-Image model using AutoImageProcessor with custom patch size and pixel limits', 'prepare random 256x256 RGB PIL images with valid aspect ratio for GLM-Image processor testing', 'test that kwargs like padding truncation and max_length are correctly passed through apply_chat_template']
```

Usage

```
{'test_GlmImageProcessor_with_images': 'test the GlmImageProcessor by passing text and PIL images and verifying model input names match', 'test_apply_chat_template': 'test the processor apply_chat_template method with batch messages and verify tokenized output matches tokenizer', 'setup_GlmImageProcessor_from_pretrained': 'setup a GlmImageProcessor from the zai-org/GLM-Image model using AutoImageProcessor with custom patch size and pixel limits', 'prepare_image_inputs_for_GLM': 'prepare random 256x256 RGB PIL images with valid aspect ratio for GLM-Image processor testing', 'test_processor_kwargs_parsing': 'test that kwargs like padding truncation and max_length are correctly passed through apply_chat_template'}
```

