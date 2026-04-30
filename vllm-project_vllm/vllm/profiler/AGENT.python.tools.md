# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/profiler/layerwise_profile.py

Prompts

```
['run layerwise profiling on a model using the layerwise_profile context manager with CPU and CUDA activities', 'print a formatted table of model layer CPU and CUDA timing stats from LayerwiseProfileResults', 'print a formatted table of aggregated layer summary stats with CUDA time and invocation counts', 'export model layer CPU and CUDA timing stats to a CSV file', 'export aggregated summary stats with CUDA time and invocations to a CSV file', 'build a table printer that formats and prints rows of dataclass instances with aligned columns', 'test the event_is_torch_op function to check if a profiler event is a torch operation', "review the event_module_repr function that generates a string representation of a profiler event's module", 'summarize the event_arg_repr function that converts profiler event arguments into string representations', 'refactor the event_torch_op_stack_trace function to build a stack trace of torch operations from a profiler event', 'create a TorchProfilerWrapper with ProfilerConfig, worker name, local rank, and activities list for GPU profiling', 'create a CudaProfilerWrapper with ProfilerConfig for CUDA profiler start and stop', 'test the WorkerProfiler step method with delay and max iteration limits', 'refactor the TorchProfilerWrapper _stop method to dump CUDA and CPU profiler tables', 'review the WorkerProfiler start method for delayed start and active state handling']
```

Usage

```
{'run_layerwise_profile': 'run layerwise profiling on a model using the layerwise_profile context manager with CPU and CUDA activities', 'print_model_table': 'print a formatted table of model layer CPU and CUDA timing stats from LayerwiseProfileResults', 'print_summary_table': 'print a formatted table of aggregated layer summary stats with CUDA time and invocation counts', 'export_model_stats_table_csv': 'export model layer CPU and CUDA timing stats to a CSV file', 'export_summary_stats_table_csv': 'export aggregated summary stats with CUDA time and invocations to a CSV file'}
```

## File: vllm-project_vllm/vllm/profiler/utils.py

Prompts

```
['run layerwise profiling on a model using the layerwise_profile context manager with CPU and CUDA activities', 'print a formatted table of model layer CPU and CUDA timing stats from LayerwiseProfileResults', 'print a formatted table of aggregated layer summary stats with CUDA time and invocation counts', 'export model layer CPU and CUDA timing stats to a CSV file', 'export aggregated summary stats with CUDA time and invocations to a CSV file', 'build a table printer that formats and prints rows of dataclass instances with aligned columns', 'test the event_is_torch_op function to check if a profiler event is a torch operation', "review the event_module_repr function that generates a string representation of a profiler event's module", 'summarize the event_arg_repr function that converts profiler event arguments into string representations', 'refactor the event_torch_op_stack_trace function to build a stack trace of torch operations from a profiler event', 'create a TorchProfilerWrapper with ProfilerConfig, worker name, local rank, and activities list for GPU profiling', 'create a CudaProfilerWrapper with ProfilerConfig for CUDA profiler start and stop', 'test the WorkerProfiler step method with delay and max iteration limits', 'refactor the TorchProfilerWrapper _stop method to dump CUDA and CPU profiler tables', 'review the WorkerProfiler start method for delayed start and active state handling']
```

Usage

```
{'build_profiler_table': 'build a table printer that formats and prints rows of dataclass instances with aligned columns', 'test_event_is_torch_op': 'test the event_is_torch_op function to check if a profiler event is a torch operation', 'review_event_module_repr': "review the event_module_repr function that generates a string representation of a profiler event's module", 'summarize_event_arg_repr': 'summarize the event_arg_repr function that converts profiler event arguments into string representations', 'refactor_event_torch_op_stack_trace': 'refactor the event_torch_op_stack_trace function to build a stack trace of torch operations from a profiler event'}
```

## File: vllm-project_vllm/vllm/profiler/wrapper.py

Prompts

```
['run layerwise profiling on a model using the layerwise_profile context manager with CPU and CUDA activities', 'print a formatted table of model layer CPU and CUDA timing stats from LayerwiseProfileResults', 'print a formatted table of aggregated layer summary stats with CUDA time and invocation counts', 'export model layer CPU and CUDA timing stats to a CSV file', 'export aggregated summary stats with CUDA time and invocations to a CSV file', 'build a table printer that formats and prints rows of dataclass instances with aligned columns', 'test the event_is_torch_op function to check if a profiler event is a torch operation', "review the event_module_repr function that generates a string representation of a profiler event's module", 'summarize the event_arg_repr function that converts profiler event arguments into string representations', 'refactor the event_torch_op_stack_trace function to build a stack trace of torch operations from a profiler event', 'create a TorchProfilerWrapper with ProfilerConfig, worker name, local rank, and activities list for GPU profiling', 'create a CudaProfilerWrapper with ProfilerConfig for CUDA profiler start and stop', 'test the WorkerProfiler step method with delay and max iteration limits', 'refactor the TorchProfilerWrapper _stop method to dump CUDA and CPU profiler tables', 'review the WorkerProfiler start method for delayed start and active state handling']
```

Usage

```
{'create_TorchProfilerWrapper': 'create a TorchProfilerWrapper with ProfilerConfig, worker name, local rank, and activities list for GPU profiling', 'create_CudaProfilerWrapper': 'create a CudaProfilerWrapper with ProfilerConfig for CUDA profiler start and stop', 'test_WorkerProfiler_step': 'test the WorkerProfiler step method with delay and max iteration limits', 'refactor_TorchProfilerWrapper_stop': 'refactor the TorchProfilerWrapper _stop method to dump CUDA and CPU profiler tables', 'review_WorkerProfiler_start': 'review the WorkerProfiler start method for delayed start and active state handling'}
```

