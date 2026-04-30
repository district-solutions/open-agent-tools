# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/qwen2_vl/test_image_processing_qwen2_vl.py

Prompts

```
['test the smart_resize function computes best-fit resolution divisible by a given factor', 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends', 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output']
```

Usage

```
{'test_smart_resize': 'test the smart_resize function computes best-fit resolution divisible by a given factor', 'test_Qwen2VLImageProcessingTester': 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test_Qwen2VLImageProcessingTest_properties': 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test_Qwen2VLImageProcessingTest_call': 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test_Qwen2VLImageProcessingTest_backends': 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends'}
```

## File: huggingface_transformers/tests/models/qwen2_vl/test_processing_qwen2_vl.py

Prompts

```
['test the smart_resize function computes best-fit resolution divisible by a given factor', 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends', 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output']
```

Usage

```
{'test_get_num_vision_tokens': 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test_apply_chat_template_video_frame_sampling': 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test_kwargs_overrides_custom_image_processor_kwargs': 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test_special_mm_token_truncation': 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test_apply_chat_template_with_images': 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output'}
```

