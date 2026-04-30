# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/sparsegpt/base.py

Prompts

```
['create a SparseGPTModifier to apply one-shot SparseGPT pruning to a PyTorch model with configurable sparsity and mask structure', 'run calibrate_module to accumulate the Hessian of input activations for a given PyTorch module during calibration', 'run compress_modules to sparsify all calibrated modules using the accumulated Hessians and target sparsity', 'review SparseGPTModifier with offload_hessians enabled to reduce GPU memory usage at the cost of increased runtime', 'refactor SparseGPTModifier to apply structured N:M mask structure instead of unstructured pruning', 'create a SparsityModifierBase subclass to implement oneshot sparsity pruning for a PyTorch model', 'run calibrate_module on a PyTorch layer to collect activation statistics during calibration', 'run compress_modules to apply sparse masks to target layers after calibration', 'run on_initialize to set up target layers and infer layer-wise sparsities from calibration data', 'run _infer_owl_layer_sparsity to compute per-layer sparsity using the OWL profile algorithm', 'create an empty hessian tensor for a given neural network module', 'run accumulate_hessian to update the hessian matrix with new input samples', "test sparsify_weight to prune a module's weights to a target sparsity using SparseGPT", 'refactor sparsify_weight to support N:M structured pruning with block-wise hessian inversion', 'review accumulate_hessian for handling Linear, Conv1D, and Conv2d input reshaping']
```

Usage

```
{'create_SparseGPTModifier': 'create a SparseGPTModifier to apply one-shot SparseGPT pruning to a PyTorch model with configurable sparsity and mask structure', 'run_calibrate_module': 'run calibrate_module to accumulate the Hessian of input activations for a given PyTorch module during calibration', 'run_compress_modules': 'run compress_modules to sparsify all calibrated modules using the accumulated Hessians and target sparsity', 'review_SparseGPTModifier_offload': 'review SparseGPTModifier with offload_hessians enabled to reduce GPU memory usage at the cost of increased runtime', 'refactor_SparseGPTModifier_mask_structure': 'refactor SparseGPTModifier to apply structured N:M mask structure instead of unstructured pruning'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/sparsegpt/sgpt_base.py

Prompts

```
['create a SparseGPTModifier to apply one-shot SparseGPT pruning to a PyTorch model with configurable sparsity and mask structure', 'run calibrate_module to accumulate the Hessian of input activations for a given PyTorch module during calibration', 'run compress_modules to sparsify all calibrated modules using the accumulated Hessians and target sparsity', 'review SparseGPTModifier with offload_hessians enabled to reduce GPU memory usage at the cost of increased runtime', 'refactor SparseGPTModifier to apply structured N:M mask structure instead of unstructured pruning', 'create a SparsityModifierBase subclass to implement oneshot sparsity pruning for a PyTorch model', 'run calibrate_module on a PyTorch layer to collect activation statistics during calibration', 'run compress_modules to apply sparse masks to target layers after calibration', 'run on_initialize to set up target layers and infer layer-wise sparsities from calibration data', 'run _infer_owl_layer_sparsity to compute per-layer sparsity using the OWL profile algorithm', 'create an empty hessian tensor for a given neural network module', 'run accumulate_hessian to update the hessian matrix with new input samples', "test sparsify_weight to prune a module's weights to a target sparsity using SparseGPT", 'refactor sparsify_weight to support N:M structured pruning with block-wise hessian inversion', 'review accumulate_hessian for handling Linear, Conv1D, and Conv2d input reshaping']
```

Usage

```
{'create_SparsityModifierBase': 'create a SparsityModifierBase subclass to implement oneshot sparsity pruning for a PyTorch model', 'run_SparsityModifierBase_calibrate_module': 'run calibrate_module on a PyTorch layer to collect activation statistics during calibration', 'run_SparsityModifierBase_compress_modules': 'run compress_modules to apply sparse masks to target layers after calibration', 'run_SparsityModifierBase_on_initialize': 'run on_initialize to set up target layers and infer layer-wise sparsities from calibration data', 'run_SparsityModifierBase_infer_owl_layer_sparsity': 'run _infer_owl_layer_sparsity to compute per-layer sparsity using the OWL profile algorithm'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/sparsegpt/sgpt_sparsify.py

Prompts

```
['create a SparseGPTModifier to apply one-shot SparseGPT pruning to a PyTorch model with configurable sparsity and mask structure', 'run calibrate_module to accumulate the Hessian of input activations for a given PyTorch module during calibration', 'run compress_modules to sparsify all calibrated modules using the accumulated Hessians and target sparsity', 'review SparseGPTModifier with offload_hessians enabled to reduce GPU memory usage at the cost of increased runtime', 'refactor SparseGPTModifier to apply structured N:M mask structure instead of unstructured pruning', 'create a SparsityModifierBase subclass to implement oneshot sparsity pruning for a PyTorch model', 'run calibrate_module on a PyTorch layer to collect activation statistics during calibration', 'run compress_modules to apply sparse masks to target layers after calibration', 'run on_initialize to set up target layers and infer layer-wise sparsities from calibration data', 'run _infer_owl_layer_sparsity to compute per-layer sparsity using the OWL profile algorithm', 'create an empty hessian tensor for a given neural network module', 'run accumulate_hessian to update the hessian matrix with new input samples', "test sparsify_weight to prune a module's weights to a target sparsity using SparseGPT", 'refactor sparsify_weight to support N:M structured pruning with block-wise hessian inversion', 'review accumulate_hessian for handling Linear, Conv1D, and Conv2d input reshaping']
```

Usage

```
{'create_empty_hessian': 'create an empty hessian tensor for a given neural network module', 'run_accumulate_hessian': 'run accumulate_hessian to update the hessian matrix with new input samples', 'test_sparsify_weight': "test sparsify_weight to prune a module's weights to a target sparsity using SparseGPT", 'refactor_sparsify_weight': 'refactor sparsify_weight to support N:M structured pruning with block-wise hessian inversion', 'review_accumulate_hessian': 'review accumulate_hessian for handling Linear, Conv1D, and Conv2d input reshaping'}
```

