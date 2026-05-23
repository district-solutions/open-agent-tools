# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/clip/clip.py

Prompts

```
['build a CLIP model with vision backbone, text backbone, tokenizer, and projection config dicts', 'extract normalized image latent features from a batch of input image tensors using CLIP', 'extract normalized text latent features from tokenized text input using the CLIP text transformer', 'compute cosine similarity logits between image and text feature pairs using CLIP extract_feat', 'predict zero-shot image classification labels by comparing image features against prepared text prototype embeddings', 'build a CLIPTransformer with specified width, layers, and attention heads for visual or text branches', 'run the CLIPTransformer forward pass to get output features, attention weights, and intermediate layer outputs', 'build a CLIPProjection neck module with input and output channel dimensions for feature projection', 'run the CLIPProjection forward pass to project backbone features into the target embedding space', 'review the CLIPTransformer and CLIPProjection classes for CLIP model visual and text branch implementations']
```

Usage

```
{'build_CLIP_model': 'build a CLIP model with vision backbone, text backbone, tokenizer, and projection config dicts', 'extract_image_features': 'extract normalized image latent features from a batch of input image tensors using CLIP', 'extract_text_features': 'extract normalized text latent features from tokenized text input using the CLIP text transformer', 'compute_image_text_similarity': 'compute cosine similarity logits between image and text feature pairs using CLIP extract_feat', 'predict_zeroshot_classification': 'predict zero-shot image classification labels by comparing image features against prepared text prototype embeddings'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/clip/clip_transformer.py

Prompts

```
['build a CLIP model with vision backbone, text backbone, tokenizer, and projection config dicts', 'extract normalized image latent features from a batch of input image tensors using CLIP', 'extract normalized text latent features from tokenized text input using the CLIP text transformer', 'compute cosine similarity logits between image and text feature pairs using CLIP extract_feat', 'predict zero-shot image classification labels by comparing image features against prepared text prototype embeddings', 'build a CLIPTransformer with specified width, layers, and attention heads for visual or text branches', 'run the CLIPTransformer forward pass to get output features, attention weights, and intermediate layer outputs', 'build a CLIPProjection neck module with input and output channel dimensions for feature projection', 'run the CLIPProjection forward pass to project backbone features into the target embedding space', 'review the CLIPTransformer and CLIPProjection classes for CLIP model visual and text branch implementations']
```

Usage

```
{'build_CLIPTransformer': 'build a CLIPTransformer with specified width, layers, and attention heads for visual or text branches', 'run_CLIPTransformer_forward': 'run the CLIPTransformer forward pass to get output features, attention weights, and intermediate layer outputs', 'build_CLIPProjection': 'build a CLIPProjection neck module with input and output channel dimensions for feature projection', 'run_CLIPProjection_forward': 'run the CLIPProjection forward pass to project backbone features into the target embedding space', 'review_CLIPTransformer_CLIPProjection': 'review the CLIPTransformer and CLIPProjection classes for CLIP model visual and text branch implementations'}
```

