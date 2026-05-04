# Agent Python Tools

- repo: facebookresearch/ffcv-ssl
- repo_uri: https://github.com/facebookresearch/ffcv-ssl

## File: facebookresearch_ffcv-ssl/ffcv/memory_managers/base.py

Prompts

```
['review the MemoryManager class constructor that builds ptr size and sample to page mappings from a Reader', 'review the MemoryContext abstract base class that defines state start_batch and context manager methods', 'build a subclass of MemoryManager that implements schedule_epoch compile_reader and state_type for custom memory scheduling', 'build a subclass of MemoryContext that implements the state property and context manager enter exit methods', 'refactor the MemoryManager sample_to_pages and page_to_samples mapping logic to use a different data structure', 'create an OSCacheManager instance by passing a Reader object to manage OS-level memory-mapped cache', 'use the OSCacheContext enter method to lazily open a numpy memmap in read-only mode', 'schedule an epoch by calling schedule_epoch on OSCacheManager to return the cache context', 'compile a numba-accelerated reader function that reads data slices by address using searchsorted', 'review the OSCacheManager state_type property that returns a numba tuple of immutable uint8 and uint64 arrays']
```

Usage

```
{'review_MemoryManager_init': 'review the MemoryManager class constructor that builds ptr size and sample to page mappings from a Reader', 'review_MemoryContext': 'review the MemoryContext abstract base class that defines state start_batch and context manager methods', 'build_MemoryManager_subclass': 'build a subclass of MemoryManager that implements schedule_epoch compile_reader and state_type for custom memory scheduling', 'build_MemoryContext_subclass': 'build a subclass of MemoryContext that implements the state property and context manager enter exit methods', 'refactor_MemoryManager_mappings': 'refactor the MemoryManager sample_to_pages and page_to_samples mapping logic to use a different data structure'}
```

## File: facebookresearch_ffcv-ssl/ffcv/memory_managers/os_cache.py

Prompts

```
['review the MemoryManager class constructor that builds ptr size and sample to page mappings from a Reader', 'review the MemoryContext abstract base class that defines state start_batch and context manager methods', 'build a subclass of MemoryManager that implements schedule_epoch compile_reader and state_type for custom memory scheduling', 'build a subclass of MemoryContext that implements the state property and context manager enter exit methods', 'refactor the MemoryManager sample_to_pages and page_to_samples mapping logic to use a different data structure', 'create an OSCacheManager instance by passing a Reader object to manage OS-level memory-mapped cache', 'use the OSCacheContext enter method to lazily open a numpy memmap in read-only mode', 'schedule an epoch by calling schedule_epoch on OSCacheManager to return the cache context', 'compile a numba-accelerated reader function that reads data slices by address using searchsorted', 'review the OSCacheManager state_type property that returns a numba tuple of immutable uint8 and uint64 arrays']
```

Usage

```
{'create_OSCacheManager': 'create an OSCacheManager instance by passing a Reader object to manage OS-level memory-mapped cache', 'use_OSCacheContext_enter': 'use the OSCacheContext enter method to lazily open a numpy memmap in read-only mode', 'schedule_epoch_OSCacheManager': 'schedule an epoch by calling schedule_epoch on OSCacheManager to return the cache context', 'compile_reader_OSCacheManager': 'compile a numba-accelerated reader function that reads data slices by address using searchsorted', 'review_OSCacheManager_state_type': 'review the OSCacheManager state_type property that returns a numba tuple of immutable uint8 and uint64 arrays'}
```

