# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/modules/masking/test_random_masking.py

Prompts

```
['test the random_masking function with various mask ratios and validate masked output tensors', 'test the random_masking_2d function with horizontal and vertical mask ratios on patch grids', 'test that random_masking raises an AssertionError when given an invalid mask ratio above 1.0', 'test random_masking with a zero mask ratio to verify no tokens are masked', 'test random_masking_2d with partial masking at 0.5 ratio for both height and width dimensions']
```

Usage

```
{'test_random_masking': 'test the random_masking function with various mask ratios and validate masked output tensors', 'test_random_masking_2d': 'test the random_masking_2d function with horizontal and vertical mask ratios on patch grids', 'test_random_masking_invalid_ratio': 'test that random_masking raises an AssertionError when given an invalid mask ratio above 1.0', 'test_random_masking_zero_ratio': 'test random_masking with a zero mask ratio to verify no tokens are masked', 'test_random_masking_2d_partial': 'test random_masking_2d with partial masking at 0.5 ratio for both height and width dimensions'}
```

