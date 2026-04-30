# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vit_msn/convert_msn_to_pytorch.py

Prompts

```
["convert a ViT MSN checkpoint from Facebook's repository to a HuggingFace PyTorch model format", 'create a list of key rename mappings between the original MSN checkpoint and HuggingFace ViTMSN model state dict', 'split the combined query-key-value projection matrix into separate attention heads for each encoder layer', 'remove the self-supervised projection head weights from a state dict for downstream task use', 'remove the classification head weights from a state dict to convert to a base model', 'build a forward pass using ViTMSNModel with pixel values and optional masked positions', 'create a ViTMSNForImageClassification model with a classifier head for image classification', 'test ViTMSNEmbeddings with mask tokens to replace masked image patches', 'review the interpolate_pos_encoding method for dynamic image resolution support', 'run eager_attention_forward with query, key, value tensors and attention mask']
```

Usage

```
{'convert_vit_msn_checkpoint': "convert a ViT MSN checkpoint from Facebook's repository to a HuggingFace PyTorch model format", 'create_rename_keys': 'create a list of key rename mappings between the original MSN checkpoint and HuggingFace ViTMSN model state dict', 'read_in_q_k_v': 'split the combined query-key-value projection matrix into separate attention heads for each encoder layer', 'remove_projection_head': 'remove the self-supervised projection head weights from a state dict for downstream task use', 'remove_classification_head_': 'remove the classification head weights from a state dict to convert to a base model'}
```

## File: huggingface_transformers/src/transformers/models/vit_msn/modeling_vit_msn.py

Prompts

```
["convert a ViT MSN checkpoint from Facebook's repository to a HuggingFace PyTorch model format", 'create a list of key rename mappings between the original MSN checkpoint and HuggingFace ViTMSN model state dict', 'split the combined query-key-value projection matrix into separate attention heads for each encoder layer', 'remove the self-supervised projection head weights from a state dict for downstream task use', 'remove the classification head weights from a state dict to convert to a base model', 'build a forward pass using ViTMSNModel with pixel values and optional masked positions', 'create a ViTMSNForImageClassification model with a classifier head for image classification', 'test ViTMSNEmbeddings with mask tokens to replace masked image patches', 'review the interpolate_pos_encoding method for dynamic image resolution support', 'run eager_attention_forward with query, key, value tensors and attention mask']
```

Usage

```
{'build_model_forward_pass': 'build a forward pass using ViTMSNModel with pixel values and optional masked positions', 'create_image_classification_head': 'create a ViTMSNForImageClassification model with a classifier head for image classification', 'test_mask_token_embeddings': 'test ViTMSNEmbeddings with mask tokens to replace masked image patches', 'review_interpolate_pos_encoding': 'review the interpolate_pos_encoding method for dynamic image resolution support', 'run_attention_forward': 'run eager_attention_forward with query, key, value tensors and attention mask'}
```

