# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/transformers/compression/compressed_tensors_utils.py

Prompts

```
["modify a PreTrainedModel's save_pretrained method to support saving models in a compressed format", 'get a ModelCompressor instance from a pretrained model with an optional quantization format override', 'update and save a compression recipe file combining existing and current recipes into a save directory', 'test the modify_save_pretrained function wraps save_pretrained with compression support', 'review the update_and_save_recipe function that merges existing recipes with the active session recipe', 'test the tensor_follows_mask_structure function to verify if a tensor follows a 2:4 sparsity mask pattern', 'infer the sparsity structure string from a list of compression modifier instances', 'infer the sparsity structure of a PyTorch model by checking its linear layers for 2:4 sparsity patterns', 'infer sparse compression target and ignore layer lists from a model given a sparsity structure and threshold', 'test the is_sparse_compression_target function to check if a module qualifies for sparse compression']
```

Usage

```
{'modify_save_pretrained': "modify a PreTrainedModel's save_pretrained method to support saving models in a compressed format", 'get_model_compressor': 'get a ModelCompressor instance from a pretrained model with an optional quantization format override', 'update_and_save_recipe': 'update and save a compression recipe file combining existing and current recipes into a save directory', 'test_modify_save_pretrained': 'test the modify_save_pretrained function wraps save_pretrained with compression support', 'review_update_and_save_recipe': 'review the update_and_save_recipe function that merges existing recipes with the active session recipe'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/transformers/compression/sparsity_helpers.py

Prompts

```
["modify a PreTrainedModel's save_pretrained method to support saving models in a compressed format", 'get a ModelCompressor instance from a pretrained model with an optional quantization format override', 'update and save a compression recipe file combining existing and current recipes into a save directory', 'test the modify_save_pretrained function wraps save_pretrained with compression support', 'review the update_and_save_recipe function that merges existing recipes with the active session recipe', 'test the tensor_follows_mask_structure function to verify if a tensor follows a 2:4 sparsity mask pattern', 'infer the sparsity structure string from a list of compression modifier instances', 'infer the sparsity structure of a PyTorch model by checking its linear layers for 2:4 sparsity patterns', 'infer sparse compression target and ignore layer lists from a model given a sparsity structure and threshold', 'test the is_sparse_compression_target function to check if a module qualifies for sparse compression']
```

Usage

```
{'test_tensor_follows_mask_structure': 'test the tensor_follows_mask_structure function to verify if a tensor follows a 2:4 sparsity mask pattern', 'infer_sparsity_structure_from_modifiers': 'infer the sparsity structure string from a list of compression modifier instances', 'infer_sparsity_structure_from_model': 'infer the sparsity structure of a PyTorch model by checking its linear layers for 2:4 sparsity patterns', 'infer_sparse_targets_and_ignores': 'infer sparse compression target and ignore layer lists from a model given a sparsity structure and threshold', 'test_is_sparse_compression_target': 'test the is_sparse_compression_target function to check if a module qualifies for sparse compression'}
```

