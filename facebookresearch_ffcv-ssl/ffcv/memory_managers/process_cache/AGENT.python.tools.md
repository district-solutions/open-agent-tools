# Agent Python Tools

- repo: facebookresearch/ffcv-ssl
- repo_uri: https://github.com/facebookresearch/ffcv-ssl

## File: facebookresearch_ffcv-ssl/ffcv/memory_managers/process_cache/context.py

Prompts

```
['create a ProcessCacheContext with a MemoryManager and batches to manage memory scheduling', 'enter a ProcessCacheContext to compute page schedule and initialize memory slots', 'start a batch in ProcessCacheContext to load required pages via the executor', 'exit a ProcessCacheContext to clean up the ScheduleExecutor and release resources', 'review the ProcessCacheContext state property to inspect memory, pointers, sizes, and page-to-slot mapping', 'review the ProcessCacheManager class and its memory scheduling and compilation methods', 'summarize the schedule_epoch method that returns a ProcessCacheContext for the given batches', 'review the state_type property that defines the numba tuple type for memory state', 'test the compile_reader method that compiles a JIT-optimized read function using Compiler', 'refactor the ProcessCacheManager to support custom page size or memory layout strategies', 'create a PageReader thread that reads pages from a file into shared memory using query and loaded queues', 'run the PageReader thread loop that processes page read queries from a queue and puts results into a loaded queue', 'initialize a PageReader with a filename, query queue, loaded queue, and numpy memory array for page caching', 'review the PageReader class that extends Thread to asynchronously read file pages into memory slots', 'summarize the PageReader run method that reads file pages at computed offsets using libffcv read', 'compute a memory page scheduling plan from a list of pages per batch with configurable prefetch ahead value', 'create a Schedule dataclass to store slot count, page to slot mapping, prefetch timing, and page lifecycle events', 'create a ScheduleExecutor with a file path, schedule object, numpy memory array, and optional worker thread count', 'load a batch of pages by calling load_batch on a ScheduleExecutor to prefetch and wait for required pages', 'enter a ScheduleExecutor context manager to spawn worker threads for concurrent page reading from disk']
```

Usage

```
{'create_ProcessCacheContext': 'create a ProcessCacheContext with a MemoryManager and batches to manage memory scheduling', 'enter_ProcessCacheContext': 'enter a ProcessCacheContext to compute page schedule and initialize memory slots', 'start_batch_ProcessCacheContext': 'start a batch in ProcessCacheContext to load required pages via the executor', 'exit_ProcessCacheContext': 'exit a ProcessCacheContext to clean up the ScheduleExecutor and release resources', 'review_ProcessCacheContext_state': 'review the ProcessCacheContext state property to inspect memory, pointers, sizes, and page-to-slot mapping'}
```

## File: facebookresearch_ffcv-ssl/ffcv/memory_managers/process_cache/manager.py

Prompts

```
['create a ProcessCacheContext with a MemoryManager and batches to manage memory scheduling', 'enter a ProcessCacheContext to compute page schedule and initialize memory slots', 'start a batch in ProcessCacheContext to load required pages via the executor', 'exit a ProcessCacheContext to clean up the ScheduleExecutor and release resources', 'review the ProcessCacheContext state property to inspect memory, pointers, sizes, and page-to-slot mapping', 'review the ProcessCacheManager class and its memory scheduling and compilation methods', 'summarize the schedule_epoch method that returns a ProcessCacheContext for the given batches', 'review the state_type property that defines the numba tuple type for memory state', 'test the compile_reader method that compiles a JIT-optimized read function using Compiler', 'refactor the ProcessCacheManager to support custom page size or memory layout strategies', 'create a PageReader thread that reads pages from a file into shared memory using query and loaded queues', 'run the PageReader thread loop that processes page read queries from a queue and puts results into a loaded queue', 'initialize a PageReader with a filename, query queue, loaded queue, and numpy memory array for page caching', 'review the PageReader class that extends Thread to asynchronously read file pages into memory slots', 'summarize the PageReader run method that reads file pages at computed offsets using libffcv read', 'compute a memory page scheduling plan from a list of pages per batch with configurable prefetch ahead value', 'create a Schedule dataclass to store slot count, page to slot mapping, prefetch timing, and page lifecycle events', 'create a ScheduleExecutor with a file path, schedule object, numpy memory array, and optional worker thread count', 'load a batch of pages by calling load_batch on a ScheduleExecutor to prefetch and wait for required pages', 'enter a ScheduleExecutor context manager to spawn worker threads for concurrent page reading from disk']
```

Usage

```
{'review_ProcessCacheManager': 'review the ProcessCacheManager class and its memory scheduling and compilation methods', 'summarize_schedule_epoch': 'summarize the schedule_epoch method that returns a ProcessCacheContext for the given batches', 'review_state_type': 'review the state_type property that defines the numba tuple type for memory state', 'test_compile_reader': 'test the compile_reader method that compiles a JIT-optimized read function using Compiler', 'refactor_ProcessCacheManager': 'refactor the ProcessCacheManager to support custom page size or memory layout strategies'}
```

