# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/modules/fusions/test_attention_fusion.py

Prompts

```
['test AttentionFusionModule fusion without encoding projection dimension using random tensor inputs', 'test AttentionFusionModule fusion with encoding_projection_dim set to 2 and verify output shape', 'test torch.jit.script compilation of AttentionFusionModule and verify scripted model produces correct output', 'review the TestAttentionFusionModule unittest class and its three test methods for coverage', 'summarize the AttentionFusionModule test suite covering no projection, projection, and scripted model scenarios', 'test DeepsetFusionModule with torch.sum pooling on multi-channel tensor inputs', 'test DeepsetFusionModule with mean, median, min, and max pooling functions', 'test DeepsetFusionWithTransformer that uses a TransformerEncoder for multimodal fusion', 'test the deepset_transformer factory function to create a fusion module with configurable attention heads', 'test that DeepsetFusionModule and DeepsetFusionWithTransformer are compatible with torch.jit.script']
```

Usage

```
{'test_AttentionFusionModule_no_projection': 'test AttentionFusionModule fusion without encoding projection dimension using random tensor inputs', 'test_AttentionFusionModule_with_projection': 'test AttentionFusionModule fusion with encoding_projection_dim set to 2 and verify output shape', 'test_AttentionFusionModule_scripted': 'test torch.jit.script compilation of AttentionFusionModule and verify scripted model produces correct output', 'review_TestAttentionFusionModule_class': 'review the TestAttentionFusionModule unittest class and its three test methods for coverage', 'summarize_AttentionFusionModule_tests': 'summarize the AttentionFusionModule test suite covering no projection, projection, and scripted model scenarios'}
```

## File: facebookresearch_multimodal/tests/modules/fusions/test_deepset_fusion.py

Prompts

```
['test AttentionFusionModule fusion without encoding projection dimension using random tensor inputs', 'test AttentionFusionModule fusion with encoding_projection_dim set to 2 and verify output shape', 'test torch.jit.script compilation of AttentionFusionModule and verify scripted model produces correct output', 'review the TestAttentionFusionModule unittest class and its three test methods for coverage', 'summarize the AttentionFusionModule test suite covering no projection, projection, and scripted model scenarios', 'test DeepsetFusionModule with torch.sum pooling on multi-channel tensor inputs', 'test DeepsetFusionModule with mean, median, min, and max pooling functions', 'test DeepsetFusionWithTransformer that uses a TransformerEncoder for multimodal fusion', 'test the deepset_transformer factory function to create a fusion module with configurable attention heads', 'test that DeepsetFusionModule and DeepsetFusionWithTransformer are compatible with torch.jit.script']
```

Usage

```
{'test_DeepsetFusionModule_sum': 'test DeepsetFusionModule with torch.sum pooling on multi-channel tensor inputs', 'test_DeepsetFusionModule_pooling': 'test DeepsetFusionModule with mean, median, min, and max pooling functions', 'test_DeepsetFusionWithTransformer': 'test DeepsetFusionWithTransformer that uses a TransformerEncoder for multimodal fusion', 'test_deepset_transformer_factory': 'test the deepset_transformer factory function to create a fusion module with configurable attention heads', 'test_torchscript_compatibility': 'test that DeepsetFusionModule and DeepsetFusionWithTransformer are compatible with torch.jit.script'}
```

