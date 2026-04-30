# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/generation/vllm_client.py

Prompts

```
['build a vLLM client to generate text completions from a running vLLM server', 'generate text completions for a list of prompts with configurable sampling parameters', 'generate chat completions from message lists with tool calling and structured output support', 'update model weights in a distributed vLLM server by initializing a communicator and broadcasting parameters', 'compute per-token logprobs for existing sequences for knowledge distillation evaluation', 'run vLLM-based text generation with tokenized prompts and optional multi-modal images', 'sync trained model weights from FSDP or DeepSpeed to the vLLM engine', 'extract logprobs and token IDs sorted by probability rank from vLLM generation outputs', 'empty the cache of the available torch device including CUDA, XPU, MLU, and NPU', 'initialize a vLLM generation backend in server or colocate mode for distributed training']
```

Usage

```
{'build_vllm_client': 'build a vLLM client to generate text completions from a running vLLM server', 'generate_text_completions': 'generate text completions for a list of prompts with configurable sampling parameters', 'generate_chat_completions': 'generate chat completions from message lists with tool calling and structured output support', 'update_model_weights': 'update model weights in a distributed vLLM server by initializing a communicator and broadcasting parameters', 'compute_sequence_logprobs': 'compute per-token logprobs for existing sequences for knowledge distillation evaluation'}
```

## File: huggingface_trl/trl/generation/vllm_generation.py

Prompts

```
['build a vLLM client to generate text completions from a running vLLM server', 'generate text completions for a list of prompts with configurable sampling parameters', 'generate chat completions from message lists with tool calling and structured output support', 'update model weights in a distributed vLLM server by initializing a communicator and broadcasting parameters', 'compute per-token logprobs for existing sequences for knowledge distillation evaluation', 'run vLLM-based text generation with tokenized prompts and optional multi-modal images', 'sync trained model weights from FSDP or DeepSpeed to the vLLM engine', 'extract logprobs and token IDs sorted by probability rank from vLLM generation outputs', 'empty the cache of the available torch device including CUDA, XPU, MLU, and NPU', 'initialize a vLLM generation backend in server or colocate mode for distributed training']
```

Usage

```
{'run_generate_completions': 'run vLLM-based text generation with tokenized prompts and optional multi-modal images', 'sync_model_weights': 'sync trained model weights from FSDP or DeepSpeed to the vLLM engine', 'extract_logprob_values': 'extract logprobs and token IDs sorted by probability rank from vLLM generation outputs', 'empty_torch_device_cache': 'empty the cache of the available torch device including CUDA, XPU, MLU, and NPU', 'init_vllm_generation_backend': 'initialize a vLLM generation backend in server or colocate mode for distributed training'}
```

