# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/testing/test_case.py

Prompts

```
["test the TestCase.get_state method to extract a model's state dict as numpy arrays", 'test the TestCase.assertStateEqual method to verify two model states are identical', 'test the TestCase.assertStateAllNotEqual method to verify two model states differ in every tensor', 'review the TestCase class that provides model state comparison utilities for unit tests', 'review the Platform class that configures a CPU-only non-parallel testing environment', 'create an InnerProductModel with a linear layer initialized with arange weights for dimension n', 'run the forward pass of InnerProductModel on input tensor x to get linear output', 'test the InnerProductModel loss_criterion property which returns an MSELoss instance', 'review the InnerProductModel init method that sets up a bias-free linear layer with arange weights', 'summarize the InnerProductModel class a minimal PyTorch toy model extending Model with a single linear layer']
```

Usage

```
{'test_TestCase_get_state': "test the TestCase.get_state method to extract a model's state dict as numpy arrays", 'test_TestCase_assertStateEqual': 'test the TestCase.assertStateEqual method to verify two model states are identical', 'test_TestCase_assertStateAllNotEqual': 'test the TestCase.assertStateAllNotEqual method to verify two model states differ in every tensor', 'review_TestCase_class': 'review the TestCase class that provides model state comparison utilities for unit tests', 'review_Platform_class': 'review the Platform class that configures a CPU-only non-parallel testing environment'}
```

## File: facebookresearch_openlth/testing/toy_model.py

Prompts

```
["test the TestCase.get_state method to extract a model's state dict as numpy arrays", 'test the TestCase.assertStateEqual method to verify two model states are identical', 'test the TestCase.assertStateAllNotEqual method to verify two model states differ in every tensor', 'review the TestCase class that provides model state comparison utilities for unit tests', 'review the Platform class that configures a CPU-only non-parallel testing environment', 'create an InnerProductModel with a linear layer initialized with arange weights for dimension n', 'run the forward pass of InnerProductModel on input tensor x to get linear output', 'test the InnerProductModel loss_criterion property which returns an MSELoss instance', 'review the InnerProductModel init method that sets up a bias-free linear layer with arange weights', 'summarize the InnerProductModel class a minimal PyTorch toy model extending Model with a single linear layer']
```

Usage

```
{'create_InnerProductModel': 'create an InnerProductModel with a linear layer initialized with arange weights for dimension n', 'run_forward_InnerProductModel': 'run the forward pass of InnerProductModel on input tensor x to get linear output', 'test_loss_criterion': 'test the InnerProductModel loss_criterion property which returns an MSELoss instance', 'review_InnerProductModel_init': 'review the InnerProductModel init method that sets up a bias-free linear layer with arange weights', 'summarize_InnerProductModel': 'summarize the InnerProductModel class a minimal PyTorch toy model extending Model with a single linear layer'}
```

