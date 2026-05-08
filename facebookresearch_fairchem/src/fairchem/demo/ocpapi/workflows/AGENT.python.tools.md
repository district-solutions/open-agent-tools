# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/demo/ocpapi/workflows/adsorbates.py

Prompts

```
['run find_adsorbate_binding_sites to search for adsorbate binding sites on surfaces of a bulk material', 'run wait_for_adsorbate_slab_relaxations to block until all relaxations in a system have finished', 'run get_adsorbate_slab_relaxation_results to fetch relaxation results for a given system ID', 'review the AdsorbateBindingSites dataclass that stores inputs and results of adsorbate placement relaxations on slabs', 'review the Lifetime enum representing SAVE, MARK_EPHEMERAL, and DELETE options for relaxation data retention', 'use the set_context_var context manager to temporarily set a ContextVar to a specific value then reset it', 'review the set_context_var context manager function that sets and resets a ContextVar safely', 'refactor the set_context_var context manager to support additional context variable operations', 'test the set_context_var context manager to verify it resets the ContextVar after the block exits', 'summarize the set_context_var context manager that temporarily assigns a value to a ContextVar', 'create a retry decorator for OCP API calls with configurable max attempts and wait times', 'use the RateLimitLogging dataclass to configure logger and action description for rate limit logging', 'use the _wait_check_retry_after wait strategy to honor retry-after headers from rate limit responses', 'use the NO_LIMIT constant to set unlimited retry attempts on the retry_api_calls decorator', 'refactor the retry_api_calls decorator to customize fixed wait seconds and max jitter values']
```

Usage

```
{'run_find_adsorbate_binding_sites': 'run find_adsorbate_binding_sites to search for adsorbate binding sites on surfaces of a bulk material', 'run_wait_for_adsorbate_slab_relaxations': 'run wait_for_adsorbate_slab_relaxations to block until all relaxations in a system have finished', 'run_get_adsorbate_slab_relaxation_results': 'run get_adsorbate_slab_relaxation_results to fetch relaxation results for a given system ID', 'review_AdsorbateBindingSites': 'review the AdsorbateBindingSites dataclass that stores inputs and results of adsorbate placement relaxations on slabs', 'review_Lifetime': 'review the Lifetime enum representing SAVE, MARK_EPHEMERAL, and DELETE options for relaxation data retention'}
```

## File: facebookresearch_fairchem/src/fairchem/demo/ocpapi/workflows/context.py

Prompts

```
['run find_adsorbate_binding_sites to search for adsorbate binding sites on surfaces of a bulk material', 'run wait_for_adsorbate_slab_relaxations to block until all relaxations in a system have finished', 'run get_adsorbate_slab_relaxation_results to fetch relaxation results for a given system ID', 'review the AdsorbateBindingSites dataclass that stores inputs and results of adsorbate placement relaxations on slabs', 'review the Lifetime enum representing SAVE, MARK_EPHEMERAL, and DELETE options for relaxation data retention', 'use the set_context_var context manager to temporarily set a ContextVar to a specific value then reset it', 'review the set_context_var context manager function that sets and resets a ContextVar safely', 'refactor the set_context_var context manager to support additional context variable operations', 'test the set_context_var context manager to verify it resets the ContextVar after the block exits', 'summarize the set_context_var context manager that temporarily assigns a value to a ContextVar', 'create a retry decorator for OCP API calls with configurable max attempts and wait times', 'use the RateLimitLogging dataclass to configure logger and action description for rate limit logging', 'use the _wait_check_retry_after wait strategy to honor retry-after headers from rate limit responses', 'use the NO_LIMIT constant to set unlimited retry attempts on the retry_api_calls decorator', 'refactor the retry_api_calls decorator to customize fixed wait seconds and max jitter values']
```

Usage

```
{'use_set_context_var': 'use the set_context_var context manager to temporarily set a ContextVar to a specific value then reset it', 'review_set_context_var': 'review the set_context_var context manager function that sets and resets a ContextVar safely', 'refactor_set_context_var': 'refactor the set_context_var context manager to support additional context variable operations', 'test_set_context_var': 'test the set_context_var context manager to verify it resets the ContextVar after the block exits', 'summarize_set_context_var': 'summarize the set_context_var context manager that temporarily assigns a value to a ContextVar'}
```

## File: facebookresearch_fairchem/src/fairchem/demo/ocpapi/workflows/retry.py

Prompts

```
['run find_adsorbate_binding_sites to search for adsorbate binding sites on surfaces of a bulk material', 'run wait_for_adsorbate_slab_relaxations to block until all relaxations in a system have finished', 'run get_adsorbate_slab_relaxation_results to fetch relaxation results for a given system ID', 'review the AdsorbateBindingSites dataclass that stores inputs and results of adsorbate placement relaxations on slabs', 'review the Lifetime enum representing SAVE, MARK_EPHEMERAL, and DELETE options for relaxation data retention', 'use the set_context_var context manager to temporarily set a ContextVar to a specific value then reset it', 'review the set_context_var context manager function that sets and resets a ContextVar safely', 'refactor the set_context_var context manager to support additional context variable operations', 'test the set_context_var context manager to verify it resets the ContextVar after the block exits', 'summarize the set_context_var context manager that temporarily assigns a value to a ContextVar', 'create a retry decorator for OCP API calls with configurable max attempts and wait times', 'use the RateLimitLogging dataclass to configure logger and action description for rate limit logging', 'use the _wait_check_retry_after wait strategy to honor retry-after headers from rate limit responses', 'use the NO_LIMIT constant to set unlimited retry attempts on the retry_api_calls decorator', 'refactor the retry_api_calls decorator to customize fixed wait seconds and max jitter values']
```

Usage

```
{'create_retry_decorator': 'create a retry decorator for OCP API calls with configurable max attempts and wait times', 'use_ratelimitlogging_dataclass': 'use the RateLimitLogging dataclass to configure logger and action description for rate limit logging', 'use_wait_check_retry_after': 'use the _wait_check_retry_after wait strategy to honor retry-after headers from rate limit responses', 'use_no_limit_constant': 'use the NO_LIMIT constant to set unlimited retry attempts on the retry_api_calls decorator', 'refactor_retry_api_calls': 'refactor the retry_api_calls decorator to customize fixed wait seconds and max jitter values'}
```

