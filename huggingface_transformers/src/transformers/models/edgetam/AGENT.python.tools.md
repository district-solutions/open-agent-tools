# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/edgetam/convert_edgetam_to_hf.py

Prompts

```
['convert an EdgeTAM checkpoint from the original repository to Hugging Face Transformers format', 'get the EdgeTamConfig with vision, prompt encoder, and mask decoder configurations for model initialization', 'replace and remap state dict keys from the original checkpoint format to Hugging Face naming conventions', 'run a sanity check on the converted model by loading an image and verifying output scores match expected values', 'push the converted EdgeTam model and processor to a Hugging Face Hub repository', 'build a segmentation model using EdgeTamModel to generate masks from input points, boxes, or masks on images', 'create image embeddings from pixel values using EdgeTamModel.get_image_embeddings for memory-efficient mask decoding', 'encode point and box prompts into sparse embeddings using EdgeTamModel.get_prompt_embeddings', 'run the vision encoder via EdgeTamVisionModel to extract FPN feature maps and positional encodings from images', 'decode mask predictions from image embeddings and prompt embeddings using EdgeTamMaskDecoder.forward', 'create an EdgeTamConfig with EdgeTamVisionConfig, EdgeTamPromptEncoderConfig, and EdgeTamMaskDecoderConfig', 'build an EdgeTamVisionModel that extracts FPN features from a RepViT backbone for image input', 'initialize an EdgeTamModel from the yonigozlan/EdgeTAM-hf checkpoint for segmentation tasks', 'configure EdgeTamVisionConfig with custom backbone channels, feature sizes, and FPN parameters', 'run EdgeTamVisionModel forward pass with pixel values to get FPN hidden states and position encodings']
```

Usage

```
{'convert_edgetam_checkpoint': 'convert an EdgeTAM checkpoint from the original repository to Hugging Face Transformers format', 'get_config': 'get the EdgeTamConfig with vision, prompt encoder, and mask decoder configurations for model initialization', 'replace_keys': 'replace and remap state dict keys from the original checkpoint format to Hugging Face naming conventions', 'run_sanity_check': 'run a sanity check on the converted model by loading an image and verifying output scores match expected values', 'push_to_hub': 'push the converted EdgeTam model and processor to a Hugging Face Hub repository'}
```

## File: huggingface_transformers/src/transformers/models/edgetam/modeling_edgetam.py

Prompts

```
['convert an EdgeTAM checkpoint from the original repository to Hugging Face Transformers format', 'get the EdgeTamConfig with vision, prompt encoder, and mask decoder configurations for model initialization', 'replace and remap state dict keys from the original checkpoint format to Hugging Face naming conventions', 'run a sanity check on the converted model by loading an image and verifying output scores match expected values', 'push the converted EdgeTam model and processor to a Hugging Face Hub repository', 'build a segmentation model using EdgeTamModel to generate masks from input points, boxes, or masks on images', 'create image embeddings from pixel values using EdgeTamModel.get_image_embeddings for memory-efficient mask decoding', 'encode point and box prompts into sparse embeddings using EdgeTamModel.get_prompt_embeddings', 'run the vision encoder via EdgeTamVisionModel to extract FPN feature maps and positional encodings from images', 'decode mask predictions from image embeddings and prompt embeddings using EdgeTamMaskDecoder.forward', 'create an EdgeTamConfig with EdgeTamVisionConfig, EdgeTamPromptEncoderConfig, and EdgeTamMaskDecoderConfig', 'build an EdgeTamVisionModel that extracts FPN features from a RepViT backbone for image input', 'initialize an EdgeTamModel from the yonigozlan/EdgeTAM-hf checkpoint for segmentation tasks', 'configure EdgeTamVisionConfig with custom backbone channels, feature sizes, and FPN parameters', 'run EdgeTamVisionModel forward pass with pixel values to get FPN hidden states and position encodings']
```

Usage

```
{'build_segmentation_model_edgetam': 'build a segmentation model using EdgeTamModel to generate masks from input points, boxes, or masks on images', 'create_image_embeddings_edgetam': 'create image embeddings from pixel values using EdgeTamModel.get_image_embeddings for memory-efficient mask decoding', 'encode_prompt_embeddings_edgetam': 'encode point and box prompts into sparse embeddings using EdgeTamModel.get_prompt_embeddings', 'run_vision_encoder_edgetam': 'run the vision encoder via EdgeTamVisionModel to extract FPN feature maps and positional encodings from images', 'decode_mask_predictions_edgetam': 'decode mask predictions from image embeddings and prompt embeddings using EdgeTamMaskDecoder.forward'}
```

## File: huggingface_transformers/src/transformers/models/edgetam/modular_edgetam.py

Prompts

```
['convert an EdgeTAM checkpoint from the original repository to Hugging Face Transformers format', 'get the EdgeTamConfig with vision, prompt encoder, and mask decoder configurations for model initialization', 'replace and remap state dict keys from the original checkpoint format to Hugging Face naming conventions', 'run a sanity check on the converted model by loading an image and verifying output scores match expected values', 'push the converted EdgeTam model and processor to a Hugging Face Hub repository', 'build a segmentation model using EdgeTamModel to generate masks from input points, boxes, or masks on images', 'create image embeddings from pixel values using EdgeTamModel.get_image_embeddings for memory-efficient mask decoding', 'encode point and box prompts into sparse embeddings using EdgeTamModel.get_prompt_embeddings', 'run the vision encoder via EdgeTamVisionModel to extract FPN feature maps and positional encodings from images', 'decode mask predictions from image embeddings and prompt embeddings using EdgeTamMaskDecoder.forward', 'create an EdgeTamConfig with EdgeTamVisionConfig, EdgeTamPromptEncoderConfig, and EdgeTamMaskDecoderConfig', 'build an EdgeTamVisionModel that extracts FPN features from a RepViT backbone for image input', 'initialize an EdgeTamModel from the yonigozlan/EdgeTAM-hf checkpoint for segmentation tasks', 'configure EdgeTamVisionConfig with custom backbone channels, feature sizes, and FPN parameters', 'run EdgeTamVisionModel forward pass with pixel values to get FPN hidden states and position encodings']
```

Usage

```
{'create_config_edgetam': 'create an EdgeTamConfig with EdgeTamVisionConfig, EdgeTamPromptEncoderConfig, and EdgeTamMaskDecoderConfig', 'build_vision_model_edgetam': 'build an EdgeTamVisionModel that extracts FPN features from a RepViT backbone for image input', 'initialize_model_edgetam': 'initialize an EdgeTamModel from the yonigozlan/EdgeTAM-hf checkpoint for segmentation tasks', 'configure_vision_backbone': 'configure EdgeTamVisionConfig with custom backbone channels, feature sizes, and FPN parameters', 'run_forward_vision_model': 'run EdgeTamVisionModel forward pass with pixel values to get FPN hidden states and position encodings'}
```

