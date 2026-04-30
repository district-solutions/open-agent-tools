# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/rwkv/test_modeling_rwkv.py

Prompts

```
['test the RwkvModel class forward pass and hidden states output shape', 'test the RwkvForCausalLM class with labels and verify loss and logits shapes', 'test incremental stateful inference produces equivalent output to full sequence', 'test attention output shape is batch_size, seq_len, hidden_size for Rwkv models', 'test loading a pretrained RWKV model from HuggingFace Hub']
```

Usage

```
{'test_rwkv_model': 'test the RwkvModel class forward pass and hidden states output shape', 'test_rwkv_lm_head_model': 'test the RwkvForCausalLM class with labels and verify loss and logits shapes', 'test_state_equivalency': 'test incremental stateful inference produces equivalent output to full sequence', 'test_attention_outputs': 'test attention output shape is batch_size, seq_len, hidden_size for Rwkv models', 'test_model_from_pretrained': 'test loading a pretrained RWKV model from HuggingFace Hub'}
```

