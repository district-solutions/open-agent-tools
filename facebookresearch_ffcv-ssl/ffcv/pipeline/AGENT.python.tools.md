# Agent Python Tools

- repo: facebookresearch/ffcv-ssl
- repo_uri: https://github.com/facebookresearch/ffcv-ssl

## File: facebookresearch_ffcv-ssl/ffcv/pipeline/compiler.py

Prompts

```
['compile a python function using numba njit with fastmath and nogil enabled via Compiler.compile', 'enable or disable the numba compiler by calling Compiler.set_enabled with a boolean value', 'set the number of parallel threads for numba and torch by calling Compiler.set_num_threads with an integer', 'get prange or range iterator for parallel loops by calling Compiler.get_iterator based on thread count', 'review the Compiler class to understand how it wraps numba njit compilation with configurable threading', 'create a subclass of Operation that implements generate_code and declare_state_and_memory abstract methods', 'call accept_field on an Operation instance to attach a Field object to it', 'call accept_globals on an Operation instance to set metadata and memory_read attributes', 'call generate_code on a concrete Operation subclass to get the callable code for the operation', 'call declare_state_and_memory on an Operation subclass with a previous State to get the new State and optional AllocationQuery', 'create a Pipeline instance with a sequence of Operation objects for data processing', 'parse a Pipeline to group operations into JIT and non-JIT blocks', 'compile all operations in a Pipeline by calling generate_code on each', 'allocate pinned memory buffers for a Pipeline given batch_size and batches_ahead parameters', 'allocate a single memory buffer for an AllocationQuery with torch or numpy dtype']
```

Usage

```
{'compile_function_with_njit': 'compile a python function using numba njit with fastmath and nogil enabled via Compiler.compile', 'set_compiler_enabled': 'enable or disable the numba compiler by calling Compiler.set_enabled with a boolean value', 'set_num_threads': 'set the number of parallel threads for numba and torch by calling Compiler.set_num_threads with an integer', 'get_iterator_for_parallel_loops': 'get prange or range iterator for parallel loops by calling Compiler.get_iterator based on thread count', 'review_compiler_class': 'review the Compiler class to understand how it wraps numba njit compilation with configurable threading'}
```

## File: facebookresearch_ffcv-ssl/ffcv/pipeline/operation.py

Prompts

```
['compile a python function using numba njit with fastmath and nogil enabled via Compiler.compile', 'enable or disable the numba compiler by calling Compiler.set_enabled with a boolean value', 'set the number of parallel threads for numba and torch by calling Compiler.set_num_threads with an integer', 'get prange or range iterator for parallel loops by calling Compiler.get_iterator based on thread count', 'review the Compiler class to understand how it wraps numba njit compilation with configurable threading', 'create a subclass of Operation that implements generate_code and declare_state_and_memory abstract methods', 'call accept_field on an Operation instance to attach a Field object to it', 'call accept_globals on an Operation instance to set metadata and memory_read attributes', 'call generate_code on a concrete Operation subclass to get the callable code for the operation', 'call declare_state_and_memory on an Operation subclass with a previous State to get the new State and optional AllocationQuery', 'create a Pipeline instance with a sequence of Operation objects for data processing', 'parse a Pipeline to group operations into JIT and non-JIT blocks', 'compile all operations in a Pipeline by calling generate_code on each', 'allocate pinned memory buffers for a Pipeline given batch_size and batches_ahead parameters', 'allocate a single memory buffer for an AllocationQuery with torch or numpy dtype']
```

Usage

```
{'implement_operation_subclass': 'create a subclass of Operation that implements generate_code and declare_state_and_memory abstract methods', 'accept_field_on_operation': 'call accept_field on an Operation instance to attach a Field object to it', 'accept_globals_on_operation': 'call accept_globals on an Operation instance to set metadata and memory_read attributes', 'generate_code_from_operation': 'call generate_code on a concrete Operation subclass to get the callable code for the operation', 'declare_state_and_memory': 'call declare_state_and_memory on an Operation subclass with a previous State to get the new State and optional AllocationQuery'}
```

## File: facebookresearch_ffcv-ssl/ffcv/pipeline/pipeline.py

Prompts

```
['compile a python function using numba njit with fastmath and nogil enabled via Compiler.compile', 'enable or disable the numba compiler by calling Compiler.set_enabled with a boolean value', 'set the number of parallel threads for numba and torch by calling Compiler.set_num_threads with an integer', 'get prange or range iterator for parallel loops by calling Compiler.get_iterator based on thread count', 'review the Compiler class to understand how it wraps numba njit compilation with configurable threading', 'create a subclass of Operation that implements generate_code and declare_state_and_memory abstract methods', 'call accept_field on an Operation instance to attach a Field object to it', 'call accept_globals on an Operation instance to set metadata and memory_read attributes', 'call generate_code on a concrete Operation subclass to get the callable code for the operation', 'call declare_state_and_memory on an Operation subclass with a previous State to get the new State and optional AllocationQuery', 'create a Pipeline instance with a sequence of Operation objects for data processing', 'parse a Pipeline to group operations into JIT and non-JIT blocks', 'compile all operations in a Pipeline by calling generate_code on each', 'allocate pinned memory buffers for a Pipeline given batch_size and batches_ahead parameters', 'allocate a single memory buffer for an AllocationQuery with torch or numpy dtype']
```

Usage

```
{'create_pipeline': 'create a Pipeline instance with a sequence of Operation objects for data processing', 'parse_pipeline': 'parse a Pipeline to group operations into JIT and non-JIT blocks', 'compile_ops': 'compile all operations in a Pipeline by calling generate_code on each', 'allocate_memory': 'allocate pinned memory buffers for a Pipeline given batch_size and batches_ahead parameters', 'allocate_query': 'allocate a single memory buffer for an AllocationQuery with torch or numpy dtype'}
```

