# Agent Python Tools

- repo: facebookresearch/llm-qat
- repo_uri: https://github.com/facebookresearch/llm-qat

## File: facebookresearch_llm-qat/train.py

Prompts

```
['run quantization-aware training on a Llama model with configurable w_bits, a_bits, and kv_bits', 'run knowledge distillation training with a teacher Llama model and configurable kd_loss_scale', 'run evaluation on a trained Llama model and compute perplexity from eval_loss', 'run standard causal language model training on a Llama model without quantization', 'run distributed Llama model training using FSDP for multi-GPU support']
```

Usage

```
{'run_llm_qat_training': 'run quantization-aware training on a Llama model with configurable w_bits, a_bits, and kv_bits', 'run_llm_kd_training': 'run knowledge distillation training with a teacher Llama model and configurable kd_loss_scale', 'run_llm_evaluation': 'run evaluation on a trained Llama model and compute perplexity from eval_loss', 'run_llm_standard_training': 'run standard causal language model training on a Llama model without quantization', 'run_llm_training_with_fsdp': 'run distributed Llama model training using FSDP for multi-GPU support'}
```

