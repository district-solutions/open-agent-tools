# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/seggpt/test_image_processing_seggpt.py

Prompts

```
['test the SegGptImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test the mask_to_rgb method to convert binary masks to RGB using a palette', 'test post_process_semantic_segmentation to verify output shapes match expected post-processed dimensions', 'test prompt mask equivalence across numpy, torch, and PIL input formats for single and batched masks', 'test backend equivalence for pixel_values, prompt_pixel_values, and prompt_masks across image processing backends', 'test the SegGptModel class for forward pass and output shape validation', 'test the SegGptForImageSegmentation class for image segmentation inference', 'test the SegGptLoss function computes segmentation loss from predicted and ground truth masks', 'test SegGpt one-shot and few-shot inference with pretrained model BAAI/seggpt-vit-large', 'test prepare_bool_masked_pos generates random masked patch positions for masked modeling']
```

Usage

```
{'test_seggpt_image_processor_properties': 'test the SegGptImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test_mask_to_rgb_conversion': 'test the mask_to_rgb method to convert binary masks to RGB using a palette', 'test_post_process_semantic_segmentation': 'test post_process_semantic_segmentation to verify output shapes match expected post-processed dimensions', 'test_prompt_mask_equivalence': 'test prompt mask equivalence across numpy, torch, and PIL input formats for single and batched masks', 'test_backends_equivalence': 'test backend equivalence for pixel_values, prompt_pixel_values, and prompt_masks across image processing backends'}
```

## File: huggingface_transformers/tests/models/seggpt/test_modeling_seggpt.py

Prompts

```
['test the SegGptImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test the mask_to_rgb method to convert binary masks to RGB using a palette', 'test post_process_semantic_segmentation to verify output shapes match expected post-processed dimensions', 'test prompt mask equivalence across numpy, torch, and PIL input formats for single and batched masks', 'test backend equivalence for pixel_values, prompt_pixel_values, and prompt_masks across image processing backends', 'test the SegGptModel class for forward pass and output shape validation', 'test the SegGptForImageSegmentation class for image segmentation inference', 'test the SegGptLoss function computes segmentation loss from predicted and ground truth masks', 'test SegGpt one-shot and few-shot inference with pretrained model BAAI/seggpt-vit-large', 'test prepare_bool_masked_pos generates random masked patch positions for masked modeling']
```

Usage

```
{'test_SegGptModel': 'test the SegGptModel class for forward pass and output shape validation', 'test_SegGptForImageSegmentation': 'test the SegGptForImageSegmentation class for image segmentation inference', 'test_SegGptLoss': 'test the SegGptLoss function computes segmentation loss from predicted and ground truth masks', 'test_SegGptModelIntegrationTest': 'test SegGpt one-shot and few-shot inference with pretrained model BAAI/seggpt-vit-large', 'test_prepare_bool_masked_pos': 'test prepare_bool_masked_pos generates random masked patch positions for masked modeling'}
```

