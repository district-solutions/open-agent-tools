# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tinker-atropos/tinker_atropos/config.py

Prompts

```
['create a TinkerAtroposConfig from a YAML file using from_yaml', 'create a TinkerAtroposConfig with default environment, OpenAI, and tinker settings', 'create a TinkerAtroposConfig with custom group_size, batch_size, and learning_rate values', 'create a TinkerAtroposConfig and convert it to a dictionary using to_dict', 'create a random 4-character suffix string using generate_run_suffix', 'run TinkerAtroposTrainer to perform RL training with LoRA fine-tuning and Atropos API coordination', 'create a LoRA training client via TinkerServiceClient with a base model and rank', 'run a FastAPI server on port 8001 serving OpenAI-compatible completions and chat endpoints', 'test the /health endpoint to verify trainer initialization status', 'review the /generate endpoint that handles tokenized input generation with logprobs']
```

Usage

```
{'create_config_load_yaml': 'create a TinkerAtroposConfig from a YAML file using from_yaml', 'create_config_defaults': 'create a TinkerAtroposConfig with default environment, OpenAI, and tinker settings', 'create_config_custom': 'create a TinkerAtroposConfig with custom group_size, batch_size, and learning_rate values', 'create_config_to_dict': 'create a TinkerAtroposConfig and convert it to a dictionary using to_dict', 'create_run_suffix': 'create a random 4-character suffix string using generate_run_suffix'}
```

## File: NousResearch_hermes-agent/tinker-atropos/tinker_atropos/trainer.py

Prompts

```
['create a TinkerAtroposConfig from a YAML file using from_yaml', 'create a TinkerAtroposConfig with default environment, OpenAI, and tinker settings', 'create a TinkerAtroposConfig with custom group_size, batch_size, and learning_rate values', 'create a TinkerAtroposConfig and convert it to a dictionary using to_dict', 'create a random 4-character suffix string using generate_run_suffix', 'run TinkerAtroposTrainer to perform RL training with LoRA fine-tuning and Atropos API coordination', 'create a LoRA training client via TinkerServiceClient with a base model and rank', 'run a FastAPI server on port 8001 serving OpenAI-compatible completions and chat endpoints', 'test the /health endpoint to verify trainer initialization status', 'review the /generate endpoint that handles tokenized input generation with logprobs']
```

Usage

```
{'run_trainer': 'run TinkerAtroposTrainer to perform RL training with LoRA fine-tuning and Atropos API coordination', 'create_training_client': 'create a LoRA training client via TinkerServiceClient with a base model and rank', 'run_fastapi_server': 'run a FastAPI server on port 8001 serving OpenAI-compatible completions and chat endpoints', 'test_health_endpoint': 'test the /health endpoint to verify trainer initialization status', 'review_generate_endpoint': 'review the /generate endpoint that handles tokenized input generation with logprobs'}
```

