# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mask2former/test_image_processing_mask2former.py

Prompts

```
['run the Mask2Former image processing test suite to verify preprocessing and postprocessing behavior', 'test the binary_mask_to_rle function that converts a binary mask array to run-length encoding', 'test post_process_semantic_segmentation to verify output segmentation shapes and target size handling', 'test post_process_instance_segmentation to verify segmentation output with threshold and binary map options', 'test post_process_panoptic_segmentation to verify label fusing and segment info output structure', 'test the Mask2FormerModel forward pass with pixel values and pixel mask inputs', 'test Mask2FormerForUniversalSegmentation with mask labels and class labels to compute loss', 'test the Mask2Former model output hidden states from encoder, pixel decoder, and transformer decoder', 'test training the Mask2FormerForUniversalSegmentation model by computing loss and calling backward', 'test loading Mask2Former with different backbone options including timm resnet18 and HF resnet-18']
```

Usage

```
{'test_mask2former_image_processing': 'run the Mask2Former image processing test suite to verify preprocessing and postprocessing behavior', 'test_binary_mask_to_rle': 'test the binary_mask_to_rle function that converts a binary mask array to run-length encoding', 'test_post_process_semantic_segmentation': 'test post_process_semantic_segmentation to verify output segmentation shapes and target size handling', 'test_post_process_instance_segmentation': 'test post_process_instance_segmentation to verify segmentation output with threshold and binary map options', 'test_post_process_panoptic_segmentation': 'test post_process_panoptic_segmentation to verify label fusing and segment info output structure'}
```

## File: huggingface_transformers/tests/models/mask2former/test_modeling_mask2former.py

Prompts

```
['run the Mask2Former image processing test suite to verify preprocessing and postprocessing behavior', 'test the binary_mask_to_rle function that converts a binary mask array to run-length encoding', 'test post_process_semantic_segmentation to verify output segmentation shapes and target size handling', 'test post_process_instance_segmentation to verify segmentation output with threshold and binary map options', 'test post_process_panoptic_segmentation to verify label fusing and segment info output structure', 'test the Mask2FormerModel forward pass with pixel values and pixel mask inputs', 'test Mask2FormerForUniversalSegmentation with mask labels and class labels to compute loss', 'test the Mask2Former model output hidden states from encoder, pixel decoder, and transformer decoder', 'test training the Mask2FormerForUniversalSegmentation model by computing loss and calling backward', 'test loading Mask2Former with different backbone options including timm resnet18 and HF resnet-18']
```

Usage

```
{'test_mask2former_model_forward': 'test the Mask2FormerModel forward pass with pixel values and pixel mask inputs', 'test_mask2former_universal_segmentation': 'test Mask2FormerForUniversalSegmentation with mask labels and class labels to compute loss', 'test_mask2former_hidden_states': 'test the Mask2Former model output hidden states from encoder, pixel decoder, and transformer decoder', 'test_mask2former_training': 'test training the Mask2FormerForUniversalSegmentation model by computing loss and calling backward', 'test_mask2former_backbone_selection': 'test loading Mask2Former with different backbone options including timm resnet18 and HF resnet-18'}
```

