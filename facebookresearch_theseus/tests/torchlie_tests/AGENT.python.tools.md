# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/torchlie_tests/test_lie_tensor.py

Prompts

```
['test LieTensor operations like exp, hat, vee, compose, transform, and log for SE3 and SO3 Lie groups', 'test backward gradient flow through LieTensor operations using Adam optimizer and loss minimization', 'test jacobian-aware operations like jexp, jcompose, jlog, and jinv for SE3 and SO3 Lie groups', 'test the LieTensor class-based API against functional implementations for correctness across all Lie group operations', 'test SE3 and SO3 group operations including inverse, adjoint, left_act, and left_project methods', 'test the torchlie global parameter configuration for SE3 and SO3 Lie group operations', 'set global tolerance parameters like so3_near_zero_eps for Lie group numerical stability', 'reset all torchlie global parameters back to their default values', 'compute the Lie algebra logarithm of an SE3 group element using SE3.log', 'use the enable_checks context manager to validate SE3 hat tensors and SO3 group tensors']
```

Usage

```
{'test_lie_tensor_operations': 'test LieTensor operations like exp, hat, vee, compose, transform, and log for SE3 and SO3 Lie groups', 'test_backward_gradient_flow': 'test backward gradient flow through LieTensor operations using Adam optimizer and loss minimization', 'test_jacobian_operations': 'test jacobian-aware operations like jexp, jcompose, jlog, and jinv for SE3 and SO3 Lie groups', 'test_LieTensor_class_api': 'test the LieTensor class-based API against functional implementations for correctness across all Lie group operations', 'test_SE3_SO3_group_ops': 'test SE3 and SO3 group operations including inverse, adjoint, left_act, and left_project methods'}
```

## File: facebookresearch_theseus/tests/torchlie_tests/test_misc.py

Prompts

```
['test LieTensor operations like exp, hat, vee, compose, transform, and log for SE3 and SO3 Lie groups', 'test backward gradient flow through LieTensor operations using Adam optimizer and loss minimization', 'test jacobian-aware operations like jexp, jcompose, jlog, and jinv for SE3 and SO3 Lie groups', 'test the LieTensor class-based API against functional implementations for correctness across all Lie group operations', 'test SE3 and SO3 group operations including inverse, adjoint, left_act, and left_project methods', 'test the torchlie global parameter configuration for SE3 and SO3 Lie group operations', 'set global tolerance parameters like so3_near_zero_eps for Lie group numerical stability', 'reset all torchlie global parameters back to their default values', 'compute the Lie algebra logarithm of an SE3 group element using SE3.log', 'use the enable_checks context manager to validate SE3 hat tensors and SO3 group tensors']
```

Usage

```
{'test_global_options': 'test the torchlie global parameter configuration for SE3 and SO3 Lie group operations', 'set_global_params': 'set global tolerance parameters like so3_near_zero_eps for Lie group numerical stability', 'reset_global_params': 'reset all torchlie global parameters back to their default values', 'SE3_log': 'compute the Lie algebra logarithm of an SE3 group element using SE3.log', 'enable_checks': 'use the enable_checks context manager to validate SE3 hat tensors and SO3 group tensors'}
```

