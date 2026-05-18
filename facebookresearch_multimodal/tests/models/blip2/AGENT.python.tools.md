# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/models/blip2/test_blip2.py

Prompts

```
['test the BLIP2 model forward pass with image and text inputs and verify output features', 'test the BLIP2 model TorchScript compilation and verify scripted output matches eager mode', 'create a QformerForCLM model with configurable dim_q, dim_kv, num_heads, and vocab_size parameters', 'create a VisionTransformer with PatchEmbeddings and TransformerEncoder for image feature extraction', 'run BLIP2 inference with image tensors, input IDs, and attention masks to get prediction scores', 'build a QformerLayer with self-attention only by setting has_cross_attention to False', 'build a QformerLayer with cross-attention by providing dim_kv and setting has_cross_attention to True', 'build a QformerEncoder with multiple Qformer layers and configurable cross-attention frequency', 'build a QformerEmbedding module with token and position embeddings for a given vocab size', 'test the QformerLayer forward pass with past key-value caching and query length parameters', 'build a QformerModel with dim_q, dim_kv, num_heads, and num_hidden_layers for BLIP-2 vision-language encoding', 'build a QformerForCLM model with vocab_size and num_hidden_layers for causal language modeling on query tokens', 'test QformerModel forward pass with attention_mask, encoder_hidden_states, and query_embeds inputs', 'test QformerModel forward pass using past_key_values cache for incremental sequence generation', 'test torch.jit.script compilation of QformerModel and QformerForCLM for TorchScript deployment', 'test get_causal_mask with attention mask and matching input shape to verify causal masking', 'test get_causal_mask with different input shape to verify padding mask extension behavior', 'test get_causal_mask with has_query flag to verify query-text interaction masking', 'review the get_causal_mask function for BLIP-2 Q-Former causal attention mask generation', 'refactor get_causal_mask to support additional attention mask configurations for Q-Former generation']
```

Usage

```
{'test_blip2_model_forward_pass': 'test the BLIP2 model forward pass with image and text inputs and verify output features', 'test_blip2_torchscript_compilation': 'test the BLIP2 model TorchScript compilation and verify scripted output matches eager mode', 'create_qformer_for_clm': 'create a QformerForCLM model with configurable dim_q, dim_kv, num_heads, and vocab_size parameters', 'create_vision_transformer_encoder': 'create a VisionTransformer with PatchEmbeddings and TransformerEncoder for image feature extraction', 'run_blip2_inference': 'run BLIP2 inference with image tensors, input IDs, and attention masks to get prediction scores'}
```

## File: facebookresearch_multimodal/tests/models/blip2/test_qformer_layers.py

Prompts

```
['test the BLIP2 model forward pass with image and text inputs and verify output features', 'test the BLIP2 model TorchScript compilation and verify scripted output matches eager mode', 'create a QformerForCLM model with configurable dim_q, dim_kv, num_heads, and vocab_size parameters', 'create a VisionTransformer with PatchEmbeddings and TransformerEncoder for image feature extraction', 'run BLIP2 inference with image tensors, input IDs, and attention masks to get prediction scores', 'build a QformerLayer with self-attention only by setting has_cross_attention to False', 'build a QformerLayer with cross-attention by providing dim_kv and setting has_cross_attention to True', 'build a QformerEncoder with multiple Qformer layers and configurable cross-attention frequency', 'build a QformerEmbedding module with token and position embeddings for a given vocab size', 'test the QformerLayer forward pass with past key-value caching and query length parameters', 'build a QformerModel with dim_q, dim_kv, num_heads, and num_hidden_layers for BLIP-2 vision-language encoding', 'build a QformerForCLM model with vocab_size and num_hidden_layers for causal language modeling on query tokens', 'test QformerModel forward pass with attention_mask, encoder_hidden_states, and query_embeds inputs', 'test QformerModel forward pass using past_key_values cache for incremental sequence generation', 'test torch.jit.script compilation of QformerModel and QformerForCLM for TorchScript deployment', 'test get_causal_mask with attention mask and matching input shape to verify causal masking', 'test get_causal_mask with different input shape to verify padding mask extension behavior', 'test get_causal_mask with has_query flag to verify query-text interaction masking', 'review the get_causal_mask function for BLIP-2 Q-Former causal attention mask generation', 'refactor get_causal_mask to support additional attention mask configurations for Q-Former generation']
```

Usage

```
{'build_QformerLayer_self_attention': 'build a QformerLayer with self-attention only by setting has_cross_attention to False', 'build_QformerLayer_cross_attention': 'build a QformerLayer with cross-attention by providing dim_kv and setting has_cross_attention to True', 'build_QformerEncoder': 'build a QformerEncoder with multiple Qformer layers and configurable cross-attention frequency', 'build_QformerEmbedding': 'build a QformerEmbedding module with token and position embeddings for a given vocab size', 'test_QformerLayer_forward': 'test the QformerLayer forward pass with past key-value caching and query length parameters'}
```

