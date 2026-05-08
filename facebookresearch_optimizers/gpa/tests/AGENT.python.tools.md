# Agent Python Tools

- repo: facebookresearch/optimizers
- repo_uri: https://github.com/facebookresearch/optimizers

## File: facebookresearch_optimizers/gpa/tests/gpa_adamw_test.py

Prompts

```
['test the GPAAdamW optimizer initialization with default and custom hyperparameters', 'test the GPAAdamW optimizer train eval mode switching and step behavior', 'test the GPAAdamW compute_avg_coeff method for schedule-free and GPA averaging modes', 'test the GPAAdamW optimizer state dict save load and roundtrip behavior', 'run all GPAAdamW unit tests using python -m unittest gpa_adamw_test -v', 'run the GPA equivalence test suite to verify GPA reduces to AdamW when mu_x equals zero', 'test that GPA optimizer with mu_x zero matches AdamW optimizer weights to floating point precision', 'test GPA with mu_x zero equals AdamW across weight_decay zero and nonzero settings', 'assert GPA with mu_x zero matches AdamW for a given weight_decay value using z-buffer comparison', 'review the GPAEquivalenceTest class and its methods for testing GPA optimizer equivalence to AdamW', 'create a simple linear PyTorch model for testing optimizer behavior with configurable input and output dimensions', 'set reproducible random gradients on all model parameters using a fixed seed for testing', 'create a GPAAdamW optimizer configured in Schedule-Free mode with interpolation coefficients', 'create a GPAAdamW optimizer configured in standard GPA mode with iterate averaging', 'run an optimizer for multiple steps using pre-generated gradient tensors on a model']
```

Usage

```
{'test_GPAAdamWInitializationTest': 'test the GPAAdamW optimizer initialization with default and custom hyperparameters', 'test_GPAAdamWStepAndModeTest': 'test the GPAAdamW optimizer train eval mode switching and step behavior', 'test_GPAAdamWAvgCoeffTest': 'test the GPAAdamW compute_avg_coeff method for schedule-free and GPA averaging modes', 'test_GPAAdamWStateDictTest': 'test the GPAAdamW optimizer state dict save load and roundtrip behavior', 'run_gpa_adamw_tests': 'run all GPAAdamW unit tests using python -m unittest gpa_adamw_test -v'}
```

## File: facebookresearch_optimizers/gpa/tests/gpa_equivalence_test.py

Prompts

```
['test the GPAAdamW optimizer initialization with default and custom hyperparameters', 'test the GPAAdamW optimizer train eval mode switching and step behavior', 'test the GPAAdamW compute_avg_coeff method for schedule-free and GPA averaging modes', 'test the GPAAdamW optimizer state dict save load and roundtrip behavior', 'run all GPAAdamW unit tests using python -m unittest gpa_adamw_test -v', 'run the GPA equivalence test suite to verify GPA reduces to AdamW when mu_x equals zero', 'test that GPA optimizer with mu_x zero matches AdamW optimizer weights to floating point precision', 'test GPA with mu_x zero equals AdamW across weight_decay zero and nonzero settings', 'assert GPA with mu_x zero matches AdamW for a given weight_decay value using z-buffer comparison', 'review the GPAEquivalenceTest class and its methods for testing GPA optimizer equivalence to AdamW', 'create a simple linear PyTorch model for testing optimizer behavior with configurable input and output dimensions', 'set reproducible random gradients on all model parameters using a fixed seed for testing', 'create a GPAAdamW optimizer configured in Schedule-Free mode with interpolation coefficients', 'create a GPAAdamW optimizer configured in standard GPA mode with iterate averaging', 'run an optimizer for multiple steps using pre-generated gradient tensors on a model']
```

Usage

```
{'run_gpa_equivalence_test': 'run the GPA equivalence test suite to verify GPA reduces to AdamW when mu_x equals zero', 'test_gpa_matches_adamw': 'test that GPA optimizer with mu_x zero matches AdamW optimizer weights to floating point precision', 'test_gpa_mu_x_zero': 'test GPA with mu_x zero equals AdamW across weight_decay zero and nonzero settings', 'assert_gpa_matches_adamw': 'assert GPA with mu_x zero matches AdamW for a given weight_decay value using z-buffer comparison', 'review_gpa_equivalence_test': 'review the GPAEquivalenceTest class and its methods for testing GPA optimizer equivalence to AdamW'}
```

## File: facebookresearch_optimizers/gpa/tests/gpa_test_utils.py

Prompts

```
['test the GPAAdamW optimizer initialization with default and custom hyperparameters', 'test the GPAAdamW optimizer train eval mode switching and step behavior', 'test the GPAAdamW compute_avg_coeff method for schedule-free and GPA averaging modes', 'test the GPAAdamW optimizer state dict save load and roundtrip behavior', 'run all GPAAdamW unit tests using python -m unittest gpa_adamw_test -v', 'run the GPA equivalence test suite to verify GPA reduces to AdamW when mu_x equals zero', 'test that GPA optimizer with mu_x zero matches AdamW optimizer weights to floating point precision', 'test GPA with mu_x zero equals AdamW across weight_decay zero and nonzero settings', 'assert GPA with mu_x zero matches AdamW for a given weight_decay value using z-buffer comparison', 'review the GPAEquivalenceTest class and its methods for testing GPA optimizer equivalence to AdamW', 'create a simple linear PyTorch model for testing optimizer behavior with configurable input and output dimensions', 'set reproducible random gradients on all model parameters using a fixed seed for testing', 'create a GPAAdamW optimizer configured in Schedule-Free mode with interpolation coefficients', 'create a GPAAdamW optimizer configured in standard GPA mode with iterate averaging', 'run an optimizer for multiple steps using pre-generated gradient tensors on a model']
```

Usage

```
{'create_simple_model': 'create a simple linear PyTorch model for testing optimizer behavior with configurable input and output dimensions', 'set_deterministic_gradients': 'set reproducible random gradients on all model parameters using a fixed seed for testing', 'create_schedulefree_optimizer': 'create a GPAAdamW optimizer configured in Schedule-Free mode with interpolation coefficients', 'create_gpa_optimizer': 'create a GPAAdamW optimizer configured in standard GPA mode with iterate averaging', 'run_optimizer_steps': 'run an optimizer for multiple steps using pre-generated gradient tensors on a model'}
```

