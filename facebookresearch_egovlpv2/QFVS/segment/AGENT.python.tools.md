# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/QFVS/segment/cpd_auto.py

Prompts

```
['run cpd_auto to detect change points in a video kernel matrix with automatic number selection', 'run estimate_vmax to compute the variance parameter from a stable segment kernel matrix', 'run centering to apply kernel centering by subtracting row and column means from a kernel matrix', 'run eval_score to evaluate the unnormalized empirical score for given change points on a kernel matrix', 'run eval_cost to evaluate the cost function for automatic change point selection with a penalty term', 'run change point detection on a kernel matrix with dynamic programming to find segment boundaries', 'run scatter computation on a kernel matrix to precompute segment-wise variance values', 'test the cpd_nonlin function with a synthetic kernel matrix and verify detected change points', 'test the calc_scatters function with a symmetric kernel matrix and verify scatter values', 'refactor cpd_nonlin to leverage kernel matrix symmetry for faster scatter precomputation']
```

Usage

```
{'run_cpd_auto': 'run cpd_auto to detect change points in a video kernel matrix with automatic number selection', 'run_estimate_vmax': 'run estimate_vmax to compute the variance parameter from a stable segment kernel matrix', 'run_centering': 'run centering to apply kernel centering by subtracting row and column means from a kernel matrix', 'run_eval_score': 'run eval_score to evaluate the unnormalized empirical score for given change points on a kernel matrix', 'run_eval_cost': 'run eval_cost to evaluate the cost function for automatic change point selection with a penalty term'}
```

## File: facebookresearch_egovlpv2/QFVS/segment/cpd_nonlin.py

Prompts

```
['run cpd_auto to detect change points in a video kernel matrix with automatic number selection', 'run estimate_vmax to compute the variance parameter from a stable segment kernel matrix', 'run centering to apply kernel centering by subtracting row and column means from a kernel matrix', 'run eval_score to evaluate the unnormalized empirical score for given change points on a kernel matrix', 'run eval_cost to evaluate the cost function for automatic change point selection with a penalty term', 'run change point detection on a kernel matrix with dynamic programming to find segment boundaries', 'run scatter computation on a kernel matrix to precompute segment-wise variance values', 'test the cpd_nonlin function with a synthetic kernel matrix and verify detected change points', 'test the calc_scatters function with a symmetric kernel matrix and verify scatter values', 'refactor cpd_nonlin to leverage kernel matrix symmetry for faster scatter precomputation']
```

Usage

```
{'run_cpd_nonlin': 'run change point detection on a kernel matrix with dynamic programming to find segment boundaries', 'run_calc_scatters': 'run scatter computation on a kernel matrix to precompute segment-wise variance values', 'test_cpd_nonlin': 'test the cpd_nonlin function with a synthetic kernel matrix and verify detected change points', 'test_calc_scatters': 'test the calc_scatters function with a symmetric kernel matrix and verify scatter values', 'refactor_cpd_nonlin': 'refactor cpd_nonlin to leverage kernel matrix symmetry for faster scatter precomputation'}
```

