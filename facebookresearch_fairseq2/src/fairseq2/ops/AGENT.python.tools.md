# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/ops/shape.py

Prompts

```
['unsqueeze a PyTorch tensor along a given dimension multiple times using the unsqueeze helper', 'repeat elements of a PyTorch tensor along a single dimension using the lightweight repeat_interleave function', 'review the unsqueeze function that loops to unsqueeze a tensor along a dimension count times', 'review the repeat_interleave function that uses unsqueeze, expand, and flatten for fast single-dimension repetition', 'summarize the shape utility module providing unsqueeze and repeat_interleave helpers for PyTorch tensors', 'reduce a tensor across all processes in a gang using all-reduce with SUM operation', 'scatter a tensor across all processes in a gang over a specified dimension', 'gather a tensor from all processes in a gang along a specified dimension', 'reduce the gradient of a tensor across all processes in a gang during the backward pass', 'review the scatter and gather autograd-aware tensor parallel operations for correctness']
```

Usage

```
{'unsqueeze_tensor_multiple_times': 'unsqueeze a PyTorch tensor along a given dimension multiple times using the unsqueeze helper', 'repeat_interleave_tensor_along_dim': 'repeat elements of a PyTorch tensor along a single dimension using the lightweight repeat_interleave function', 'review_unsqueeze_function': 'review the unsqueeze function that loops to unsqueeze a tensor along a dimension count times', 'review_repeat_interleave_function': 'review the repeat_interleave function that uses unsqueeze, expand, and flatten for fast single-dimension repetition', 'summarize_shape_operations': 'summarize the shape utility module providing unsqueeze and repeat_interleave helpers for PyTorch tensors'}
```

## File: facebookresearch_fairseq2/src/fairseq2/ops/tensor_parallel.py

Prompts

```
['unsqueeze a PyTorch tensor along a given dimension multiple times using the unsqueeze helper', 'repeat elements of a PyTorch tensor along a single dimension using the lightweight repeat_interleave function', 'review the unsqueeze function that loops to unsqueeze a tensor along a dimension count times', 'review the repeat_interleave function that uses unsqueeze, expand, and flatten for fast single-dimension repetition', 'summarize the shape utility module providing unsqueeze and repeat_interleave helpers for PyTorch tensors', 'reduce a tensor across all processes in a gang using all-reduce with SUM operation', 'scatter a tensor across all processes in a gang over a specified dimension', 'gather a tensor from all processes in a gang along a specified dimension', 'reduce the gradient of a tensor across all processes in a gang during the backward pass', 'review the scatter and gather autograd-aware tensor parallel operations for correctness']
```

Usage

```
{'reduce_tensor_across_gang': 'reduce a tensor across all processes in a gang using all-reduce with SUM operation', 'scatter_tensor_across_gang': 'scatter a tensor across all processes in a gang over a specified dimension', 'gather_tensor_across_gang': 'gather a tensor from all processes in a gang along a specified dimension', 'reduce_gradient_on_backward': 'reduce the gradient of a tensor across all processes in a gang during the backward pass', 'review_scatter_gather_ops': 'review the scatter and gather autograd-aware tensor parallel operations for correctness'}
```

