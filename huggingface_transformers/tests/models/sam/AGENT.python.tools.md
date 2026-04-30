# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/sam/test_image_processing_sam.py

Prompts

```
['create a SamImageProcessingTester instance with configurable batch size, image size, pad size, and normalization settings', 'test that the Sam image processor has all expected attributes like image_mean, image_std, do_pad, and mask_pad_size', 'test loading a Sam image processor from a config dict and overriding parameters like size via kwargs', 'test calling the Sam image processor with segmentation maps on single and batched inputs to verify pixel_values and labels shapes', 'test that multiple Sam image processing backends produce equivalent pixel_values and segmentation labels within tolerance', 'run the SAM model integration tests for mask generation with points and boxes', 'test the SAM model class for attention outputs and image feature extraction', 'test the SAM vision encoder model for attention outputs and embeddings', 'review the SamModelTester class that generates configs and dummy inputs for SAM model tests', 'review the SamVisionModelTester class that creates SamVisionConfig and pixel value tensors', 'test SamProcessor image processing without segmentation masks and verify pixel value shapes', 'test SamProcessor image processing with segmentation maps and verify label output shapes', 'test post_process_masks method to resize dummy masks back to original image dimensions', 'test the _mask_to_rle function for run-length encoding of binary mask tensors', 'review the SamProcessorTest class and its test methods for image processing and mask handling']
```

Usage

```
{'create_SamImageProcessingTester': 'create a SamImageProcessingTester instance with configurable batch size, image size, pad size, and normalization settings', 'test_image_processor_properties': 'test that the Sam image processor has all expected attributes like image_mean, image_std, do_pad, and mask_pad_size', 'test_image_processor_from_dict_with_kwargs': 'test loading a Sam image processor from a config dict and overriding parameters like size via kwargs', 'test_call_segmentation_maps': 'test calling the Sam image processor with segmentation maps on single and batched inputs to verify pixel_values and labels shapes', 'test_backends_equivalence': 'test that multiple Sam image processing backends produce equivalent pixel_values and segmentation labels within tolerance'}
```

## File: huggingface_transformers/tests/models/sam/test_modeling_sam.py

Prompts

```
['create a SamImageProcessingTester instance with configurable batch size, image size, pad size, and normalization settings', 'test that the Sam image processor has all expected attributes like image_mean, image_std, do_pad, and mask_pad_size', 'test loading a Sam image processor from a config dict and overriding parameters like size via kwargs', 'test calling the Sam image processor with segmentation maps on single and batched inputs to verify pixel_values and labels shapes', 'test that multiple Sam image processing backends produce equivalent pixel_values and segmentation labels within tolerance', 'run the SAM model integration tests for mask generation with points and boxes', 'test the SAM model class for attention outputs and image feature extraction', 'test the SAM vision encoder model for attention outputs and embeddings', 'review the SamModelTester class that generates configs and dummy inputs for SAM model tests', 'review the SamVisionModelTester class that creates SamVisionConfig and pixel value tensors', 'test SamProcessor image processing without segmentation masks and verify pixel value shapes', 'test SamProcessor image processing with segmentation maps and verify label output shapes', 'test post_process_masks method to resize dummy masks back to original image dimensions', 'test the _mask_to_rle function for run-length encoding of binary mask tensors', 'review the SamProcessorTest class and its test methods for image processing and mask handling']
```

Usage

```
{'run_SamModelIntegrationTest': 'run the SAM model integration tests for mask generation with points and boxes', 'test_SamModelTest': 'test the SAM model class for attention outputs and image feature extraction', 'test_SamVisionModelTest': 'test the SAM vision encoder model for attention outputs and embeddings', 'review_SamModelTester': 'review the SamModelTester class that generates configs and dummy inputs for SAM model tests', 'review_SamVisionModelTester': 'review the SamVisionModelTester class that creates SamVisionConfig and pixel value tensors'}
```

## File: huggingface_transformers/tests/models/sam/test_processing_sam.py

Prompts

```
['create a SamImageProcessingTester instance with configurable batch size, image size, pad size, and normalization settings', 'test that the Sam image processor has all expected attributes like image_mean, image_std, do_pad, and mask_pad_size', 'test loading a Sam image processor from a config dict and overriding parameters like size via kwargs', 'test calling the Sam image processor with segmentation maps on single and batched inputs to verify pixel_values and labels shapes', 'test that multiple Sam image processing backends produce equivalent pixel_values and segmentation labels within tolerance', 'run the SAM model integration tests for mask generation with points and boxes', 'test the SAM model class for attention outputs and image feature extraction', 'test the SAM vision encoder model for attention outputs and embeddings', 'review the SamModelTester class that generates configs and dummy inputs for SAM model tests', 'review the SamVisionModelTester class that creates SamVisionConfig and pixel value tensors', 'test SamProcessor image processing without segmentation masks and verify pixel value shapes', 'test SamProcessor image processing with segmentation maps and verify label output shapes', 'test post_process_masks method to resize dummy masks back to original image dimensions', 'test the _mask_to_rle function for run-length encoding of binary mask tensors', 'review the SamProcessorTest class and its test methods for image processing and mask handling']
```

Usage

```
{'test_sam_processor_no_masks': 'test SamProcessor image processing without segmentation masks and verify pixel value shapes', 'test_sam_processor_with_masks': 'test SamProcessor image processing with segmentation maps and verify label output shapes', 'test_post_process_masks': 'test post_process_masks method to resize dummy masks back to original image dimensions', 'test_mask_to_rle_encoding': 'test the _mask_to_rle function for run-length encoding of binary mask tensors', 'review_sam_processor_test': 'review the SamProcessorTest class and its test methods for image processing and mask handling'}
```

