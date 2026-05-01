# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/smolvlm/test_image_processing_smolvlm.py

Prompts

```
['test the SmolVLMImageProcessor by encoding numpy array images and verifying output tensor shapes', 'test the SmolVLMImageProcessor by encoding PIL images and verifying output tensor shapes match expected dimensions', 'test the SmolVLMImageProcessor by encoding PyTorch tensor images and verifying batched output shapes', 'test that all SmolVLM image processing backends produce equivalent pixel values and attention masks', 'test the get_number_of_image_patches method to verify patch counts for different image sizes and splitting settings', 'test the SmolVLMModel class with config, embedding resize, and forward pass validation', 'test the SmolVLMForConditionalGeneration class with generation, pipeline, and model mixin tests', 'create a model tester with vision and text configs for SmolVLM unit testing', 'test SmolVLM integration by generating text from image and video inputs with the pretrained model', 'test exporting SmolVLM vision encoder, connector, and text decoder to ExecuTorch ExportedProgram', 'test the SmolVLM processor handles interleaved images and text prompts without image splitting', 'test the SmolVLM processor handles interleaved images and text prompts with image splitting enabled', 'test the SmolVLM processor applies chat template with mixed text and image message content', 'test the SmolVLM processor raises errors for mismatched image and text inputs', 'test the SmolVLM processor works correctly with text-only input without images', 'test SmolVLMVideoProcessor creation from a config dictionary with optional kwargs overrides', 'test SmolVLMVideoProcessor frame sampling behavior with and without video metadata', 'create a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'prepare synthetic video inputs with configurable batch size, frames, and resolution for testing', 'review the SmolVLMVideoProcessingTester class that configures video processing test parameters and expected output shapes']
```

Usage

```
{'test_smolvlm_image_processor_with_numpy': 'test the SmolVLMImageProcessor by encoding numpy array images and verifying output tensor shapes', 'test_smolvlm_image_processor_with_pil': 'test the SmolVLMImageProcessor by encoding PIL images and verifying output tensor shapes match expected dimensions', 'test_smolvlm_image_processor_with_pytorch': 'test the SmolVLMImageProcessor by encoding PyTorch tensor images and verifying batched output shapes', 'test_smolvlm_backend_equivalence': 'test that all SmolVLM image processing backends produce equivalent pixel values and attention masks', 'test_smolvlm_get_number_of_image_patches': 'test the get_number_of_image_patches method to verify patch counts for different image sizes and splitting settings'}
```

## File: huggingface_transformers/tests/models/smolvlm/test_modeling_smolvlm.py

Prompts

```
['test the SmolVLMImageProcessor by encoding numpy array images and verifying output tensor shapes', 'test the SmolVLMImageProcessor by encoding PIL images and verifying output tensor shapes match expected dimensions', 'test the SmolVLMImageProcessor by encoding PyTorch tensor images and verifying batched output shapes', 'test that all SmolVLM image processing backends produce equivalent pixel values and attention masks', 'test the get_number_of_image_patches method to verify patch counts for different image sizes and splitting settings', 'test the SmolVLMModel class with config, embedding resize, and forward pass validation', 'test the SmolVLMForConditionalGeneration class with generation, pipeline, and model mixin tests', 'create a model tester with vision and text configs for SmolVLM unit testing', 'test SmolVLM integration by generating text from image and video inputs with the pretrained model', 'test exporting SmolVLM vision encoder, connector, and text decoder to ExecuTorch ExportedProgram', 'test the SmolVLM processor handles interleaved images and text prompts without image splitting', 'test the SmolVLM processor handles interleaved images and text prompts with image splitting enabled', 'test the SmolVLM processor applies chat template with mixed text and image message content', 'test the SmolVLM processor raises errors for mismatched image and text inputs', 'test the SmolVLM processor works correctly with text-only input without images', 'test SmolVLMVideoProcessor creation from a config dictionary with optional kwargs overrides', 'test SmolVLMVideoProcessor frame sampling behavior with and without video metadata', 'create a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'prepare synthetic video inputs with configurable batch size, frames, and resolution for testing', 'review the SmolVLMVideoProcessingTester class that configures video processing test parameters and expected output shapes']
```

Usage

```
{'test_SmolVLMModel': 'test the SmolVLMModel class with config, embedding resize, and forward pass validation', 'test_SmolVLMForConditionalGeneration': 'test the SmolVLMForConditionalGeneration class with generation, pipeline, and model mixin tests', 'create_SmolVLMVisionText2TextModelTester': 'create a model tester with vision and text configs for SmolVLM unit testing', 'test_SmolVLMIntegration': 'test SmolVLM integration by generating text from image and video inputs with the pretrained model', 'test_SmolVLMExport': 'test exporting SmolVLM vision encoder, connector, and text decoder to ExecuTorch ExportedProgram'}
```

