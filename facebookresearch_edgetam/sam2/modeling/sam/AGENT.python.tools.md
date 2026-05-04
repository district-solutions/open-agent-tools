# Agent Python Tools

- repo: facebookresearch/edgetam
- repo_uri: https://github.com/facebookresearch/edgetam

## File: facebookresearch_edgetam/sam2/modeling/sam/mask_decoder.py

Prompts

```
['build a MaskDecoder with a transformer module to predict segmentation masks from image and prompt embeddings', 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flags', 'test the MaskDecoder predict_masks method to verify mask and IoU predictions from transformer output', 'review the MaskDecoder _dynamic_multimask_via_stability method that falls back to best multimask when single mask stability is low', 'summarize the MaskDecoder _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds', 'build a PromptEncoder module to encode point, box, and mask prompts for SAM mask decoder input', 'embed point prompts with coordinates and labels into sparse embeddings using the PromptEncoder', 'embed box prompts with corner coordinates into sparse embeddings using the PromptEncoder', 'embed mask inputs through the mask downscaling conv layers into dense embeddings', 'get the dense positional encoding tensor for the image embedding size from the PromptEncoder', 'build a TwoWayTransformer decoder that attends to an image embedding using query point embeddings', 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run the Attention layer forward pass with query, key, and value tensors using scaled dot-product attention', 'review the RoPEAttention class that applies rotary position encoding before scaled dot-product attention', 'test the RoPEAttentionv2 class with separate query and key rotary position encoding frequency tensors']
```

Usage

```
{'build_mask_decoder': 'build a MaskDecoder with a transformer module to predict segmentation masks from image and prompt embeddings', 'run_mask_decoder_forward': 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flags', 'test_predict_masks': 'test the MaskDecoder predict_masks method to verify mask and IoU predictions from transformer output', 'review_dynamic_multimask_via_stability': 'review the MaskDecoder _dynamic_multimask_via_stability method that falls back to best multimask when single mask stability is low', 'summarize_get_stability_scores': 'summarize the MaskDecoder _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds'}
```

## File: facebookresearch_edgetam/sam2/modeling/sam/prompt_encoder.py

Prompts

```
['build a MaskDecoder with a transformer module to predict segmentation masks from image and prompt embeddings', 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flags', 'test the MaskDecoder predict_masks method to verify mask and IoU predictions from transformer output', 'review the MaskDecoder _dynamic_multimask_via_stability method that falls back to best multimask when single mask stability is low', 'summarize the MaskDecoder _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds', 'build a PromptEncoder module to encode point, box, and mask prompts for SAM mask decoder input', 'embed point prompts with coordinates and labels into sparse embeddings using the PromptEncoder', 'embed box prompts with corner coordinates into sparse embeddings using the PromptEncoder', 'embed mask inputs through the mask downscaling conv layers into dense embeddings', 'get the dense positional encoding tensor for the image embedding size from the PromptEncoder', 'build a TwoWayTransformer decoder that attends to an image embedding using query point embeddings', 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run the Attention layer forward pass with query, key, and value tensors using scaled dot-product attention', 'review the RoPEAttention class that applies rotary position encoding before scaled dot-product attention', 'test the RoPEAttentionv2 class with separate query and key rotary position encoding frequency tensors']
```

Usage

```
{'build_prompt_encoder': 'build a PromptEncoder module to encode point, box, and mask prompts for SAM mask decoder input', 'embed_points': 'embed point prompts with coordinates and labels into sparse embeddings using the PromptEncoder', 'embed_boxes': 'embed box prompts with corner coordinates into sparse embeddings using the PromptEncoder', 'embed_masks': 'embed mask inputs through the mask downscaling conv layers into dense embeddings', 'get_dense_pe': 'get the dense positional encoding tensor for the image embedding size from the PromptEncoder'}
```

## File: facebookresearch_edgetam/sam2/modeling/sam/transformer.py

Prompts

```
['build a MaskDecoder with a transformer module to predict segmentation masks from image and prompt embeddings', 'run the MaskDecoder forward pass with image embeddings, prompt embeddings, and multimask output flags', 'test the MaskDecoder predict_masks method to verify mask and IoU predictions from transformer output', 'review the MaskDecoder _dynamic_multimask_via_stability method that falls back to best multimask when single mask stability is low', 'summarize the MaskDecoder _get_stability_scores method that computes mask stability via IoU between upper and lower thresholds', 'build a PromptEncoder module to encode point, box, and mask prompts for SAM mask decoder input', 'embed point prompts with coordinates and labels into sparse embeddings using the PromptEncoder', 'embed box prompts with corner coordinates into sparse embeddings using the PromptEncoder', 'embed mask inputs through the mask downscaling conv layers into dense embeddings', 'get the dense positional encoding tensor for the image embedding size from the PromptEncoder', 'build a TwoWayTransformer decoder that attends to an image embedding using query point embeddings', 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run the Attention layer forward pass with query, key, and value tensors using scaled dot-product attention', 'review the RoPEAttention class that applies rotary position encoding before scaled dot-product attention', 'test the RoPEAttentionv2 class with separate query and key rotary position encoding frequency tensors']
```

Usage

```
{'build_TwoWayTransformer': 'build a TwoWayTransformer decoder that attends to an image embedding using query point embeddings', 'create_TwoWayAttentionBlock': 'create a TwoWayAttentionBlock with self-attention, cross-attention, and MLP layers for sparse and dense inputs', 'run_Attention_forward': 'run the Attention layer forward pass with query, key, and value tensors using scaled dot-product attention', 'review_RoPEAttention': 'review the RoPEAttention class that applies rotary position encoding before scaled dot-product attention', 'test_RoPEAttentionv2': 'test the RoPEAttentionv2 class with separate query and key rotary position encoding frequency tensors'}
```

