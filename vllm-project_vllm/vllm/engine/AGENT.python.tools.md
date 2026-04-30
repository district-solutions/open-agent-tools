# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/engine/arg_utils.py

Prompts

```
['create a VllmConfig from EngineArgs by parsing CLI arguments and building model, cache, parallel, and scheduler configs', 'build a CLI argument parser for vLLM engine with grouped arguments for model, cache, parallel, scheduler, and observability configs', 'create a ModelConfig from EngineArgs containing model, tokenizer, dtype, quantization, and multimodal settings', "parse human-readable integers like '1k', '2M', '25.6k' with decimal or binary multipliers into int values", 'create EngineArgs from parsed CLI argparse namespace by mapping argument attributes to dataclass fields', 'build a vLLM engine client that generates text outputs from prompts using generate with streaming', 'create a vLLM engine client that encodes prompts using encode with pooling parameters', 'test the EngineClient.abort method to cancel in-flight generation requests', 'refactor the EngineClient.add_lora method to load new LoRA adapters into the engine', 'review the EngineClient.check_health method to verify engine health status']
```

Usage

```
{'create_vllm_engine_config': 'create a VllmConfig from EngineArgs by parsing CLI arguments and building model, cache, parallel, and scheduler configs', 'build_engine_cli_args': 'build a CLI argument parser for vLLM engine with grouped arguments for model, cache, parallel, scheduler, and observability configs', 'create_model_config': 'create a ModelConfig from EngineArgs containing model, tokenizer, dtype, quantization, and multimodal settings', 'parse_human_readable_int': "parse human-readable integers like '1k', '2M', '25.6k' with decimal or binary multipliers into int values", 'create_engine_args_from_cli': 'create EngineArgs from parsed CLI argparse namespace by mapping argument attributes to dataclass fields'}
```

## File: vllm-project_vllm/vllm/engine/protocol.py

Prompts

```
['create a VllmConfig from EngineArgs by parsing CLI arguments and building model, cache, parallel, and scheduler configs', 'build a CLI argument parser for vLLM engine with grouped arguments for model, cache, parallel, scheduler, and observability configs', 'create a ModelConfig from EngineArgs containing model, tokenizer, dtype, quantization, and multimodal settings', "parse human-readable integers like '1k', '2M', '25.6k' with decimal or binary multipliers into int values", 'create EngineArgs from parsed CLI argparse namespace by mapping argument attributes to dataclass fields', 'build a vLLM engine client that generates text outputs from prompts using generate with streaming', 'create a vLLM engine client that encodes prompts using encode with pooling parameters', 'test the EngineClient.abort method to cancel in-flight generation requests', 'refactor the EngineClient.add_lora method to load new LoRA adapters into the engine', 'review the EngineClient.check_health method to verify engine health status']
```

Usage

```
{'build_engine_generate': 'build a vLLM engine client that generates text outputs from prompts using generate with streaming', 'create_engine_encode': 'create a vLLM engine client that encodes prompts using encode with pooling parameters', 'test_engine_abort': 'test the EngineClient.abort method to cancel in-flight generation requests', 'refactor_engine_add_lora': 'refactor the EngineClient.add_lora method to load new LoRA adapters into the engine', 'review_engine_check_health': 'review the EngineClient.check_health method to verify engine health status'}
```

