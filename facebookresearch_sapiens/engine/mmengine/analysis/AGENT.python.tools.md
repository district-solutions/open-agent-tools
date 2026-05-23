# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/analysis/complexity_analysis.py

Prompts

```
['analyze a PyTorch model to get the total flop count using FlopAnalyzer', 'analyze a PyTorch model to get flop counts broken down by operator type', 'analyze a PyTorch model to get the total activation count using ActivationAnalyzer', 'run flop_count on a PyTorch model to get per-operator GFLOPs and unsupported ops', 'run parameter_count_table on a PyTorch model to print a formatted parameter count table', 'build a JitModelAnalysis instance to trace a PyTorch model and compute per-operator statistics', 'review the set_op_handle method to register custom operator handles for flop counting', 'test the by_module method to get aggregated statistics grouped by submodule names', 'summarize the by_operator method to get statistics grouped by operator type for a submodule', 'run the uncalled_modules method to find submodules never called during the trace', 'count the number of floating point operations for a convolution layer using conv_flop_count', 'count flops for a fully connected layer using the addmm_flop_jit handle', 'count flops for a batch matrix multiplication using the bmm_flop_jit handle', 'count flops for an einsum operation using the einsum_flop_jit handle', 'count flops for normalization layers using the norm_flop_counter factory function', 'get the complexity info of a PyTorch model including flops, activations, and parameters', 'build a string representation of a model with parameters and flops for each submodule', 'build a formatted table showing per-module parameters, flops, and activations for a model', 'format an integer into a human-readable string with K, M, G, or T suffixes', 'count the number of parameters in a PyTorch model organized by submodule']
```

Usage

```
{'analyze_FlopAnalyzer_total': 'analyze a PyTorch model to get the total flop count using FlopAnalyzer', 'analyze_FlopAnalyzer_by_operator': 'analyze a PyTorch model to get flop counts broken down by operator type', 'analyze_ActivationAnalyzer_total': 'analyze a PyTorch model to get the total activation count using ActivationAnalyzer', 'run_flop_count': 'run flop_count on a PyTorch model to get per-operator GFLOPs and unsupported ops', 'run_parameter_count_table': 'run parameter_count_table on a PyTorch model to print a formatted parameter count table'}
```

## File: facebookresearch_sapiens/engine/mmengine/analysis/jit_analysis.py

Prompts

```
['analyze a PyTorch model to get the total flop count using FlopAnalyzer', 'analyze a PyTorch model to get flop counts broken down by operator type', 'analyze a PyTorch model to get the total activation count using ActivationAnalyzer', 'run flop_count on a PyTorch model to get per-operator GFLOPs and unsupported ops', 'run parameter_count_table on a PyTorch model to print a formatted parameter count table', 'build a JitModelAnalysis instance to trace a PyTorch model and compute per-operator statistics', 'review the set_op_handle method to register custom operator handles for flop counting', 'test the by_module method to get aggregated statistics grouped by submodule names', 'summarize the by_operator method to get statistics grouped by operator type for a submodule', 'run the uncalled_modules method to find submodules never called during the trace', 'count the number of floating point operations for a convolution layer using conv_flop_count', 'count flops for a fully connected layer using the addmm_flop_jit handle', 'count flops for a batch matrix multiplication using the bmm_flop_jit handle', 'count flops for an einsum operation using the einsum_flop_jit handle', 'count flops for normalization layers using the norm_flop_counter factory function', 'get the complexity info of a PyTorch model including flops, activations, and parameters', 'build a string representation of a model with parameters and flops for each submodule', 'build a formatted table showing per-module parameters, flops, and activations for a model', 'format an integer into a human-readable string with K, M, G, or T suffixes', 'count the number of parameters in a PyTorch model organized by submodule']
```

Usage

```
{'build_JitModelAnalysis': 'build a JitModelAnalysis instance to trace a PyTorch model and compute per-operator statistics', 'review_JitModelAnalysis_set_op_handle': 'review the set_op_handle method to register custom operator handles for flop counting', 'test_JitModelAnalysis_by_module': 'test the by_module method to get aggregated statistics grouped by submodule names', 'summarize_JitModelAnalysis_by_operator': 'summarize the by_operator method to get statistics grouped by operator type for a submodule', 'run_JitModelAnalysis_uncalled_modules': 'run the uncalled_modules method to find submodules never called during the trace'}
```

