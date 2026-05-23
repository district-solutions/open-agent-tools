# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/torchlie_tests/functional/common.py

Prompts

```
['run unit tests for a Lie group operator checking jacobian consistency and multi-batch output', 'sample random tensor inputs of specified types for Lie group operator testing', 'check that Lie group function jacobians from autograd match custom backward implementations', 'check vmap jacrev works for unary Lie group operations like exp and inv', 'check binary Lie group operations like compose and transform handle broadcasting correctly', 'test SE3 Lie group operations like exp, log, adjoint, inverse, hat, compose, transform across batch sizes and dtypes', 'test the vee operator by verifying hat and vee are inverse operations on SE3 tangent vectors', 'test Jacobian reverse-mode differentiation for unary SE3 operations like exp and inverse', 'test Jacobian reverse-mode differentiation for binary SE3 operations like compose, transform, and untransform', 'test binary operation broadcasting behavior for SE3 compose, transform, and untransform across various batch shapes', 'run pytest tests for SO3 Lie group operations including exp, log, adjoint, inverse, hat, compose, transform', 'test the vee operator by verifying hat and vee are inverse operations on SO3 tangent vectors', 'test reverse-mode Jacobian correctness for unary SO3 operations like exp and inverse', 'test reverse-mode Jacobian correctness for binary SO3 operations like compose and transform', 'test binary operation and left project broadcasting behavior across various batch sizes for SO3']
```

Usage

```
{'run_test_op': 'run unit tests for a Lie group operator checking jacobian consistency and multi-batch output', 'sample_inputs': 'sample random tensor inputs of specified types for Lie group operator testing', 'check_lie_group_function': 'check that Lie group function jacobians from autograd match custom backward implementations', 'check_jacrev_unary': 'check vmap jacrev works for unary Lie group operations like exp and inv', 'check_binary_op_broadcasting': 'check binary Lie group operations like compose and transform handle broadcasting correctly'}
```

## File: facebookresearch_theseus/tests/torchlie_tests/functional/test_se3.py

Prompts

```
['run unit tests for a Lie group operator checking jacobian consistency and multi-batch output', 'sample random tensor inputs of specified types for Lie group operator testing', 'check that Lie group function jacobians from autograd match custom backward implementations', 'check vmap jacrev works for unary Lie group operations like exp and inv', 'check binary Lie group operations like compose and transform handle broadcasting correctly', 'test SE3 Lie group operations like exp, log, adjoint, inverse, hat, compose, transform across batch sizes and dtypes', 'test the vee operator by verifying hat and vee are inverse operations on SE3 tangent vectors', 'test Jacobian reverse-mode differentiation for unary SE3 operations like exp and inverse', 'test Jacobian reverse-mode differentiation for binary SE3 operations like compose, transform, and untransform', 'test binary operation broadcasting behavior for SE3 compose, transform, and untransform across various batch shapes', 'run pytest tests for SO3 Lie group operations including exp, log, adjoint, inverse, hat, compose, transform', 'test the vee operator by verifying hat and vee are inverse operations on SO3 tangent vectors', 'test reverse-mode Jacobian correctness for unary SO3 operations like exp and inverse', 'test reverse-mode Jacobian correctness for binary SO3 operations like compose and transform', 'test binary operation and left project broadcasting behavior across various batch sizes for SO3']
```

Usage

```
{'test_SE3_operations': 'test SE3 Lie group operations like exp, log, adjoint, inverse, hat, compose, transform across batch sizes and dtypes', 'test_vee_hat_roundtrip': 'test the vee operator by verifying hat and vee are inverse operations on SE3 tangent vectors', 'test_jacrev_unary_SE3': 'test Jacobian reverse-mode differentiation for unary SE3 operations like exp and inverse', 'test_jacrev_binary_SE3': 'test Jacobian reverse-mode differentiation for binary SE3 operations like compose, transform, and untransform', 'test_SE3_broadcasting': 'test binary operation broadcasting behavior for SE3 compose, transform, and untransform across various batch shapes'}
```

## File: facebookresearch_theseus/tests/torchlie_tests/functional/test_so3.py

Prompts

```
['run unit tests for a Lie group operator checking jacobian consistency and multi-batch output', 'sample random tensor inputs of specified types for Lie group operator testing', 'check that Lie group function jacobians from autograd match custom backward implementations', 'check vmap jacrev works for unary Lie group operations like exp and inv', 'check binary Lie group operations like compose and transform handle broadcasting correctly', 'test SE3 Lie group operations like exp, log, adjoint, inverse, hat, compose, transform across batch sizes and dtypes', 'test the vee operator by verifying hat and vee are inverse operations on SE3 tangent vectors', 'test Jacobian reverse-mode differentiation for unary SE3 operations like exp and inverse', 'test Jacobian reverse-mode differentiation for binary SE3 operations like compose, transform, and untransform', 'test binary operation broadcasting behavior for SE3 compose, transform, and untransform across various batch shapes', 'run pytest tests for SO3 Lie group operations including exp, log, adjoint, inverse, hat, compose, transform', 'test the vee operator by verifying hat and vee are inverse operations on SO3 tangent vectors', 'test reverse-mode Jacobian correctness for unary SO3 operations like exp and inverse', 'test reverse-mode Jacobian correctness for binary SO3 operations like compose and transform', 'test binary operation and left project broadcasting behavior across various batch sizes for SO3']
```

Usage

```
{'test_SO3_operations': 'run pytest tests for SO3 Lie group operations including exp, log, adjoint, inverse, hat, compose, transform', 'test_SO3_vee': 'test the vee operator by verifying hat and vee are inverse operations on SO3 tangent vectors', 'test_SO3_jacrev_unary': 'test reverse-mode Jacobian correctness for unary SO3 operations like exp and inverse', 'test_SO3_jacrev_binary': 'test reverse-mode Jacobian correctness for binary SO3 operations like compose and transform', 'test_SO3_broadcasting': 'test binary operation and left project broadcasting behavior across various batch sizes for SO3'}
```

