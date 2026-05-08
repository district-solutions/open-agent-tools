# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/et_replay/tests/test_et_replay.py

Prompts

```
['run the ETReplayIntegrationTest to benchmark ExgrReplayManager on extracted ET trace files', 'test the is_gpu_arch_supported function to check if the GPU supports PT2 triton kernels', 'test the get_et_files function to extract tar.gz ET trace files to temporary directories', 'review the ETReplayIntegrationTest class and its test_et_replay_integration_test method for CUDA availability', 'refactor the is_gpu_arch_supported function to add support for additional GPU architectures', 'run the unittest suite to load and validate execution trace JSON files', 'test loading an ExecutionTrace object from a gzipped JSON trace file', 'test that TraceValidator validates an ExecutionTrace and returns true', 'test that TraceValidator reports the total number of ops in a trace', 'test that TraceValidator reports the number of communication ops in a trace']
```

Usage

```
{'run_et_replay_integration_test': 'run the ETReplayIntegrationTest to benchmark ExgrReplayManager on extracted ET trace files', 'test_is_gpu_arch_supported': 'test the is_gpu_arch_supported function to check if the GPU supports PT2 triton kernels', 'test_get_et_files': 'test the get_et_files function to extract tar.gz ET trace files to temporary directories', 'review_ETReplayIntegrationTest': 'review the ETReplayIntegrationTest class and its test_et_replay_integration_test method for CUDA availability', 'refactor_is_gpu_arch_supported': 'refactor the is_gpu_arch_supported function to add support for additional GPU architectures'}
```

## File: facebookresearch_param/et_replay/tests/test_execution_trace.py

Prompts

```
['run the ETReplayIntegrationTest to benchmark ExgrReplayManager on extracted ET trace files', 'test the is_gpu_arch_supported function to check if the GPU supports PT2 triton kernels', 'test the get_et_files function to extract tar.gz ET trace files to temporary directories', 'review the ETReplayIntegrationTest class and its test_et_replay_integration_test method for CUDA availability', 'refactor the is_gpu_arch_supported function to add support for additional GPU architectures', 'run the unittest suite to load and validate execution trace JSON files', 'test loading an ExecutionTrace object from a gzipped JSON trace file', 'test that TraceValidator validates an ExecutionTrace and returns true', 'test that TraceValidator reports the total number of ops in a trace', 'test that TraceValidator reports the number of communication ops in a trace']
```

Usage

```
{'run_test_trace_load_and_validate': 'run the unittest suite to load and validate execution trace JSON files', 'test_ExecutionTrace_from_json': 'test loading an ExecutionTrace object from a gzipped JSON trace file', 'test_TraceValidator_validate': 'test that TraceValidator validates an ExecutionTrace and returns true', 'test_num_ops_count': 'test that TraceValidator reports the total number of ops in a trace', 'test_num_comm_ops_count': 'test that TraceValidator reports the number of communication ops in a trace'}
```

