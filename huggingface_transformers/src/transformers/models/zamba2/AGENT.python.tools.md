# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/zamba2/modeling_zamba2.py

Prompts

```
['create a Zamba2ForCausalLM model for autoregressive text generation from pretrained weights', 'build a Zamba2ForSequenceClassification model for text classification using the last token', 'run a Zamba2Model forward pass with input_ids, attention_mask, and position_ids to get hidden states', 'test the Zamba2MambaMixer SSM layer with cuda kernels or naive torch implementation for state space modeling', 'review the Zamba2Attention multi-headed attention layer with RoPE embeddings and KV caching support', 'create a Zamba2ForSequenceClassification model for sequence classification with pooled logits', 'build a Zamba2Model with hybrid Mamba and transformer decoder layers and rotary embeddings', 'run forward pass on Zamba2Model with input_ids, attention_mask, and optional past_key_values cache', 'use Zamba2MambaMixer with selective state-space SSM kernels for efficient sequence modeling']
```

Usage

```
{'create_zamba2_causal_lm': 'create a Zamba2ForCausalLM model for autoregressive text generation from pretrained weights', 'build_zamba2_sequence_classifier': 'build a Zamba2ForSequenceClassification model for text classification using the last token', 'run_zamba2_model_forward': 'run a Zamba2Model forward pass with input_ids, attention_mask, and position_ids to get hidden states', 'test_zamba2_mamba_mixer': 'test the Zamba2MambaMixer SSM layer with cuda kernels or naive torch implementation for state space modeling', 'review_zamba2_attention_layer': 'review the Zamba2Attention multi-headed attention layer with RoPE embeddings and KV caching support'}
```

## File: huggingface_transformers/src/transformers/models/zamba2/modular_zamba2.py

Prompts

```
['create a Zamba2ForCausalLM model for autoregressive text generation from pretrained weights', 'build a Zamba2ForSequenceClassification model for text classification using the last token', 'run a Zamba2Model forward pass with input_ids, attention_mask, and position_ids to get hidden states', 'test the Zamba2MambaMixer SSM layer with cuda kernels or naive torch implementation for state space modeling', 'review the Zamba2Attention multi-headed attention layer with RoPE embeddings and KV caching support', 'create a Zamba2ForSequenceClassification model for sequence classification with pooled logits', 'build a Zamba2Model with hybrid Mamba and transformer decoder layers and rotary embeddings', 'run forward pass on Zamba2Model with input_ids, attention_mask, and optional past_key_values cache', 'use Zamba2MambaMixer with selective state-space SSM kernels for efficient sequence modeling']
```

Usage

```
{'create_zamba2_causal_lm': 'create a Zamba2ForCausalLM model from a Zamba2Config for autoregressive text generation', 'create_zamba2_sequence_classifier': 'create a Zamba2ForSequenceClassification model for sequence classification with pooled logits', 'build_zamba2_model': 'build a Zamba2Model with hybrid Mamba and transformer decoder layers and rotary embeddings', 'run_zamba2_forward': 'run forward pass on Zamba2Model with input_ids, attention_mask, and optional past_key_values cache', 'use_zamba2_mamba_mixer': 'use Zamba2MambaMixer with selective state-space SSM kernels for efficient sequence modeling'}
```

