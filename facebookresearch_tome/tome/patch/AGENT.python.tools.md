# Agent Python Tools

- repo: facebookresearch/tome
- repo_uri: https://github.com/facebookresearch/tome

## File: facebookresearch_tome/tome/patch/mae.py

Prompts

```
['apply ToMe token merging to a MAE VisionTransformer model by swapping its class and submodule classes', 'create a ToMe-patched VisionTransformer subclass with modified forward and forward_features methods for MAE', 'apply ToMe to a MAE model with source tracing enabled for token visualization', 'apply ToMe to a MAE model with attention propagation disabled as recommended for MAE', 'create a ToMe VisionTransformer class that performs global average pooling proportional to token size', 'apply ToMe patch to a SWAG vision transformer model for token merging during inference', 'create a ToMeBlock class that applies token merging between attention and MLP layers', 'create a ToMeVisionTransformer class that initializes reduction ratios and token tracking for a transformer', 'create a ToMeEncoder class that permutes encoder dimensions to batch first format', 'run proportional multihead attention that returns attention output and key mean for token merging', 'apply ToMe token merging patch to a timm VisionTransformer model for accelerated inference', 'run the ToMeBlock forward pass to merge tokens using bipartite soft matching between attention and MLP', 'run the ToMeAttention forward pass with proportional attention and return key mean metric for merging', 'create a ToMeVisionTransformer subclass that initializes token reduction ratio, size, and source tracking', 'review the apply_patch function parameters trace_source and prop_attn for visualization and proportional attention control']
```

Usage

```
{'apply_patch_mae_model': 'apply ToMe token merging to a MAE VisionTransformer model by swapping its class and submodule classes', 'make_tome_class_transformer': 'create a ToMe-patched VisionTransformer subclass with modified forward and forward_features methods for MAE', 'apply_patch_trace_source': 'apply ToMe to a MAE model with source tracing enabled for token visualization', 'apply_patch_prop_attn': 'apply ToMe to a MAE model with attention propagation disabled as recommended for MAE', 'make_tome_class_global_pool': 'create a ToMe VisionTransformer class that performs global average pooling proportional to token size'}
```

## File: facebookresearch_tome/tome/patch/swag.py

Prompts

```
['apply ToMe token merging to a MAE VisionTransformer model by swapping its class and submodule classes', 'create a ToMe-patched VisionTransformer subclass with modified forward and forward_features methods for MAE', 'apply ToMe to a MAE model with source tracing enabled for token visualization', 'apply ToMe to a MAE model with attention propagation disabled as recommended for MAE', 'create a ToMe VisionTransformer class that performs global average pooling proportional to token size', 'apply ToMe patch to a SWAG vision transformer model for token merging during inference', 'create a ToMeBlock class that applies token merging between attention and MLP layers', 'create a ToMeVisionTransformer class that initializes reduction ratios and token tracking for a transformer', 'create a ToMeEncoder class that permutes encoder dimensions to batch first format', 'run proportional multihead attention that returns attention output and key mean for token merging', 'apply ToMe token merging patch to a timm VisionTransformer model for accelerated inference', 'run the ToMeBlock forward pass to merge tokens using bipartite soft matching between attention and MLP', 'run the ToMeAttention forward pass with proportional attention and return key mean metric for merging', 'create a ToMeVisionTransformer subclass that initializes token reduction ratio, size, and source tracking', 'review the apply_patch function parameters trace_source and prop_attn for visualization and proportional attention control']
```

Usage

```
{'apply_patch_SWAG_transformer': 'apply ToMe patch to a SWAG vision transformer model for token merging during inference', 'make_block_class_ToMeBlock': 'create a ToMeBlock class that applies token merging between attention and MLP layers', 'make_transformer_class_ToMeVisionTransformer': 'create a ToMeVisionTransformer class that initializes reduction ratios and token tracking for a transformer', 'make_encoder_class_ToMeEncoder': 'create a ToMeEncoder class that permutes encoder dimensions to batch first format', 'ToMeAttention_forward': 'run proportional multihead attention that returns attention output and key mean for token merging'}
```

## File: facebookresearch_tome/tome/patch/timm.py

Prompts

```
['apply ToMe token merging to a MAE VisionTransformer model by swapping its class and submodule classes', 'create a ToMe-patched VisionTransformer subclass with modified forward and forward_features methods for MAE', 'apply ToMe to a MAE model with source tracing enabled for token visualization', 'apply ToMe to a MAE model with attention propagation disabled as recommended for MAE', 'create a ToMe VisionTransformer class that performs global average pooling proportional to token size', 'apply ToMe patch to a SWAG vision transformer model for token merging during inference', 'create a ToMeBlock class that applies token merging between attention and MLP layers', 'create a ToMeVisionTransformer class that initializes reduction ratios and token tracking for a transformer', 'create a ToMeEncoder class that permutes encoder dimensions to batch first format', 'run proportional multihead attention that returns attention output and key mean for token merging', 'apply ToMe token merging patch to a timm VisionTransformer model for accelerated inference', 'run the ToMeBlock forward pass to merge tokens using bipartite soft matching between attention and MLP', 'run the ToMeAttention forward pass with proportional attention and return key mean metric for merging', 'create a ToMeVisionTransformer subclass that initializes token reduction ratio, size, and source tracking', 'review the apply_patch function parameters trace_source and prop_attn for visualization and proportional attention control']
```

Usage

```
{'apply_patch_to_vision_transformer': 'apply ToMe token merging patch to a timm VisionTransformer model for accelerated inference', 'use_TomeBlock_forward': 'run the ToMeBlock forward pass to merge tokens using bipartite soft matching between attention and MLP', 'use_TomeAttention_forward': 'run the ToMeAttention forward pass with proportional attention and return key mean metric for merging', 'use_make_tome_class': 'create a ToMeVisionTransformer subclass that initializes token reduction ratio, size, and source tracking', 'review_apply_patch_parameters': 'review the apply_patch function parameters trace_source and prop_attn for visualization and proportional attention control'}
```

