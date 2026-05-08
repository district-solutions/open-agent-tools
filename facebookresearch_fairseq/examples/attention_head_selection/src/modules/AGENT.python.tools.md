# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/attention_head_selection/src/modules/attn_head_selector.py

Prompts

```
['create an AttnHeadSelector module with num_tasks, num_layers, total_num_heads, and num_heads parameters', 'gumbel sample attention head logits with configurable temperature for soft selection', 'select top-k attention heads by highest softmax values using subset selection strategy', 'select top-k attention heads in groups using the group selection strategy', 'perform head selection for given task_ids using gumbel sampling and the configured strategy', 'build a HeadSelectionTransformerEncoderLayer with args, layer index, and an attention head selector', 'build a HeadSelectionTransformerDecoderLayer with args, layer index, and self and encoder attention head selectors', 'create a MultiheadAttentionSelection module for encoder self-attention using build_self_attention_selection', 'create a MultiheadAttentionSelection module for encoder-decoder cross-attention using build_encoder_attention_selection', 'review the HeadSelectionTransformerEncoderLayer and HeadSelectionTransformerDecoderLayer classes and their attention head selection methods', 'create a MultiheadAttentionSelection module with configurable total and selected attention heads for fairseq', 'build an attention head selector to dynamically choose which heads to use per layer', 'run a forward pass through MultiheadAttentionSelection that selects a subset of attention heads', 'review the MultiheadAttentionSelection init to understand total_num_heads versus num_heads configuration', 'test the MultiheadAttentionSelection forward method with subset_heads and subset_weights for training', 'run multi_head_attention_forward to compute multi-head attention output with query, key, value tensors and optional subset heads', 'run _scaled_dot_product_attention to compute scaled dot-product attention with optional head selection and weighting', 'run _in_projection to apply separate linear projections to query, key, and value tensors', 'test multi_head_attention_forward with subset_heads and subset_weights to select and weight specific attention heads', 'review multi_head_attention_forward to understand how attn_mask and key_padding_mask are merged and applied']
```

Usage

```
{'create_attn_head_selector': 'create an AttnHeadSelector module with num_tasks, num_layers, total_num_heads, and num_heads parameters', 'gumbel_sample_logits': 'gumbel sample attention head logits with configurable temperature for soft selection', 'subset_select_heads': 'select top-k attention heads by highest softmax values using subset selection strategy', 'group_select_heads': 'select top-k attention heads in groups using the group selection strategy', 'head_select_task_ids': 'perform head selection for given task_ids using gumbel sampling and the configured strategy'}
```

## File: facebookresearch_fairseq/examples/attention_head_selection/src/modules/head_selection_transformer_layer.py

Prompts

```
['create an AttnHeadSelector module with num_tasks, num_layers, total_num_heads, and num_heads parameters', 'gumbel sample attention head logits with configurable temperature for soft selection', 'select top-k attention heads by highest softmax values using subset selection strategy', 'select top-k attention heads in groups using the group selection strategy', 'perform head selection for given task_ids using gumbel sampling and the configured strategy', 'build a HeadSelectionTransformerEncoderLayer with args, layer index, and an attention head selector', 'build a HeadSelectionTransformerDecoderLayer with args, layer index, and self and encoder attention head selectors', 'create a MultiheadAttentionSelection module for encoder self-attention using build_self_attention_selection', 'create a MultiheadAttentionSelection module for encoder-decoder cross-attention using build_encoder_attention_selection', 'review the HeadSelectionTransformerEncoderLayer and HeadSelectionTransformerDecoderLayer classes and their attention head selection methods', 'create a MultiheadAttentionSelection module with configurable total and selected attention heads for fairseq', 'build an attention head selector to dynamically choose which heads to use per layer', 'run a forward pass through MultiheadAttentionSelection that selects a subset of attention heads', 'review the MultiheadAttentionSelection init to understand total_num_heads versus num_heads configuration', 'test the MultiheadAttentionSelection forward method with subset_heads and subset_weights for training', 'run multi_head_attention_forward to compute multi-head attention output with query, key, value tensors and optional subset heads', 'run _scaled_dot_product_attention to compute scaled dot-product attention with optional head selection and weighting', 'run _in_projection to apply separate linear projections to query, key, and value tensors', 'test multi_head_attention_forward with subset_heads and subset_weights to select and weight specific attention heads', 'review multi_head_attention_forward to understand how attn_mask and key_padding_mask are merged and applied']
```

Usage

```
{'build_encoder_layer_with_head_selection': 'build a HeadSelectionTransformerEncoderLayer with args, layer index, and an attention head selector', 'build_decoder_layer_with_head_selection': 'build a HeadSelectionTransformerDecoderLayer with args, layer index, and self and encoder attention head selectors', 'create_encoder_self_attention_selection': 'create a MultiheadAttentionSelection module for encoder self-attention using build_self_attention_selection', 'create_decoder_encoder_attention_selection': 'create a MultiheadAttentionSelection module for encoder-decoder cross-attention using build_encoder_attention_selection', 'review_head_selection_transformer_layer_classes': 'review the HeadSelectionTransformerEncoderLayer and HeadSelectionTransformerDecoderLayer classes and their attention head selection methods'}
```

