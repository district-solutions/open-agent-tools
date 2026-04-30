# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/serve/rlhf/api_router.py

Prompts

```
['pause vLLM model generation with mode abort, wait, or keep to allow weight updates', 'resume vLLM model generation after a pause caused by weight transfer operations', 'initialize weight transfer engine with init_info payload for distributed weight updates', 'update vLLM model weights with update_info payload during RLHF fine-tuning', 'attach the RLHF API router to a FastAPI app when server dev mode is enabled']
```

Usage

```
{'pause_generation': 'pause vLLM model generation with mode abort, wait, or keep to allow weight updates', 'resume_generation': 'resume vLLM model generation after a pause caused by weight transfer operations', 'init_weight_transfer_engine': 'initialize weight transfer engine with init_info payload for distributed weight updates', 'update_weights': 'update vLLM model weights with update_info payload during RLHF fine-tuning', 'attach_router': 'attach the RLHF API router to a FastAPI app when server dev mode is enabled'}
```

