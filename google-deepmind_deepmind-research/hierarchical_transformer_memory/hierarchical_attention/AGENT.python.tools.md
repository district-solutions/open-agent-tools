# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/hierarchical_transformer_memory/hierarchical_attention/htm_attention.py

Prompts

```
['build a Haiku module that performs multi-head hierarchical attention over stored memories with top-k sampling', 'create sinusoidal positional encodings for a sequence given its length and hidden dimension size', 'create a HierarchicalMemory namedtuple with keys, contents, steps_since_last_write, and accumulator fields', 'review the HierarchicalMemoryAttention call method that computes attention logits and returns value updates for queries', 'test the hk_vmap helper function that wraps Haiku vmap with backward-compatible split_rng support', 'test the HierarchicalMemoryAttention class output shapes with parameterized query lengths and memory configurations', 'test the HierarchicalMemoryAttention class with boolean masking across batch, query, and memory dimensions', 'run the absltest suite for hierarchical transformer memory attention tests', 'review the HierarchicalAttentionTest class test methods and parameterized test cases', 'summarize the helper function that builds dummy queries and HierarchicalMemory objects for testing']
```

Usage

```
{'build_hierarchical_memory_attention': 'build a Haiku module that performs multi-head hierarchical attention over stored memories with top-k sampling', 'create_sinusoid_position_encoding': 'create sinusoidal positional encodings for a sequence given its length and hidden dimension size', 'create_hierarchical_memory_namedtuple': 'create a HierarchicalMemory namedtuple with keys, contents, steps_since_last_write, and accumulator fields', 'review_hierarchical_memory_attention_call': 'review the HierarchicalMemoryAttention call method that computes attention logits and returns value updates for queries', 'test_hk_vmap_helper': 'test the hk_vmap helper function that wraps Haiku vmap with backward-compatible split_rng support'}
```

## File: google-deepmind_deepmind-research/hierarchical_transformer_memory/hierarchical_attention/htm_attention_test.py

Prompts

```
['build a Haiku module that performs multi-head hierarchical attention over stored memories with top-k sampling', 'create sinusoidal positional encodings for a sequence given its length and hidden dimension size', 'create a HierarchicalMemory namedtuple with keys, contents, steps_since_last_write, and accumulator fields', 'review the HierarchicalMemoryAttention call method that computes attention logits and returns value updates for queries', 'test the hk_vmap helper function that wraps Haiku vmap with backward-compatible split_rng support', 'test the HierarchicalMemoryAttention class output shapes with parameterized query lengths and memory configurations', 'test the HierarchicalMemoryAttention class with boolean masking across batch, query, and memory dimensions', 'run the absltest suite for hierarchical transformer memory attention tests', 'review the HierarchicalAttentionTest class test methods and parameterized test cases', 'summarize the helper function that builds dummy queries and HierarchicalMemory objects for testing']
```

Usage

```
{'test_HierarchicalMemoryAttention_output_shapes': 'test the HierarchicalMemoryAttention class output shapes with parameterized query lengths and memory configurations', 'test_HierarchicalMemoryAttention_masking': 'test the HierarchicalMemoryAttention class with boolean masking across batch, query, and memory dimensions', 'run_htm_attention_tests': 'run the absltest suite for hierarchical transformer memory attention tests', 'review_HierarchicalAttentionTest': 'review the HierarchicalAttentionTest class test methods and parameterized test cases', 'summarize_build_queries_and_memory': 'summarize the helper function that builds dummy queries and HierarchicalMemory objects for testing'}
```

