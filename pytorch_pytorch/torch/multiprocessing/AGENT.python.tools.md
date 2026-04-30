# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/multiprocessing/_atfork.py

Prompts

```
['register a callable to be executed in the child process after a fork using register_after_fork', 'test register_after_fork with a no-argument function called after os.fork in python 3.7+', 'create a multiprocessing Pool that uses SimpleQueue for passing tensors in shared memory across processes', 'test the Pool class that extends multiprocessing.pool.Pool with SimpleQueue-based inter-process communication', 'refactor the Pool class _setup_queues method to use SimpleQueue for input and output queues', 'review the clean_worker function that wraps multiprocessing.pool.worker with explicit garbage collection', 'summarize the Pool class _repopulate_pool method that restores worker count after process reaping', 'create a multiprocessing Queue with ForkingPickler serialization for inter-process communication', 'create a multiprocessing SimpleQueue with ForkingPickler serialization for inter-process communication', 'build a ConnectionWrapper proxy that wraps a _multiprocessing.Connection using ForkingPickler for object serialization', 'test the Queue class send and recv methods with ForkingPickler serialization', 'review the ConnectionWrapper class send, recv, and __getattr__ methods for proxying multiprocessing connections', 'build a function to serialize a PyTorch tensor for inter-process communication using reduce_tensor', 'create a function to serialize a CPU PyTorch storage object for file descriptor or file system sharing', 'build a function to register all PyTorch tensor and storage types with ForkingPickler for multiprocessing', 'build a function to serialize a CUDA event for IPC using reduce_event and rebuild_event', 'build a function to serialize sparse PyTorch tensors including COO and compressed layouts', 'build a script that uses torch.multiprocessing.spawn to launch nprocs worker processes with a target function', 'create a multiprocessing setup using torch.multiprocessing.start_processes with a custom start_method', 'test the ProcessContext.join method that waits for spawned processes and handles failures', 'review the ProcessException class hierarchy including ProcessRaisedException and ProcessExitedException', 'summarize the _wrap helper function that runs a target function in a child process and propagates tracebacks']
```

Usage

```
{'register_after_fork': 'register a callable to be executed in the child process after a fork using register_after_fork', 'test_register_after_fork': 'test register_after_fork with a no-argument function called after os.fork in python 3.7+'}
```

## File: pytorch_pytorch/torch/multiprocessing/pool.py

Prompts

```
['register a callable to be executed in the child process after a fork using register_after_fork', 'test register_after_fork with a no-argument function called after os.fork in python 3.7+', 'create a multiprocessing Pool that uses SimpleQueue for passing tensors in shared memory across processes', 'test the Pool class that extends multiprocessing.pool.Pool with SimpleQueue-based inter-process communication', 'refactor the Pool class _setup_queues method to use SimpleQueue for input and output queues', 'review the clean_worker function that wraps multiprocessing.pool.worker with explicit garbage collection', 'summarize the Pool class _repopulate_pool method that restores worker count after process reaping', 'create a multiprocessing Queue with ForkingPickler serialization for inter-process communication', 'create a multiprocessing SimpleQueue with ForkingPickler serialization for inter-process communication', 'build a ConnectionWrapper proxy that wraps a _multiprocessing.Connection using ForkingPickler for object serialization', 'test the Queue class send and recv methods with ForkingPickler serialization', 'review the ConnectionWrapper class send, recv, and __getattr__ methods for proxying multiprocessing connections', 'build a function to serialize a PyTorch tensor for inter-process communication using reduce_tensor', 'create a function to serialize a CPU PyTorch storage object for file descriptor or file system sharing', 'build a function to register all PyTorch tensor and storage types with ForkingPickler for multiprocessing', 'build a function to serialize a CUDA event for IPC using reduce_event and rebuild_event', 'build a function to serialize sparse PyTorch tensors including COO and compressed layouts', 'build a script that uses torch.multiprocessing.spawn to launch nprocs worker processes with a target function', 'create a multiprocessing setup using torch.multiprocessing.start_processes with a custom start_method', 'test the ProcessContext.join method that waits for spawned processes and handles failures', 'review the ProcessException class hierarchy including ProcessRaisedException and ProcessExitedException', 'summarize the _wrap helper function that runs a target function in a child process and propagates tracebacks']
```

