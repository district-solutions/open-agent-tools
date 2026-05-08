# Agent Python Tools

- repo: facebookresearch/higher
- repo_uri: https://github.com/facebookresearch/higher

## File: facebookresearch_higher/tests/test_higher.py

Prompts

```
['test that higher.innerloop_ctx preserves fast weight equality after monkey patching a PyTorch module', 'test that unrolled patched and reference networks produce identical meta loss values over inner loop steps', 'test that metagrads computed via torch.autograd.grad match between reference and patched networks', 'test inner loop SGD updates without a differentiable optimizer by manually computing and applying gradients', 'test the _ReferenceNet forward pass with explicit fast weight parameters for conv and batch norm layers', 'test diff-optim correctness across SGD, Adam, AdamW optimizers with various model configurations', 'test gradient correctness by comparing autograd gradients against finite difference approximations', 'test that diffopt handles models with frozen parameters that have requires_grad set to False', 'test get_trainable_opt_params and apply_trainable_opt_params round-trip to verify learned hyperparameter extraction and restoration', 'test gradient callback functionality by applying different gradient scaling callbacks and verifying parameter divergence', 'test higher.patch.make_functional to convert a PyTorch model into a callable functional form', 'test higher.patch.monkeypatch to patch a PyTorch model for differentiable inner-loop optimization', 'test higher.innerloop_ctx context manager to run MAML-style inner-loop SGD updates on a model', 'test higher.utils.get_func_params to extract functional parameters from a PyTorch model', 'test setting fmodel.fast_params to update patched model weights after computing differentiable gradients']
```

Usage

```
{'test_innerloop_ctx_fast_weights': 'test that higher.innerloop_ctx preserves fast weight equality after monkey patching a PyTorch module', 'test_unroll_equality_forward': 'test that unrolled patched and reference networks produce identical meta loss values over inner loop steps', 'test_unroll_equality_backward': 'test that metagrads computed via torch.autograd.grad match between reference and patched networks', 'test_manual_unroll_inner_loop': 'test inner loop SGD updates without a differentiable optimizer by manually computing and applying gradients', 'test_reference_net_forward_with_params': 'test the _ReferenceNet forward pass with explicit fast weight parameters for conv and batch norm layers'}
```

## File: facebookresearch_higher/tests/test_optim.py

Prompts

```
['test that higher.innerloop_ctx preserves fast weight equality after monkey patching a PyTorch module', 'test that unrolled patched and reference networks produce identical meta loss values over inner loop steps', 'test that metagrads computed via torch.autograd.grad match between reference and patched networks', 'test inner loop SGD updates without a differentiable optimizer by manually computing and applying gradients', 'test the _ReferenceNet forward pass with explicit fast weight parameters for conv and batch norm layers', 'test diff-optim correctness across SGD, Adam, AdamW optimizers with various model configurations', 'test gradient correctness by comparing autograd gradients against finite difference approximations', 'test that diffopt handles models with frozen parameters that have requires_grad set to False', 'test get_trainable_opt_params and apply_trainable_opt_params round-trip to verify learned hyperparameter extraction and restoration', 'test gradient callback functionality by applying different gradient scaling callbacks and verifying parameter divergence', 'test higher.patch.make_functional to convert a PyTorch model into a callable functional form', 'test higher.patch.monkeypatch to patch a PyTorch model for differentiable inner-loop optimization', 'test higher.innerloop_ctx context manager to run MAML-style inner-loop SGD updates on a model', 'test higher.utils.get_func_params to extract functional parameters from a PyTorch model', 'test setting fmodel.fast_params to update patched model weights after computing differentiable gradients']
```

Usage

```
{'test_diff_opt_correctness': 'test diff-optim correctness across SGD, Adam, AdamW optimizers with various model configurations', 'test_gradient_correctness': 'test gradient correctness by comparing autograd gradients against finite difference approximations', 'test_frozen_parameters': 'test that diffopt handles models with frozen parameters that have requires_grad set to False', 'test_get_apply_round_trip': 'test get_trainable_opt_params and apply_trainable_opt_params round-trip to verify learned hyperparameter extraction and restoration', 'test_diff_opt_callback': 'test gradient callback functionality by applying different gradient scaling callbacks and verifying parameter divergence'}
```

## File: facebookresearch_higher/tests/test_patch.py

Prompts

```
['test that higher.innerloop_ctx preserves fast weight equality after monkey patching a PyTorch module', 'test that unrolled patched and reference networks produce identical meta loss values over inner loop steps', 'test that metagrads computed via torch.autograd.grad match between reference and patched networks', 'test inner loop SGD updates without a differentiable optimizer by manually computing and applying gradients', 'test the _ReferenceNet forward pass with explicit fast weight parameters for conv and batch norm layers', 'test diff-optim correctness across SGD, Adam, AdamW optimizers with various model configurations', 'test gradient correctness by comparing autograd gradients against finite difference approximations', 'test that diffopt handles models with frozen parameters that have requires_grad set to False', 'test get_trainable_opt_params and apply_trainable_opt_params round-trip to verify learned hyperparameter extraction and restoration', 'test gradient callback functionality by applying different gradient scaling callbacks and verifying parameter divergence', 'test higher.patch.make_functional to convert a PyTorch model into a callable functional form', 'test higher.patch.monkeypatch to patch a PyTorch model for differentiable inner-loop optimization', 'test higher.innerloop_ctx context manager to run MAML-style inner-loop SGD updates on a model', 'test higher.utils.get_func_params to extract functional parameters from a PyTorch model', 'test setting fmodel.fast_params to update patched model weights after computing differentiable gradients']
```

Usage

```
{'test_make_functional': 'test higher.patch.make_functional to convert a PyTorch model into a callable functional form', 'test_monkeypatch': 'test higher.patch.monkeypatch to patch a PyTorch model for differentiable inner-loop optimization', 'test_innerloop_ctx': 'test higher.innerloop_ctx context manager to run MAML-style inner-loop SGD updates on a model', 'test_get_func_params': 'test higher.utils.get_func_params to extract functional parameters from a PyTorch model', 'test_fast_params': 'test setting fmodel.fast_params to update patched model weights after computing differentiable gradients'}
```

