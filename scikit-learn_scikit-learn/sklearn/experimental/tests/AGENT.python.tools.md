# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/experimental/tests/test_enable_hist_gradient_boosting.py

Prompts

```
['test that importing enable_hist_gradient_boosting raises a UserWarning about the feature being stable', 'test the test_imports_strategies function that validates experimental import strategies for IterativeImputer', 'test importing IterativeImputer via sklearn.experimental.enable_iterative_imputer before sklearn.impute import', 'test importing IterativeImputer after importing sklearn.ensemble before enable_iterative_imputer', 'test that importing IterativeImputer without enable_iterative_imputer raises ImportError', 'test running a python script in a subprocess and verifying no output with assert_run_python_script_without_output']
```

Usage

```
{'test_import_raises_warning': 'test that importing enable_hist_gradient_boosting raises a UserWarning about the feature being stable'}
```

## File: scikit-learn_scikit-learn/sklearn/experimental/tests/test_enable_iterative_imputer.py

Prompts

```
['test that importing enable_hist_gradient_boosting raises a UserWarning about the feature being stable', 'test the test_imports_strategies function that validates experimental import strategies for IterativeImputer', 'test importing IterativeImputer via sklearn.experimental.enable_iterative_imputer before sklearn.impute import', 'test importing IterativeImputer after importing sklearn.ensemble before enable_iterative_imputer', 'test that importing IterativeImputer without enable_iterative_imputer raises ImportError', 'test running a python script in a subprocess and verifying no output with assert_run_python_script_without_output']
```

Usage

```
{'test_imports_strategies': 'test the test_imports_strategies function that validates experimental import strategies for IterativeImputer', 'test_enable_iterative_imputer_import': 'test importing IterativeImputer via sklearn.experimental.enable_iterative_imputer before sklearn.impute import', 'test_import_with_ensemble_first': 'test importing IterativeImputer after importing sklearn.ensemble before enable_iterative_imputer', 'test_bad_import_raises_importerror': 'test that importing IterativeImputer without enable_iterative_imputer raises ImportError', 'test_assert_run_python_script_without_output': 'test running a python script in a subprocess and verifying no output with assert_run_python_script_without_output'}
```

