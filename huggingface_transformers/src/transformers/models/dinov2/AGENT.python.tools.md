# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dinov2/convert_dinov2_to_hf.py

Prompts

```
['convert a DINOv2 checkpoint from Facebook Research to HuggingFace transformers format', 'get a Dinov2Config object for a specified model name and architecture variant', 'create a mapping of state dict key renames from original DINOv2 to HuggingFace structure', 'split a combined qkv projection matrix into separate query, key, and value tensors', 'download and prepare a sample cat image from COCO dataset for model verification', 'build a Dinov2Model transformer that processes image pixel values and returns pooled CLS token embeddings', 'create a Dinov2ForImageClassification model with a classifier head on top of the CLS and mean-pooled patch tokens', 'run the Dinov2Model forward pass on image pixel values to get last hidden state and pooled output', 'build a Dinov2Backbone feature extractor that outputs multi-stage feature maps for DETR and MaskFormer', 'test the Dinov2Embeddings class that constructs CLS token, patch embeddings, and interpolated position encodings']
```

Usage

```
{'convert_dinov2_checkpoint': 'convert a DINOv2 checkpoint from Facebook Research to HuggingFace transformers format', 'get_dinov2_config': 'get a Dinov2Config object for a specified model name and architecture variant', 'create_rename_keys': 'create a mapping of state dict key renames from original DINOv2 to HuggingFace structure', 'read_in_q_k_v': 'split a combined qkv projection matrix into separate query, key, and value tensors', 'prepare_img': 'download and prepare a sample cat image from COCO dataset for model verification'}
```

## File: huggingface_transformers/src/transformers/models/dinov2/modeling_dinov2.py

Prompts

```
['convert a DINOv2 checkpoint from Facebook Research to HuggingFace transformers format', 'get a Dinov2Config object for a specified model name and architecture variant', 'create a mapping of state dict key renames from original DINOv2 to HuggingFace structure', 'split a combined qkv projection matrix into separate query, key, and value tensors', 'download and prepare a sample cat image from COCO dataset for model verification', 'build a Dinov2Model transformer that processes image pixel values and returns pooled CLS token embeddings', 'create a Dinov2ForImageClassification model with a classifier head on top of the CLS and mean-pooled patch tokens', 'run the Dinov2Model forward pass on image pixel values to get last hidden state and pooled output', 'build a Dinov2Backbone feature extractor that outputs multi-stage feature maps for DETR and MaskFormer', 'test the Dinov2Embeddings class that constructs CLS token, patch embeddings, and interpolated position encodings']
```

Usage

```
{'build_dinov2_model': 'build a Dinov2Model transformer that processes image pixel values and returns pooled CLS token embeddings', 'create_image_classifier': 'create a Dinov2ForImageClassification model with a classifier head on top of the CLS and mean-pooled patch tokens', 'run_dinov2_forward': 'run the Dinov2Model forward pass on image pixel values to get last hidden state and pooled output', 'build_dinov2_backbone': 'build a Dinov2Backbone feature extractor that outputs multi-stage feature maps for DETR and MaskFormer', 'test_dinov2_embeddings': 'test the Dinov2Embeddings class that constructs CLS token, patch embeddings, and interpolated position encodings'}
```

