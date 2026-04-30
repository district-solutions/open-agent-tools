# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/falcon_mamba/test_modeling_falcon_mamba.py

Prompts

```
['test the FalconMambaModel class forward pass and hidden states output shape', 'test the FalconMambaForCausalLM class loss computation and logits output shape', 'test that FalconMambaModel cached autoregressive decoding produces identical outputs to full forward pass', 'test that tuple and dict model outputs are numerically equivalent for FalconMambaModel and FalconMambaForCausalLM', 'test FalconMamba-7b text generation with fp16 precision and deterministic decoding on GPU']
```

Usage

```
{'test_falcon_mamba_model': 'test the FalconMambaModel class forward pass and hidden states output shape', 'test_falcon_mamba_lm_head_model': 'test the FalconMambaForCausalLM class loss computation and logits output shape', 'test_state_equivalency': 'test that FalconMambaModel cached autoregressive decoding produces identical outputs to full forward pass', 'test_model_outputs_equivalence': 'test that tuple and dict model outputs are numerically equivalent for FalconMambaModel and FalconMambaForCausalLM', 'test_generation_fp16': 'test FalconMamba-7b text generation with fp16 precision and deterministic decoding on GPU'}
```

