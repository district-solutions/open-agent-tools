# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/modules/fusions/attention_fusion.py

Prompts

```
['build an AttentionFusionModule that fuses multi-channel embeddings using learned attention weights', 'create an AttentionFusionModule with a custom encoding projection dimension for all channels', 'run a forward pass on the AttentionFusionModule with a dictionary of channel embeddings', 'review how the AttentionFusionModule computes attention weights via a linear layer and softmax', 'refactor the AttentionFusionModule to use a custom default for the encoding projection dimension', 'build a ConcatFusionModule to fuse multimodal embeddings via concatenation along the last dimension', 'create a ConcatFusionModule with a custom projection layer to transform concatenated multimodal embeddings', 'test the ConcatFusionModule forward pass with a dictionary of modality tensors as input', 'review the ConcatFusionModule forward method to verify embeddings are sorted by keys for consistency', 'refactor the ConcatFusionModule to use nn.Identity as the default projection when none is provided', 'build a DeepsetFusionModule to fuse multimodal embeddings using stacking, pooling, and an MLP classifier', 'create a DeepsetFusionWithTransformer that uses a TransformerEncoder as the pooling function for multimodal fusion', 'build a multimodal fusion module using the deepset_transformer helper with configurable transformer layers and attention heads', 'review the get_projection_dim class method to determine the target projection dimension from channel encoder dims', 'test the _pool_features method to verify pooling returns a tensor from the normalized stacked embeddings']
```

Usage

```
{'build_attention_fusion_module': 'build an AttentionFusionModule that fuses multi-channel embeddings using learned attention weights', 'create_fusion_with_projection_dim': 'create an AttentionFusionModule with a custom encoding projection dimension for all channels', 'run_forward_pass': 'run a forward pass on the AttentionFusionModule with a dictionary of channel embeddings', 'review_attention_weights': 'review how the AttentionFusionModule computes attention weights via a linear layer and softmax', 'refactor_fusion_default_dim': 'refactor the AttentionFusionModule to use a custom default for the encoding projection dimension'}
```

## File: facebookresearch_multimodal/torchmultimodal/modules/fusions/concat_fusion.py

Prompts

```
['build an AttentionFusionModule that fuses multi-channel embeddings using learned attention weights', 'create an AttentionFusionModule with a custom encoding projection dimension for all channels', 'run a forward pass on the AttentionFusionModule with a dictionary of channel embeddings', 'review how the AttentionFusionModule computes attention weights via a linear layer and softmax', 'refactor the AttentionFusionModule to use a custom default for the encoding projection dimension', 'build a ConcatFusionModule to fuse multimodal embeddings via concatenation along the last dimension', 'create a ConcatFusionModule with a custom projection layer to transform concatenated multimodal embeddings', 'test the ConcatFusionModule forward pass with a dictionary of modality tensors as input', 'review the ConcatFusionModule forward method to verify embeddings are sorted by keys for consistency', 'refactor the ConcatFusionModule to use nn.Identity as the default projection when none is provided', 'build a DeepsetFusionModule to fuse multimodal embeddings using stacking, pooling, and an MLP classifier', 'create a DeepsetFusionWithTransformer that uses a TransformerEncoder as the pooling function for multimodal fusion', 'build a multimodal fusion module using the deepset_transformer helper with configurable transformer layers and attention heads', 'review the get_projection_dim class method to determine the target projection dimension from channel encoder dims', 'test the _pool_features method to verify pooling returns a tensor from the normalized stacked embeddings']
```

Usage

```
{'build_concat_fusion_module': 'build a ConcatFusionModule to fuse multimodal embeddings via concatenation along the last dimension', 'create_concat_fusion_with_projection': 'create a ConcatFusionModule with a custom projection layer to transform concatenated multimodal embeddings', 'test_concat_fusion_forward': 'test the ConcatFusionModule forward pass with a dictionary of modality tensors as input', 'review_concat_fusion_sorted_keys': 'review the ConcatFusionModule forward method to verify embeddings are sorted by keys for consistency', 'refactor_concat_fusion_identity_projection': 'refactor the ConcatFusionModule to use nn.Identity as the default projection when none is provided'}
```

## File: facebookresearch_multimodal/torchmultimodal/modules/fusions/deepset_fusion.py

Prompts

```
['build an AttentionFusionModule that fuses multi-channel embeddings using learned attention weights', 'create an AttentionFusionModule with a custom encoding projection dimension for all channels', 'run a forward pass on the AttentionFusionModule with a dictionary of channel embeddings', 'review how the AttentionFusionModule computes attention weights via a linear layer and softmax', 'refactor the AttentionFusionModule to use a custom default for the encoding projection dimension', 'build a ConcatFusionModule to fuse multimodal embeddings via concatenation along the last dimension', 'create a ConcatFusionModule with a custom projection layer to transform concatenated multimodal embeddings', 'test the ConcatFusionModule forward pass with a dictionary of modality tensors as input', 'review the ConcatFusionModule forward method to verify embeddings are sorted by keys for consistency', 'refactor the ConcatFusionModule to use nn.Identity as the default projection when none is provided', 'build a DeepsetFusionModule to fuse multimodal embeddings using stacking, pooling, and an MLP classifier', 'create a DeepsetFusionWithTransformer that uses a TransformerEncoder as the pooling function for multimodal fusion', 'build a multimodal fusion module using the deepset_transformer helper with configurable transformer layers and attention heads', 'review the get_projection_dim class method to determine the target projection dimension from channel encoder dims', 'test the _pool_features method to verify pooling returns a tensor from the normalized stacked embeddings']
```

Usage

```
{'build_deepset_fusion_module': 'build a DeepsetFusionModule to fuse multimodal embeddings using stacking, pooling, and an MLP classifier', 'create_deepset_fusion_with_transformer': 'create a DeepsetFusionWithTransformer that uses a TransformerEncoder as the pooling function for multimodal fusion', 'build_deepset_transformer_helper': 'build a multimodal fusion module using the deepset_transformer helper with configurable transformer layers and attention heads', 'review_get_projection_dim': 'review the get_projection_dim class method to determine the target projection dimension from channel encoder dims', 'test_pool_features': 'test the _pool_features method to verify pooling returns a tensor from the normalized stacked embeddings'}
```