## File: huggingface_transformers/tests/models/smolvlm/test_processing_smolvlm.py

Prompts

```
['test the SmolVLMImageProcessor by encoding numpy array images and verifying output tensor shapes', 'test the SmolVLMImageProcessor by encoding PIL images and verifying output tensor shapes match expected dimensions', 'test the SmolVLMImageProcessor by encoding PyTorch tensor images and verifying batched output shapes', 'test that all SmolVLM image processing backends produce equivalent pixel values and attention masks', 'test the get_number_of_image_patches method to verify patch counts for different image sizes and splitting settings', 'test the SmolVLMModel class with config, embedding resize, and forward pass validation', 'test the SmolVLMForConditionalGeneration class with generation, pipeline, and model mixin tests', 'create a model tester with vision and text configs for SmolVLM unit testing', 'test SmolVLM integration by generating text from image and video inputs with the pretrained model', 'test exporting SmolVLM vision encoder, connector, and text decoder to ExecuTorch ExportedProgram', 'test the SmolVLM processor handles interleaved images and text prompts without image splitting', 'test the SmolVLM processor handles interleaved images and text prompts with image splitting enabled', 'test the SmolVLM processor applies chat template with mixed text and image message content', 'test the SmolVLM processor raises errors for mismatched image and text inputs', 'test the SmolVLM processor works correctly with text-only input without images', 'test SmolVLMVideoProcessor creation from a config dictionary with optional kwargs overrides', 'test SmolVLMVideoProcessor frame sampling behavior with and without video metadata', 'create a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'prepare synthetic video inputs with configurable batch size, frames, and resolution for testing', 'review the SmolVLMVideoProcessingTester class that configures video processing test parameters and expected output shapes']
```

Usage

```
{'test_process_interleaved_images_prompts_no_image_splitting': 'test the SmolVLM processor handles interleaved images and text prompts without image splitting', 'test_process_interleaved_images_prompts_image_splitting': 'test the SmolVLM processor handles interleaved images and text prompts with image splitting enabled', 'test_apply_chat_template': 'test the SmolVLM processor applies chat template with mixed text and image message content', 'test_process_interleaved_images_prompts_image_error': 'test the SmolVLM processor raises errors for mismatched image and text inputs', 'test_text_only_inference': 'test the SmolVLM processor works correctly with text-only input without images'}
```

## File: huggingface_transformers/tests/models/smolvlm/test_video_processing_smolvlm.py

Prompts

```
['test the SmolVLMImageProcessor by encoding numpy array images and verifying output tensor shapes', 'test the SmolVLMImageProcessor by encoding PIL images and verifying output tensor shapes match expected dimensions', 'test the SmolVLMImageProcessor by encoding PyTorch tensor images and verifying batched output shapes', 'test that all SmolVLM image processing backends produce equivalent pixel values and attention masks', 'test the get_number_of_image_patches method to verify patch counts for different image sizes and splitting settings', 'test the SmolVLMModel class with config, embedding resize, and forward pass validation', 'test the SmolVLMForConditionalGeneration class with generation, pipeline, and model mixin tests', 'create a model tester with vision and text configs for SmolVLM unit testing', 'test SmolVLM integration by generating text from image and video inputs with the pretrained model', 'test exporting SmolVLM vision encoder, connector, and text decoder to ExecuTorch ExportedProgram', 'test the SmolVLM processor handles interleaved images and text prompts without image splitting', 'test the SmolVLM processor handles interleaved images and text prompts with image splitting enabled', 'test the SmolVLM processor applies chat template with mixed text and image message content', 'test the SmolVLM processor raises errors for mismatched image and text inputs', 'test the SmolVLM processor works correctly with text-only input without images', 'test SmolVLMVideoProcessor creation from a config dictionary with optional kwargs overrides', 'test SmolVLMVideoProcessor frame sampling behavior with and without video metadata', 'create a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'prepare synthetic video inputs with configurable batch size, frames, and resolution for testing', 'review the SmolVLMVideoProcessingTester class that configures video processing test parameters and expected output shapes']
```

Usage

```
{'test_smolvlm_video_processor_from_dict': 'test SmolVLMVideoProcessor creation from a config dictionary with optional kwargs overrides', 'test_smolvlm_video_frame_sampling': 'test SmolVLMVideoProcessor frame sampling behavior with and without video metadata', 'create_video_processor_config': 'create a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'prepare_smolvlm_video_inputs': 'prepare synthetic video inputs with configurable batch size, frames, and resolution for testing', 'review_smolvlm_video_processing_tester': 'review the SmolVLMVideoProcessingTester class that configures video processing test parameters and expected output shapes'}
```

