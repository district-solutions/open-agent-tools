# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/gpt_oss/convert_gpt_oss_weights_to_hf.py

Prompts

```
['convert GPT OSS model weights from original format to HuggingFace transformers format using write_model', 'run the GPT OSS weight conversion CLI with input_dir and output_dir arguments via main', 'convert MOE packed FP4 tensors to unpacked bfloat16 tensors using convert_moe_packed_tensors', 'write GPT OSS tokenizer with Harmony chat template to output directory using write_tokenizer', 'convert original model state dict keys to HuggingFace key format using convert_old_keys_to_new_keys', 'build a GptOssForCausalLM model from config and generate text from a tokenizer prompt', 'test the GptOssModel forward pass with input_ids, attention_mask, and past_key_values caching', 'refactor the GptOssAttention module to support sliding window attention with sink tokens', 'summarize the GptOssMLP mixture-of-experts module with top-k router and expert routing', 'review the load_balancing_loss_func for MoE auxiliary loss computation across experts', 'create a GptOssForCausalLM model from a GptOssConfig for autoregressive text generation', 'build a GptOssModel with GptOssDecoderLayer blocks, GptOssAttention, and GptOssMLP with MoE routing', 'test GptOssAttention with sink tokens, rotary embeddings, and eager attention forward pass', 'refactor GptOssMLP to use GptOssTopKRouter and GptOssExperts for mixture-of-experts inference', 'summarize GptOssDecoderLayer with GptOssRMSNorm, GptOssAttention, and GptOssMLP residual connections']
```

Usage

```
{'convert_gpt_oss_weights_to_hf': 'convert GPT OSS model weights from original format to HuggingFace transformers format using write_model', 'run_convert_gpt_oss_cli': 'run the GPT OSS weight conversion CLI with input_dir and output_dir arguments via main', 'convert_moe_packed_tensors': 'convert MOE packed FP4 tensors to unpacked bfloat16 tensors using convert_moe_packed_tensors', 'write_gpt_oss_tokenizer': 'write GPT OSS tokenizer with Harmony chat template to output directory using write_tokenizer', 'convert_old_keys_to_new_keys': 'convert original model state dict keys to HuggingFace key format using convert_old_keys_to_new_keys'}
```

## File: huggingface_transformers/src/transformers/models/gpt_oss/modeling_gpt_oss.py

Prompts

```
['convert GPT OSS model weights from original format to HuggingFace transformers format using write_model', 'run the GPT OSS weight conversion CLI with input_dir and output_dir arguments via main', 'convert MOE packed FP4 tensors to unpacked bfloat16 tensors using convert_moe_packed_tensors', 'write GPT OSS tokenizer with Harmony chat template to output directory using write_tokenizer', 'convert original model state dict keys to HuggingFace key format using convert_old_keys_to_new_keys', 'build a GptOssForCausalLM model from config and generate text from a tokenizer prompt', 'test the GptOssModel forward pass with input_ids, attention_mask, and past_key_values caching', 'refactor the GptOssAttention module to support sliding window attention with sink tokens', 'summarize the GptOssMLP mixture-of-experts module with top-k router and expert routing', 'review the load_balancing_loss_func for MoE auxiliary loss computation across experts', 'create a GptOssForCausalLM model from a GptOssConfig for autoregressive text generation', 'build a GptOssModel with GptOssDecoderLayer blocks, GptOssAttention, and GptOssMLP with MoE routing', 'test GptOssAttention with sink tokens, rotary embeddings, and eager attention forward pass', 'refactor GptOssMLP to use GptOssTopKRouter and GptOssExperts for mixture-of-experts inference', 'summarize GptOssDecoderLayer with GptOssRMSNorm, GptOssAttention, and GptOssMLP residual connections']
```

Usage

```
{'build_gpt_oss_causal_lm': 'build a GptOssForCausalLM model from config and generate text from a tokenizer prompt', 'test_gpt_oss_model_forward': 'test the GptOssModel forward pass with input_ids, attention_mask, and past_key_values caching', 'refactor_gpt_oss_attention': 'refactor the GptOssAttention module to support sliding window attention with sink tokens', 'summarize_gpt_oss_moe_mlp': 'summarize the GptOssMLP mixture-of-experts module with top-k router and expert routing', 'review_load_balancing_loss': 'review the load_balancing_loss_func for MoE auxiliary loss computation across experts'}
```

## File: huggingface_transformers/src/transformers/models/gpt_oss/modular_gpt_oss.py

Prompts

```
['convert GPT OSS model weights from original format to HuggingFace transformers format using write_model', 'run the GPT OSS weight conversion CLI with input_dir and output_dir arguments via main', 'convert MOE packed FP4 tensors to unpacked bfloat16 tensors using convert_moe_packed_tensors', 'write GPT OSS tokenizer with Harmony chat template to output directory using write_tokenizer', 'convert original model state dict keys to HuggingFace key format using convert_old_keys_to_new_keys', 'build a GptOssForCausalLM model from config and generate text from a tokenizer prompt', 'test the GptOssModel forward pass with input_ids, attention_mask, and past_key_values caching', 'refactor the GptOssAttention module to support sliding window attention with sink tokens', 'summarize the GptOssMLP mixture-of-experts module with top-k router and expert routing', 'review the load_balancing_loss_func for MoE auxiliary loss computation across experts', 'create a GptOssForCausalLM model from a GptOssConfig for autoregressive text generation', 'build a GptOssModel with GptOssDecoderLayer blocks, GptOssAttention, and GptOssMLP with MoE routing', 'test GptOssAttention with sink tokens, rotary embeddings, and eager attention forward pass', 'refactor GptOssMLP to use GptOssTopKRouter and GptOssExperts for mixture-of-experts inference', 'summarize GptOssDecoderLayer with GptOssRMSNorm, GptOssAttention, and GptOssMLP residual connections']
```

Usage

```
{'create_gptoss_causal_lm': 'create a GptOssForCausalLM model from a GptOssConfig for autoregressive text generation', 'build_gptoss_model': 'build a GptOssModel with GptOssDecoderLayer blocks, GptOssAttention, and GptOssMLP with MoE routing', 'test_gptoss_attention': 'test GptOssAttention with sink tokens, rotary embeddings, and eager attention forward pass', 'refactor_gptoss_moe': 'refactor GptOssMLP to use GptOssTopKRouter and GptOssExperts for mixture-of-experts inference', 'summarize_gptoss_decoder': 'summarize GptOssDecoderLayer with GptOssRMSNorm, GptOssAttention, and GptOssMLP residual connections'}
```

