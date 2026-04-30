# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/pool/late_interaction.py

Prompts

```
['build late interaction query params with a query key and number of expected query uses', 'build late interaction document params with a query key for scoring documents', 'compute MaxSim scores for multiple query and document embedding pairs in mini-batches', 'get the engine index for routing late interaction requests by query key', 'review the late interaction mode constants for cache query and score doc operations', 'build a pooling cursor from scheduled token counts, sequence lengths, and device for pooling operations', 'create pooling metadata with prompt lengths, token ids, pooling params, and pooling states for embedding pooling', 'get per-prompt token id lists from pooling metadata by slicing prompt token ids with prompt lengths', 'test whether a pooling cursor represents a partial prefill by comparing prompt lengths to scheduled tokens', 'slice pooling metadata by indices to extract a subset of prompts, params, states, and cursor data']
```

Usage

```
{'build_late_interaction_query_params': 'build late interaction query params with a query key and number of expected query uses', 'build_late_interaction_doc_params': 'build late interaction document params with a query key for scoring documents', 'compute_maxsim_score_batched': 'compute MaxSim scores for multiple query and document embedding pairs in mini-batches', 'get_late_interaction_engine_index': 'get the engine index for routing late interaction requests by query key', 'review_late_interaction_modes': 'review the late interaction mode constants for cache query and score doc operations'}
```

## File: vllm-project_vllm/vllm/v1/pool/metadata.py

Prompts

```
['build late interaction query params with a query key and number of expected query uses', 'build late interaction document params with a query key for scoring documents', 'compute MaxSim scores for multiple query and document embedding pairs in mini-batches', 'get the engine index for routing late interaction requests by query key', 'review the late interaction mode constants for cache query and score doc operations', 'build a pooling cursor from scheduled token counts, sequence lengths, and device for pooling operations', 'create pooling metadata with prompt lengths, token ids, pooling params, and pooling states for embedding pooling', 'get per-prompt token id lists from pooling metadata by slicing prompt token ids with prompt lengths', 'test whether a pooling cursor represents a partial prefill by comparing prompt lengths to scheduled tokens', 'slice pooling metadata by indices to extract a subset of prompts, params, states, and cursor data']
```

Usage

```
{'build_pooling_cursor': 'build a pooling cursor from scheduled token counts, sequence lengths, and device for pooling operations', 'create_pooling_metadata': 'create pooling metadata with prompt lengths, token ids, pooling params, and pooling states for embedding pooling', 'get_prompt_token_ids': 'get per-prompt token id lists from pooling metadata by slicing prompt token ids with prompt lengths', 'test_pooling_cursor_partial_prefill': 'test whether a pooling cursor represents a partial prefill by comparing prompt lengths to scheduled tokens', 'slice_pooling_metadata': 'slice pooling metadata by indices to extract a subset of prompts, params, states, and cursor data'}
```

