# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/lw_detr/configuration_lw_detr.py

Prompts

```
['create an LwDetrViTConfig instance with custom window blocks, image size, and position embeddings', 'create an LwDetrConfig instance with custom backbone, decoder heads, and number of queries', 'validate LwDetrViTConfig architecture ensuring num_windows is a perfect square and image_size is divisible', 'validate LwDetrConfig projector_scale_factors containing only supported values 0.5, 1.0, or 2.0', 'initialize an LwDetrModel from LwDetrConfig and access the model configuration via model.config', 'convert an LW-DETR checkpoint to HuggingFace format and save it locally', 'run the LW-DETR checkpoint converter CLI with a model name and output directory', 'get the model configuration for a given LW-DETR model size and training dataset', 'test model outputs by comparing logits, boxes, and loss against expected values', 'get the key mapping for backbone projector sampling layers based on model config', 'create an LwDetrForObjectDetection model for object detection with configurable backbone and decoder', 'build an LwDetrViTBackbone encoder that extracts multi-scale feature maps from input images', 'run forward inference on LwDetrForObjectDetection to get classification logits and predicted bounding boxes', 'test the LwDetrDecoder with multiscale deformable cross-attention and sine positional embeddings', 'review the LwDetrMultiScaleProjector that aggregates multi-scale backbone features into unified query embeddings', 'test the LwDetrDecoder with group DETR technique for faster training convergence and deformable cross-attention']
```

Usage

```
{'create_LwDetrViTConfig': 'create an LwDetrViTConfig instance with custom window blocks, image size, and position embeddings', 'create_LwDetrConfig': 'create an LwDetrConfig instance with custom backbone, decoder heads, and number of queries', 'validate_LwDetrViTConfig': 'validate LwDetrViTConfig architecture ensuring num_windows is a perfect square and image_size is divisible', 'validate_LwDetrConfig': 'validate LwDetrConfig projector_scale_factors containing only supported values 0.5, 1.0, or 2.0', 'initialize_LwDetrModel': 'initialize an LwDetrModel from LwDetrConfig and access the model configuration via model.config'}
```

## File: huggingface_transformers/src/transformers/models/lw_detr/convert_lw_detr_to_hf.py

Prompts

```
['create an LwDetrViTConfig instance with custom window blocks, image size, and position embeddings', 'create an LwDetrConfig instance with custom backbone, decoder heads, and number of queries', 'validate LwDetrViTConfig architecture ensuring num_windows is a perfect square and image_size is divisible', 'validate LwDetrConfig projector_scale_factors containing only supported values 0.5, 1.0, or 2.0', 'initialize an LwDetrModel from LwDetrConfig and access the model configuration via model.config', 'convert an LW-DETR checkpoint to HuggingFace format and save it locally', 'run the LW-DETR checkpoint converter CLI with a model name and output directory', 'get the model configuration for a given LW-DETR model size and training dataset', 'test model outputs by comparing logits, boxes, and loss against expected values', 'get the key mapping for backbone projector sampling layers based on model config', 'create an LwDetrForObjectDetection model for object detection with configurable backbone and decoder', 'build an LwDetrViTBackbone encoder that extracts multi-scale feature maps from input images', 'run forward inference on LwDetrForObjectDetection to get classification logits and predicted bounding boxes', 'test the LwDetrDecoder with multiscale deformable cross-attention and sine positional embeddings', 'review the LwDetrMultiScaleProjector that aggregates multi-scale backbone features into unified query embeddings', 'test the LwDetrDecoder with group DETR technique for faster training convergence and deformable cross-attention']
```

Usage

```
{'convert_lw_detr_checkpoint': 'convert an LW-DETR checkpoint to HuggingFace format and save it locally', 'run_convert_cli': 'run the LW-DETR checkpoint converter CLI with a model name and output directory', 'get_model_config': 'get the model configuration for a given LW-DETR model size and training dataset', 'test_models_outputs': 'test model outputs by comparing logits, boxes, and loss against expected values', 'get_backbone_projector_sampling_key_mapping': 'get the key mapping for backbone projector sampling layers based on model config'}
```

## File: huggingface_transformers/src/transformers/models/lw_detr/modeling_lw_detr.py

Prompts