## File: facebookresearch_multimodal/tests/models/blip2/test_qformer_model.py

Prompts

```
['test the BLIP2 model forward pass with image and text inputs and verify output features', 'test the BLIP2 model TorchScript compilation and verify scripted output matches eager mode', 'create a QformerForCLM model with configurable dim_q, dim_kv, num_heads, and vocab_size parameters', 'create a VisionTransformer with PatchEmbeddings and TransformerEncoder for image feature extraction', 'run BLIP2 inference with image tensors, input IDs, and attention masks to get prediction scores', 'build a QformerLayer with self-attention only by setting has_cross_attention to False', 'build a QformerLayer with cross-attention by providing dim_kv and setting has_cross_attention to True', 'build a QformerEncoder with multiple Qformer layers and configurable cross-attention frequency', 'build a QformerEmbedding module with token and position embeddings for a given vocab size', 'test the QformerLayer forward pass with past key-value caching and query length parameters', 'build a QformerModel with dim_q, dim_kv, num_heads, and num_hidden_layers for BLIP-2 vision-language encoding', 'build a QformerForCLM model with vocab_size and num_hidden_layers for causal language modeling on query tokens', 'test QformerModel forward pass with attention_mask, encoder_hidden_states, and query_embeds inputs', 'test QformerModel forward pass using past_key_values cache for incremental sequence generation', 'test torch.jit.script compilation of QformerModel and QformerForCLM for TorchScript deployment', 'test get_causal_mask with attention mask and matching input shape to verify causal masking', 'test get_causal_mask with different input shape to verify padding mask extension behavior', 'test get_causal_mask with has_query flag to verify query-text interaction masking', 'review the get_causal_mask function for BLIP-2 Q-Former causal attention mask generation', 'refactor get_causal_mask to support additional attention mask configurations for Q-Former generation']
```

Usage

```
{'build_qformer_model': 'build a QformerModel with dim_q, dim_kv, num_heads, and num_hidden_layers for BLIP-2 vision-language encoding', 'build_qformer_for_clm': 'build a QformerForCLM model with vocab_size and num_hidden_layers for causal language modeling on query tokens', 'test_qformer_with_attn_mask': 'test QformerModel forward pass with attention_mask, encoder_hidden_states, and query_embeds inputs', 'test_qformer_with_past_key_values': 'test QformerModel forward pass using past_key_values cache for incremental sequence generation', 'test_qformer_scripting': 'test torch.jit.script compilation of QformerModel and QformerForCLM for TorchScript deployment'}
```

## File: facebookresearch_multimodal/tests/models/blip2/test_qformer_utils.py

Prompts

```
['test the BLIP2 model forward pass with image and text inputs and verify output features', 'test the BLIP2 model TorchScript compilation and verify scripted output matches eager mode', 'create a QformerForCLM model with configurable dim_q, dim_kv, num_heads, and vocab_size parameters', 'create a VisionTransformer with PatchEmbeddings and TransformerEncoder for image feature extraction', 'run BLIP2 inference with image tensors, input IDs, and attention masks to get prediction scores', 'build a QformerLayer with self-attention only by setting has_cross_attention to False', 'build a QformerLayer with cross-attention by providing dim_kv and setting has_cross_attention to True', 'build a QformerEncoder with multiple Qformer layers and configurable cross-attention frequency', 'build a QformerEmbedding module with token and position embeddings for a given vocab size', 'test the QformerLayer forward pass with past key-value caching and query length parameters', 'build a QformerModel with dim_q, dim_kv, num_heads, and num_hidden_layers for BLIP-2 vision-language encoding', 'build a QformerForCLM model with vocab_size and num_hidden_layers for causal language modeling on query tokens', 'test QformerModel forward pass with attention_mask, encoder_hidden_states, and query_embeds inputs', 'test QformerModel forward pass using past_key_values cache for incremental sequence generation', 'test torch.jit.script compilation of QformerModel and QformerForCLM for TorchScript deployment', 'test get_causal_mask with attention mask and matching input shape to verify causal masking', 'test get_causal_mask with different input shape to verify padding mask extension behavior', 'test get_causal_mask with has_query flag to verify query-text interaction masking', 'review the get_causal_mask function for BLIP-2 Q-Former causal attention mask generation', 'refactor get_causal_mask to support additional attention mask configurations for Q-Former generation']
```

Usage

```
{'test_get_causal_mask_basic': 'test get_causal_mask with attention mask and matching input shape to verify causal masking', 'test_get_causal_mask_diff_size': 'test get_causal_mask with different input shape to verify padding mask extension behavior', 'test_get_causal_mask_with_query': 'test get_causal_mask with has_query flag to verify query-text interaction masking', 'review_get_causal_mask': 'review the get_causal_mask function for BLIP-2 Q-Former causal attention mask generation', 'refactor_get_causal_mask': 'refactor get_causal_mask to support additional attention mask configurations for Q-Former generation'}
```

