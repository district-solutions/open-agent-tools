# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/demo/ocpapi/tests/unit/workflows/test_adsorbates.py

Prompts

```
['test the get_adsorbate_slab_relaxation_results function to verify retry logic and result fetching', 'test the wait_for_adsorbate_slab_relaxations function to verify polling until all statuses are terminal', 'test the find_adsorbate_binding_sites workflow to verify end-to-end adsorbate slab relaxation submission and result collection', 'test the MockGetRelaxationResults helper class to verify it returns expected configs and omitted config IDs', 'test error handling for unsupported models, adsorbates, bulks, and retryable exceptions in the binding sites workflow', 'test the set_context_var context manager that temporarily sets and resets a ContextVar value', 'run the TestContext unit test class to verify context variable set and reset behavior', 'review the TestContext class and its test_set_context_var method for context variable testing patterns', 'refactor the test_set_context_var method to add additional edge case assertions for context variable reset', 'summarize the TestContext class which tests the set_context_var context manager for temporary ContextVar updates', 'test the retry_api_calls decorator retry behavior for success, non-retryable, and retryable exceptions', 'test the retry_api_calls decorator wait times with fixed_wait_sec and max_jitter_sec parameters', 'test the retry_api_calls decorator rate limit logging with RateLimitLogging and mocked logger', 'run the TestRetry unit test class to validate retry logic, wait times, and logging', 'review the retry_api_calls decorator usage with max_attempts, fixed_wait_sec, and rate_limit_logging']
```

Usage

```
{'test_adsorbate_slab_relaxation_results': 'test the get_adsorbate_slab_relaxation_results function to verify retry logic and result fetching', 'test_wait_for_adsorbate_slab_relaxations': 'test the wait_for_adsorbate_slab_relaxations function to verify polling until all statuses are terminal', 'test_find_adsorbate_binding_sites': 'test the find_adsorbate_binding_sites workflow to verify end-to-end adsorbate slab relaxation submission and result collection', 'test_mock_get_relaxation_results': 'test the MockGetRelaxationResults helper class to verify it returns expected configs and omitted config IDs', 'test_adsorbate_binding_sites_error_handling': 'test error handling for unsupported models, adsorbates, bulks, and retryable exceptions in the binding sites workflow'}
```

## File: facebookresearch_fairchem/tests/demo/ocpapi/tests/unit/workflows/test_context.py

Prompts

```
['test the get_adsorbate_slab_relaxation_results function to verify retry logic and result fetching', 'test the wait_for_adsorbate_slab_relaxations function to verify polling until all statuses are terminal', 'test the find_adsorbate_binding_sites workflow to verify end-to-end adsorbate slab relaxation submission and result collection', 'test the MockGetRelaxationResults helper class to verify it returns expected configs and omitted config IDs', 'test error handling for unsupported models, adsorbates, bulks, and retryable exceptions in the binding sites workflow', 'test the set_context_var context manager that temporarily sets and resets a ContextVar value', 'run the TestContext unit test class to verify context variable set and reset behavior', 'review the TestContext class and its test_set_context_var method for context variable testing patterns', 'refactor the test_set_context_var method to add additional edge case assertions for context variable reset', 'summarize the TestContext class which tests the set_context_var context manager for temporary ContextVar updates', 'test the retry_api_calls decorator retry behavior for success, non-retryable, and retryable exceptions', 'test the retry_api_calls decorator wait times with fixed_wait_sec and max_jitter_sec parameters', 'test the retry_api_calls decorator rate limit logging with RateLimitLogging and mocked logger', 'run the TestRetry unit test class to validate retry logic, wait times, and logging', 'review the retry_api_calls decorator usage with max_attempts, fixed_wait_sec, and rate_limit_logging']
```

Usage

```
{'test_set_context_var': 'test the set_context_var context manager that temporarily sets and resets a ContextVar value', 'run_test_context': 'run the TestContext unit test class to verify context variable set and reset behavior', 'review_test_context': 'review the TestContext class and its test_set_context_var method for context variable testing patterns', 'refactor_test_set_context_var': 'refactor the test_set_context_var method to add additional edge case assertions for context variable reset', 'summarize_test_context': 'summarize the TestContext class which tests the set_context_var context manager for temporary ContextVar updates'}
```

## File: facebookresearch_fairchem/tests/demo/ocpapi/tests/unit/workflows/test_retry.py

Prompts

```
['test the get_adsorbate_slab_relaxation_results function to verify retry logic and result fetching', 'test the wait_for_adsorbate_slab_relaxations function to verify polling until all statuses are terminal', 'test the find_adsorbate_binding_sites workflow to verify end-to-end adsorbate slab relaxation submission and result collection', 'test the MockGetRelaxationResults helper class to verify it returns expected configs and omitted config IDs', 'test error handling for unsupported models, adsorbates, bulks, and retryable exceptions in the binding sites workflow', 'test the set_context_var context manager that temporarily sets and resets a ContextVar value', 'run the TestContext unit test class to verify context variable set and reset behavior', 'review the TestContext class and its test_set_context_var method for context variable testing patterns', 'refactor the test_set_context_var method to add additional edge case assertions for context variable reset', 'summarize the TestContext class which tests the set_context_var context manager for temporary ContextVar updates', 'test the retry_api_calls decorator retry behavior for success, non-retryable, and retryable exceptions', 'test the retry_api_calls decorator wait times with fixed_wait_sec and max_jitter_sec parameters', 'test the retry_api_calls decorator rate limit logging with RateLimitLogging and mocked logger', 'run the TestRetry unit test class to validate retry logic, wait times, and logging', 'review the retry_api_calls decorator usage with max_attempts, fixed_wait_sec, and rate_limit_logging']
```

Usage

```
{'test_retry_api_calls_results': 'test the retry_api_calls decorator retry behavior for success, non-retryable, and retryable exceptions', 'test_retry_api_calls_wait': 'test the retry_api_calls decorator wait times with fixed_wait_sec and max_jitter_sec parameters', 'test_retry_api_calls_logging': 'test the retry_api_calls decorator rate limit logging with RateLimitLogging and mocked logger', 'run_test_retry_unit_tests': 'run the TestRetry unit test class to validate retry logic, wait times, and logging', 'review_retry_api_calls_decorator': 'review the retry_api_calls decorator usage with max_attempts, fixed_wait_sec, and rate_limit_logging'}
```

