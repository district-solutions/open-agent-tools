# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/fuyu/test_image_processing_fuyu.py

Prompts

```
['test the Fuyu image processing tests for PIL, numpy, and pytorch input backends', 'test that patchify_image produces the expected number of patches for a given image size', 'test that preprocess returns the correct output structure with images, heights, widths, and scale factors', 'test processing multiple images with mixed PIL and numpy inputs in a batch', 'test that resize maintains aspect ratio correctly for both PIL and torchvision backends', 'test that padding works correctly for the torchvision backend with a specified target size', 'test preprocess_with_tokenizer_info for generating image input IDs and patch indices', 'test that multiple backends produce equivalent encoded outputs for the same input image', 'test the FuyuModelTest class that validates FuyuModel and FuyuForCausalLM with unit tests', 'test FuyuModelTester.prepare_config_and_inputs to generate model config and input tensors', 'test FuyuModelTester.prepare_config_and_inputs_for_common to prepare inputs for common test utilities', 'test FuyuModelTest.test_mismatching_image_patches to verify error handling for mismatched image patches', 'test FuyuModelIntegrationTest.greedy_generation to run slow integration test on the real Fuyu-8b model', 'run the FuyuProcessingTest suite to verify FuyuProcessor handles text and image inputs correctly', 'run the TestImageTextProcessingUtils suite to test construct_full_unpacked_stream and full_unpacked_stream_to_tensor helpers', 'run the TestProcessImagesForModelInput suite to verify FuyuImageProcessor preprocess_with_tokenizer_info output shapes', 'test FuyuProcessor by passing text and a PIL image and assert image_patches_indices and input_ids match expected tensors', 'test FuyuProcessor with text-only input and verify output input_ids match the standalone tokenizer output']
```

Usage

```
{'test_image_processing_fuyu': 'test the Fuyu image processing tests for PIL, numpy, and pytorch input backends', 'test_fuyu_image_patching': 'test that patchify_image produces the expected number of patches for a given image size', 'test_fuyu_preprocess_output': 'test that preprocess returns the correct output structure with images, heights, widths, and scale factors', 'test_fuyu_batch_processing': 'test processing multiple images with mixed PIL and numpy inputs in a batch', 'test_fuyu_resize_aspect_ratio': 'test that resize maintains aspect ratio correctly for both PIL and torchvision backends', 'test_fuyu_padding_torchvision': 'test that padding works correctly for the torchvision backend with a specified target size', 'test_fuyu_preprocess_tokenizer_info': 'test preprocess_with_tokenizer_info for generating image input IDs and patch indices', 'test_fuyu_backend_equivalence': 'test that multiple backends produce equivalent encoded outputs for the same input image'}
```

## File: huggingface_transformers/tests/models/fuyu/test_modeling_fuyu.py

Prompts

```
['test the Fuyu image processing tests for PIL, numpy, and pytorch input backends', 'test that patchify_image produces the expected number of patches for a given image size', 'test that preprocess returns the correct output structure with images, heights, widths, and scale factors', 'test processing multiple images with mixed PIL and numpy inputs in a batch', 'test that resize maintains aspect ratio correctly for both PIL and torchvision backends', 'test that padding works correctly for the torchvision backend with a specified target size', 'test preprocess_with_tokenizer_info for generating image input IDs and patch indices', 'test that multiple backends produce equivalent encoded outputs for the same input image', 'test the FuyuModelTest class that validates FuyuModel and FuyuForCausalLM with unit tests', 'test FuyuModelTester.prepare_config_and_inputs to generate model config and input tensors', 'test FuyuModelTester.prepare_config_and_inputs_for_common to prepare inputs for common test utilities', 'test FuyuModelTest.test_mismatching_image_patches to verify error handling for mismatched image patches', 'test FuyuModelIntegrationTest.greedy_generation to run slow integration test on the real Fuyu-8b model', 'run the FuyuProcessingTest suite to verify FuyuProcessor handles text and image inputs correctly', 'run the TestImageTextProcessingUtils suite to test construct_full_unpacked_stream and full_unpacked_stream_to_tensor helpers', 'run the TestProcessImagesForModelInput suite to verify FuyuImageProcessor preprocess_with_tokenizer_info output shapes', 'test FuyuProcessor by passing text and a PIL image and assert image_patches_indices and input_ids match expected tensors', 'test FuyuProcessor with text-only input and verify output input_ids match the standalone tokenizer output']
```

Usage

```
{'test_FuyuModelTest': 'test the FuyuModelTest class that validates FuyuModel and FuyuForCausalLM with unit tests', 'test_FuyuModelTester_prepare_config': 'test FuyuModelTester.prepare_config_and_inputs to generate model config and input tensors', 'test_FuyuModelTester_prepare_common': 'test FuyuModelTester.prepare_config_and_inputs_for_common to prepare inputs for common test utilities', 'test_mismatching_image_patches': 'test FuyuModelTest.test_mismatching_image_patches to verify error handling for mismatched image patches', 'test_FuyuModelIntegrationTest': 'test FuyuModelIntegrationTest.greedy_generation to run slow integration test on the real Fuyu-8b model'}
```

## File: huggingface_transformers/tests/models/fuyu/test_processing_fuyu.py

Prompts

```
['test the Fuyu image processing tests for PIL, numpy, and pytorch input backends', 'test that patchify_image produces the expected number of patches for a given image size', 'test that preprocess returns the correct output structure with images, heights, widths, and scale factors', 'test processing multiple images with mixed PIL and numpy inputs in a batch', 'test that resize maintains aspect ratio correctly for both PIL and torchvision backends', 'test that padding works correctly for the torchvision backend with a specified target size', 'test preprocess_with_tokenizer_info for generating image input IDs and patch indices', 'test that multiple backends produce equivalent encoded outputs for the same input image', 'test the FuyuModelTest class that validates FuyuModel and FuyuForCausalLM with unit tests', 'test FuyuModelTester.prepare_config_and_inputs to generate model config and input tensors', 'test FuyuModelTester.prepare_config_and_inputs_for_common to prepare inputs for common test utilities', 'test FuyuModelTest.test_mismatching_image_patches to verify error handling for mismatched image patches', 'test FuyuModelIntegrationTest.greedy_generation to run slow integration test on the real Fuyu-8b model', 'run the FuyuProcessingTest suite to verify FuyuProcessor handles text and image inputs correctly', 'run the TestImageTextProcessingUtils suite to test construct_full_unpacked_stream and full_unpacked_stream_to_tensor helpers', 'run the TestProcessImagesForModelInput suite to verify FuyuImageProcessor preprocess_with_tokenizer_info output shapes', 'test FuyuProcessor by passing text and a PIL image and assert image_patches_indices and input_ids match expected tensors', 'test FuyuProcessor with text-only input and verify output input_ids match the standalone tokenizer output']
```

Usage

```
{'run_FuyuProcessingTest': 'run the FuyuProcessingTest suite to verify FuyuProcessor handles text and image inputs correctly', 'run_TestImageTextProcessingUtils': 'run the TestImageTextProcessingUtils suite to test construct_full_unpacked_stream and full_unpacked_stream_to_tensor helpers', 'run_TestProcessImagesForModelInput': 'run the TestProcessImagesForModelInput suite to verify FuyuImageProcessor preprocess_with_tokenizer_info output shapes', 'test_FuyuProcessor_with_text_and_image': 'test FuyuProcessor by passing text and a PIL image and assert image_patches_indices and input_ids match expected tensors', 'test_FuyuProcessor_text_only': 'test FuyuProcessor with text-only input and verify output input_ids match the standalone tokenizer output'}
```

