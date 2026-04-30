# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/sam/test_image_processing_sam.py

Prompts

```
['create a SamImageProcessingTester instance with configurable batch size, image size, pad size, and normalization settings', 'test that the Sam image processor has all expected attributes like image_mean, image_std, do_pad, and mask_pad_size', 'test loading a Sam image processor from a config dict and overriding parameters like size via kwargs', 'test calling the Sam image processor with segmentation maps on single and batched inputs to verify pixel_values and labels shapes', 'test that multiple Sam image processing backends produce equivalent pixel_values and segmentation labels within tolerance']
```

Usage

```
{'create_SamImageProcessingTester': 'create a SamImageProcessingTester instance with configurable batch size, image size, pad size, and normalization settings', 'test_image_processor_properties': 'test that the Sam image processor has all expected attributes like image_mean, image_std, do_pad, and mask_pad_size', 'test_image_processor_from_dict_with_kwargs': 'test loading a Sam image processor from a config dict and overriding parameters like size via kwargs', 'test_call_segmentation_maps': 'test calling the Sam image processor with segmentation maps on single and batched inputs to verify pixel_values and labels shapes', 'test_backends_equivalence': 'test that multiple Sam image processing backends produce equivalent pixel_values and segmentation labels within tolerance'}
```

