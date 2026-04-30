# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/oneformer/test_image_processing_oneformer.py

Prompts

```
['run the OneFormerImageProcessingTest suite to verify image processing and segmentation functionality', 'test the binary_mask_to_rle function that converts a binary mask numpy array to run-length encoding', 'test post_process_semantic_segmentation to verify it returns correct segmentation shapes from OneFormer model outputs', 'test post_process_instance_segmentation to verify it returns segmentation maps and segments_info with correct shapes', 'test post_process_panoptic_segmentation to verify it returns segmentation maps and segments_info for panoptic tasks', 'test the OneFormerModel forward pass with pixel values and task inputs', 'test the OneFormerForUniversalSegmentation model with mask labels and class labels', 'test the OneFormerForUniversalSegmentation training loop with loss backward pass', 'test the OneFormerModel output hidden states from encoder and pixel decoder', 'test the OneFormer model with timm or HuggingFace backbone selection', 'load class metadata from a HuggingFace Hub dataset JSON file into a dictionary with class names and thing IDs', 'create a processor dictionary with image processor and CLIPTokenizer for OneFormer model testing', 'compute expected height, width, and sequence length for OneFormer processor image inputs', 'generate fake OneFormerForUniversalSegmentationOutput tensors with random class and mask query logits']
```

Usage

```
{'test_oneformer_image_processor': 'run the OneFormerImageProcessingTest suite to verify image processing and segmentation functionality', 'test_binary_mask_to_rle': 'test the binary_mask_to_rle function that converts a binary mask numpy array to run-length encoding', 'test_post_process_semantic_segmentation': 'test post_process_semantic_segmentation to verify it returns correct segmentation shapes from OneFormer model outputs', 'test_post_process_instance_segmentation': 'test post_process_instance_segmentation to verify it returns segmentation maps and segments_info with correct shapes', 'test_post_process_panoptic_segmentation': 'test post_process_panoptic_segmentation to verify it returns segmentation maps and segments_info for panoptic tasks'}
```

## File: huggingface_transformers/tests/models/oneformer/test_modeling_oneformer.py

Prompts

```
['run the OneFormerImageProcessingTest suite to verify image processing and segmentation functionality', 'test the binary_mask_to_rle function that converts a binary mask numpy array to run-length encoding', 'test post_process_semantic_segmentation to verify it returns correct segmentation shapes from OneFormer model outputs', 'test post_process_instance_segmentation to verify it returns segmentation maps and segments_info with correct shapes', 'test post_process_panoptic_segmentation to verify it returns segmentation maps and segments_info for panoptic tasks', 'test the OneFormerModel forward pass with pixel values and task inputs', 'test the OneFormerForUniversalSegmentation model with mask labels and class labels', 'test the OneFormerForUniversalSegmentation training loop with loss backward pass', 'test the OneFormerModel output hidden states from encoder and pixel decoder', 'test the OneFormer model with timm or HuggingFace backbone selection', 'load class metadata from a HuggingFace Hub dataset JSON file into a dictionary with class names and thing IDs', 'create a processor dictionary with image processor and CLIPTokenizer for OneFormer model testing', 'compute expected height, width, and sequence length for OneFormer processor image inputs', 'generate fake OneFormerForUniversalSegmentationOutput tensors with random class and mask query logits']
```

Usage

```
{'test_oneformer_model_forward': 'test the OneFormerModel forward pass with pixel values and task inputs', 'test_oneformer_universal_segmentation': 'test the OneFormerForUniversalSegmentation model with mask labels and class labels', 'test_oneformer_training': 'test the OneFormerForUniversalSegmentation training loop with loss backward pass', 'test_oneformer_hidden_states': 'test the OneFormerModel output hidden states from encoder and pixel decoder', 'test_oneformer_backbone_selection': 'test the OneFormer model with timm or HuggingFace backbone selection'}
```

## File: huggingface_transformers/tests/models/oneformer/test_processing_oneformer.py

Prompts

```
['run the OneFormerImageProcessingTest suite to verify image processing and segmentation functionality', 'test the binary_mask_to_rle function that converts a binary mask numpy array to run-length encoding', 'test post_process_semantic_segmentation to verify it returns correct segmentation shapes from OneFormer model outputs', 'test post_process_instance_segmentation to verify it returns segmentation maps and segments_info with correct shapes', 'test post_process_panoptic_segmentation to verify it returns segmentation maps and segments_info for panoptic tasks', 'test the OneFormerModel forward pass with pixel values and task inputs', 'test the OneFormerForUniversalSegmentation model with mask labels and class labels', 'test the OneFormerForUniversalSegmentation training loop with loss backward pass', 'test the OneFormerModel output hidden states from encoder and pixel decoder', 'test the OneFormer model with timm or HuggingFace backbone selection', 'load class metadata from a HuggingFace Hub dataset JSON file into a dictionary with class names and thing IDs', 'create a processor dictionary with image processor and CLIPTokenizer for OneFormer model testing', 'compute expected height, width, and sequence length for OneFormer processor image inputs', 'generate fake OneFormerForUniversalSegmentationOutput tensors with random class and mask query logits']
```

Usage

```
{'prepare_metadata': 'load class metadata from a HuggingFace Hub dataset JSON file into a dictionary with class names and thing IDs', 'OneFormerProcessorTester_prepare_processor_dict': 'create a processor dictionary with image processor and CLIPTokenizer for OneFormer model testing', 'OneFormerProcessorTester_get_expected_values': 'compute expected height, width, and sequence length for OneFormer processor image inputs', 'OneFormerProcessorTester_get_fake_oneformer_outputs': 'generate fake OneFormerForUniversalSegmentationOutput tensors with random class and mask query logits', 'test_binary_mask_to_rle': 'test the binary_mask_to_rle function by converting a numpy binary mask to run-length encoding'}
```

