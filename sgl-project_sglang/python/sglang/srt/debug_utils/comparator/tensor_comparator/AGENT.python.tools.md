# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/tensor_comparator/comparator.py

Prompts

```
['compute TensorInfo with shape, dtype, stats, and optional sample for a single PyTorch tensor', 'compare two PyTorch tensors and return TensorComparisonInfo with diff metrics and shape mismatch detection', 'compute TensorStats including mean, abs_mean, std, min, max, and percentiles for a PyTorch tensor', 'compute percentile values at default levels for a PyTorch tensor', 'compute DiffInfo with rel_diff, max_abs_diff, mean_abs_diff, and per-token rel_diff between two PyTorch tensors', 'summarize the format_comparison function that produces text output for tensor comparison info', 'summarize the format_comparison_rich function that formats tensor comparison records with rich markup and verbosity levels', 'review the format_replicated_checks function that formats replicated tensor check results with pass/fail markers', 'create format_stats_rich that produces aligned baseline vs target stat lines with mean, std, range, and percentiles', 'test the _format_bundle_section function that formats file bundle info with shapes, dtypes, and parallel metadata']
```

Usage

```
{'create_compute_tensor_info': 'compute TensorInfo with shape, dtype, stats, and optional sample for a single PyTorch tensor', 'compare_tensor_pair': 'compare two PyTorch tensors and return TensorComparisonInfo with diff metrics and shape mismatch detection', 'compute_tensor_stats': 'compute TensorStats including mean, abs_mean, std, min, max, and percentiles for a PyTorch tensor', 'compute_percentiles': 'compute percentile values at default levels for a PyTorch tensor', 'compute_diff': 'compute DiffInfo with rel_diff, max_abs_diff, mean_abs_diff, and per-token rel_diff between two PyTorch tensors'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/tensor_comparator/formatter.py

Prompts

```
['compute TensorInfo with shape, dtype, stats, and optional sample for a single PyTorch tensor', 'compare two PyTorch tensors and return TensorComparisonInfo with diff metrics and shape mismatch detection', 'compute TensorStats including mean, abs_mean, std, min, max, and percentiles for a PyTorch tensor', 'compute percentile values at default levels for a PyTorch tensor', 'compute DiffInfo with rel_diff, max_abs_diff, mean_abs_diff, and per-token rel_diff between two PyTorch tensors', 'summarize the format_comparison function that produces text output for tensor comparison info', 'summarize the format_comparison_rich function that formats tensor comparison records with rich markup and verbosity levels', 'review the format_replicated_checks function that formats replicated tensor check results with pass/fail markers', 'create format_stats_rich that produces aligned baseline vs target stat lines with mean, std, range, and percentiles', 'test the _format_bundle_section function that formats file bundle info with shapes, dtypes, and parallel metadata']
```

Usage

```
{'summarize_format_comparison': 'summarize the format_comparison function that produces text output for tensor comparison info', 'summarize_format_comparison_rich': 'summarize the format_comparison_rich function that formats tensor comparison records with rich markup and verbosity levels', 'review_format_replicated_checks': 'review the format_replicated_checks function that formats replicated tensor check results with pass/fail markers', 'create_format_stats_rich': 'create format_stats_rich that produces aligned baseline vs target stat lines with mean, std, range, and percentiles', 'test_format_bundle_section': 'test the _format_bundle_section function that formats file bundle info with shapes, dtypes, and parallel metadata'}
```

