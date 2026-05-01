# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/depth_pro/test_image_processing_depth_pro.py

Prompts

```
['test the DepthProImageProcessingTest to verify image processor has required properties like image_mean and do_resize', 'test the DepthProImageProcessingTest from_dict method to verify size kwarg overrides the config dict', 'create a DepthProImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration dictionary', 'create a DepthProImageProcessingTester and call prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'create a DepthProImageProcessingTester and call expected_output_image_shape to get the expected output shape tuple for processed images', 'test DepthProForDepthEstimation model forward pass and predicted depth output shape', 'test DepthProForDepthEstimation field-of-view inference with batched and single-row inputs', 'test DepthProModel basic forward pass and last_hidden_state output shape', 'test loading the apple/DepthPro-hf model from HuggingFace hub and verifying it loads', 'test DepthProImageProcessor post_process_depth_estimation to resize predicted depth to original image dimensions']
```

Usage

```
{'test_image_processor_properties': 'test the DepthProImageProcessingTest to verify image processor has required properties like image_mean and do_resize', 'test_image_processor_from_dict_with_kwargs': 'test the DepthProImageProcessingTest from_dict method to verify size kwarg overrides the config dict', 'prepare_image_processor_dict': 'create a DepthProImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration dictionary', 'prepare_image_inputs': 'create a DepthProImageProcessingTester and call prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'expected_output_image_shape': 'create a DepthProImageProcessingTester and call expected_output_image_shape to get the expected output shape tuple for processed images'}
```

## File: huggingface_transformers/tests/models/depth_pro/test_modeling_depth_pro.py

Prompts

```
['test the DepthProImageProcessingTest to verify image processor has required properties like image_mean and do_resize', 'test the DepthProImageProcessingTest from_dict method to verify size kwarg overrides the config dict', 'create a DepthProImageProcessingTester and call prepare_image_processor_dict to get the image processor configuration dictionary', 'create a DepthProImageProcessingTester and call prepare_image_inputs to generate test image batches with optional numpy or torch conversion', 'create a DepthProImageProcessingTester and call expected_output_image_shape to get the expected output shape tuple for processed images', 'test DepthProForDepthEstimation model forward pass and predicted depth output shape', 'test DepthProForDepthEstimation field-of-view inference with batched and single-row inputs', 'test DepthProModel basic forward pass and last_hidden_state output shape', 'test loading the apple/DepthPro-hf model from HuggingFace hub and verifying it loads', 'test DepthProImageProcessor post_process_depth_estimation to resize predicted depth to original image dimensions']
```

Usage

```
{'test_model_for_depth_estimation': 'test DepthProForDepthEstimation model forward pass and predicted depth output shape', 'test_model_for_fov': 'test DepthProForDepthEstimation field-of-view inference with batched and single-row inputs', 'test_model_basic_forward': 'test DepthProModel basic forward pass and last_hidden_state output shape', 'test_model_from_pretrained': 'test loading the apple/DepthPro-hf model from HuggingFace hub and verifying it loads', 'test_post_processing_depth_estimation': 'test DepthProImageProcessor post_process_depth_estimation to resize predicted depth to original image dimensions'}
```

