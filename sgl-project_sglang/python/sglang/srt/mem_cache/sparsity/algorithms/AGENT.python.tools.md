# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/sparsity/algorithms/base_algorithm.py

Prompts

```
['initialize algorithm-specific representation pools for sparse attention with layer range and token pools', 'construct KV cache representations during prefill phase by computing page-level scores', 'incrementally update KV cache representations during decode phase for newly generated pages', 'retrieve top-k important KV cache indices for sparse attention using query-based scoring', 'retrieve top-k KV pages with recent page retention and sparsity ratio filtering', 'create a DeepSeekNSAAlgorithm instance with config, torch device, and kwargs']
```

Usage

```
{'initialize_representation_pool': 'initialize algorithm-specific representation pools for sparse attention with layer range and token pools', 'construct_representations': 'construct KV cache representations during prefill phase by computing page-level scores', 'update_representations': 'incrementally update KV cache representations during decode phase for newly generated pages', 'retrieve_topk': 'retrieve top-k important KV cache indices for sparse attention using query-based scoring', 'retrieve_topk_recent_retention': 'retrieve top-k KV pages with recent page retention and sparsity ratio filtering'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/sparsity/algorithms/deepseek_nsa.py

Prompts

```
['initialize algorithm-specific representation pools for sparse attention with layer range and token pools', 'construct KV cache representations during prefill phase by computing page-level scores', 'incrementally update KV cache representations during decode phase for newly generated pages', 'retrieve top-k important KV cache indices for sparse attention using query-based scoring', 'retrieve top-k KV pages with recent page retention and sparsity ratio filtering', 'create a DeepSeekNSAAlgorithm instance with config, torch device, and kwargs']
```

Usage

```
{'create_DeepSeekNSAAlgorithm': 'create a DeepSeekNSAAlgorithm instance with config, torch device, and kwargs', 'retrieve_topk': 'retrieve top-k attention keys using indexer with x, q_lora, positions, and forward_batch', 'initialize_representation_pool': 'initialize the representation pool for a range of transformer layers', 'construct_representations': 'construct sparse attention representations from k_buffer for a given layer', 'update_representations': 'update sparse attention representations incrementally for a given layer'}
```

