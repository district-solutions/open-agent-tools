# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/sam2/modeling/sam/mask_decoder.py

Prompts

```
['build a MaskDecoder instance with a transformer, transformer_dim, and multimask output configuration', 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flag', 'call predict_masks to get mask logits, IoU predictions, mask tokens, and object score logits', 'review the _dynamic_multimask_via_stability method that falls back to best multimask output when single mask stability is low', 'summarize the _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds', 'build a PromptEncoder instance with embed_dim, image_embedding_size, input_image_size, and mask_in_chans parameters', 'embed point prompts with coordinates and labels using the _embed_points method of PromptEncoder', 'embed box prompts by passing a tensor of box coordinates to the _embed_boxes method', 'embed mask inputs by passing a mask tensor through the _embed_masks method of PromptEncoder', 'run the PromptEncoder forward pass with points, boxes, and masks to get sparse and dense embeddings', 'build a TwoWayTransformer decoder that attends to an input image using supplied query point embeddings', 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run the Attention layer forward pass with query, key, and value tensors using scaled dot product attention', 'review the RoPEAttention class that extends Attention with rotary position encoding for cross-attention to memories', 'test the TwoWayTransformer forward pass with image embedding, image positional encoding, and point embedding tensors']
```

Usage

```
{'build_mask_decoder': 'build a MaskDecoder instance with a transformer, transformer_dim, and multimask output configuration', 'run_mask_decoder_forward': 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flag', 'predict_masks': 'call predict_masks to get mask logits, IoU predictions, mask tokens, and object score logits', 'review_dynamic_multimask_via_stability': 'review the _dynamic_multimask_via_stability method that falls back to best multimask output when single mask stability is low', 'summarize_get_stability_scores': 'summarize the _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds'}
```

## File: facebookresearch_sam2/sam2/modeling/sam/prompt_encoder.py

Prompts

```
['build a MaskDecoder instance with a transformer, transformer_dim, and multimask output configuration', 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flag', 'call predict_masks to get mask logits, IoU predictions, mask tokens, and object score logits', 'review the _dynamic_multimask_via_stability method that falls back to best multimask output when single mask stability is low', 'summarize the _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds', 'build a PromptEncoder instance with embed_dim, image_embedding_size, input_image_size, and mask_in_chans parameters', 'embed point prompts with coordinates and labels using the _embed_points method of PromptEncoder', 'embed box prompts by passing a tensor of box coordinates to the _embed_boxes method', 'embed mask inputs by passing a mask tensor through the _embed_masks method of PromptEncoder', 'run the PromptEncoder forward pass with points, boxes, and masks to get sparse and dense embeddings', 'build a TwoWayTransformer decoder that attends to an input image using supplied query point embeddings', 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run the Attention layer forward pass with query, key, and value tensors using scaled dot product attention', 'review the RoPEAttention class that extends Attention with rotary position encoding for cross-attention to memories', 'test the TwoWayTransformer forward pass with image embedding, image positional encoding, and point embedding tensors']
```

Usage

```
{'build_prompt_encoder': 'build a PromptEncoder instance with embed_dim, image_embedding_size, input_image_size, and mask_in_chans parameters', 'embed_points': 'embed point prompts with coordinates and labels using the _embed_points method of PromptEncoder', 'embed_boxes': 'embed box prompts by passing a tensor of box coordinates to the _embed_boxes method', 'embed_masks': 'embed mask inputs by passing a mask tensor through the _embed_masks method of PromptEncoder', 'forward_prompt_encoder': 'run the PromptEncoder forward pass with points, boxes, and masks to get sparse and dense embeddings'}
```

## File: facebookresearch_sam2/sam2/modeling/sam/transformer.py

Prompts

```
['build a MaskDecoder instance with a transformer, transformer_dim, and multimask output configuration', 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flag', 'call predict_masks to get mask logits, IoU predictions, mask tokens, and object score logits', 'review the _dynamic_multimask_via_stability method that falls back to best multimask output when single mask stability is low', 'summarize the _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds', 'build a PromptEncoder instance with embed_dim, image_embedding_size, input_image_size, and mask_in_chans parameters', 'embed point prompts with coordinates and labels using the _embed_points method of PromptEncoder', 'embed box prompts by passing a tensor of box coordinates to the _embed_boxes method', 'embed mask inputs by passing a mask tensor through the _embed_masks method of PromptEncoder', 'run the PromptEncoder forward pass with points, boxes, and masks to get sparse and dense embeddings', 'build a TwoWayTransformer decoder that attends to an input image using supplied query point embeddings', 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run the Attention layer forward pass with query, key, and value tensors using scaled dot product attention', 'review the RoPEAttention class that extends Attention with rotary position encoding for cross-attention to memories', 'test the TwoWayTransformer forward pass with image embedding, image positional encoding, and point embedding tensors']
```

Usage

```
{'build_TwoWayTransformer': 'build a TwoWayTransformer decoder that attends to an input image using supplied query point embeddings', 'create_TwoWayAttentionBlock': 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run_Attention_forward': 'run the Attention layer forward pass with query, key, and value tensors using scaled dot product attention', 'review_RoPEAttention': 'review the RoPEAttention class that extends Attention with rotary position encoding for cross-attention to memories', 'test_TwoWayTransformer_forward': 'test the TwoWayTransformer forward pass with image embedding, image positional encoding, and point embedding tensors'}
```

