# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/tests/compat/test_compat.py

Prompts

```
['test creating a Version object from another Version instance and verify string representation', 'test creating a Version object from a packaging version string and verify output', 'test creating a Version from a module name using mocked metadata to look up version', 'test comparing a Version object against version strings using less than and equality operators', 'test the _compare method returns NotImplemented when the comparison method raises a TypeError', 'test the pandas assert_frame_equal compatibility wrapper across versions 1.0 through 1.2', 'test the pandas assert_series_equal compatibility wrapper across versions 1.0 through 1.3', 'test that the pandas compat version object matches the expected compat.Version', 'review the TestPandas unittest class and its version-specific assertion test methods', 'run the unittest test suite for pandas compatibility assertion wrappers', 'test that the sklearn compat module version equals the compat Version object for sklearn', 'test the mean squared error function with sample weights and multioutput kwargs', 'test the mean squared error function with squared=False to compute root mean squared error', 'test the mean squared log error function with sample weights for sklearn version 0.24', 'test the mean squared log error with squared=False for both sklearn 0.24 and 1.0 versions']
```

Usage

```
{'test_Version_from_Version': 'test creating a Version object from another Version instance and verify string representation', 'test_Version_from_packaging': 'test creating a Version object from a packaging version string and verify output', 'test_Version_module': 'test creating a Version from a module name using mocked metadata to look up version', 'test_Version_compare_str': 'test comparing a Version object against version strings using less than and equality operators', 'test_incompatible_Version': 'test the _compare method returns NotImplemented when the comparison method raises a TypeError'}
```

## File: facebookresearch_kats/kats/tests/compat/test_pandas.py

Prompts

```
['test creating a Version object from another Version instance and verify string representation', 'test creating a Version object from a packaging version string and verify output', 'test creating a Version from a module name using mocked metadata to look up version', 'test comparing a Version object against version strings using less than and equality operators', 'test the _compare method returns NotImplemented when the comparison method raises a TypeError', 'test the pandas assert_frame_equal compatibility wrapper across versions 1.0 through 1.2', 'test the pandas assert_series_equal compatibility wrapper across versions 1.0 through 1.3', 'test that the pandas compat version object matches the expected compat.Version', 'review the TestPandas unittest class and its version-specific assertion test methods', 'run the unittest test suite for pandas compatibility assertion wrappers', 'test that the sklearn compat module version equals the compat Version object for sklearn', 'test the mean squared error function with sample weights and multioutput kwargs', 'test the mean squared error function with squared=False to compute root mean squared error', 'test the mean squared log error function with sample weights for sklearn version 0.24', 'test the mean squared log error with squared=False for both sklearn 0.24 and 1.0 versions']
```

Usage

```
{'test_assert_frame_equal_pandas_compat': 'test the pandas assert_frame_equal compatibility wrapper across versions 1.0 through 1.2', 'test_assert_series_equal_pandas_compat': 'test the pandas assert_series_equal compatibility wrapper across versions 1.0 through 1.3', 'test_pandas_version': 'test that the pandas compat version object matches the expected compat.Version', 'review_TestPandas_class': 'review the TestPandas unittest class and its version-specific assertion test methods', 'run_pandas_compat_tests': 'run the unittest test suite for pandas compatibility assertion wrappers'}
```

## File: facebookresearch_kats/kats/tests/compat/test_sklearn.py

Prompts

```
['test creating a Version object from another Version instance and verify string representation', 'test creating a Version object from a packaging version string and verify output', 'test creating a Version from a module name using mocked metadata to look up version', 'test comparing a Version object against version strings using less than and equality operators', 'test the _compare method returns NotImplemented when the comparison method raises a TypeError', 'test the pandas assert_frame_equal compatibility wrapper across versions 1.0 through 1.2', 'test the pandas assert_series_equal compatibility wrapper across versions 1.0 through 1.3', 'test that the pandas compat version object matches the expected compat.Version', 'review the TestPandas unittest class and its version-specific assertion test methods', 'run the unittest test suite for pandas compatibility assertion wrappers', 'test that the sklearn compat module version equals the compat Version object for sklearn', 'test the mean squared error function with sample weights and multioutput kwargs', 'test the mean squared error function with squared=False to compute root mean squared error', 'test the mean squared log error function with sample weights for sklearn version 0.24', 'test the mean squared log error with squared=False for both sklearn 0.24 and 1.0 versions']
```

Usage

```
{'test_sklearn_version': 'test that the sklearn compat module version equals the compat Version object for sklearn', 'test_mean_squared_error': 'test the mean squared error function with sample weights and multioutput kwargs', 'test_root_mean_squared_error': 'test the mean squared error function with squared=False to compute root mean squared error', 'test_mean_squared_log_error': 'test the mean squared log error function with sample weights for sklearn version 0.24', 'test_root_mean_squared_log_error': 'test the mean squared log error with squared=False for both sklearn 0.24 and 1.0 versions'}
```

