# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/internvl/test_modeling_internvl.py

Prompts

```
['test the InternVLConfig class with the ConfigTester for common configuration tests', 'test the InternVLForConditionalGeneration model forward pass with pixel values and input ids', 'test the InternVLForConditionalGeneration model text generation with image and text prompts', 'test the InternVLForConditionalGeneration model batched generation with multiple images and prompts', 'test the InternVLForConditionalGeneration model video understanding with 4-bit quantization and video input', 'test the InternVLProcessorTest class with image, video, and tokenizer setup methods', 'test the _get_num_multimodal_tokens helper for computing image token counts from image sizes', 'test processing interleaved images and videos via apply_chat_template with batched inputs', 'test video frame sampling with configurable num_frames in apply_chat_template', 'test direct processor call with text and video frames returning correct pixel_values shape', 'test InternVLVideoProcessor from_dict method with size kwargs to verify correct configuration', 'create an InternVLVideoProcessingTester instance with custom batch size, frames, and resolution parameters', 'build a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'generate synthetic video inputs with configurable batch size, frames, channels, and resolution ranges', 'run the InternVLVideoProcessingTest suite to verify video processor initialization and from_dict behavior']
```

Usage

```
{'test_internvl_model_config': 'test the InternVLConfig class with the ConfigTester for common configuration tests', 'test_internvl_model_forward': 'test the InternVLForConditionalGeneration model forward pass with pixel values and input ids', 'test_internvl_model_generate': 'test the InternVLForConditionalGeneration model text generation with image and text prompts', 'test_internvl_model_batched_generate': 'test the InternVLForConditionalGeneration model batched generation with multiple images and prompts', 'test_internvl_model_video': 'test the InternVLForConditionalGeneration model video understanding with 4-bit quantization and video input'}
```

## File: huggingface_transformers/tests/models/internvl/test_processing_internvl.py

Prompts

```
['test the InternVLConfig class with the ConfigTester for common configuration tests', 'test the InternVLForConditionalGeneration model forward pass with pixel values and input ids', 'test the InternVLForConditionalGeneration model text generation with image and text prompts', 'test the InternVLForConditionalGeneration model batched generation with multiple images and prompts', 'test the InternVLForConditionalGeneration model video understanding with 4-bit quantization and video input', 'test the InternVLProcessorTest class with image, video, and tokenizer setup methods', 'test the _get_num_multimodal_tokens helper for computing image token counts from image sizes', 'test processing interleaved images and videos via apply_chat_template with batched inputs', 'test video frame sampling with configurable num_frames in apply_chat_template', 'test direct processor call with text and video frames returning correct pixel_values shape', 'test InternVLVideoProcessor from_dict method with size kwargs to verify correct configuration', 'create an InternVLVideoProcessingTester instance with custom batch size, frames, and resolution parameters', 'build a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'generate synthetic video inputs with configurable batch size, frames, channels, and resolution ranges', 'run the InternVLVideoProcessingTest suite to verify video processor initialization and from_dict behavior']
```

Usage

```
{'test_internvl_processor_setup': 'test the InternVLProcessorTest class with image, video, and tokenizer setup methods', 'test_internvl_get_num_vision_tokens': 'test the _get_num_multimodal_tokens helper for computing image token counts from image sizes', 'test_internvl_process_interleaved': 'test processing interleaved images and videos via apply_chat_template with batched inputs', 'test_internvl_video_frame_sampling': 'test video frame sampling with configurable num_frames in apply_chat_template', 'test_internvl_frames_binding': 'test direct processor call with text and video frames returning correct pixel_values shape'}
```

## File: huggingface_transformers/tests/models/internvl/test_video_processing_internvl.py

Prompts

```
['test the InternVLConfig class with the ConfigTester for common configuration tests', 'test the InternVLForConditionalGeneration model forward pass with pixel values and input ids', 'test the InternVLForConditionalGeneration model text generation with image and text prompts', 'test the InternVLForConditionalGeneration model batched generation with multiple images and prompts', 'test the InternVLForConditionalGeneration model video understanding with 4-bit quantization and video input', 'test the InternVLProcessorTest class with image, video, and tokenizer setup methods', 'test the _get_num_multimodal_tokens helper for computing image token counts from image sizes', 'test processing interleaved images and videos via apply_chat_template with batched inputs', 'test video frame sampling with configurable num_frames in apply_chat_template', 'test direct processor call with text and video frames returning correct pixel_values shape', 'test InternVLVideoProcessor from_dict method with size kwargs to verify correct configuration', 'create an InternVLVideoProcessingTester instance with custom batch size, frames, and resolution parameters', 'build a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'generate synthetic video inputs with configurable batch size, frames, channels, and resolution ranges', 'run the InternVLVideoProcessingTest suite to verify video processor initialization and from_dict behavior']
```

Usage

```
{'test_InternVLVideoProcessor_from_dict': 'test InternVLVideoProcessor from_dict method with size kwargs to verify correct configuration', 'create_InternVLVideoProcessingTester': 'create an InternVLVideoProcessingTester instance with custom batch size, frames, and resolution parameters', 'prepare_video_processor_dict': 'build a video processor configuration dictionary with resize, normalize, and RGB conversion settings', 'prepare_video_inputs': 'generate synthetic video inputs with configurable batch size, frames, channels, and resolution ranges', 'test_InternVLVideoProcessingTest': 'run the InternVLVideoProcessingTest suite to verify video processor initialization and from_dict behavior'}
```

