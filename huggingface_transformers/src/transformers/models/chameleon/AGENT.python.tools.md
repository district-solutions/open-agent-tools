# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/chameleon/convert_chameleon_weights_to_hf.py

Prompts

```
['convert Chameleon model weights from Meta format to HuggingFace Transformers format', 'build a Chameleon model checkpoint in HuggingFace format with configurable model size', 'test the converted Chameleon model with single-image and multi-image generation inference', 'run the CLI tool to convert 7B or 30B Chameleon weights to HuggingFace format', 'summarize the weight mapping between Chameleon original checkpoints and HuggingFace model structure', 'create a ChameleonImageProcessor instance with custom kwargs for image preprocessing', 'convert a PIL image with RGBA transparency to RGB by blending with white background', 'resize a torch.Tensor image to a target size with LANCZOS fallback to BICUBIC interpolation', 'test the convert_to_rgb method handles RGBA images with transparency layers correctly', 'review the resize method LANCZOS-to-BICUBIC fallback behavior for torch.Tensor inputs', 'build a convert_to_rgb call that blends RGBA images onto a white background', 'test the ChameleonImageProcessorPil configuration defaults for resize, crop, rescale, and normalize', 'review the convert_to_rgb method that handles RGBA transparency blending with numpy arrays', 'summarize the ChameleonImageProcessorPil PIL backend class and its image preprocessing pipeline', 'create a ChameleonForConditionalGeneration model for multimodal text and image generation with causal LM head', 'encode images into discrete tokens using ChameleonVQVAE encoder and vector quantizer modules', 'generate text autoregressively from ChameleonForConditionalGeneration with input images and text prompts', 'get image features from pixel values using ChameleonModel get_image_features method with VQVAE encoding', 'build a multimodal forward pass in ChameleonModel that merges image features with text embeddings']
```

Usage

```
{'convert_chameleon_weights_to_hf': 'convert Chameleon model weights from Meta format to HuggingFace Transformers format', 'build_chameleon_model_conversion': 'build a Chameleon model checkpoint in HuggingFace format with configurable model size', 'test_chameleon_conversion_inference': 'test the converted Chameleon model with single-image and multi-image generation inference', 'run_chameleon_weight_conversion': 'run the CLI tool to convert 7B or 30B Chameleon weights to HuggingFace format', 'summarize_chameleon_weight_mapping': 'summarize the weight mapping between Chameleon original checkpoints and HuggingFace model structure'}
```

## File: huggingface_transformers/src/transformers/models/chameleon/image_processing_chameleon.py

Prompts

```
['convert Chameleon model weights from Meta format to HuggingFace Transformers format', 'build a Chameleon model checkpoint in HuggingFace format with configurable model size', 'test the converted Chameleon model with single-image and multi-image generation inference', 'run the CLI tool to convert 7B or 30B Chameleon weights to HuggingFace format', 'summarize the weight mapping between Chameleon original checkpoints and HuggingFace model structure', 'create a ChameleonImageProcessor instance with custom kwargs for image preprocessing', 'convert a PIL image with RGBA transparency to RGB by blending with white background', 'resize a torch.Tensor image to a target size with LANCZOS fallback to BICUBIC interpolation', 'test the convert_to_rgb method handles RGBA images with transparency layers correctly', 'review the resize method LANCZOS-to-BICUBIC fallback behavior for torch.Tensor inputs', 'build a convert_to_rgb call that blends RGBA images onto a white background', 'test the ChameleonImageProcessorPil configuration defaults for resize, crop, rescale, and normalize', 'review the convert_to_rgb method that handles RGBA transparency blending with numpy arrays', 'summarize the ChameleonImageProcessorPil PIL backend class and its image preprocessing pipeline', 'create a ChameleonForConditionalGeneration model for multimodal text and image generation with causal LM head', 'encode images into discrete tokens using ChameleonVQVAE encoder and vector quantizer modules', 'generate text autoregressively from ChameleonForConditionalGeneration with input images and text prompts', 'get image features from pixel values using ChameleonModel get_image_features method with VQVAE encoding', 'build a multimodal forward pass in ChameleonModel that merges image features with text embeddings']
```

Usage

```
{'create_chameleon_image_processor': 'create a ChameleonImageProcessor instance with custom kwargs for image preprocessing', 'convert_image_to_rgb': 'convert a PIL image with RGBA transparency to RGB by blending with white background', 'resize_torch_tensor_image': 'resize a torch.Tensor image to a target size with LANCZOS fallback to BICUBIC interpolation', 'test_convert_to_rgb_transparency': 'test the convert_to_rgb method handles RGBA images with transparency layers correctly', 'review_resize_interpolation_fallback': 'review the resize method LANCZOS-to-BICUBIC fallback behavior for torch.Tensor inputs'}
```

