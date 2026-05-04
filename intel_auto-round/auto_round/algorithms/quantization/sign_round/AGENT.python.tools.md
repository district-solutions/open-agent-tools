# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/algorithms/quantization/sign_round/config.py

Prompts

```
['create a SignRoundConfig instance with custom iterations and learning rate for quantization', 'create a SignRoundConfig with enable_adam to use AdamRoundQuantizer instead of SignRoundQuantizer', 'create a SignRoundConfig with enable_minmax_tuning disabled to skip min-max parameter tuning', 'validate a SignRoundConfig instance by calling check_configs to verify batch size and iterations', 'review how SignRoundConfig auto-sets learning rate based on iteration count and bit width', 'build a python module that uses SignRoundQuantizer to quantize a model block with SignSGD optimizer and MSE loss', 'create a function that quantizes a single model layer outside a block using WrapperLinear and SignSGD', 'build a python module that configures SignRoundQuantizer with custom learning rate, momentum, and batch size settings', 'create a function that computes MSE loss between quantized and reference outputs with optional attention mask support', 'build a python module that enables minmax parameter tuning alongside round parameters during SignRound quantization', 'create a SignSGD optimizer for model parameters with a specified learning rate', 'run a single SignSGD optimization step on model parameters after computing gradients', 'build a functional SGD call that updates parameters using sign-based gradient descent', 'refactor the single tensor SGD function to apply sign-based parameter updates with momentum', 'review the SignSGD optimizer class to support Nesterov momentum with sign-based updates']
```

Usage

```
{'create_sign_round_config': 'create a SignRoundConfig instance with custom iterations and learning rate for quantization', 'create_sign_round_config_with_adam': 'create a SignRoundConfig with enable_adam to use AdamRoundQuantizer instead of SignRoundQuantizer', 'create_sign_round_config_minmax_tuning': 'create a SignRoundConfig with enable_minmax_tuning disabled to skip min-max parameter tuning', 'check_sign_round_config': 'validate a SignRoundConfig instance by calling check_configs to verify batch size and iterations', 'review_sign_round_config_lr': 'review how SignRoundConfig auto-sets learning rate based on iteration count and bit width'}
```

## File: intel_auto-round/auto_round/algorithms/quantization/sign_round/quantizer.py

Prompts

```
['create a SignRoundConfig instance with custom iterations and learning rate for quantization', 'create a SignRoundConfig with enable_adam to use AdamRoundQuantizer instead of SignRoundQuantizer', 'create a SignRoundConfig with enable_minmax_tuning disabled to skip min-max parameter tuning', 'validate a SignRoundConfig instance by calling check_configs to verify batch size and iterations', 'review how SignRoundConfig auto-sets learning rate based on iteration count and bit width', 'build a python module that uses SignRoundQuantizer to quantize a model block with SignSGD optimizer and MSE loss', 'create a function that quantizes a single model layer outside a block using WrapperLinear and SignSGD', 'build a python module that configures SignRoundQuantizer with custom learning rate, momentum, and batch size settings', 'create a function that computes MSE loss between quantized and reference outputs with optional attention mask support', 'build a python module that enables minmax parameter tuning alongside round parameters during SignRound quantization', 'create a SignSGD optimizer for model parameters with a specified learning rate', 'run a single SignSGD optimization step on model parameters after computing gradients', 'build a functional SGD call that updates parameters using sign-based gradient descent', 'refactor the single tensor SGD function to apply sign-based parameter updates with momentum', 'review the SignSGD optimizer class to support Nesterov momentum with sign-based updates']
```

Usage

```
{'quantize_block_with_sign_round': 'build a python module that uses SignRoundQuantizer to quantize a model block with SignSGD optimizer and MSE loss', 'quantize_layer_outside_block': 'create a function that quantizes a single model layer outside a block using WrapperLinear and SignSGD', 'configure_sign_round_optimizer': 'build a python module that configures SignRoundQuantizer with custom learning rate, momentum, and batch size settings', 'compute_mse_loss_with_mask': 'create a function that computes MSE loss between quantized and reference outputs with optional attention mask support', 'tune_minmax_parameters': 'build a python module that enables minmax parameter tuning alongside round parameters during SignRound quantization'}
```

## File: intel_auto-round/auto_round/algorithms/quantization/sign_round/sign_sgd.py

Prompts

```
['create a SignRoundConfig instance with custom iterations and learning rate for quantization', 'create a SignRoundConfig with enable_adam to use AdamRoundQuantizer instead of SignRoundQuantizer', 'create a SignRoundConfig with enable_minmax_tuning disabled to skip min-max parameter tuning', 'validate a SignRoundConfig instance by calling check_configs to verify batch size and iterations', 'review how SignRoundConfig auto-sets learning rate based on iteration count and bit width', 'build a python module that uses SignRoundQuantizer to quantize a model block with SignSGD optimizer and MSE loss', 'create a function that quantizes a single model layer outside a block using WrapperLinear and SignSGD', 'build a python module that configures SignRoundQuantizer with custom learning rate, momentum, and batch size settings', 'create a function that computes MSE loss between quantized and reference outputs with optional attention mask support', 'build a python module that enables minmax parameter tuning alongside round parameters during SignRound quantization', 'create a SignSGD optimizer for model parameters with a specified learning rate', 'run a single SignSGD optimization step on model parameters after computing gradients', 'build a functional SGD call that updates parameters using sign-based gradient descent', 'refactor the single tensor SGD function to apply sign-based parameter updates with momentum', 'review the SignSGD optimizer class to support Nesterov momentum with sign-based updates']
```

Usage

```
{'create_SignSGD_optimizer': 'create a SignSGD optimizer for model parameters with a specified learning rate', 'run_SignSGD_step': 'run a single SignSGD optimization step on model parameters after computing gradients', 'build_sgd_functional': 'build a functional SGD call that updates parameters using sign-based gradient descent', 'refactor_single_tensor_sgd': 'refactor the single tensor SGD function to apply sign-based parameter updates with momentum', 'review_SignSGD_nesterov': 'review the SignSGD optimizer class to support Nesterov momentum with sign-based updates'}
```

