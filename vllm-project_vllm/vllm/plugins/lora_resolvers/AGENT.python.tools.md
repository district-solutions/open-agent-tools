# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/plugins/lora_resolvers/filesystem_resolver.py

Prompts

```
['create a FilesystemResolver instance with a cache directory path for resolving local LoRA adapters', 'build a LoRARequest from a base model name and LoRA name by resolving its filesystem path', 'test an adapter path by checking for adapter_config.json with valid LORA peft_type and matching base_model_name', 'register a FilesystemResolver with the LoRAResolverRegistry using the VLLM_LORA_RESOLVER_CACHE_DIR environment variable', 'review the register_filesystem_resolver function that validates the cache directory exists and is a directory before registering', 'build a vLLM LoRA resolver that downloads adapter snapshots from Hugging Face Hub repositories', 'create an HfHubResolver instance with a list of allowed Hugging Face Hub repository names', 'test the resolve_lora method to resolve a LoRA request from a Hugging Face Hub repo and subpath', "refactor the register_hf_hub_resolver function to register the resolver with vLLM's LoRAResolverRegistry", 'review the _get_adapter_dirs method that scans a HF Hub repo for directories containing adapter_config.json']
```

Usage

```
{'create_filesystem_resolver': 'create a FilesystemResolver instance with a cache directory path for resolving local LoRA adapters', 'build_resolve_lora': 'build a LoRARequest from a base model name and LoRA name by resolving its filesystem path', 'test_validate_adapter': 'test an adapter path by checking for adapter_config.json with valid LORA peft_type and matching base_model_name', 'register_filesystem_resolver': 'register a FilesystemResolver with the LoRAResolverRegistry using the VLLM_LORA_RESOLVER_CACHE_DIR environment variable', 'review_register_validation': 'review the register_filesystem_resolver function that validates the cache directory exists and is a directory before registering'}
```

## File: vllm-project_vllm/vllm/plugins/lora_resolvers/hf_hub_resolver.py

Prompts

```
['create a FilesystemResolver instance with a cache directory path for resolving local LoRA adapters', 'build a LoRARequest from a base model name and LoRA name by resolving its filesystem path', 'test an adapter path by checking for adapter_config.json with valid LORA peft_type and matching base_model_name', 'register a FilesystemResolver with the LoRAResolverRegistry using the VLLM_LORA_RESOLVER_CACHE_DIR environment variable', 'review the register_filesystem_resolver function that validates the cache directory exists and is a directory before registering', 'build a vLLM LoRA resolver that downloads adapter snapshots from Hugging Face Hub repositories', 'create an HfHubResolver instance with a list of allowed Hugging Face Hub repository names', 'test the resolve_lora method to resolve a LoRA request from a Hugging Face Hub repo and subpath', "refactor the register_hf_hub_resolver function to register the resolver with vLLM's LoRAResolverRegistry", 'review the _get_adapter_dirs method that scans a HF Hub repo for directories containing adapter_config.json']
```

Usage

```
{'build_hf_hub_resolver': 'build a vLLM LoRA resolver that downloads adapter snapshots from Hugging Face Hub repositories', 'create_hf_hub_resolver_instance': 'create an HfHubResolver instance with a list of allowed Hugging Face Hub repository names', 'test_resolve_lora': 'test the resolve_lora method to resolve a LoRA request from a Hugging Face Hub repo and subpath', 'refactor_register_hf_hub_resolver': "refactor the register_hf_hub_resolver function to register the resolver with vLLM's LoRAResolverRegistry", 'review_get_adapter_dirs': 'review the _get_adapter_dirs method that scans a HF Hub repo for directories containing adapter_config.json'}
```