## File: facebookresearch_fairseq/examples/attention_head_selection/src/modules/multihead_attention_selection.py

Prompts

```
['create an AttnHeadSelector module with num_tasks, num_layers, total_num_heads, and num_heads parameters', 'gumbel sample attention head logits with configurable temperature for soft selection', 'select top-k attention heads by highest softmax values using subset selection strategy', 'select top-k attention heads in groups using the group selection strategy', 'perform head selection for given task_ids using gumbel sampling and the configured strategy', 'build a HeadSelectionTransformerEncoderLayer with args, layer index, and an attention head selector', 'build a HeadSelectionTransformerDecoderLayer with args, layer index, and self and encoder attention head selectors', 'create a MultiheadAttentionSelection module for encoder self-attention using build_self_attention_selection', 'create a MultiheadAttentionSelection module for encoder-decoder cross-attention using build_encoder_attention_selection', 'review the HeadSelectionTransformerEncoderLayer and HeadSelectionTransformerDecoderLayer classes and their attention head selection methods', 'create a MultiheadAttentionSelection module with configurable total and selected attention heads for fairseq', 'build an attention head selector to dynamically choose which heads to use per layer', 'run a forward pass through MultiheadAttentionSelection that selects a subset of attention heads', 'review the MultiheadAttentionSelection init to understand total_num_heads versus num_heads configuration', 'test the MultiheadAttentionSelection forward method with subset_heads and subset_weights for training', 'run multi_head_attention_forward to compute multi-head attention output with query, key, value tensors and optional subset heads', 'run _scaled_dot_product_attention to compute scaled dot-product attention with optional head selection and weighting', 'run _in_projection to apply separate linear projections to query, key, and value tensors', 'test multi_head_attention_forward with subset_heads and subset_weights to select and weight specific attention heads', 'review multi_head_attention_forward to understand how attn_mask and key_padding_mask are merged and applied']
```

Usage

```
{'create_multihead_attention_selection_module': 'create a MultiheadAttentionSelection module with configurable total and selected attention heads for fairseq', 'build_attention_head_selector': 'build an attention head selector to dynamically choose which heads to use per layer', 'run_forward_pass_with_head_selection': 'run a forward pass through MultiheadAttentionSelection that selects a subset of attention heads', 'review_multihead_attention_selection_init': 'review the MultiheadAttentionSelection init to understand total_num_heads versus num_heads configuration', 'test_head_selection_during_training': 'test the MultiheadAttentionSelection forward method with subset_heads and subset_weights for training'}
```

## File: facebookresearch_fairseq/examples/attention_head_selection/src/modules/multihead_functional.py

Prompts

```
['create an AttnHeadSelector module with num_tasks, num_layers, total_num_heads, and num_heads parameters', 'gumbel sample attention head logits with configurable temperature for soft selection', 'select top-k attention heads by highest softmax values using subset selection strategy', 'select top-k attention heads in groups using the group selection strategy', 'perform head selection for given task_ids using gumbel sampling and the configured strategy', 'build a HeadSelectionTransformerEncoderLayer with args, layer index, and an attention head selector', 'build a HeadSelectionTransformerDecoderLayer with args, layer index, and self and encoder attention head selectors', 'create a MultiheadAttentionSelection module for encoder self-attention using build_self_attention_selection', 'create a MultiheadAttentionSelection module for encoder-decoder cross-attention using build_encoder_attention_selection', 'review the HeadSelectionTransformerEncoderLayer and HeadSelectionTransformerDecoderLayer classes and their attention head selection methods', 'create a MultiheadAttentionSelection module with configurable total and selected attention heads for fairseq', 'build an attention head selector to dynamically choose which heads to use per layer', 'run a forward pass through MultiheadAttentionSelection that selects a subset of attention heads', 'review the MultiheadAttentionSelection init to understand total_num_heads versus num_heads configuration', 'test the MultiheadAttentionSelection forward method with subset_heads and subset_weights for training', 'run multi_head_attention_forward to compute multi-head attention output with query, key, value tensors and optional subset heads', 'run _scaled_dot_product_attention to compute scaled dot-product attention with optional head selection and weighting', 'run _in_projection to apply separate linear projections to query, key, and value tensors', 'test multi_head_attention_forward with subset_heads and subset_weights to select and weight specific attention heads', 'review multi_head_attention_forward to understand how attn_mask and key_padding_mask are merged and applied']
```

Usage

```
{'run_multi_head_attention_forward': 'run multi_head_attention_forward to compute multi-head attention output with query, key, value tensors and optional subset heads', 'run_scaled_dot_product_attention': 'run _scaled_dot_product_attention to compute scaled dot-product attention with optional head selection and weighting', 'run_in_projection': 'run _in_projection to apply separate linear projections to query, key, and value tensors', 'test_multi_head_attention_forward_subset_heads': 'test multi_head_attention_forward with subset_heads and subset_weights to select and weight specific attention heads', 'review_multi_head_attention_forward_masks': 'review multi_head_attention_forward to understand how attn_mask and key_padding_mask are merged and applied'}
```

