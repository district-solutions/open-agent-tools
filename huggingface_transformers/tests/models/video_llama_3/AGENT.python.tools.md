# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/video_llama_3/test_image_processing_video_llama_3.py

Prompts

```
['run the VideoLlama3ImageProcessingTest suite to verify image processor behavior with PIL, numpy, and PyTorch inputs', 'test the smart_resize function to compute the best resolution for given dimensions and a factor', 'test that the VideoLlama3 image processor exposes do_normalize, image_mean, image_std, do_resize, and patch_size properties', 'test the image processor with nested list inputs to verify consistent pixel values across input formats', 'test the get_number_of_image_patches method to calculate patch counts for given height, width, and patch_size', 'test the VideoLlama3VisionModelTest class for vision encoder unit tests', 'test the VideoLlama3ModelTest class for conditional generation model unit tests', 'test the VideoLlama3IntegrationTest class for slow integration tests with the real model', 'create a VideoLlama3VisionModelTester to generate config and pixel value inputs for vision model tests', 'create a VideoLlama3VisionText2TextModelTester to generate config and multimodal inputs for text-to-text model tests', 'test the VideoLlama3ProcessorTest class to verify processor functionality for image and video inputs', 'test the processor _get_num_multimodal_tokens helper to verify image token and patch counts', 'test video frame sampling with num_frames and fps arguments in the chat template', 'test that max_pixels kwargs correctly override custom image processor settings', 'test that special multimodal vision tokens are not truncated when truncation is enabled', 'test the VideoLlama3VideoProcessor class initialization and property checks', 'test loading a VideoLlama3VideoProcessor from a configuration dictionary with kwargs override', 'test serializing a VideoLlama3VideoProcessor configuration to a JSON string', 'test processing video inputs as PIL images, numpy arrays, and pytorch tensors with batched and unbatched modes', 'test nested list video inputs and frame sampling with do_sample_frames and fps parameters']
```

Usage

```
{'test_video_llama3_image_processing': 'run the VideoLlama3ImageProcessingTest suite to verify image processor behavior with PIL, numpy, and PyTorch inputs', 'test_smart_resize': 'test the smart_resize function to compute the best resolution for given dimensions and a factor', 'test_image_processor_properties': 'test that the VideoLlama3 image processor exposes do_normalize, image_mean, image_std, do_resize, and patch_size properties', 'test_nested_input_processing': 'test the image processor with nested list inputs to verify consistent pixel values across input formats', 'test_get_number_of_image_patches': 'test the get_number_of_image_patches method to calculate patch counts for given height, width, and patch_size'}
```

## File: huggingface_transformers/tests/models/video_llama_3/test_modeling_video_llama_3.py

Prompts

```
['run the VideoLlama3ImageProcessingTest suite to verify image processor behavior with PIL, numpy, and PyTorch inputs', 'test the smart_resize function to compute the best resolution for given dimensions and a factor', 'test that the VideoLlama3 image processor exposes do_normalize, image_mean, image_std, do_resize, and patch_size properties', 'test the image processor with nested list inputs to verify consistent pixel values across input formats', 'test the get_number_of_image_patches method to calculate patch counts for given height, width, and patch_size', 'test the VideoLlama3VisionModelTest class for vision encoder unit tests', 'test the VideoLlama3ModelTest class for conditional generation model unit tests', 'test the VideoLlama3IntegrationTest class for slow integration tests with the real model', 'create a VideoLlama3VisionModelTester to generate config and pixel value inputs for vision model tests', 'create a VideoLlama3VisionText2TextModelTester to generate config and multimodal inputs for text-to-text model tests', 'test the VideoLlama3ProcessorTest class to verify processor functionality for image and video inputs', 'test the processor _get_num_multimodal_tokens helper to verify image token and patch counts', 'test video frame sampling with num_frames and fps arguments in the chat template', 'test that max_pixels kwargs correctly override custom image processor settings', 'test that special multimodal vision tokens are not truncated when truncation is enabled', 'test the VideoLlama3VideoProcessor class initialization and property checks', 'test loading a VideoLlama3VideoProcessor from a configuration dictionary with kwargs override', 'test serializing a VideoLlama3VideoProcessor configuration to a JSON string', 'test processing video inputs as PIL images, numpy arrays, and pytorch tensors with batched and unbatched modes', 'test nested list video inputs and frame sampling with do_sample_frames and fps parameters']
```

Usage

```
{'test_VideoLlama3VisionModelTest': 'test the VideoLlama3VisionModelTest class for vision encoder unit tests', 'test_VideoLlama3ModelTest': 'test the VideoLlama3ModelTest class for conditional generation model unit tests', 'test_VideoLlama3IntegrationTest': 'test the VideoLlama3IntegrationTest class for slow integration tests with the real model', 'create_VideoLlama3VisionModelTester': 'create a VideoLlama3VisionModelTester to generate config and pixel value inputs for vision model tests', 'create_VideoLlama3VisionText2TextModelTester': 'create a VideoLlama3VisionText2TextModelTester to generate config and multimodal inputs for text-to-text model tests'}
```

