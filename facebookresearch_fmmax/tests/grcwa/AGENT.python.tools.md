# Agent Python Tools

- repo: facebookresearch/fmmax
- repo_uri: https://github.com/facebookresearch/fmmax

## File: facebookresearch_fmmax/tests/grcwa/test_fmm.py

Prompts

```
['run the test to compare uniform layer eigenvalues and eigenvectors against grcwa', 'run the test to compare patterned layer eigenvalues and eigenvectors against grcwa', 'test the _sort_eigs function that sorts eigenvalues and enforces phase convention', 'review the fmm._eigensolve_uniform_isotropic_media function for uniform layer eigensolving', 'review the fmm._eigensolve_patterned_isotropic_media function for patterned layer eigensolving', 'test the ScatteringMatrixTest class to verify fmmax scattering stack_s_matrix matches grcwa results', 'test the test_compare_to_grcwa method to validate S-matrix computation against grcwa with dummy solve results', 'test the test_compare_to_grcwa_actual_solve method to validate S-matrix against grcwa with real eigensolve results', 'run the unittest ScatteringMatrixTest suite to compare fmmax scattering matrix output with grcwa reference', 'review the _dummy_solve_result and _stack_solve_result helper functions that generate test data for scattering tests']
```

Usage

```
{'run_uniform_layer_eigensolve_test': 'run the test to compare uniform layer eigenvalues and eigenvectors against grcwa', 'run_patterned_layer_eigensolve_test': 'run the test to compare patterned layer eigenvalues and eigenvectors against grcwa', 'test_sort_eigs': 'test the _sort_eigs function that sorts eigenvalues and enforces phase convention', 'review_eigensolve_uniform_isotropic_media': 'review the fmm._eigensolve_uniform_isotropic_media function for uniform layer eigensolving', 'review_eigensolve_patterned_isotropic_media': 'review the fmm._eigensolve_patterned_isotropic_media function for patterned layer eigensolving'}
```

## File: facebookresearch_fmmax/tests/grcwa/test_scattering.py

Prompts

```
['run the test to compare uniform layer eigenvalues and eigenvectors against grcwa', 'run the test to compare patterned layer eigenvalues and eigenvectors against grcwa', 'test the _sort_eigs function that sorts eigenvalues and enforces phase convention', 'review the fmm._eigensolve_uniform_isotropic_media function for uniform layer eigensolving', 'review the fmm._eigensolve_patterned_isotropic_media function for patterned layer eigensolving', 'test the ScatteringMatrixTest class to verify fmmax scattering stack_s_matrix matches grcwa results', 'test the test_compare_to_grcwa method to validate S-matrix computation against grcwa with dummy solve results', 'test the test_compare_to_grcwa_actual_solve method to validate S-matrix against grcwa with real eigensolve results', 'run the unittest ScatteringMatrixTest suite to compare fmmax scattering matrix output with grcwa reference', 'review the _dummy_solve_result and _stack_solve_result helper functions that generate test data for scattering tests']
```

Usage

```
{'test_scattering_matrix_s_matrix': 'test the ScatteringMatrixTest class to verify fmmax scattering stack_s_matrix matches grcwa results', 'test_compare_to_grcwa': 'test the test_compare_to_grcwa method to validate S-matrix computation against grcwa with dummy solve results', 'test_compare_to_grcwa_actual_solve': 'test the test_compare_to_grcwa_actual_solve method to validate S-matrix against grcwa with real eigensolve results', 'run_scattering_tests': 'run the unittest ScatteringMatrixTest suite to compare fmmax scattering matrix output with grcwa reference', 'review_scattering_test_helpers': 'review the _dummy_solve_result and _stack_solve_result helper functions that generate test data for scattering tests'}
```