## File: facebookresearch_ffcv-ssl/ffcv/memory_managers/process_cache/page_reader.py

Prompts

```
['create a ProcessCacheContext with a MemoryManager and batches to manage memory scheduling', 'enter a ProcessCacheContext to compute page schedule and initialize memory slots', 'start a batch in ProcessCacheContext to load required pages via the executor', 'exit a ProcessCacheContext to clean up the ScheduleExecutor and release resources', 'review the ProcessCacheContext state property to inspect memory, pointers, sizes, and page-to-slot mapping', 'review the ProcessCacheManager class and its memory scheduling and compilation methods', 'summarize the schedule_epoch method that returns a ProcessCacheContext for the given batches', 'review the state_type property that defines the numba tuple type for memory state', 'test the compile_reader method that compiles a JIT-optimized read function using Compiler', 'refactor the ProcessCacheManager to support custom page size or memory layout strategies', 'create a PageReader thread that reads pages from a file into shared memory using query and loaded queues', 'run the PageReader thread loop that processes page read queries from a queue and puts results into a loaded queue', 'initialize a PageReader with a filename, query queue, loaded queue, and numpy memory array for page caching', 'review the PageReader class that extends Thread to asynchronously read file pages into memory slots', 'summarize the PageReader run method that reads file pages at computed offsets using libffcv read', 'compute a memory page scheduling plan from a list of pages per batch with configurable prefetch ahead value', 'create a Schedule dataclass to store slot count, page to slot mapping, prefetch timing, and page lifecycle events', 'create a ScheduleExecutor with a file path, schedule object, numpy memory array, and optional worker thread count', 'load a batch of pages by calling load_batch on a ScheduleExecutor to prefetch and wait for required pages', 'enter a ScheduleExecutor context manager to spawn worker threads for concurrent page reading from disk']
```

Usage

```
{'create_page_reader_thread': 'create a PageReader thread that reads pages from a file into shared memory using query and loaded queues', 'run_page_reader_loop': 'run the PageReader thread loop that processes page read queries from a queue and puts results into a loaded queue', 'initialize_page_reader': 'initialize a PageReader with a filename, query queue, loaded queue, and numpy memory array for page caching', 'review_page_reader_class': 'review the PageReader class that extends Thread to asynchronously read file pages into memory slots', 'summarize_page_reader_run': 'summarize the PageReader run method that reads file pages at computed offsets using libffcv read'}
```

## File: facebookresearch_ffcv-ssl/ffcv/memory_managers/process_cache/schedule.py

Prompts

```
['create a ProcessCacheContext with a MemoryManager and batches to manage memory scheduling', 'enter a ProcessCacheContext to compute page schedule and initialize memory slots', 'start a batch in ProcessCacheContext to load required pages via the executor', 'exit a ProcessCacheContext to clean up the ScheduleExecutor and release resources', 'review the ProcessCacheContext state property to inspect memory, pointers, sizes, and page-to-slot mapping', 'review the ProcessCacheManager class and its memory scheduling and compilation methods', 'summarize the schedule_epoch method that returns a ProcessCacheContext for the given batches', 'review the state_type property that defines the numba tuple type for memory state', 'test the compile_reader method that compiles a JIT-optimized read function using Compiler', 'refactor the ProcessCacheManager to support custom page size or memory layout strategies', 'create a PageReader thread that reads pages from a file into shared memory using query and loaded queues', 'run the PageReader thread loop that processes page read queries from a queue and puts results into a loaded queue', 'initialize a PageReader with a filename, query queue, loaded queue, and numpy memory array for page caching', 'review the PageReader class that extends Thread to asynchronously read file pages into memory slots', 'summarize the PageReader run method that reads file pages at computed offsets using libffcv read', 'compute a memory page scheduling plan from a list of pages per batch with configurable prefetch ahead value', 'create a Schedule dataclass to store slot count, page to slot mapping, prefetch timing, and page lifecycle events', 'create a ScheduleExecutor with a file path, schedule object, numpy memory array, and optional worker thread count', 'load a batch of pages by calling load_batch on a ScheduleExecutor to prefetch and wait for required pages', 'enter a ScheduleExecutor context manager to spawn worker threads for concurrent page reading from disk']
```

Usage

```
{'compute_schedule': 'compute a memory page scheduling plan from a list of pages per batch with configurable prefetch ahead value', 'create_Schedule_dataclass': 'create a Schedule dataclass to store slot count, page to slot mapping, prefetch timing, and page lifecycle events', 'create_ScheduleExecutor': 'create a ScheduleExecutor with a file path, schedule object, numpy memory array, and optional worker thread count', 'load_batch_ScheduleExecutor': 'load a batch of pages by calling load_batch on a ScheduleExecutor to prefetch and wait for required pages', 'enter_ScheduleExecutor_context': 'enter a ScheduleExecutor context manager to spawn worker threads for concurrent page reading from disk'}
```

