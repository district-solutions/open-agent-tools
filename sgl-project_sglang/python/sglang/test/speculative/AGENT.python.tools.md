# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/test/speculative/test_spec_utils.py

Prompts

```
['test assign_draft_cache_locs with a single sequence and page_size=4', 'test assign_draft_cache_locs with multiple sequences and varying sequence lengths', 'test assign_draft_cache_locs with page_size=1 to verify no duplication', 'test assign_draft_cache_locs when page_size exceeds speculative_num_steps', 'test copy_all_layer_kv_cache_tiled to duplicate KV cache values from source to target locations']
```

Usage

```
{'test_assign_draft_cache_locs_single_seq': 'test assign_draft_cache_locs with a single sequence and page_size=4', 'test_assign_draft_cache_locs_multi_seq': 'test assign_draft_cache_locs with multiple sequences and varying sequence lengths', 'test_assign_draft_cache_locs_page_size_1': 'test assign_draft_cache_locs with page_size=1 to verify no duplication', 'test_assign_draft_cache_locs_page_size_gt_spec_steps': 'test assign_draft_cache_locs when page_size exceeds speculative_num_steps', 'test_copy_all_layer_kv_cache_tiled': 'test copy_all_layer_kv_cache_tiled to duplicate KV cache values from source to target locations'}
```

