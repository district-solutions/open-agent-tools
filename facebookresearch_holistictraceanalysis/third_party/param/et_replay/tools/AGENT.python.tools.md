# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/third_party/param/et_replay/tools/comm_replay.py

Prompts

```
['run the comms trace replay benchmark by reading a trace file and replaying collective communications with timing metrics', 'replay a collective communications trace file using commsTraceReplayBench to benchmark all_reduce, all_to_allv, and broadcast operations', 'convert a basic trace JSON list into commsArgs objects by parsing collective operation names, message sizes, and process group info', 'write replayed communication performance metrics for a given rank to a JSON file in the specified output folder', 'rebalance all_to_allv split sizes across ranks using an equal distribution policy during warm-up replay', 'run the execution trace replay benchmark on a PyTorch trace JSON file with warmup and replay iterations', 'generate a standalone Python benchmark script from an execution trace file using the code generator mode', 'profile GPU memory allocation and reservation per operator during execution trace replay', 'replay only compute operators from an execution trace while skipping communication operators', 'replay an execution trace on CPU instead of GPU for debugging or environments without CUDA', 'run the TraceValidator to validate a PyTorch execution trace JSON file and print validation results', 'use TraceValidator.num_ops to count the total number of operator nodes in an execution trace', 'use TraceValidator.num_comm_ops to count record_param_comms operator nodes in an execution trace', 'use TraceValidator.num_triton_ops to count triton kernel operator nodes in an execution trace', 'review the TraceValidator class and its validate method to understand PyTorch trace validation logic']
```

Usage

```
{'run_comms_trace_replay': 'run the comms trace replay benchmark by reading a trace file and replaying collective communications with timing metrics', 'replay_collective_comms_trace': 'replay a collective communications trace file using commsTraceReplayBench to benchmark all_reduce, all_to_allv, and broadcast operations', 'extract_comms_info_from_trace': 'convert a basic trace JSON list into commsArgs objects by parsing collective operation names, message sizes, and process group info', 'write_replayed_comms_details': 'write replayed communication performance metrics for a given rank to a JSON file in the specified output folder', 'rebalance_all_to_allv_splits': 'rebalance all_to_allv split sizes across ranks using an equal distribution policy during warm-up replay'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/et_replay/tools/et_replay.py

Prompts

```
['run the comms trace replay benchmark by reading a trace file and replaying collective communications with timing metrics', 'replay a collective communications trace file using commsTraceReplayBench to benchmark all_reduce, all_to_allv, and broadcast operations', 'convert a basic trace JSON list into commsArgs objects by parsing collective operation names, message sizes, and process group info', 'write replayed communication performance metrics for a given rank to a JSON file in the specified output folder', 'rebalance all_to_allv split sizes across ranks using an equal distribution policy during warm-up replay', 'run the execution trace replay benchmark on a PyTorch trace JSON file with warmup and replay iterations', 'generate a standalone Python benchmark script from an execution trace file using the code generator mode', 'profile GPU memory allocation and reservation per operator during execution trace replay', 'replay only compute operators from an execution trace while skipping communication operators', 'replay an execution trace on CPU instead of GPU for debugging or environments without CUDA', 'run the TraceValidator to validate a PyTorch execution trace JSON file and print validation results', 'use TraceValidator.num_ops to count the total number of operator nodes in an execution trace', 'use TraceValidator.num_comm_ops to count record_param_comms operator nodes in an execution trace', 'use TraceValidator.num_triton_ops to count triton kernel operator nodes in an execution trace', 'review the TraceValidator class and its validate method to understand PyTorch trace validation logic']
```

Usage

```
{'run_et_replay_benchmark': 'run the execution trace replay benchmark on a PyTorch trace JSON file with warmup and replay iterations', 'generate_benchmark_code': 'generate a standalone Python benchmark script from an execution trace file using the code generator mode', 'profile_replay_memory': 'profile GPU memory allocation and reservation per operator during execution trace replay', 'replay_compute_only': 'replay only compute operators from an execution trace while skipping communication operators', 'replay_on_cpu': 'replay an execution trace on CPU instead of GPU for debugging or environments without CUDA'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/et_replay/tools/validate_trace.py

Prompts

```
['run the comms trace replay benchmark by reading a trace file and replaying collective communications with timing metrics', 'replay a collective communications trace file using commsTraceReplayBench to benchmark all_reduce, all_to_allv, and broadcast operations', 'convert a basic trace JSON list into commsArgs objects by parsing collective operation names, message sizes, and process group info', 'write replayed communication performance metrics for a given rank to a JSON file in the specified output folder', 'rebalance all_to_allv split sizes across ranks using an equal distribution policy during warm-up replay', 'run the execution trace replay benchmark on a PyTorch trace JSON file with warmup and replay iterations', 'generate a standalone Python benchmark script from an execution trace file using the code generator mode', 'profile GPU memory allocation and reservation per operator during execution trace replay', 'replay only compute operators from an execution trace while skipping communication operators', 'replay an execution trace on CPU instead of GPU for debugging or environments without CUDA', 'run the TraceValidator to validate a PyTorch execution trace JSON file and print validation results', 'use TraceValidator.num_ops to count the total number of operator nodes in an execution trace', 'use TraceValidator.num_comm_ops to count record_param_comms operator nodes in an execution trace', 'use TraceValidator.num_triton_ops to count triton kernel operator nodes in an execution trace', 'review the TraceValidator class and its validate method to understand PyTorch trace validation logic']
```

Usage

```
{'validate_execution_trace': 'run the TraceValidator to validate a PyTorch execution trace JSON file and print validation results', 'count_ops_in_trace': 'use TraceValidator.num_ops to count the total number of operator nodes in an execution trace', 'count_comm_ops_in_trace': 'use TraceValidator.num_comm_ops to count record_param_comms operator nodes in an execution trace', 'count_triton_ops_in_trace': 'use TraceValidator.num_triton_ops to count triton kernel operator nodes in an execution trace', 'review_trace_validation': 'review the TraceValidator class and its validate method to understand PyTorch trace validation logic'}
```

