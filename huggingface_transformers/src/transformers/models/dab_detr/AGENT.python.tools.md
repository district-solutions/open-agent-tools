# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dab_detr/configuration_dab_detr.py

Prompts

```
['create a DAB-DETR model configuration with default resnet-50 backbone settings', 'build a DAB-DETR configuration with custom encoder layers, decoder layers, and query dimensions', 'test the DabDetrConfig validate_architecture method enforces query_dim equals 4', 'review the DabDetrConfig class and its backbone consolidation with timm default kwargs', 'summarize the DabDetrConfig configuration parameters for initializing a DAB-DETR detection model', 'convert a DAB-DETR original PyTorch checkpoint to HuggingFace format', 'write a DAB-DETR model from original weights to HuggingFace PyTorch format', 'write a ConditionalDetrImageProcessor for COCO detection format', 'convert original DAB-DETR state dict keys to HuggingFace key names', 'run the DAB-DETR checkpoint conversion script from the command line', 'create a DAB-DETR object detection model with backbone and transformer encoder-decoder for COCO detection', 'build a DAB-DETR base model with backbone and encoder-decoder transformer outputting raw hidden states', 'test the DAB-DETR decoder with iterative bounding box refinement and auxiliary loss support', 'refactor the DAB-DETR encoder to add object queries scaled by positional embeddings to self-attention layers', 'review the DAB-DETR sine position embedding that encodes 2D image coordinates using sine and cosine functions']
```

Usage

```
{'create_DabDetrConfig': 'create a DAB-DETR model configuration with default resnet-50 backbone settings', 'build_DabDetrConfig_custom': 'build a DAB-DETR configuration with custom encoder layers, decoder layers, and query dimensions', 'test_validate_architecture': 'test the DabDetrConfig validate_architecture method enforces query_dim equals 4', 'review_DabDetrConfig': 'review the DabDetrConfig class and its backbone consolidation with timm default kwargs', 'summarize_DabDetrConfig': 'summarize the DabDetrConfig configuration parameters for initializing a DAB-DETR detection model'}
```

## File: huggingface_transformers/src/transformers/models/dab_detr/convert_dab_detr_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a DAB-DETR model configuration with default resnet-50 backbone settings', 'build a DAB-DETR configuration with custom encoder layers, decoder layers, and query dimensions', 'test the DabDetrConfig validate_architecture method enforces query_dim equals 4', 'review the DabDetrConfig class and its backbone consolidation with timm default kwargs', 'summarize the DabDetrConfig configuration parameters for initializing a DAB-DETR detection model', 'convert a DAB-DETR original PyTorch checkpoint to HuggingFace format', 'write a DAB-DETR model from original weights to HuggingFace PyTorch format', 'write a ConditionalDetrImageProcessor for COCO detection format', 'convert original DAB-DETR state dict keys to HuggingFace key names', 'run the DAB-DETR checkpoint conversion script from the command line', 'create a DAB-DETR object detection model with backbone and transformer encoder-decoder for COCO detection', 'build a DAB-DETR base model with backbone and encoder-decoder transformer outputting raw hidden states', 'test the DAB-DETR decoder with iterative bounding box refinement and auxiliary loss support', 'refactor the DAB-DETR encoder to add object queries scaled by positional embeddings to self-attention layers', 'review the DAB-DETR sine position embedding that encodes 2D image coordinates using sine and cosine functions']
```

Usage

```
{'convert_dab_detr_checkpoint': 'convert a DAB-DETR original PyTorch checkpoint to HuggingFace format', 'write_model': 'write a DAB-DETR model from original weights to HuggingFace PyTorch format', 'write_image_processor': 'write a ConditionalDetrImageProcessor for COCO detection format', 'convert_old_keys_to_new_keys': 'convert original DAB-DETR state dict keys to HuggingFace key names', 'convert_dab_detr_checkpoint_cli': 'run the DAB-DETR checkpoint conversion script from the command line'}
```

## File: huggingface_transformers/src/transformers/models/dab_detr/modeling_dab_detr.py

Prompts

```
['create a DAB-DETR model configuration with default resnet-50 backbone settings', 'build a DAB-DETR configuration with custom encoder layers, decoder layers, and query dimensions', 'test the DabDetrConfig validate_architecture method enforces query_dim equals 4', 'review the DabDetrConfig class and its backbone consolidation with timm default kwargs', 'summarize the DabDetrConfig configuration parameters for initializing a DAB-DETR detection model', 'convert a DAB-DETR original PyTorch checkpoint to HuggingFace format', 'write a DAB-DETR model from original weights to HuggingFace PyTorch format', 'write a ConditionalDetrImageProcessor for COCO detection format', 'convert original DAB-DETR state dict keys to HuggingFace key names', 'run the DAB-DETR checkpoint conversion script from the command line', 'create a DAB-DETR object detection model with backbone and transformer encoder-decoder for COCO detection', 'build a DAB-DETR base model with backbone and encoder-decoder transformer outputting raw hidden states', 'test the DAB-DETR decoder with iterative bounding box refinement and auxiliary loss support', 'refactor the DAB-DETR encoder to add object queries scaled by positional embeddings to self-attention layers', 'review the DAB-DETR sine position embedding that encodes 2D image coordinates using sine and cosine functions']
```

Usage

```
{'create_DabDetrForObjectDetection': 'create a DAB-DETR object detection model with backbone and transformer encoder-decoder for COCO detection', 'build_DabDetrModel': 'build a DAB-DETR base model with backbone and encoder-decoder transformer outputting raw hidden states', 'test_DabDetrDecoder': 'test the DAB-DETR decoder with iterative bounding box refinement and auxiliary loss support', 'refactor_DabDetrEncoder': 'refactor the DAB-DETR encoder to add object queries scaled by positional embeddings to self-attention layers', 'review_DabDetrSinePositionEmbedding': 'review the DAB-DETR sine position embedding that encodes 2D image coordinates using sine and cosine functions'}
```

