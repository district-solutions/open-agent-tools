# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/wanda/base.py

Prompts

```
['create a WandaPruningModifier to apply one-shot WANDA pruning with configurable sparsity and mask structure', 'run calibrate_module to accumulate row scalars of module inputs during calibration', 'run compress_modules to sparsify calibrated modules using accumulated row scalars', 'test on_finalize to clean up calibration state and remove hooks after pruning', 'summarize the WandaPruningModifier class that applies WANDA algorithm for model pruning', "create an empty tensor of row scalars for a neural network module's weight columns", 'build accumulated row scalars from input tensors across dataset samples for WANDA pruning', "run WANDA sparsification on a module's weights given accumulated row scalars and target sparsity", 'test making an empty row scalars tensor for a linear module on a specific device', 'refactor the sparsify_weight function to support structured N:M pruning with configurable prune_n and prune_m']
```

Usage

```
{'create_WandaPruningModifier': 'create a WandaPruningModifier to apply one-shot WANDA pruning with configurable sparsity and mask structure', 'run_calibrate_module': 'run calibrate_module to accumulate row scalars of module inputs during calibration', 'run_compress_modules': 'run compress_modules to sparsify calibrated modules using accumulated row scalars', 'test_on_finalize': 'test on_finalize to clean up calibration state and remove hooks after pruning', 'summarize_WandaPruningModifier': 'summarize the WandaPruningModifier class that applies WANDA algorithm for model pruning'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/pruning/wanda/wanda_sparsify.py

Prompts

```
['create a WandaPruningModifier to apply one-shot WANDA pruning with configurable sparsity and mask structure', 'run calibrate_module to accumulate row scalars of module inputs during calibration', 'run compress_modules to sparsify calibrated modules using accumulated row scalars', 'test on_finalize to clean up calibration state and remove hooks after pruning', 'summarize the WandaPruningModifier class that applies WANDA algorithm for model pruning', "create an empty tensor of row scalars for a neural network module's weight columns", 'build accumulated row scalars from input tensors across dataset samples for WANDA pruning', "run WANDA sparsification on a module's weights given accumulated row scalars and target sparsity", 'test making an empty row scalars tensor for a linear module on a specific device', 'refactor the sparsify_weight function to support structured N:M pruning with configurable prune_n and prune_m']
```

Usage

```
{'create_empty_row_scalars': "create an empty tensor of row scalars for a neural network module's weight columns", 'build_accumulate_row_scalars': 'build accumulated row scalars from input tensors across dataset samples for WANDA pruning', 'run_sparsify_weight': "run WANDA sparsification on a module's weights given accumulated row scalars and target sparsity", 'test_make_empty_row_scalars': 'test making an empty row scalars tensor for a linear module on a specific device', 'refactor_sparsify_weight': 'refactor the sparsify_weight function to support structured N:M pruning with configurable prune_n and prune_m'}
```

