# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/embodied/misc/test_variable_difference.py

Prompts

```
['test the Difference cost function jacobian computation against numerical jacobian for SO2, SE2, SO3, and SE3 groups', 'test copying a Difference cost function and verify all internal variables, targets, and weights are deep copied', 'test the Difference cost function error computation for Point2 variables by comparing against expected tensor subtraction', 'test the Difference cost function error for SO2 rotations by comparing against precomputed squared distance errors', 'test the Difference cost function error for SE2 poses by comparing against precomputed squared distance errors']
```

Usage

```
{'test_Difference_jacobian_SO2_SE2_SO3_SE3': 'test the Difference cost function jacobian computation against numerical jacobian for SO2, SE2, SO3, and SE3 groups', 'test_Difference_copy': 'test copying a Difference cost function and verify all internal variables, targets, and weights are deep copied', 'test_Difference_error_Point2': 'test the Difference cost function error computation for Point2 variables by comparing against expected tensor subtraction', 'test_Difference_error_SO2': 'test the Difference cost function error for SO2 rotations by comparing against precomputed squared distance errors', 'test_Difference_error_SE2': 'test the Difference cost function error for SE2 poses by comparing against precomputed squared distance errors'}
```