## File: huggingface_transformers/tests/models/video_llama_3/test_processing_video_llama_3.py

Prompts

```
['run the VideoLlama3ImageProcessingTest suite to verify image processor behavior with PIL, numpy, and PyTorch inputs', 'test the smart_resize function to compute the best resolution for given dimensions and a factor', 'test that the VideoLlama3 image processor exposes do_normalize, image_mean, image_std, do_resize, and patch_size properties', 'test the image processor with nested list inputs to verify consistent pixel values across input formats', 'test the get_number_of_image_patches method to calculate patch counts for given height, width, and patch_size', 'test the VideoLlama3VisionModelTest class for vision encoder unit tests', 'test the VideoLlama3ModelTest class for conditional generation model unit tests', 'test the VideoLlama3IntegrationTest class for slow integration tests with the real model', 'create a VideoLlama3VisionModelTester to generate config and pixel value inputs for vision model tests', 'create a VideoLlama3VisionText2TextModelTester to generate config and multimodal inputs for text-to-text model tests', 'test the VideoLlama3ProcessorTest class to verify processor functionality for image and video inputs', 'test the processor _get_num_multimodal_tokens helper to verify image token and patch counts', 'test video frame sampling with num_frames and fps arguments in the chat template', 'test that max_pixels kwargs correctly override custom image processor settings', 'test that special multimodal vision tokens are not truncated when truncation is enabled', 'test the VideoLlama3VideoProcessor class initialization and property checks', 'test loading a VideoLlama3VideoProcessor from a configuration dictionary with kwargs override', 'test serializing a VideoLlama3VideoProcessor configuration to a JSON string', 'test processing video inputs as PIL images, numpy arrays, and pytorch tensors with batched and unbatched modes', 'test nested list video inputs and frame sampling with do_sample_frames and fps parameters']
```

Usage

```
{'test_VideoLlama3ProcessorTest': 'test the VideoLlama3ProcessorTest class to verify processor functionality for image and video inputs', 'test_get_num_vision_tokens': 'test the processor _get_num_multimodal_tokens helper to verify image token and patch counts', 'test_apply_chat_template_video_frame_sampling': 'test video frame sampling with num_frames and fps arguments in the chat template', 'test_kwargs_overrides_custom_image_processor_kwargs': 'test that max_pixels kwargs correctly override custom image processor settings', 'test_special_mm_token_truncation': 'test that special multimodal vision tokens are not truncated when truncation is enabled'}
```

## File: huggingface_transformers/tests/models/video_llama_3/test_video_processing_video_llama_3.py

Prompts

```
['run the VideoLlama3ImageProcessingTest suite to verify image processor behavior with PIL, numpy, and PyTorch inputs', 'test the smart_resize function to compute the best resolution for given dimensions and a factor', 'test that the VideoLlama3 image processor exposes do_normalize, image_mean, image_std, do_resize, and patch_size properties', 'test the image processor with nested list inputs to verify consistent pixel values across input formats', 'test the get_number_of_image_patches method to calculate patch counts for given height, width, and patch_size', 'test the VideoLlama3VisionModelTest class for vision encoder unit tests', 'test the VideoLlama3ModelTest class for conditional generation model unit tests', 'test the VideoLlama3IntegrationTest class for slow integration tests with the real model', 'create a VideoLlama3VisionModelTester to generate config and pixel value inputs for vision model tests', 'create a VideoLlama3VisionText2TextModelTester to generate config and multimodal inputs for text-to-text model tests', 'test the VideoLlama3ProcessorTest class to verify processor functionality for image and video inputs', 'test the processor _get_num_multimodal_tokens helper to verify image token and patch counts', 'test video frame sampling with num_frames and fps arguments in the chat template', 'test that max_pixels kwargs correctly override custom image processor settings', 'test that special multimodal vision tokens are not truncated when truncation is enabled', 'test the VideoLlama3VideoProcessor class initialization and property checks', 'test loading a VideoLlama3VideoProcessor from a configuration dictionary with kwargs override', 'test serializing a VideoLlama3VideoProcessor configuration to a JSON string', 'test processing video inputs as PIL images, numpy arrays, and pytorch tensors with batched and unbatched modes', 'test nested list video inputs and frame sampling with do_sample_frames and fps parameters']
```

Usage

```
{'test_VideoLlama3VideoProcessor': 'test the VideoLlama3VideoProcessor class initialization and property checks', 'test_video_processor_from_dict': 'test loading a VideoLlama3VideoProcessor from a configuration dictionary with kwargs override', 'test_video_processor_to_json': 'test serializing a VideoLlama3VideoProcessor configuration to a JSON string', 'test_call_pil_numpy_torch': 'test processing video inputs as PIL images, numpy arrays, and pytorch tensors with batched and unbatched modes', 'test_nested_input_sampling': 'test nested list video inputs and frame sampling with do_sample_frames and fps parameters'}
```

