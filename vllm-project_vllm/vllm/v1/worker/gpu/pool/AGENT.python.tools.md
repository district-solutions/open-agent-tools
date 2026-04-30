# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/worker/gpu/pool/late_interaction_runner.py

Prompts

```
['create a LateInteractionRunner instance to manage worker-side state and postprocessing for late-interaction scoring', 'run postprocess_pooler_output to compute maxsim scores from cached query embeddings and document token embeddings', 'register a request with LateInteractionRunner by providing a request id and pooling params with late interaction metadata', 'run on_requests_finished to release cached query embeddings when document requests complete', 'clear all cached query embeddings, query use counts, and document-to-query key mappings in LateInteractionRunner', 'create a PoolingRunner instance from a pooling model to handle embedding pooling operations', 'test the PoolingRunner.get_supported_tasks method to check which pooling tasks the model supports', 'build embeddings by calling the pool method with hidden states, input batch, and request states', 'review the dummy_pooler_run method for normalization-only inference on hidden states', 'refactor the pool method to support additional pooling tasks beyond embed']
```

Usage

```
{'create_LateInteractionRunner': 'create a LateInteractionRunner instance to manage worker-side state and postprocessing for late-interaction scoring', 'run_postprocess_pooler_output': 'run postprocess_pooler_output to compute maxsim scores from cached query embeddings and document token embeddings', 'register_request_LateInteractionRunner': 'register a request with LateInteractionRunner by providing a request id and pooling params with late interaction metadata', 'run_on_requests_finished': 'run on_requests_finished to release cached query embeddings when document requests complete', 'clear_LateInteractionRunner': 'clear all cached query embeddings, query use counts, and document-to-query key mappings in LateInteractionRunner'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/pool/pooling_runner.py

Prompts

```
['create a LateInteractionRunner instance to manage worker-side state and postprocessing for late-interaction scoring', 'run postprocess_pooler_output to compute maxsim scores from cached query embeddings and document token embeddings', 'register a request with LateInteractionRunner by providing a request id and pooling params with late interaction metadata', 'run on_requests_finished to release cached query embeddings when document requests complete', 'clear all cached query embeddings, query use counts, and document-to-query key mappings in LateInteractionRunner', 'create a PoolingRunner instance from a pooling model to handle embedding pooling operations', 'test the PoolingRunner.get_supported_tasks method to check which pooling tasks the model supports', 'build embeddings by calling the pool method with hidden states, input batch, and request states', 'review the dummy_pooler_run method for normalization-only inference on hidden states', 'refactor the pool method to support additional pooling tasks beyond embed']
```

Usage

```
{'create_PoolingRunner': 'create a PoolingRunner instance from a pooling model to handle embedding pooling operations', 'test_get_supported_tasks': 'test the PoolingRunner.get_supported_tasks method to check which pooling tasks the model supports', 'build_pool_method': 'build embeddings by calling the pool method with hidden states, input batch, and request states', 'review_dummy_pooler_run': 'review the dummy_pooler_run method for normalization-only inference on hidden states', 'refactor_pool_method': 'refactor the pool method to support additional pooling tasks beyond embed'}
```

