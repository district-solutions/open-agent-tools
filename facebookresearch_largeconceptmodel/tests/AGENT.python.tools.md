# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/tests/common.py

Prompts

```
['assert two PyTorch tensors are element-wise equal within a tolerance', 'assert two PyTorch tensors are element-wise exactly equal with zero tolerance', 'test the assert_close function with two PyTorch tensors', 'test the assert_equal function with a tensor and a list of values', 'review the common test utilities module for assert_close and assert_equal functions', 'run the test_headers script to auto-fix missing copyright headers in all tracked files', 'test all git-tracked files in the repo to verify they have a Meta copyright header', 'check if a single file has the correct Meta copyright header and optionally autofix it', 'refactor the check_file function to support additional file suffixes for double-slash comment headers', 'review the test_all_files_have_a_copyright_header function to understand which file types are skipped during header checks']
```

Usage

```
{'assert_close_tensors': 'assert two PyTorch tensors are element-wise equal within a tolerance', 'assert_equal_tensors': 'assert two PyTorch tensors are element-wise exactly equal with zero tolerance', 'test_assert_close': 'test the assert_close function with two PyTorch tensors', 'test_assert_equal': 'test the assert_equal function with a tensor and a list of values', 'review_common_test_utils': 'review the common test utilities module for assert_close and assert_equal functions'}
```

## File: facebookresearch_largeconceptmodel/tests/test_headers.py

Prompts

```
['assert two PyTorch tensors are element-wise equal within a tolerance', 'assert two PyTorch tensors are element-wise exactly equal with zero tolerance', 'test the assert_close function with two PyTorch tensors', 'test the assert_equal function with a tensor and a list of values', 'review the common test utilities module for assert_close and assert_equal functions', 'run the test_headers script to auto-fix missing copyright headers in all tracked files', 'test all git-tracked files in the repo to verify they have a Meta copyright header', 'check if a single file has the correct Meta copyright header and optionally autofix it', 'refactor the check_file function to support additional file suffixes for double-slash comment headers', 'review the test_all_files_have_a_copyright_header function to understand which file types are skipped during header checks']
```

Usage

```
{'run_copyright_autofix': 'run the test_headers script to auto-fix missing copyright headers in all tracked files', 'test_copyright_headers': 'test all git-tracked files in the repo to verify they have a Meta copyright header', 'check_file_copyright': 'check if a single file has the correct Meta copyright header and optionally autofix it', 'refactor_check_file': 'refactor the check_file function to support additional file suffixes for double-slash comment headers', 'review_test_all_files_have_a_copyright_header': 'review the test_all_files_have_a_copyright_header function to understand which file types are skipped during header checks'}
```

