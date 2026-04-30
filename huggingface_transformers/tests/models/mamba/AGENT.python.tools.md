# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mamba/test_modeling_mamba.py

Prompts

```
['test the MambaModel forward pass and verify output shape and hidden states', 'test the MambaForCausalLM forward pass with labels and verify loss and logits shape', 'test MambaModel cached incremental decoding matches full-sequence forward output', 'test tuple and dict model outputs are numerically equal across all model classes', 'test MambaForCausalLM with torch.compile and static cache implementation produces correct generation']
```

Usage

```
{'test_mamba_model': 'test the MambaModel forward pass and verify output shape and hidden states', 'test_mamba_lm_head_model': 'test the MambaForCausalLM forward pass with labels and verify loss and logits shape', 'test_state_equivalency': 'test MambaModel cached incremental decoding matches full-sequence forward output', 'test_model_outputs_equivalence': 'test tuple and dict model outputs are numerically equal across all model classes', 'test_compile_mamba_cache': 'test MambaForCausalLM with torch.compile and static cache implementation produces correct generation'}
```

