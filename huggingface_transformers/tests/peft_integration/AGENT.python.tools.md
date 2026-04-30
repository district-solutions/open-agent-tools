# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/peft_integration/test_peft_integration.py

Prompts

```
['test loading a PEFT adapter model from pretrained with LoRA weights injected automatically', 'test saving a PEFT adapter model to disk produces adapter_model.safetensors and adapter_config.json', 'test adding a LoRA adapter to a base transformers model via add_adapter method', 'test deleting PEFT adapters including edge cases with multiple adapters and error handling', 'test PEFT hotswap requires existing adapter with matching name before loading new weights']
```

Usage

```
{'test_peft_from_pretrained': 'test loading a PEFT adapter model from pretrained with LoRA weights injected automatically', 'test_peft_save_pretrained': 'test saving a PEFT adapter model to disk produces adapter_model.safetensors and adapter_config.json', 'test_peft_add_adapter': 'test adding a LoRA adapter to a base transformers model via add_adapter method', 'test_delete_adapter': 'test deleting PEFT adapters including edge cases with multiple adapters and error handling', 'test_hotswap_different_adapter_name_raises': 'test PEFT hotswap requires existing adapter with matching name before loading new weights'}
```

