# Agent Python Tools

- repo: facebookresearch/meru
- repo_uri: https://github.com/facebookresearch/meru

## File: facebookresearch_meru/meru/encoders/image_encoders.py

Prompts

```
['build a Vision Transformer image encoder from timm with a specified architecture and global pooling strategy', 'build a ViT encoder using fixed 2D sine-cosine position embeddings instead of learned ones', 'build a ViT image encoder with gradient checkpointing enabled to reduce memory usage', 'create a small Vision Transformer with 12 heads as used by MoCo-v3 for better performance', 'build a ViT encoder using global average pooling instead of the CLS token for feature extraction', 'build a TransformerTextEncoder with arch L12_W512_A8 vocab 49408 and context length 77', 'create a _TransformerBlock with d_model 512 and n_head 8 for self-attention and MLP', 'encode tokenized text sequences through the TransformerTextEncoder forward pass to get textual features', 'enable gradient checkpointing on TransformerTextEncoder to reduce memory during training', 'parse an architecture string like L12_W512_A8 to extract layers width and attention heads']
```

Usage

```
{'build_vit_encoder': 'build a Vision Transformer image encoder from timm with a specified architecture and global pooling strategy', 'build_vit_with_sincos_pos': 'build a ViT encoder using fixed 2D sine-cosine position embeddings instead of learned ones', 'build_vit_with_grad_checkpointing': 'build a ViT image encoder with gradient checkpointing enabled to reduce memory usage', 'create_mocov3_vit_small': 'create a small Vision Transformer with 12 heads as used by MoCo-v3 for better performance', 'build_vit_avg_pooling': 'build a ViT encoder using global average pooling instead of the CLS token for feature extraction'}
```

## File: facebookresearch_meru/meru/encoders/text_encoders.py

Prompts

```
['build a Vision Transformer image encoder from timm with a specified architecture and global pooling strategy', 'build a ViT encoder using fixed 2D sine-cosine position embeddings instead of learned ones', 'build a ViT image encoder with gradient checkpointing enabled to reduce memory usage', 'create a small Vision Transformer with 12 heads as used by MoCo-v3 for better performance', 'build a ViT encoder using global average pooling instead of the CLS token for feature extraction', 'build a TransformerTextEncoder with arch L12_W512_A8 vocab 49408 and context length 77', 'create a _TransformerBlock with d_model 512 and n_head 8 for self-attention and MLP', 'encode tokenized text sequences through the TransformerTextEncoder forward pass to get textual features', 'enable gradient checkpointing on TransformerTextEncoder to reduce memory during training', 'parse an architecture string like L12_W512_A8 to extract layers width and attention heads']
```

Usage

```
{'build_transformer_text_encoder': 'build a TransformerTextEncoder with arch L12_W512_A8 vocab 49408 and context length 77', 'create_transformer_block': 'create a _TransformerBlock with d_model 512 and n_head 8 for self-attention and MLP', 'encode_text_tokens': 'encode tokenized text sequences through the TransformerTextEncoder forward pass to get textual features', 'enable_grad_checkpointing': 'enable gradient checkpointing on TransformerTextEncoder to reduce memory during training', 'parse_architecture_string': 'parse an architecture string like L12_W512_A8 to extract layers width and attention heads'}
```

