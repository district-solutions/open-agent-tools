# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/dllm/mixin/req.py

Prompts

```
['initialize DllmReqMixin on a request object with a DllmConfig to set up diffusion-LLM phase tracking', 'check whether a request object is configured for diffusion-LLM processing by inspecting its dllm_config attribute', 'determine whether a request is currently in a prefill phase for diffusion-LLM scheduling', 'compute the staging prefill or staging decode phase for a request based on prefix indices and fill IDs', 'build fill_ids for a diffusion-LLM request by combining origin input IDs, output IDs, and mask padding tokens', 'generate a new DLLM batch from waiting and staging queues for scheduling', 'process batch generation results including token allocation and cache release', 'create a DllmManager instance to manage waiting and staging queues for Diffusion LLM requests', 'process staging DLLM requests with resource allocation and preemption support']
```

Usage

```
{'init_diffusion_llm': 'initialize DllmReqMixin on a request object with a DllmConfig to set up diffusion-LLM phase tracking', 'is_dllm': 'check whether a request object is configured for diffusion-LLM processing by inspecting its dllm_config attribute', 'is_dllm_prefill': 'determine whether a request is currently in a prefill phase for diffusion-LLM scheduling', 'determine_dllm_phase': 'compute the staging prefill or staging decode phase for a request based on prefix indices and fill IDs', '_init_fill_ids_for_dllm': 'build fill_ids for a diffusion-LLM request by combining origin input IDs, output IDs, and mask padding tokens'}
```

## File: sgl-project_sglang/python/sglang/srt/dllm/mixin/scheduler.py

Prompts

```
['initialize DllmReqMixin on a request object with a DllmConfig to set up diffusion-LLM phase tracking', 'check whether a request object is configured for diffusion-LLM processing by inspecting its dllm_config attribute', 'determine whether a request is currently in a prefill phase for diffusion-LLM scheduling', 'compute the staging prefill or staging decode phase for a request based on prefix indices and fill IDs', 'build fill_ids for a diffusion-LLM request by combining origin input IDs, output IDs, and mask padding tokens', 'generate a new DLLM batch from waiting and staging queues for scheduling', 'process batch generation results including token allocation and cache release', 'create a DllmManager instance to manage waiting and staging queues for Diffusion LLM requests', 'process staging DLLM requests with resource allocation and preemption support']
```

Usage

```
{'init_diffusion_llm': 'initialize the DLLM manager and configuration for Diffusion LLM scheduling', 'get_new_batch_dllm': 'generate a new DLLM batch from waiting and staging queues for scheduling', 'process_batch_result_dllm': 'process batch generation results including token allocation and cache release', 'create_dllm_manager': 'create a DllmManager instance to manage waiting and staging queues for Diffusion LLM requests', 'process_dllm_staging_reqs': 'process staging DLLM requests with resource allocation and preemption support'}
```