## File: huggingface_transformers/src/transformers/models/chameleon/image_processing_pil_chameleon.py

Prompts

```
['convert Chameleon model weights from Meta format to HuggingFace Transformers format', 'build a Chameleon model checkpoint in HuggingFace format with configurable model size', 'test the converted Chameleon model with single-image and multi-image generation inference', 'run the CLI tool to convert 7B or 30B Chameleon weights to HuggingFace format', 'summarize the weight mapping between Chameleon original checkpoints and HuggingFace model structure', 'create a ChameleonImageProcessor instance with custom kwargs for image preprocessing', 'convert a PIL image with RGBA transparency to RGB by blending with white background', 'resize a torch.Tensor image to a target size with LANCZOS fallback to BICUBIC interpolation', 'test the convert_to_rgb method handles RGBA images with transparency layers correctly', 'review the resize method LANCZOS-to-BICUBIC fallback behavior for torch.Tensor inputs', 'build a convert_to_rgb call that blends RGBA images onto a white background', 'test the ChameleonImageProcessorPil configuration defaults for resize, crop, rescale, and normalize', 'review the convert_to_rgb method that handles RGBA transparency blending with numpy arrays', 'summarize the ChameleonImageProcessorPil PIL backend class and its image preprocessing pipeline', 'create a ChameleonForConditionalGeneration model for multimodal text and image generation with causal LM head', 'encode images into discrete tokens using ChameleonVQVAE encoder and vector quantizer modules', 'generate text autoregressively from ChameleonForConditionalGeneration with input images and text prompts', 'get image features from pixel values using ChameleonModel get_image_features method with VQVAE encoding', 'build a multimodal forward pass in ChameleonModel that merges image features with text embeddings']
```

Usage

```
{'create_chameleon_image_processor': 'create a ChameleonImageProcessorPil instance with custom image processing kwargs', 'build_convert_to_rgb': 'build a convert_to_rgb call that blends RGBA images onto a white background', 'test_chameleon_image_processor_config': 'test the ChameleonImageProcessorPil configuration defaults for resize, crop, rescale, and normalize', 'review_convert_to_rgb_transparency': 'review the convert_to_rgb method that handles RGBA transparency blending with numpy arrays', 'summarize_pil_backend_class': 'summarize the ChameleonImageProcessorPil PIL backend class and its image preprocessing pipeline'}
```

## File: huggingface_transformers/src/transformers/models/chameleon/modeling_chameleon.py

Prompts

```
['convert Chameleon model weights from Meta format to HuggingFace Transformers format', 'build a Chameleon model checkpoint in HuggingFace format with configurable model size', 'test the converted Chameleon model with single-image and multi-image generation inference', 'run the CLI tool to convert 7B or 30B Chameleon weights to HuggingFace format', 'summarize the weight mapping between Chameleon original checkpoints and HuggingFace model structure', 'create a ChameleonImageProcessor instance with custom kwargs for image preprocessing', 'convert a PIL image with RGBA transparency to RGB by blending with white background', 'resize a torch.Tensor image to a target size with LANCZOS fallback to BICUBIC interpolation', 'test the convert_to_rgb method handles RGBA images with transparency layers correctly', 'review the resize method LANCZOS-to-BICUBIC fallback behavior for torch.Tensor inputs', 'build a convert_to_rgb call that blends RGBA images onto a white background', 'test the ChameleonImageProcessorPil configuration defaults for resize, crop, rescale, and normalize', 'review the convert_to_rgb method that handles RGBA transparency blending with numpy arrays', 'summarize the ChameleonImageProcessorPil PIL backend class and its image preprocessing pipeline', 'create a ChameleonForConditionalGeneration model for multimodal text and image generation with causal LM head', 'encode images into discrete tokens using ChameleonVQVAE encoder and vector quantizer modules', 'generate text autoregressively from ChameleonForConditionalGeneration with input images and text prompts', 'get image features from pixel values using ChameleonModel get_image_features method with VQVAE encoding', 'build a multimodal forward pass in ChameleonModel that merges image features with text embeddings']
```

Usage

```
{'create_chameleon_conditional_generation': 'create a ChameleonForConditionalGeneration model for multimodal text and image generation with causal LM head', 'encode_images_with_vqvae': 'encode images into discrete tokens using ChameleonVQVAE encoder and vector quantizer modules', 'generate_text_with_images': 'generate text autoregressively from ChameleonForConditionalGeneration with input images and text prompts', 'get_image_features': 'get image features from pixel values using ChameleonModel get_image_features method with VQVAE encoding', 'build_multimodal_forward_pass': 'build a multimodal forward pass in ChameleonModel that merges image features with text embeddings'}
```

