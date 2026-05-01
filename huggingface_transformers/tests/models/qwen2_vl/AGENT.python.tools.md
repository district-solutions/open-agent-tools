# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/qwen2_vl/test_image_processing_qwen2_vl.py

Prompts

```
['test the smart_resize function computes best-fit resolution divisible by a given factor', 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends', 'test the Qwen2VL model tester by preparing config and inputs for common test cases', 'run the mismatching number of image tokens test to verify error handling for image-token mismatches', 'test that Qwen2VL computes new rope deltas each forward pass and caches them during generation', 'test vision position IDs are built correctly for images and videos with multi-frame grids', 'run the Qwen2VL integration test for batch generation with multiple images and different resolutions', 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output', 'test the Qwen2VLVideoProcessor with PIL Image video inputs in batched and unbatched mode', 'test the Qwen2VLVideoProcessor with numpy array video inputs for shape validation', 'test the Qwen2VLVideoProcessor with PyTorch tensor video inputs and verify output shapes', 'test the Qwen2VLVideoProcessor frame sampling with num_frames and fps parameters', 'test saving and loading Qwen2VLVideoProcessor with custom min_pixels and max_pixels settings']
```

Usage

```
{'test_smart_resize': 'test the smart_resize function computes best-fit resolution divisible by a given factor', 'test_Qwen2VLImageProcessingTester': 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test_Qwen2VLImageProcessingTest_properties': 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test_Qwen2VLImageProcessingTest_call': 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test_Qwen2VLImageProcessingTest_backends': 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends'}
```

## File: huggingface_transformers/tests/models/qwen2_vl/test_modeling_qwen2_vl.py

Prompts

```
['test the smart_resize function computes best-fit resolution divisible by a given factor', 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends', 'test the Qwen2VL model tester by preparing config and inputs for common test cases', 'run the mismatching number of image tokens test to verify error handling for image-token mismatches', 'test that Qwen2VL computes new rope deltas each forward pass and caches them during generation', 'test vision position IDs are built correctly for images and videos with multi-frame grids', 'run the Qwen2VL integration test for batch generation with multiple images and different resolutions', 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output', 'test the Qwen2VLVideoProcessor with PIL Image video inputs in batched and unbatched mode', 'test the Qwen2VLVideoProcessor with numpy array video inputs for shape validation', 'test the Qwen2VLVideoProcessor with PyTorch tensor video inputs and verify output shapes', 'test the Qwen2VLVideoProcessor frame sampling with num_frames and fps parameters', 'test saving and loading Qwen2VLVideoProcessor with custom min_pixels and max_pixels settings']
```

Usage

```
{'test_Qwen2VLVisionText2TextModelTester': 'test the Qwen2VL model tester by preparing config and inputs for common test cases', 'run_Qwen2VLModelTest_mismatching_tokens': 'run the mismatching number of image tokens test to verify error handling for image-token mismatches', 'test_Qwen2VLModelTest_rope_deltas': 'test that Qwen2VL computes new rope deltas each forward pass and caches them during generation', 'test_Qwen2VLModelTest_vision_position_ids': 'test vision position IDs are built correctly for images and videos with multi-frame grids', 'run_Qwen2VLIntegrationTest_batch': 'run the Qwen2VL integration test for batch generation with multiple images and different resolutions'}
```

## File: huggingface_transformers/tests/models/qwen2_vl/test_processing_qwen2_vl.py

Prompts

```
['test the smart_resize function computes best-fit resolution divisible by a given factor', 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends', 'test the Qwen2VL model tester by preparing config and inputs for common test cases', 'run the mismatching number of image tokens test to verify error handling for image-token mismatches', 'test that Qwen2VL computes new rope deltas each forward pass and caches them during generation', 'test vision position IDs are built correctly for images and videos with multi-frame grids', 'run the Qwen2VL integration test for batch generation with multiple images and different resolutions', 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output', 'test the Qwen2VLVideoProcessor with PIL Image video inputs in batched and unbatched mode', 'test the Qwen2VLVideoProcessor with numpy array video inputs for shape validation', 'test the Qwen2VLVideoProcessor with PyTorch tensor video inputs and verify output shapes', 'test the Qwen2VLVideoProcessor frame sampling with num_frames and fps parameters', 'test saving and loading Qwen2VLVideoProcessor with custom min_pixels and max_pixels settings']
```

Usage

```
{'test_get_num_vision_tokens': 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test_apply_chat_template_video_frame_sampling': 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test_kwargs_overrides_custom_image_processor_kwargs': 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test_special_mm_token_truncation': 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test_apply_chat_template_with_images': 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output'}
```

## File: huggingface_transformers/tests/models/qwen2_vl/test_video_processing_qwen2_vl.py

Prompts

```
['test the smart_resize function computes best-fit resolution divisible by a given factor', 'test the Qwen2VLImageProcessingTester class prepares image processor dict and image inputs for Qwen2-VL', 'test the Qwen2VLImageProcessingTest class verifies image processor properties like do_normalize and patch_size', 'test the Qwen2VLImageProcessingTest class processes PIL, numpy, and PyTorch image inputs with batched and unbatched modes', 'test the Qwen2VLImageProcessingTest class verifies equivalence across multiple image processing backends', 'test the Qwen2VL model tester by preparing config and inputs for common test cases', 'run the mismatching number of image tokens test to verify error handling for image-token mismatches', 'test that Qwen2VL computes new rope deltas each forward pass and caches them during generation', 'test vision position IDs are built correctly for images and videos with multi-frame grids', 'run the Qwen2VL integration test for batch generation with multiple images and different resolutions', 'test the Qwen2VLProcessor._get_num_multimodal_tokens method to compute image patch counts from image sizes', 'test the Qwen2VLProcessor.apply_chat_template method for video frame sampling with fps and num_frames arguments', 'test that processor kwargs override custom image processor parameters like max_pixels during text and image tokenization', 'test that special multimodal vision tokens are not truncated when truncation is enabled with max_length on the processor', 'test the Qwen2VLProcessor.apply_chat_template method with image modality inputs and return_dict tokenized output', 'test the Qwen2VLVideoProcessor with PIL Image video inputs in batched and unbatched mode', 'test the Qwen2VLVideoProcessor with numpy array video inputs for shape validation', 'test the Qwen2VLVideoProcessor with PyTorch tensor video inputs and verify output shapes', 'test the Qwen2VLVideoProcessor frame sampling with num_frames and fps parameters', 'test saving and loading Qwen2VLVideoProcessor with custom min_pixels and max_pixels settings']
```

Usage

```
{'test_Qwen2VLVideoProcessor_pil_inputs': 'test the Qwen2VLVideoProcessor with PIL Image video inputs in batched and unbatched mode', 'test_Qwen2VLVideoProcessor_numpy_inputs': 'test the Qwen2VLVideoProcessor with numpy array video inputs for shape validation', 'test_Qwen2VLVideoProcessor_torch_inputs': 'test the Qwen2VLVideoProcessor with PyTorch tensor video inputs and verify output shapes', 'test_Qwen2VLVideoProcessor_frame_sampling': 'test the Qwen2VLVideoProcessor frame sampling with num_frames and fps parameters', 'test_Qwen2VLVideoProcessor_serialization': 'test saving and loading Qwen2VLVideoProcessor with custom min_pixels and max_pixels settings'}
```