Usage

```
{'create_Pool': 'create a multiprocessing Pool that uses SimpleQueue for passing tensors in shared memory across processes', 'test_Pool': 'test the Pool class that extends multiprocessing.pool.Pool with SimpleQueue-based inter-process communication', 'refactor_Pool': 'refactor the Pool class _setup_queues method to use SimpleQueue for input and output queues', 'review_clean_worker': 'review the clean_worker function that wraps multiprocessing.pool.worker with explicit garbage collection', 'summarize_Pool': 'summarize the Pool class _repopulate_pool method that restores worker count after process reaping'}
```

## File: pytorch_pytorch/torch/multiprocessing/queue.py

Prompts

```
['register a callable to be executed in the child process after a fork using register_after_fork', 'test register_after_fork with a no-argument function called after os.fork in python 3.7+', 'create a multiprocessing Pool that uses SimpleQueue for passing tensors in shared memory across processes', 'test the Pool class that extends multiprocessing.pool.Pool with SimpleQueue-based inter-process communication', 'refactor the Pool class _setup_queues method to use SimpleQueue for input and output queues', 'review the clean_worker function that wraps multiprocessing.pool.worker with explicit garbage collection', 'summarize the Pool class _repopulate_pool method that restores worker count after process reaping', 'create a multiprocessing Queue with ForkingPickler serialization for inter-process communication', 'create a multiprocessing SimpleQueue with ForkingPickler serialization for inter-process communication', 'build a ConnectionWrapper proxy that wraps a _multiprocessing.Connection using ForkingPickler for object serialization', 'test the Queue class send and recv methods with ForkingPickler serialization', 'review the ConnectionWrapper class send, recv, and __getattr__ methods for proxying multiprocessing connections', 'build a function to serialize a PyTorch tensor for inter-process communication using reduce_tensor', 'create a function to serialize a CPU PyTorch storage object for file descriptor or file system sharing', 'build a function to register all PyTorch tensor and storage types with ForkingPickler for multiprocessing', 'build a function to serialize a CUDA event for IPC using reduce_event and rebuild_event', 'build a function to serialize sparse PyTorch tensors including COO and compressed layouts', 'build a script that uses torch.multiprocessing.spawn to launch nprocs worker processes with a target function', 'create a multiprocessing setup using torch.multiprocessing.start_processes with a custom start_method', 'test the ProcessContext.join method that waits for spawned processes and handles failures', 'review the ProcessException class hierarchy including ProcessRaisedException and ProcessExitedException', 'summarize the _wrap helper function that runs a target function in a child process and propagates tracebacks']
```

Usage

```
{'create_queue': 'create a multiprocessing Queue with ForkingPickler serialization for inter-process communication', 'create_simple_queue': 'create a multiprocessing SimpleQueue with ForkingPickler serialization for inter-process communication', 'build_connection_wrapper': 'build a ConnectionWrapper proxy that wraps a _multiprocessing.Connection using ForkingPickler for object serialization', 'test_queue_send_recv': 'test the Queue class send and recv methods with ForkingPickler serialization', 'review_connection_wrapper': 'review the ConnectionWrapper class send, recv, and __getattr__ methods for proxying multiprocessing connections'}
```

## File: pytorch_pytorch/torch/multiprocessing/reductions.py

Prompts

