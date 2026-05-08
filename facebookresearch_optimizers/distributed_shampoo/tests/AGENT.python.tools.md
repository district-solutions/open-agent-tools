# Agent Python Tools

- repo: facebookresearch/optimizers
- repo_uri: https://github.com/facebookresearch/optimizers

## File: facebookresearch_optimizers/distributed_shampoo/tests/distributed_shampoo_test.py

Prompts

```
['create a DistributedShampoo optimizer with DefaultShampooConfig preconditioner for a PyTorch model', 'test that DistributedShampoo raises ValueError for invalid lr, betas, epsilon, or weight_decay settings', 'test that DistributedShampoo state_dict and load_state_dict correctly serialize and restore optimizer state', 'test that DistributedShampoo train and eval mode switching works with GeneralizedPrimalAveragingConfig or ScheduleFreeConfig', 'test that DistributedShampoo zero_grad with set_to_none properly frees gradient memory via garbage collection', 'construct a training problem with a model, loss function, input data, and target tensor for optimizer testing', 'train a model for a specified number of steps using a given optimizer and model factory', 'compare two optimizers on the same device by training identical models and asserting close weights and loss', 'compare two optimizers across different devices by training models and asserting close weights and loss', 'compare the same optimizer running on CPU versus another device by asserting close weights and loss', 'test AdaGradPreconditionerConfig subclasses reject invalid epsilon values of 0.0 or negative', 'test RMSpropPreconditionerConfig subclasses reject beta2 values outside the range (0.0, 1.0]', 'test ClassicShampooPreconditionerConfig rejects non-positive orders or invalid dimension overrides in inverse_exponent_override', 'test EigenvalueCorrectedShampooPreconditionerConfig rejects duplicate or out-of-range ignored basis change dimensions', 'test SignDescentPreconditionerConfig default and custom scale_fn behavior with torch gradient tensors']
```

Usage

```
{'init_distributed_shampoo_optimizer': 'create a DistributedShampoo optimizer with DefaultShampooConfig preconditioner for a PyTorch model', 'test_invalid_hyperparameters': 'test that DistributedShampoo raises ValueError for invalid lr, betas, epsilon, or weight_decay settings', 'test_state_dict_serialization': 'test that DistributedShampoo state_dict and load_state_dict correctly serialize and restore optimizer state', 'test_train_eval_mode_switching': 'test that DistributedShampoo train and eval mode switching works with GeneralizedPrimalAveragingConfig or ScheduleFreeConfig', 'test_zero_grad_memory_freeing': 'test that DistributedShampoo zero_grad with set_to_none properly frees gradient memory via garbage collection'}
```

## File: facebookresearch_optimizers/distributed_shampoo/tests/shampoo_test_utils.py

Prompts

```
['create a DistributedShampoo optimizer with DefaultShampooConfig preconditioner for a PyTorch model', 'test that DistributedShampoo raises ValueError for invalid lr, betas, epsilon, or weight_decay settings', 'test that DistributedShampoo state_dict and load_state_dict correctly serialize and restore optimizer state', 'test that DistributedShampoo train and eval mode switching works with GeneralizedPrimalAveragingConfig or ScheduleFreeConfig', 'test that DistributedShampoo zero_grad with set_to_none properly frees gradient memory via garbage collection', 'construct a training problem with a model, loss function, input data, and target tensor for optimizer testing', 'train a model for a specified number of steps using a given optimizer and model factory', 'compare two optimizers on the same device by training identical models and asserting close weights and loss', 'compare two optimizers across different devices by training models and asserting close weights and loss', 'compare the same optimizer running on CPU versus another device by asserting close weights and loss', 'test AdaGradPreconditionerConfig subclasses reject invalid epsilon values of 0.0 or negative', 'test RMSpropPreconditionerConfig subclasses reject beta2 values outside the range (0.0, 1.0]', 'test ClassicShampooPreconditionerConfig rejects non-positive orders or invalid dimension overrides in inverse_exponent_override', 'test EigenvalueCorrectedShampooPreconditionerConfig rejects duplicate or out-of-range ignored basis change dimensions', 'test SignDescentPreconditionerConfig default and custom scale_fn behavior with torch gradient tensors']
```

Usage

```
{'construct_training_problem': 'construct a training problem with a model, loss function, input data, and target tensor for optimizer testing', 'train_model': 'train a model for a specified number of steps using a given optimizer and model factory', 'compare_two_optimizers_on_weight_and_loss': 'compare two optimizers on the same device by training identical models and asserting close weights and loss', 'compare_two_optimizers_devices_on_weight_and_loss': 'compare two optimizers across different devices by training models and asserting close weights and loss', 'compare_optimizer_on_cpu_and_device': 'compare the same optimizer running on CPU versus another device by asserting close weights and loss'}
```

## File: facebookresearch_optimizers/distributed_shampoo/tests/shampoo_types_test.py

Prompts

```
['create a DistributedShampoo optimizer with DefaultShampooConfig preconditioner for a PyTorch model', 'test that DistributedShampoo raises ValueError for invalid lr, betas, epsilon, or weight_decay settings', 'test that DistributedShampoo state_dict and load_state_dict correctly serialize and restore optimizer state', 'test that DistributedShampoo train and eval mode switching works with GeneralizedPrimalAveragingConfig or ScheduleFreeConfig', 'test that DistributedShampoo zero_grad with set_to_none properly frees gradient memory via garbage collection', 'construct a training problem with a model, loss function, input data, and target tensor for optimizer testing', 'train a model for a specified number of steps using a given optimizer and model factory', 'compare two optimizers on the same device by training identical models and asserting close weights and loss', 'compare two optimizers across different devices by training models and asserting close weights and loss', 'compare the same optimizer running on CPU versus another device by asserting close weights and loss', 'test AdaGradPreconditionerConfig subclasses reject invalid epsilon values of 0.0 or negative', 'test RMSpropPreconditionerConfig subclasses reject beta2 values outside the range (0.0, 1.0]', 'test ClassicShampooPreconditionerConfig rejects non-positive orders or invalid dimension overrides in inverse_exponent_override', 'test EigenvalueCorrectedShampooPreconditionerConfig rejects duplicate or out-of-range ignored basis change dimensions', 'test SignDescentPreconditionerConfig default and custom scale_fn behavior with torch gradient tensors']
```

Usage

```
{'test_adagrad_epsilon_validation': 'test AdaGradPreconditionerConfig subclasses reject invalid epsilon values of 0.0 or negative', 'test_rmsprop_beta2_validation': 'test RMSpropPreconditionerConfig subclasses reject beta2 values outside the range (0.0, 1.0]', 'test_classic_shampoo_inverse_exponent': 'test ClassicShampooPreconditionerConfig rejects non-positive orders or invalid dimension overrides in inverse_exponent_override', 'test_eigenvalue_corrected_basis_change': 'test EigenvalueCorrectedShampooPreconditionerConfig rejects duplicate or out-of-range ignored basis change dimensions', 'test_sign_descent_scale_fn': 'test SignDescentPreconditionerConfig default and custom scale_fn behavior with torch gradient tensors'}
```

