# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mobilevit/test_image_processing_mobilevit.py

Prompts

```
['test the MobileViT image processor has do_resize, size, do_center_crop, crop_size, do_flip_channel_order, and do_reduce_labels properties', 'test the MobileViT image processor from_dict method with size, crop_size, and do_reduce_labels kwargs', 'test the MobileViT image processor processes single and batched segmentation maps with torch tensors and PIL images', 'test the MobileViT image processor do_reduce_labels flag reduces ADE20k labels from 150 classes to 255', 'test the MobileViT image processor produces equivalent results across different backend implementations', 'test the MobileViTModel forward pass and verify last_hidden_state output shape', 'test MobileViTForImageClassification with pixel values and labels to verify logits shape', 'test MobileViTForSemanticSegmentation with pixel values and pixel labels to verify logits shape', 'test MobileViTModel output_hidden_states to verify feature map dimensions across stages', 'test MobileViTConfig common properties including hidden_sizes, neck_hidden_sizes, and num_attention_heads', 'run inference on MobileViTForImageClassification with a sample image and verify logits', 'run inference on MobileViTForSemanticSegmentation with a sample image and verify segmentation output']
```

Usage

```
{'test_image_processor_properties': 'test the MobileViT image processor has do_resize, size, do_center_crop, crop_size, do_flip_channel_order, and do_reduce_labels properties', 'test_image_processor_from_dict_with_kwargs': 'test the MobileViT image processor from_dict method with size, crop_size, and do_reduce_labels kwargs', 'test_call_segmentation_maps': 'test the MobileViT image processor processes single and batched segmentation maps with torch tensors and PIL images', 'test_reduce_labels': 'test the MobileViT image processor do_reduce_labels flag reduces ADE20k labels from 150 classes to 255', 'test_backends_equivalence': 'test the MobileViT image processor produces equivalent results across different backend implementations'}
```

## File: huggingface_transformers/tests/models/mobilevit/test_modeling_mobilevit.py

Prompts

```
['test the MobileViT image processor has do_resize, size, do_center_crop, crop_size, do_flip_channel_order, and do_reduce_labels properties', 'test the MobileViT image processor from_dict method with size, crop_size, and do_reduce_labels kwargs', 'test the MobileViT image processor processes single and batched segmentation maps with torch tensors and PIL images', 'test the MobileViT image processor do_reduce_labels flag reduces ADE20k labels from 150 classes to 255', 'test the MobileViT image processor produces equivalent results across different backend implementations', 'test the MobileViTModel forward pass and verify last_hidden_state output shape', 'test MobileViTForImageClassification with pixel values and labels to verify logits shape', 'test MobileViTForSemanticSegmentation with pixel values and pixel labels to verify logits shape', 'test MobileViTModel output_hidden_states to verify feature map dimensions across stages', 'test MobileViTConfig common properties including hidden_sizes, neck_hidden_sizes, and num_attention_heads', 'run inference on MobileViTForImageClassification with a sample image and verify logits', 'run inference on MobileViTForSemanticSegmentation with a sample image and verify segmentation output']
```

Usage

```
{'test_mobilevit_model': 'test the MobileViTModel forward pass and verify last_hidden_state output shape', 'test_mobilevit_image_classification': 'test MobileViTForImageClassification with pixel values and labels to verify logits shape', 'test_mobilevit_semantic_segmentation': 'test MobileViTForSemanticSegmentation with pixel values and pixel labels to verify logits shape', 'test_mobilevit_hidden_states': 'test MobileViTModel output_hidden_states to verify feature map dimensions across stages', 'test_mobilevit_config': 'test MobileViTConfig common properties including hidden_sizes, neck_hidden_sizes, and num_attention_heads', 'test_mobilevit_inference_image_classification': 'run inference on MobileViTForImageClassification with a sample image and verify logits', 'test_mobilevit_inference_semantic_segmentation': 'run inference on MobileViTForSemanticSegmentation with a sample image and verify segmentation output'}
```

