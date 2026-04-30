# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/sam_hq/test_modeling_sam_hq.py

Prompts

```
['test the SamHQVisionModel class with config and pixel values to verify forward pass output shapes', 'test the SamHQModel class with multimask_output to verify iou_scores and pred_masks output shapes', 'test SamHQModel attention outputs for both vision encoder and mask decoder with expected attention shapes', 'run SamHQModel inference for mask generation with input points, boxes, and labels on a real image', 'test the mask-generation pipeline with SamHQModel using a generator and real image input', 'test the SamHQProcessor class for processing images with segmentation prompts', 'test the SamHQProcessor image processing path without segmentation masks', 'test the SamHQProcessor image processing with segmentation map masks', 'test the post_process_masks method for resizing and scaling output masks', 'create a SamHQProcessor instance with an image processor for prompt-based segmentation']
```

Usage

```
{'test_SamHQVisionModel': 'test the SamHQVisionModel class with config and pixel values to verify forward pass output shapes', 'test_SamHQModel': 'test the SamHQModel class with multimask_output to verify iou_scores and pred_masks output shapes', 'test_SamHQModel_attention_outputs': 'test SamHQModel attention outputs for both vision encoder and mask decoder with expected attention shapes', 'run_SamHQ_inference_mask_generation': 'run SamHQModel inference for mask generation with input points, boxes, and labels on a real image', 'test_SamHQ_pipeline_mask_generation': 'test the mask-generation pipeline with SamHQModel using a generator and real image input'}
```

## File: huggingface_transformers/tests/models/sam_hq/test_processing_sam_hq.py

Prompts

```
['test the SamHQVisionModel class with config and pixel values to verify forward pass output shapes', 'test the SamHQModel class with multimask_output to verify iou_scores and pred_masks output shapes', 'test SamHQModel attention outputs for both vision encoder and mask decoder with expected attention shapes', 'run SamHQModel inference for mask generation with input points, boxes, and labels on a real image', 'test the mask-generation pipeline with SamHQModel using a generator and real image input', 'test the SamHQProcessor class for processing images with segmentation prompts', 'test the SamHQProcessor image processing path without segmentation masks', 'test the SamHQProcessor image processing with segmentation map masks', 'test the post_process_masks method for resizing and scaling output masks', 'create a SamHQProcessor instance with an image processor for prompt-based segmentation']
```

Usage

```
{'test_SamHQProcessor': 'test the SamHQProcessor class for processing images with segmentation prompts', 'test_image_processor_no_masks': 'test the SamHQProcessor image processing path without segmentation masks', 'test_image_processor_with_masks': 'test the SamHQProcessor image processing with segmentation map masks', 'test_post_process_masks': 'test the post_process_masks method for resizing and scaling output masks', 'create_SamHQProcessor': 'create a SamHQProcessor instance with an image processor for prompt-based segmentation'}
```

