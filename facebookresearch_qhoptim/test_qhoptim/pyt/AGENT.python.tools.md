# Agent Python Tools

- repo: facebookresearch/qhoptim
- repo_uri: https://github.com/facebookresearch/qhoptim

## File: facebookresearch_qhoptim/test_qhoptim/pyt/test_qhadam.py

Prompts

```
['test that QHAdam optimizer produces equivalent results to standard PyTorch Adam when nus are set to 1.0', 'test that QHAdamW optimizer produces equivalent results to standard PyTorch AdamW when nus are set to 1.0', 'run the test_adam_equiv function to verify QHAdam and QHAdamW match Adam and AdamW behavior', 'review the assert_optimizers_equal utility used to compare two optimizer constructors for equivalence', 'refactor QHAdam usage to experiment with different nus values beyond the default 1.0 equivalence point', 'test that QHM with nu=1.0 and beta=0.0 is equivalent to plain SGD', 'test that QHM with nu=1.0 and beta=0.9 is equivalent to SGD with momentum', 'test that QHM with nu=beta is equivalent to SGD with Nesterov momentum', 'run all QHM optimizer equivalence tests against SGD using pytest', 'test two PyTorch optimizer constructors produce identical parameters over a linear regression training loop', 'refactor assert_optimizers_equal to support custom model architectures instead of hardcoded nn.Linear', 'summarize the assert_optimizers_equal utility that runs paired optimizer steps and asserts parameter closeness', 'build a test harness using assert_optimizers_equal to verify a new optimizer matches a reference optimizer']
```

Usage

```
{'test_QHAdam_equivalence_to_Adam': 'test that QHAdam optimizer produces equivalent results to standard PyTorch Adam when nus are set to 1.0', 'test_QHAdamW_equivalence_to_AdamW': 'test that QHAdamW optimizer produces equivalent results to standard PyTorch AdamW when nus are set to 1.0', 'run_test_adam_equiv': 'run the test_adam_equiv function to verify QHAdam and QHAdamW match Adam and AdamW behavior', 'review_assert_optimizers_equal': 'review the assert_optimizers_equal utility used to compare two optimizer constructors for equivalence', 'refactor_QHAdam_nus_parameter': 'refactor QHAdam usage to experiment with different nus values beyond the default 1.0 equivalence point'}
```

## File: facebookresearch_qhoptim/test_qhoptim/pyt/test_qhm.py

Prompts

```
['test that QHAdam optimizer produces equivalent results to standard PyTorch Adam when nus are set to 1.0', 'test that QHAdamW optimizer produces equivalent results to standard PyTorch AdamW when nus are set to 1.0', 'run the test_adam_equiv function to verify QHAdam and QHAdamW match Adam and AdamW behavior', 'review the assert_optimizers_equal utility used to compare two optimizer constructors for equivalence', 'refactor QHAdam usage to experiment with different nus values beyond the default 1.0 equivalence point', 'test that QHM with nu=1.0 and beta=0.0 is equivalent to plain SGD', 'test that QHM with nu=1.0 and beta=0.9 is equivalent to SGD with momentum', 'test that QHM with nu=beta is equivalent to SGD with Nesterov momentum', 'run all QHM optimizer equivalence tests against SGD using pytest', 'test two PyTorch optimizer constructors produce identical parameters over a linear regression training loop', 'refactor assert_optimizers_equal to support custom model architectures instead of hardcoded nn.Linear', 'summarize the assert_optimizers_equal utility that runs paired optimizer steps and asserts parameter closeness', 'build a test harness using assert_optimizers_equal to verify a new optimizer matches a reference optimizer']
```

Usage

```
{'test_plain_sgd_equiv': 'test that QHM with nu=1.0 and beta=0.0 is equivalent to plain SGD', 'test_momentum_equiv': 'test that QHM with nu=1.0 and beta=0.9 is equivalent to SGD with momentum', 'test_nesterov_equiv': 'test that QHM with nu=beta is equivalent to SGD with Nesterov momentum', 'run_test_qhm': 'run all QHM optimizer equivalence tests against SGD using pytest', 'review_assert_optimizers_equal': 'review the assert_optimizers_equal utility that compares two optimizer constructors over training iterations'}
```

## File: facebookresearch_qhoptim/test_qhoptim/pyt/util.py

Prompts

```
['test that QHAdam optimizer produces equivalent results to standard PyTorch Adam when nus are set to 1.0', 'test that QHAdamW optimizer produces equivalent results to standard PyTorch AdamW when nus are set to 1.0', 'run the test_adam_equiv function to verify QHAdam and QHAdamW match Adam and AdamW behavior', 'review the assert_optimizers_equal utility used to compare two optimizer constructors for equivalence', 'refactor QHAdam usage to experiment with different nus values beyond the default 1.0 equivalence point', 'test that QHM with nu=1.0 and beta=0.0 is equivalent to plain SGD', 'test that QHM with nu=1.0 and beta=0.9 is equivalent to SGD with momentum', 'test that QHM with nu=beta is equivalent to SGD with Nesterov momentum', 'run all QHM optimizer equivalence tests against SGD using pytest', 'test two PyTorch optimizer constructors produce identical parameters over a linear regression training loop', 'refactor assert_optimizers_equal to support custom model architectures instead of hardcoded nn.Linear', 'summarize the assert_optimizers_equal utility that runs paired optimizer steps and asserts parameter closeness', 'build a test harness using assert_optimizers_equal to verify a new optimizer matches a reference optimizer']
```

Usage

```
{'test_assert_optimizers_equal': 'test two PyTorch optimizer constructors produce identical parameters over a linear regression training loop', 'review_assert_optimizers_equal': 'review the assert_optimizers_equal function that validates optimizer equivalence using nn.Linear and MSE loss', 'refactor_assert_optimizers_equal': 'refactor assert_optimizers_equal to support custom model architectures instead of hardcoded nn.Linear', 'summarize_assert_optimizers_equal': 'summarize the assert_optimizers_equal utility that runs paired optimizer steps and asserts parameter closeness', 'build_optimizer_test': 'build a test harness using assert_optimizers_equal to verify a new optimizer matches a reference optimizer'}
```