```
['register a callable to be executed in the child process after a fork using register_after_fork', 'test register_after_fork with a no-argument function called after os.fork in python 3.7+', 'create a multiprocessing Pool that uses SimpleQueue for passing tensors in shared memory across processes', 'test the Pool class that extends multiprocessing.pool.Pool with SimpleQueue-based inter-process communication', 'refactor the Pool class _setup_queues method to use SimpleQueue for input and output queues', 'review the clean_worker function that wraps multiprocessing.pool.worker with explicit garbage collection', 'summarize the Pool class _repopulate_pool method that restores worker count after process reaping', 'create a multiprocessing Queue with ForkingPickler serialization for inter-process communication', 'create a multiprocessing SimpleQueue with ForkingPickler serialization for inter-process communication', 'build a ConnectionWrapper proxy that wraps a _multiprocessing.Connection using ForkingPickler for object serialization', 'test the Queue class send and recv methods with ForkingPickler serialization', 'review the ConnectionWrapper class send, recv, and __getattr__ methods for proxying multiprocessing connections', 'build a function to serialize a PyTorch tensor for inter-process communication using reduce_tensor', 'create a function to serialize a CPU PyTorch storage object for file descriptor or file system sharing', 'build a function to register all PyTorch tensor and storage types with ForkingPickler for multiprocessing', 'build a function to serialize a CUDA event for IPC using reduce_event and rebuild_event', 'build a function to serialize sparse PyTorch tensors including COO and compressed layouts', 'build a script that uses torch.multiprocessing.spawn to launch nprocs worker processes with a target function', 'create a multiprocessing setup using torch.multiprocessing.start_processes with a custom start_method', 'test the ProcessContext.join method that waits for spawned processes and handles failures', 'review the ProcessException class hierarchy including ProcessRaisedException and ProcessExitedException', 'summarize the _wrap helper function that runs a target function in a child process and propagates tracebacks']
```

Usage

```
{'build_reduce_tensor': 'build a function to serialize a PyTorch tensor for inter-process communication using reduce_tensor', 'create_reduce_storage': 'create a function to serialize a CPU PyTorch storage object for file descriptor or file system sharing', 'build_init_reductions': 'build a function to register all PyTorch tensor and storage types with ForkingPickler for multiprocessing', 'build_reduce_event': 'build a function to serialize a CUDA event for IPC using reduce_event and rebuild_event', 'build_reduce_sparse_tensor': 'build a function to serialize sparse PyTorch tensors including COO and compressed layouts'}
```

## File: pytorch_pytorch/torch/multiprocessing/spawn.py

Prompts

```
['register a callable to be executed in the child process after a fork using register_after_fork', 'test register_after_fork with a no-argument function called after os.fork in python 3.7+', 'create a multiprocessing Pool that uses SimpleQueue for passing tensors in shared memory across processes', 'test the Pool class that extends multiprocessing.pool.Pool with SimpleQueue-based inter-process communication', 'refactor the Pool class _setup_queues method to use SimpleQueue for input and output queues', 'review the clean_worker function that wraps multiprocessing.pool.worker with explicit garbage collection', 'summarize the Pool class _repopulate_pool method that restores worker count after process reaping', 'create a multiprocessing Queue with ForkingPickler serialization for inter-process communication', 'create a multiprocessing SimpleQueue with ForkingPickler serialization for inter-process communication', 'build a ConnectionWrapper proxy that wraps a _multiprocessing.Connection using ForkingPickler for object serialization', 'test the Queue class send and recv methods with ForkingPickler serialization', 'review the ConnectionWrapper class send, recv, and __getattr__ methods for proxying multiprocessing connections', 'build a function to serialize a PyTorch tensor for inter-process communication using reduce_tensor', 'create a function to serialize a CPU PyTorch storage object for file descriptor or file system sharing', 'build a function to register all PyTorch tensor and storage types with ForkingPickler for multiprocessing', 'build a function to serialize a CUDA event for IPC using reduce_event and rebuild_event', 'build a function to serialize sparse PyTorch tensors including COO and compressed layouts', 'build a script that uses torch.multiprocessing.spawn to launch nprocs worker processes with a target function', 'create a multiprocessing setup using torch.multiprocessing.start_processes with a custom start_method', 'test the ProcessContext.join method that waits for spawned processes and handles failures', 'review the ProcessException class hierarchy including ProcessRaisedException and ProcessExitedException', 'summarize the _wrap helper function that runs a target function in a child process and propagates tracebacks']
```

Usage

```
{'build_spawn_processes': 'build a script that uses torch.multiprocessing.spawn to launch nprocs worker processes with a target function', 'create_start_processes': 'create a multiprocessing setup using torch.multiprocessing.start_processes with a custom start_method', 'test_process_context_join': 'test the ProcessContext.join method that waits for spawned processes and handles failures', 'review_process_exception': 'review the ProcessException class hierarchy including ProcessRaisedException and ProcessExitedException', 'summarize_wrap_function': 'summarize the _wrap helper function that runs a target function in a child process and propagates tracebacks'}
```

