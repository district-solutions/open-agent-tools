# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/deit/convert_deit_timm_to_pytorch.py

Prompts

```
['convert a DeiT timm checkpoint to a HuggingFace PyTorch model and save to a directory', 'create a list of key renaming pairs from timm state dict keys to HuggingFace DeiT state dict keys', "split timm's combined qkv weight matrix into separate query, key, and value weight tensors", 'download and return a sample COCO validation image for verifying converted model outputs', 'run the DeiT timm-to-HuggingFace conversion script via command line with model name and output path', 'build a DeiT model for image classification with a linear head on the CLS token', 'create a DeiT transformer base model that extracts patch embeddings and encodes image features', 'run DeiT masked image modeling to reconstruct masked patches using a SimMIM decoder', 'test DeiT classification with teacher distillation that averages CLS and distillation token logits', 'review DeiT embeddings and its position encoding interpolation for higher resolution images']
```

Usage

```
{'convert_deit_checkpoint': 'convert a DeiT timm checkpoint to a HuggingFace PyTorch model and save to a directory', 'create_rename_keys': 'create a list of key renaming pairs from timm state dict keys to HuggingFace DeiT state dict keys', 'read_in_q_k_v': "split timm's combined qkv weight matrix into separate query, key, and value weight tensors", 'prepare_img': 'download and return a sample COCO validation image for verifying converted model outputs', 'run_deit_conversion_cli': 'run the DeiT timm-to-HuggingFace conversion script via command line with model name and output path'}
```

## File: huggingface_transformers/src/transformers/models/deit/modeling_deit.py

Prompts

```
['convert a DeiT timm checkpoint to a HuggingFace PyTorch model and save to a directory', 'create a list of key renaming pairs from timm state dict keys to HuggingFace DeiT state dict keys', "split timm's combined qkv weight matrix into separate query, key, and value weight tensors", 'download and return a sample COCO validation image for verifying converted model outputs', 'run the DeiT timm-to-HuggingFace conversion script via command line with model name and output path', 'build a DeiT model for image classification with a linear head on the CLS token', 'create a DeiT transformer base model that extracts patch embeddings and encodes image features', 'run DeiT masked image modeling to reconstruct masked patches using a SimMIM decoder', 'test DeiT classification with teacher distillation that averages CLS and distillation token logits', 'review DeiT embeddings and its position encoding interpolation for higher resolution images']
```

Usage

```
{'build_deit_image_classifier': 'build a DeiT model for image classification with a linear head on the CLS token', 'create_deit_base_model': 'create a DeiT transformer base model that extracts patch embeddings and encodes image features', 'run_deit_masked_image_modeling': 'run DeiT masked image modeling to reconstruct masked patches using a SimMIM decoder', 'test_deit_distillation_classification': 'test DeiT classification with teacher distillation that averages CLS and distillation token logits', 'review_deit_embeddings_interpolation': 'review DeiT embeddings and its position encoding interpolation for higher resolution images'}
```

