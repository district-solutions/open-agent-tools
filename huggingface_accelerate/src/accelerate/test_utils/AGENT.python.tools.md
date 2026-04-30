# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/src/accelerate/test_utils/examples.py

Prompts

```
["extract a named function's source lines from a list of code lines by function name", 'clean a list of code lines by removing comment lines and blank lines', 'compare a feature example script against a complete example script to find missing implementations', 'test the compare_against_test function to verify feature examples are implemented in complete examples', 'review the get_function_contents_by_name function that extracts function source code from segmented lines', 'test the get_backend function to detect the current hardware accelerator backend and device count', 'build a subprocess launch command list for accelerate with kwargs like num_processes and device_count', 'run an async subprocess command with streaming stdout/stderr and timeout handling', 'test the AccelerateTestCase class that resets AcceleratorState singleton after every test method', 'test the assert_exception context manager to verify expected exception classes and messages are raised', 'create a RegressionDataset with custom slope, intercept, length, and seed for synthetic linear data generation', 'create a RegressionModel as a PyTorch module with learnable parameters a and b for linear regression', 'test mocked_dataloaders to build train and eval DataLoaders from MRPC dataset with BERT tokenizer', 'test mocked_dataloaders_for_autoregressive_models to build dataloaders for autoregressive language models with SmolLM tokenizer', 'review RegressionModel forward method that computes x * a + b with dtype logging on first batch']
```

Usage

```
{'extract_function_contents_by_name': "extract a named function's source lines from a list of code lines by function name", 'clean_lines_remove_comments': 'clean a list of code lines by removing comment lines and blank lines', 'compare_against_test': 'compare a feature example script against a complete example script to find missing implementations', 'test_compare_against_test': 'test the compare_against_test function to verify feature examples are implemented in complete examples', 'review_get_function_contents_by_name': 'review the get_function_contents_by_name function that extracts function source code from segmented lines'}
```

## File: huggingface_accelerate/src/accelerate/test_utils/testing.py

Prompts

```
["extract a named function's source lines from a list of code lines by function name", 'clean a list of code lines by removing comment lines and blank lines', 'compare a feature example script against a complete example script to find missing implementations', 'test the compare_against_test function to verify feature examples are implemented in complete examples', 'review the get_function_contents_by_name function that extracts function source code from segmented lines', 'test the get_backend function to detect the current hardware accelerator backend and device count', 'build a subprocess launch command list for accelerate with kwargs like num_processes and device_count', 'run an async subprocess command with streaming stdout/stderr and timeout handling', 'test the AccelerateTestCase class that resets AcceleratorState singleton after every test method', 'test the assert_exception context manager to verify expected exception classes and messages are raised', 'create a RegressionDataset with custom slope, intercept, length, and seed for synthetic linear data generation', 'create a RegressionModel as a PyTorch module with learnable parameters a and b for linear regression', 'test mocked_dataloaders to build train and eval DataLoaders from MRPC dataset with BERT tokenizer', 'test mocked_dataloaders_for_autoregressive_models to build dataloaders for autoregressive language models with SmolLM tokenizer', 'review RegressionModel forward method that computes x * a + b with dtype logging on first batch']
```

Usage

```
{'test_get_backend': 'test the get_backend function to detect the current hardware accelerator backend and device count', 'build_get_launch_command': 'build a subprocess launch command list for accelerate with kwargs like num_processes and device_count', 'run_execute_subprocess_async': 'run an async subprocess command with streaming stdout/stderr and timeout handling', 'test_AccelerateTestCase': 'test the AccelerateTestCase class that resets AcceleratorState singleton after every test method', 'test_assert_exception': 'test the assert_exception context manager to verify expected exception classes and messages are raised'}
```

## File: huggingface_accelerate/src/accelerate/test_utils/training.py

Prompts

```
["extract a named function's source lines from a list of code lines by function name", 'clean a list of code lines by removing comment lines and blank lines', 'compare a feature example script against a complete example script to find missing implementations', 'test the compare_against_test function to verify feature examples are implemented in complete examples', 'review the get_function_contents_by_name function that extracts function source code from segmented lines', 'test the get_backend function to detect the current hardware accelerator backend and device count', 'build a subprocess launch command list for accelerate with kwargs like num_processes and device_count', 'run an async subprocess command with streaming stdout/stderr and timeout handling', 'test the AccelerateTestCase class that resets AcceleratorState singleton after every test method', 'test the assert_exception context manager to verify expected exception classes and messages are raised', 'create a RegressionDataset with custom slope, intercept, length, and seed for synthetic linear data generation', 'create a RegressionModel as a PyTorch module with learnable parameters a and b for linear regression', 'test mocked_dataloaders to build train and eval DataLoaders from MRPC dataset with BERT tokenizer', 'test mocked_dataloaders_for_autoregressive_models to build dataloaders for autoregressive language models with SmolLM tokenizer', 'review RegressionModel forward method that computes x * a + b with dtype logging on first batch']
```

Usage

```
{'create_RegressionDataset': 'create a RegressionDataset with custom slope, intercept, length, and seed for synthetic linear data generation', 'create_RegressionModel': 'create a RegressionModel as a PyTorch module with learnable parameters a and b for linear regression', 'test_mocked_dataloaders': 'test mocked_dataloaders to build train and eval DataLoaders from MRPC dataset with BERT tokenizer', 'test_mocked_dataloaders_for_autoregressive_models': 'test mocked_dataloaders_for_autoregressive_models to build dataloaders for autoregressive language models with SmolLM tokenizer', 'review_RegressionModel_forward': 'review RegressionModel forward method that computes x * a + b with dtype logging on first batch'}
```

