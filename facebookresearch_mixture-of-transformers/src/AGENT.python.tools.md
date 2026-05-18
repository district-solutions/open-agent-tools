# Agent Python Tools

- repo: facebookresearch/mixture-of-transformers
- repo_uri: https://github.com/facebookresearch/mixture-of-transformers

## File: facebookresearch_mixture-of-transformers/src/simple_ModalityUntiedAttention.py

Prompts

```
['create a SimpleModalityUntiedAttention module with modality-specific QKV projections and multihead attention', 'build modality-specific query, key, and value linear projections using _create_experts helper', 'run the forward pass with input tensor, attention mask, and modality masks', 'review the qk_normalize_tensor function that reshapes and normalizes tensors for LayerNorm', 'test the _process_final_output method that applies modality-specific output projections and normalization', 'build a SimpleModalityUntiedFeedForward module with separate feed-forward experts per modality and RMSNorm', 'build a SimpleFeedForward SwiGLU module with w1, w3 gating and w2 projection layers', 'run the forward pass of SimpleModalityUntiedFeedForward with input tensor and modality masks', 'run the forward pass of SimpleFeedForward to compute SwiGLU gated output from input tensor', 'review the SimpleModalityUntiedFeedForward local experts and per-modality normalization setup', 'merge modality-specific expert outputs into a unified tensor using modality masks', 'create a SimpleRMSNorm normalization layer with a given dimension and epsilon value', 'test the merge_modalities function with multiple expert outputs and modality masks', 'review the SimpleRMSNorm forward pass that normalizes input tensors using RMS normalization', 'refactor the SimpleRMSNorm reset_parameters method to reinitialize weights to ones']
```

Usage

```
{'create_modality_untied_attention': 'create a SimpleModalityUntiedAttention module with modality-specific QKV projections and multihead attention', 'build_qkv_projections': 'build modality-specific query, key, and value linear projections using _create_experts helper', 'run_forward_pass': 'run the forward pass with input tensor, attention mask, and modality masks', 'review_qk_normalize_tensor': 'review the qk_normalize_tensor function that reshapes and normalizes tensors for LayerNorm', 'test_process_final_output': 'test the _process_final_output method that applies modality-specific output projections and normalization'}
```

## File: facebookresearch_mixture-of-transformers/src/simple_ModalityUntiedFeedForward.py

Prompts

```
['create a SimpleModalityUntiedAttention module with modality-specific QKV projections and multihead attention', 'build modality-specific query, key, and value linear projections using _create_experts helper', 'run the forward pass with input tensor, attention mask, and modality masks', 'review the qk_normalize_tensor function that reshapes and normalizes tensors for LayerNorm', 'test the _process_final_output method that applies modality-specific output projections and normalization', 'build a SimpleModalityUntiedFeedForward module with separate feed-forward experts per modality and RMSNorm', 'build a SimpleFeedForward SwiGLU module with w1, w3 gating and w2 projection layers', 'run the forward pass of SimpleModalityUntiedFeedForward with input tensor and modality masks', 'run the forward pass of SimpleFeedForward to compute SwiGLU gated output from input tensor', 'review the SimpleModalityUntiedFeedForward local experts and per-modality normalization setup', 'merge modality-specific expert outputs into a unified tensor using modality masks', 'create a SimpleRMSNorm normalization layer with a given dimension and epsilon value', 'test the merge_modalities function with multiple expert outputs and modality masks', 'review the SimpleRMSNorm forward pass that normalizes input tensors using RMS normalization', 'refactor the SimpleRMSNorm reset_parameters method to reinitialize weights to ones']
```

Usage

```
{'build_modality_untied_ffn': 'build a SimpleModalityUntiedFeedForward module with separate feed-forward experts per modality and RMSNorm', 'build_simple_feedforward': 'build a SimpleFeedForward SwiGLU module with w1, w3 gating and w2 projection layers', 'run_modality_untied_forward': 'run the forward pass of SimpleModalityUntiedFeedForward with input tensor and modality masks', 'run_simple_feedforward_forward': 'run the forward pass of SimpleFeedForward to compute SwiGLU gated output from input tensor', 'review_modality_untied_experts': 'review the SimpleModalityUntiedFeedForward local experts and per-modality normalization setup'}
```

## File: facebookresearch_mixture-of-transformers/src/utils.py

Prompts

```
['create a SimpleModalityUntiedAttention module with modality-specific QKV projections and multihead attention', 'build modality-specific query, key, and value linear projections using _create_experts helper', 'run the forward pass with input tensor, attention mask, and modality masks', 'review the qk_normalize_tensor function that reshapes and normalizes tensors for LayerNorm', 'test the _process_final_output method that applies modality-specific output projections and normalization', 'build a SimpleModalityUntiedFeedForward module with separate feed-forward experts per modality and RMSNorm', 'build a SimpleFeedForward SwiGLU module with w1, w3 gating and w2 projection layers', 'run the forward pass of SimpleModalityUntiedFeedForward with input tensor and modality masks', 'run the forward pass of SimpleFeedForward to compute SwiGLU gated output from input tensor', 'review the SimpleModalityUntiedFeedForward local experts and per-modality normalization setup', 'merge modality-specific expert outputs into a unified tensor using modality masks', 'create a SimpleRMSNorm normalization layer with a given dimension and epsilon value', 'test the merge_modalities function with multiple expert outputs and modality masks', 'review the SimpleRMSNorm forward pass that normalizes input tensors using RMS normalization', 'refactor the SimpleRMSNorm reset_parameters method to reinitialize weights to ones']
```

Usage

```
{'merge_modality_outputs': 'merge modality-specific expert outputs into a unified tensor using modality masks', 'create_rmsnorm_layer': 'create a SimpleRMSNorm normalization layer with a given dimension and epsilon value', 'test_merge_modalities': 'test the merge_modalities function with multiple expert outputs and modality masks', 'review_rmsnorm_forward': 'review the SimpleRMSNorm forward pass that normalizes input tensors using RMS normalization', 'refactor_rmsnorm_reset': 'refactor the SimpleRMSNorm reset_parameters method to reinitialize weights to ones'}
```

