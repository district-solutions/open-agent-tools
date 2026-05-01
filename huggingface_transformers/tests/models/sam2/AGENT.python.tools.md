# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/sam2/test_image_processing_sam2.py

Prompts

```
['test the Sam2ImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test the Sam2 image processor call method with segmentation maps for single and batched inputs', 'test the Sam2 image processor from_dict method with keyword argument overrides for size', 'create a function that loads a single image and segmentation map from the ADE20K dataset fixture', 'create a function that loads a batch of images and segmentation maps from the ADE20K dataset fixture', 'test the Sam2VisionModel class with config and pixel value inputs for vision encoder inference', 'test the Sam2Model class with config and pixel value inputs for end-to-end mask generation', 'test the Sam2VisionModel attention outputs with correct number of attentions and window shapes', 'test the Sam2Model attention outputs with vision attentions and correct window shapes', 'test SAM2 inference mask generation with point prompts, batched images, and existing masks', 'test the Sam2Processor by processing images without segmentation masks and verifying pixel value output', 'test the Sam2Processor by processing images with segmentation masks and verifying label shapes', 'test the post_process_masks method by resizing dummy masks to original image dimensions', 'create dummy PyTorch image input tensors with random uint8 values for testing', 'create dummy PyTorch mask input tensors with random uint8 values for testing']
```

Usage

```
{'test_sam2_image_processor_properties': 'test the Sam2ImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test_sam2_segmentation_maps': 'test the Sam2 image processor call method with segmentation maps for single and batched inputs', 'test_sam2_from_dict_with_kwargs': 'test the Sam2 image processor from_dict method with keyword argument overrides for size', 'prepare_semantic_single_inputs': 'create a function that loads a single image and segmentation map from the ADE20K dataset fixture', 'prepare_semantic_batch_inputs': 'create a function that loads a batch of images and segmentation maps from the ADE20K dataset fixture'}
```

## File: huggingface_transformers/tests/models/sam2/test_modeling_sam2.py

Prompts

```
['test the Sam2ImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test the Sam2 image processor call method with segmentation maps for single and batched inputs', 'test the Sam2 image processor from_dict method with keyword argument overrides for size', 'create a function that loads a single image and segmentation map from the ADE20K dataset fixture', 'create a function that loads a batch of images and segmentation maps from the ADE20K dataset fixture', 'test the Sam2VisionModel class with config and pixel value inputs for vision encoder inference', 'test the Sam2Model class with config and pixel value inputs for end-to-end mask generation', 'test the Sam2VisionModel attention outputs with correct number of attentions and window shapes', 'test the Sam2Model attention outputs with vision attentions and correct window shapes', 'test SAM2 inference mask generation with point prompts, batched images, and existing masks', 'test the Sam2Processor by processing images without segmentation masks and verifying pixel value output', 'test the Sam2Processor by processing images with segmentation masks and verifying label shapes', 'test the post_process_masks method by resizing dummy masks to original image dimensions', 'create dummy PyTorch image input tensors with random uint8 values for testing', 'create dummy PyTorch mask input tensors with random uint8 values for testing']
```

Usage

```
{'test_Sam2VisionModel': 'test the Sam2VisionModel class with config and pixel value inputs for vision encoder inference', 'test_Sam2Model': 'test the Sam2Model class with config and pixel value inputs for end-to-end mask generation', 'test_attention_outputs_Sam2VisionModel': 'test the Sam2VisionModel attention outputs with correct number of attentions and window shapes', 'test_attention_outputs_Sam2Model': 'test the Sam2Model attention outputs with vision attentions and correct window shapes', 'test_inference_mask_generation': 'test SAM2 inference mask generation with point prompts, batched images, and existing masks'}
```

## File: huggingface_transformers/tests/models/sam2/test_processor_sam2.py

Prompts

```
['test the Sam2ImageProcessingTest class to verify image processor properties like image_mean and do_resize', 'test the Sam2 image processor call method with segmentation maps for single and batched inputs', 'test the Sam2 image processor from_dict method with keyword argument overrides for size', 'create a function that loads a single image and segmentation map from the ADE20K dataset fixture', 'create a function that loads a batch of images and segmentation maps from the ADE20K dataset fixture', 'test the Sam2VisionModel class with config and pixel value inputs for vision encoder inference', 'test the Sam2Model class with config and pixel value inputs for end-to-end mask generation', 'test the Sam2VisionModel attention outputs with correct number of attentions and window shapes', 'test the Sam2Model attention outputs with vision attentions and correct window shapes', 'test SAM2 inference mask generation with point prompts, batched images, and existing masks', 'test the Sam2Processor by processing images without segmentation masks and verifying pixel value output', 'test the Sam2Processor by processing images with segmentation masks and verifying label shapes', 'test the post_process_masks method by resizing dummy masks to original image dimensions', 'create dummy PyTorch image input tensors with random uint8 values for testing', 'create dummy PyTorch mask input tensors with random uint8 values for testing']
```

Usage

```
{'test_sam2_processor_no_masks': 'test the Sam2Processor by processing images without segmentation masks and verifying pixel value output', 'test_sam2_processor_with_masks': 'test the Sam2Processor by processing images with segmentation masks and verifying label shapes', 'test_post_process_masks': 'test the post_process_masks method by resizing dummy masks to original image dimensions', 'prepare_image_inputs': 'create dummy PyTorch image input tensors with random uint8 values for testing', 'prepare_mask_inputs': 'create dummy PyTorch mask input tensors with random uint8 values for testing'}
```

