# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/llama/test_modeling_llama.py

Prompts

```
['test the LlamaForCausalLM model generates expected text for a french revolution prompt', 'test the LlamaForCausalLM model outputs correct logits in bfloat16 precision on various accelerators', 'test the LlamaForCausalLM model outputs correct logits in float16 precision on various accelerators', 'test the LlamaForCausalLM model with torch compile and static cache produces expected text completions', 'test exporting LlamaForCausalLM with static cache to TorchExportableModuleForDecoderOnlyLM and generating text']
```

Usage

```
{'test_llama_generation': 'test the LlamaForCausalLM model generates expected text for a french revolution prompt', 'test_model_logits_bf16': 'test the LlamaForCausalLM model outputs correct logits in bfloat16 precision on various accelerators', 'test_model_logits_fp16': 'test the LlamaForCausalLM model outputs correct logits in float16 precision on various accelerators', 'test_compile_static_cache': 'test the LlamaForCausalLM model with torch compile and static cache produces expected text completions', 'test_export_static_cache': 'test exporting LlamaForCausalLM with static cache to TorchExportableModuleForDecoderOnlyLM and generating text'}
```

