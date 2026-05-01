# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/dinov3_vit/test_image_processing_dinov3_vit.py

Prompts

```
['test that DINOv3ViT image processor has do_resize, size, do_center_crop, and do_normalize attributes', 'test DINOv3ViT image processor from_dict method with size and crop_size keyword argument overrides', 'create a configuration dictionary with resize, crop, normalize, and RGB conversion settings for DINOv3ViT image processing', 'generate test image inputs with configurable batch size, resolution range, and numpy or torch tensor output', 'compute the expected output image shape given crop size height and width for DINOv3ViT processing', 'create a DINOv3ViTConfig with custom image size, patch size, hidden size, and register tokens', 'test the DINOv3ViTModelTester to prepare config and pixel values for model inputs', 'run create and check model to validate DINOv3ViTModel output shape and last hidden state', 'run create and check backbone to validate DINOv3ViTBackbone feature maps output', 'test inference with a pretrained DINOv3ViT model on a sample image and verify outputs']
```

Usage

```
{'test_image_processor_properties': 'test that DINOv3ViT image processor has do_resize, size, do_center_crop, and do_normalize attributes', 'test_image_processor_from_dict_with_kwargs': 'test DINOv3ViT image processor from_dict method with size and crop_size keyword argument overrides', 'prepare_image_processor_dict': 'create a configuration dictionary with resize, crop, normalize, and RGB conversion settings for DINOv3ViT image processing', 'prepare_image_inputs': 'generate test image inputs with configurable batch size, resolution range, and numpy or torch tensor output', 'expected_output_image_shape': 'compute the expected output image shape given crop size height and width for DINOv3ViT processing'}
```

## File: huggingface_transformers/tests/models/dinov3_vit/test_modeling_dinov3_vit.py

Prompts

```
['test that DINOv3ViT image processor has do_resize, size, do_center_crop, and do_normalize attributes', 'test DINOv3ViT image processor from_dict method with size and crop_size keyword argument overrides', 'create a configuration dictionary with resize, crop, normalize, and RGB conversion settings for DINOv3ViT image processing', 'generate test image inputs with configurable batch size, resolution range, and numpy or torch tensor output', 'compute the expected output image shape given crop size height and width for DINOv3ViT processing', 'create a DINOv3ViTConfig with custom image size, patch size, hidden size, and register tokens', 'test the DINOv3ViTModelTester to prepare config and pixel values for model inputs', 'run create and check model to validate DINOv3ViTModel output shape and last hidden state', 'run create and check backbone to validate DINOv3ViTBackbone feature maps output', 'test inference with a pretrained DINOv3ViT model on a sample image and verify outputs']
```

Usage

```
{'create_DINOv3ViTConfig': 'create a DINOv3ViTConfig with custom image size, patch size, hidden size, and register tokens', 'test_DINOv3ViTModelTester': 'test the DINOv3ViTModelTester to prepare config and pixel values for model inputs', 'run_create_and_check_model': 'run create and check model to validate DINOv3ViTModel output shape and last hidden state', 'run_create_and_check_backbone': 'run create and check backbone to validate DINOv3ViTBackbone feature maps output', 'test_inference_no_head': 'test inference with a pretrained DINOv3ViT model on a sample image and verify outputs'}
```

