# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vit/convert_dino_to_pytorch.py

Prompts

```
['convert a DINO-trained ViT checkpoint to HuggingFace PyTorch format', 'create key renaming mappings from DINO checkpoint keys to HuggingFace ViT keys', "split DINO's combined qkv projection matrix into separate query, key, and value weights", 'remove classification head weights from a DINO state dictionary', 'download a sample COCO image to verify converted model outputs', 'convert a timm ViT checkpoint to a HuggingFace PyTorch model and save it to a directory', 'create a list of weight key mappings to rename timm ViT state dict keys to HuggingFace ViT format', "split timm's combined qkv projection weights into separate query, key, and value weights for each encoder layer", 'remove classification head weights from a timm state dict for base model conversion', 'run the convert_vit_timm_to_pytorch script via argparse to convert a timm ViT model to HuggingFace format', 'build a ViT model forward pass that encodes pixel values into hidden states with optional pooling', 'create ViT embeddings that add CLS token, patch embeddings, and interpolated position encodings to image tensors', 'test the ViT image classification head that pools the CLS token through a linear classifier layer', 'run masked image modeling that reconstructs masked patches using a SimMIM-style decoder on ViT hidden states', 'review the ViT self-attention layer with QKV projections and configurable attention backend selection']
```

Usage

```
{'convert_dino_vit_checkpoint': 'convert a DINO-trained ViT checkpoint to HuggingFace PyTorch format', 'create_rename_keys_for_vit': 'create key renaming mappings from DINO checkpoint keys to HuggingFace ViT keys', 'read_in_q_k_v_from_state_dict': "split DINO's combined qkv projection matrix into separate query, key, and value weights", 'remove_classification_head_from_state_dict': 'remove classification head weights from a DINO state dictionary', 'prepare_test_image_for_verification': 'download a sample COCO image to verify converted model outputs'}
```

## File: huggingface_transformers/src/transformers/models/vit/convert_vit_timm_to_pytorch.py

Prompts

```
['convert a DINO-trained ViT checkpoint to HuggingFace PyTorch format', 'create key renaming mappings from DINO checkpoint keys to HuggingFace ViT keys', "split DINO's combined qkv projection matrix into separate query, key, and value weights", 'remove classification head weights from a DINO state dictionary', 'download a sample COCO image to verify converted model outputs', 'convert a timm ViT checkpoint to a HuggingFace PyTorch model and save it to a directory', 'create a list of weight key mappings to rename timm ViT state dict keys to HuggingFace ViT format', "split timm's combined qkv projection weights into separate query, key, and value weights for each encoder layer", 'remove classification head weights from a timm state dict for base model conversion', 'run the convert_vit_timm_to_pytorch script via argparse to convert a timm ViT model to HuggingFace format', 'build a ViT model forward pass that encodes pixel values into hidden states with optional pooling', 'create ViT embeddings that add CLS token, patch embeddings, and interpolated position encodings to image tensors', 'test the ViT image classification head that pools the CLS token through a linear classifier layer', 'run masked image modeling that reconstructs masked patches using a SimMIM-style decoder on ViT hidden states', 'review the ViT self-attention layer with QKV projections and configurable attention backend selection']
```

Usage

```
{'convert_vit_checkpoint': 'convert a timm ViT checkpoint to a HuggingFace PyTorch model and save it to a directory', 'create_rename_keys': 'create a list of weight key mappings to rename timm ViT state dict keys to HuggingFace ViT format', 'read_in_q_k_v': "split timm's combined qkv projection weights into separate query, key, and value weights for each encoder layer", 'remove_classification_head_': 'remove classification head weights from a timm state dict for base model conversion', 'run_convert_cli': 'run the convert_vit_timm_to_pytorch script via argparse to convert a timm ViT model to HuggingFace format'}
```

## File: huggingface_transformers/src/transformers/models/vit/modeling_vit.py

Prompts

```
['convert a DINO-trained ViT checkpoint to HuggingFace PyTorch format', 'create key renaming mappings from DINO checkpoint keys to HuggingFace ViT keys', "split DINO's combined qkv projection matrix into separate query, key, and value weights", 'remove classification head weights from a DINO state dictionary', 'download a sample COCO image to verify converted model outputs', 'convert a timm ViT checkpoint to a HuggingFace PyTorch model and save it to a directory', 'create a list of weight key mappings to rename timm ViT state dict keys to HuggingFace ViT format', "split timm's combined qkv projection weights into separate query, key, and value weights for each encoder layer", 'remove classification head weights from a timm state dict for base model conversion', 'run the convert_vit_timm_to_pytorch script via argparse to convert a timm ViT model to HuggingFace format', 'build a ViT model forward pass that encodes pixel values into hidden states with optional pooling', 'create ViT embeddings that add CLS token, patch embeddings, and interpolated position encodings to image tensors', 'test the ViT image classification head that pools the CLS token through a linear classifier layer', 'run masked image modeling that reconstructs masked patches using a SimMIM-style decoder on ViT hidden states', 'review the ViT self-attention layer with QKV projections and configurable attention backend selection']
```

Usage

```
{'build_vit_model_forward': 'build a ViT model forward pass that encodes pixel values into hidden states with optional pooling', 'create_vit_embeddings_with_position_encoding': 'create ViT embeddings that add CLS token, patch embeddings, and interpolated position encodings to image tensors', 'test_vit_image_classification_head': 'test the ViT image classification head that pools the CLS token through a linear classifier layer', 'run_vit_masked_image_modeling': 'run masked image modeling that reconstructs masked patches using a SimMIM-style decoder on ViT hidden states', 'review_vit_self_attention_layer': 'review the ViT self-attention layer with QKV projections and configurable attention backend selection'}
```

