# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/tests/units/inference/test_base_lcm_batched_inference.py

Prompts

```
['test LCMGenerator batching produces identical outputs with and without batching using different batch sizes', 'test LCMGenerator caching behavior with enable and disable cache modes across batched inference', 'test LCMGenerator output length control using different eos_threshold stopping criterion values', 'test LCMGenerator does not stop prematurely when processing small batches with single inputs', 'test BaseLCModelConfig with TransformerConfig to create and run batched LCM model inference', 'test that LCMGenerator KV caching produces identical outputs to non-cached generation across multiple prefix lengths', 'create a BaseLCModel using BaseLCModelConfig with a TransformerConfig for the lcm transformer component', 'create an LCMGenerator with an LCM model, eos vector, and LCMGeneratorOptions for generation control', 'generate sequences using LCMGenerator with an EmbeddingsBatch input and max_gen_len parameter', 'compare LCMGenerator output hypotheses sequences with and without KV caching using torch.allclose']
```

Usage

```
{'test_LCMGenerator_batching': 'test LCMGenerator batching produces identical outputs with and without batching using different batch sizes', 'test_LCMGenerator_caching': 'test LCMGenerator caching behavior with enable and disable cache modes across batched inference', 'test_LCMGenerator_eos_threshold': 'test LCMGenerator output length control using different eos_threshold stopping criterion values', 'test_LCMGenerator_single_input_stopping': 'test LCMGenerator does not stop prematurely when processing small batches with single inputs', 'test_BaseLCModelConfig_inference': 'test BaseLCModelConfig with TransformerConfig to create and run batched LCM model inference'}
```

## File: facebookresearch_largeconceptmodel/tests/units/inference/test_base_lcm_kv_caching.py

Prompts

```
['test LCMGenerator batching produces identical outputs with and without batching using different batch sizes', 'test LCMGenerator caching behavior with enable and disable cache modes across batched inference', 'test LCMGenerator output length control using different eos_threshold stopping criterion values', 'test LCMGenerator does not stop prematurely when processing small batches with single inputs', 'test BaseLCModelConfig with TransformerConfig to create and run batched LCM model inference', 'test that LCMGenerator KV caching produces identical outputs to non-cached generation across multiple prefix lengths', 'create a BaseLCModel using BaseLCModelConfig with a TransformerConfig for the lcm transformer component', 'create an LCMGenerator with an LCM model, eos vector, and LCMGeneratorOptions for generation control', 'generate sequences using LCMGenerator with an EmbeddingsBatch input and max_gen_len parameter', 'compare LCMGenerator output hypotheses sequences with and without KV caching using torch.allclose']
```

Usage

```
{'test_kv_caching': 'test that LCMGenerator KV caching produces identical outputs to non-cached generation across multiple prefix lengths', 'create_base_lcm_model': 'create a BaseLCModel using BaseLCModelConfig with a TransformerConfig for the lcm transformer component', 'create_lcm_generator': 'create an LCMGenerator with an LCM model, eos vector, and LCMGeneratorOptions for generation control', 'generate_with_embeddings_batch': 'generate sequences using LCMGenerator with an EmbeddingsBatch input and max_gen_len parameter', 'compare_cached_vs_uncached_output': 'compare LCMGenerator output hypotheses sequences with and without KV caching using torch.allclose'}
```