## File: facebookresearch_sapiens/engine/mmengine/analysis/jit_handles.py

Prompts

```
['analyze a PyTorch model to get the total flop count using FlopAnalyzer', 'analyze a PyTorch model to get flop counts broken down by operator type', 'analyze a PyTorch model to get the total activation count using ActivationAnalyzer', 'run flop_count on a PyTorch model to get per-operator GFLOPs and unsupported ops', 'run parameter_count_table on a PyTorch model to print a formatted parameter count table', 'build a JitModelAnalysis instance to trace a PyTorch model and compute per-operator statistics', 'review the set_op_handle method to register custom operator handles for flop counting', 'test the by_module method to get aggregated statistics grouped by submodule names', 'summarize the by_operator method to get statistics grouped by operator type for a submodule', 'run the uncalled_modules method to find submodules never called during the trace', 'count the number of floating point operations for a convolution layer using conv_flop_count', 'count flops for a fully connected layer using the addmm_flop_jit handle', 'count flops for a batch matrix multiplication using the bmm_flop_jit handle', 'count flops for an einsum operation using the einsum_flop_jit handle', 'count flops for normalization layers using the norm_flop_counter factory function', 'get the complexity info of a PyTorch model including flops, activations, and parameters', 'build a string representation of a model with parameters and flops for each submodule', 'build a formatted table showing per-module parameters, flops, and activations for a model', 'format an integer into a human-readable string with K, M, G, or T suffixes', 'count the number of parameters in a PyTorch model organized by submodule']
```

Usage

```
{'count_conv_flops': 'count the number of floating point operations for a convolution layer using conv_flop_count', 'count_linear_flops': 'count flops for a fully connected layer using the addmm_flop_jit handle', 'count_bmm_flops': 'count flops for a batch matrix multiplication using the bmm_flop_jit handle', 'count_einsum_flops': 'count flops for an einsum operation using the einsum_flop_jit handle', 'count_norm_flops': 'count flops for normalization layers using the norm_flop_counter factory function'}
```

## File: facebookresearch_sapiens/engine/mmengine/analysis/print_helper.py

Prompts

```
['analyze a PyTorch model to get the total flop count using FlopAnalyzer', 'analyze a PyTorch model to get flop counts broken down by operator type', 'analyze a PyTorch model to get the total activation count using ActivationAnalyzer', 'run flop_count on a PyTorch model to get per-operator GFLOPs and unsupported ops', 'run parameter_count_table on a PyTorch model to print a formatted parameter count table', 'build a JitModelAnalysis instance to trace a PyTorch model and compute per-operator statistics', 'review the set_op_handle method to register custom operator handles for flop counting', 'test the by_module method to get aggregated statistics grouped by submodule names', 'summarize the by_operator method to get statistics grouped by operator type for a submodule', 'run the uncalled_modules method to find submodules never called during the trace', 'count the number of floating point operations for a convolution layer using conv_flop_count', 'count flops for a fully connected layer using the addmm_flop_jit handle', 'count flops for a batch matrix multiplication using the bmm_flop_jit handle', 'count flops for an einsum operation using the einsum_flop_jit handle', 'count flops for normalization layers using the norm_flop_counter factory function', 'get the complexity info of a PyTorch model including flops, activations, and parameters', 'build a string representation of a model with parameters and flops for each submodule', 'build a formatted table showing per-module parameters, flops, and activations for a model', 'format an integer into a human-readable string with K, M, G, or T suffixes', 'count the number of parameters in a PyTorch model organized by submodule']
```

Usage

```
{'get_model_complexity_info': 'get the complexity info of a PyTorch model including flops, activations, and parameters', 'complexity_stats_str': 'build a string representation of a model with parameters and flops for each submodule', 'complexity_stats_table': 'build a formatted table showing per-module parameters, flops, and activations for a model', 'format_size': 'format an integer into a human-readable string with K, M, G, or T suffixes', 'parameter_count': 'count the number of parameters in a PyTorch model organized by submodule'}
```