```
['create an LwDetrViTConfig instance with custom window blocks, image size, and position embeddings', 'create an LwDetrConfig instance with custom backbone, decoder heads, and number of queries', 'validate LwDetrViTConfig architecture ensuring num_windows is a perfect square and image_size is divisible', 'validate LwDetrConfig projector_scale_factors containing only supported values 0.5, 1.0, or 2.0', 'initialize an LwDetrModel from LwDetrConfig and access the model configuration via model.config', 'convert an LW-DETR checkpoint to HuggingFace format and save it locally', 'run the LW-DETR checkpoint converter CLI with a model name and output directory', 'get the model configuration for a given LW-DETR model size and training dataset', 'test model outputs by comparing logits, boxes, and loss against expected values', 'get the key mapping for backbone projector sampling layers based on model config', 'create an LwDetrForObjectDetection model for object detection with configurable backbone and decoder', 'build an LwDetrViTBackbone encoder that extracts multi-scale feature maps from input images', 'run forward inference on LwDetrForObjectDetection to get classification logits and predicted bounding boxes', 'test the LwDetrDecoder with multiscale deformable cross-attention and sine positional embeddings', 'review the LwDetrMultiScaleProjector that aggregates multi-scale backbone features into unified query embeddings', 'test the LwDetrDecoder with group DETR technique for faster training convergence and deformable cross-attention']
```

Usage

```
{'create_lwdetr_object_detection_model': 'create an LwDetrForObjectDetection model for object detection with configurable backbone and decoder', 'build_lwdetr_backbone_encoder': 'build an LwDetrViTBackbone encoder that extracts multi-scale feature maps from input images', 'run_lwdetr_forward_inference': 'run forward inference on LwDetrForObjectDetection to get classification logits and predicted bounding boxes', 'test_lwdetr_decoder_with_cross_attention': 'test the LwDetrDecoder with multiscale deformable cross-attention and sine positional embeddings', 'review_lwdetr_multi_scale_projector': 'review the LwDetrMultiScaleProjector that aggregates multi-scale backbone features into unified query embeddings'}
```

## File: huggingface_transformers/src/transformers/models/lw_detr/modular_lw_detr.py

Prompts

```
['create an LwDetrViTConfig instance with custom window blocks, image size, and position embeddings', 'create an LwDetrConfig instance with custom backbone, decoder heads, and number of queries', 'validate LwDetrViTConfig architecture ensuring num_windows is a perfect square and image_size is divisible', 'validate LwDetrConfig projector_scale_factors containing only supported values 0.5, 1.0, or 2.0', 'initialize an LwDetrModel from LwDetrConfig and access the model configuration via model.config', 'convert an LW-DETR checkpoint to HuggingFace format and save it locally', 'run the LW-DETR checkpoint converter CLI with a model name and output directory', 'get the model configuration for a given LW-DETR model size and training dataset', 'test model outputs by comparing logits, boxes, and loss against expected values', 'get the key mapping for backbone projector sampling layers based on model config', 'create an LwDetrForObjectDetection model for object detection with configurable backbone and decoder', 'build an LwDetrViTBackbone encoder that extracts multi-scale feature maps from input images', 'run forward inference on LwDetrForObjectDetection to get classification logits and predicted bounding boxes', 'test the LwDetrDecoder with multiscale deformable cross-attention and sine positional embeddings', 'review the LwDetrMultiScaleProjector that aggregates multi-scale backbone features into unified query embeddings', 'test the LwDetrDecoder with group DETR technique for faster training convergence and deformable cross-attention']
```

Usage

```
{'create_lwdetr_object_detection_model': 'create an LwDetrForObjectDetection model for COCO-style object detection with classification and bounding box heads', 'build_lwdetr_backbone_encoder': 'build an LwDetrViTBackbone with windowed ViT encoder that extracts multi-scale feature maps from pixel values', 'run_lwdetr_forward_inference': 'run forward inference on LwDetrModel to get decoder hidden states, reference points, and encoder outputs', 'test_lwdetr_decoder_with_group_detr': 'test the LwDetrDecoder with group DETR technique for faster training convergence and deformable cross-attention', 'review_lwdetr_multi_scale_projector': 'review the LwDetrMultiScaleProjector that aggregates multi-scale backbone features into unified query embeddings'}
```

