# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/peft/layer.py

Prompts

```
['run the GaudiAdaloraLayerSVDLinearForward function to apply Adalora SVD linear forward with BF16 batch_gemm fix on HPU', 'run the GaudiPolyLayerLinearForward function to apply Poly LoRA forward with mixing weights and task routing on HPU', 'compute query states with rotary positional embeddings and past key value cache support for adaption prompts', 'run the GaudiAdaptedAttentionPreAttnForward function to compute attention with adaption prompt output added to the model output', 'run the GaudiBoftLinearForward function to apply Block Orthogonal Fine Tuning with butterfly rotation and scaling on HPU', 'review the gaudi_generate function that overrides PEFT model generation for Gaudi hardware with prompt learning support', 'review the gaudi_prepare_inputs_for_generation function that handles prompt tuning prefix tuning and cache formats for Gaudi', 'refactor the gaudi_generate function to add proper error handling instead of a bare except clause', 'refactor gaudi_prepare_inputs_for_generation to support additional PEFT types beyond POLY and PREFIX_TUNING', 'test gaudi_prepare_inputs_for_generation with different transformers versions and cache formats for llama and mistral models']
```

Usage

```
{'run_adalora_forward': 'run the GaudiAdaloraLayerSVDLinearForward function to apply Adalora SVD linear forward with BF16 batch_gemm fix on HPU', 'run_poly_forward': 'run the GaudiPolyLayerLinearForward function to apply Poly LoRA forward with mixing weights and task routing on HPU', 'compute_query_states': 'compute query states with rotary positional embeddings and past key value cache support for adaption prompts', 'run_adapted_attention_forward': 'run the GaudiAdaptedAttentionPreAttnForward function to compute attention with adaption prompt output added to the model output', 'run_boft_forward': 'run the GaudiBoftLinearForward function to apply Block Orthogonal Fine Tuning with butterfly rotation and scaling on HPU'}
```

## File: huggingface_optimum-habana/optimum/habana/peft/peft_model.py

Prompts

```
['run the GaudiAdaloraLayerSVDLinearForward function to apply Adalora SVD linear forward with BF16 batch_gemm fix on HPU', 'run the GaudiPolyLayerLinearForward function to apply Poly LoRA forward with mixing weights and task routing on HPU', 'compute query states with rotary positional embeddings and past key value cache support for adaption prompts', 'run the GaudiAdaptedAttentionPreAttnForward function to compute attention with adaption prompt output added to the model output', 'run the GaudiBoftLinearForward function to apply Block Orthogonal Fine Tuning with butterfly rotation and scaling on HPU', 'review the gaudi_generate function that overrides PEFT model generation for Gaudi hardware with prompt learning support', 'review the gaudi_prepare_inputs_for_generation function that handles prompt tuning prefix tuning and cache formats for Gaudi', 'refactor the gaudi_generate function to add proper error handling instead of a bare except clause', 'refactor gaudi_prepare_inputs_for_generation to support additional PEFT types beyond POLY and PREFIX_TUNING', 'test gaudi_prepare_inputs_for_generation with different transformers versions and cache formats for llama and mistral models']
```

Usage

```
{'review_gaudi_generate': 'review the gaudi_generate function that overrides PEFT model generation for Gaudi hardware with prompt learning support', 'review_gaudi_prepare_inputs_for_generation': 'review the gaudi_prepare_inputs_for_generation function that handles prompt tuning prefix tuning and cache formats for Gaudi', 'refactor_gaudi_generate': 'refactor the gaudi_generate function to add proper error handling instead of a bare except clause', 'refactor_gaudi_prepare_inputs_for_generation': 'refactor gaudi_prepare_inputs_for_generation to support additional PEFT types beyond POLY and PREFIX_TUNING', 'test_gaudi_prepare_inputs_for_generation': 'test gaudi_prepare_inputs_for_generation with different transformers versions and cache formats for llama and mistral models'}
```

