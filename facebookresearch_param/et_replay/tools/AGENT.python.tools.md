# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/et_replay/tools/comm_replay.py

Prompts

```
['run the comms trace replay benchmark using argparse CLI with --trace-path and --output-path flags', 'replay a collective communications trace with warmup iterations and record latency metrics per rank', 'replay a single collective communication operation like all_reduce or all_to_allv and measure latency', 'report replay benchmark statistics including message size distributions and collective latency percentiles', 'write replayed communication performance details for a given rank to a JSON file in the output folder', 'run the et_replay CLI to replay a PyTorch execution trace JSON file as a benchmark', 'run the et_replay tool in comm mode to replay only communication operators from a trace', 'run the et_replay tool in comp mode to replay only compute operators from a trace', 'run the et_replay tool with profile-memory enabled to log per-operator GPU memory allocation', 'run the et_replay tool with trace-path to replay multi-rank distributed traces across processes', 'run the TraceValidator on a PyTorch execution trace JSON file to validate operators and param comms', 'validate that all PyTorch operators in an execution trace have valid names', 'validate that record_param_comms nodes have correct process group attributes for a given schema version', 'count the total number of ops, communication ops, and triton ops in an execution trace', 'validate that triton kernel nodes in an execution trace have correct values']
```

Usage

```
{'run_comms_trace_replay_benchmark': 'run the comms trace replay benchmark using argparse CLI with --trace-path and --output-path flags', 'replay_comms_trace': 'replay a collective communications trace with warmup iterations and record latency metrics per rank', 'replay_single_collective': 'replay a single collective communication operation like all_reduce or all_to_allv and measure latency', 'report_benchmark_statistics': 'report replay benchmark statistics including message size distributions and collective latency percentiles', 'write_comm_details_json': 'write replayed communication performance details for a given rank to a JSON file in the output folder'}
```

## File: facebookresearch_param/et_replay/tools/et_replay.py

Prompts

```
['run the comms trace replay benchmark using argparse CLI with --trace-path and --output-path flags', 'replay a collective communications trace with warmup iterations and record latency metrics per rank', 'replay a single collective communication operation like all_reduce or all_to_allv and measure latency', 'report replay benchmark statistics including message size distributions and collective latency percentiles', 'write replayed communication performance details for a given rank to a JSON file in the output folder', 'run the et_replay CLI to replay a PyTorch execution trace JSON file as a benchmark', 'run the et_replay tool in comm mode to replay only communication operators from a trace', 'run the et_replay tool in comp mode to replay only compute operators from a trace', 'run the et_replay tool with profile-memory enabled to log per-operator GPU memory allocation', 'run the et_replay tool with trace-path to replay multi-rank distributed traces across processes', 'run the TraceValidator on a PyTorch execution trace JSON file to validate operators and param comms', 'validate that all PyTorch operators in an execution trace have valid names', 'validate that record_param_comms nodes have correct process group attributes for a given schema version', 'count the total number of ops, communication ops, and triton ops in an execution trace', 'validate that triton kernel nodes in an execution trace have correct values']
```

Usage

```
{'run_et_replay_benchmark': 'run the et_replay CLI to replay a PyTorch execution trace JSON file as a benchmark', 'run_et_replay_comms_only': 'run the et_replay tool in comm mode to replay only communication operators from a trace', 'run_et_replay_compute_only': 'run the et_replay tool in comp mode to replay only compute operators from a trace', 'profile_et_replay_memory': 'run the et_replay tool with profile-memory enabled to log per-operator GPU memory allocation', 'run_et_replay_multi_rank': 'run the et_replay tool with trace-path to replay multi-rank distributed traces across processes'}
```

## File: facebookresearch_param/et_replay/tools/validate_trace.py

Prompts

```
['run the comms trace replay benchmark using argparse CLI with --trace-path and --output-path flags', 'replay a collective communications trace with warmup iterations and record latency metrics per rank', 'replay a single collective communication operation like all_reduce or all_to_allv and measure latency', 'report replay benchmark statistics including message size distributions and collective latency percentiles', 'write replayed communication performance details for a given rank to a JSON file in the output folder', 'run the et_replay CLI to replay a PyTorch execution trace JSON file as a benchmark', 'run the et_replay tool in comm mode to replay only communication operators from a trace', 'run the et_replay tool in comp mode to replay only compute operators from a trace', 'run the et_replay tool with profile-memory enabled to log per-operator GPU memory allocation', 'run the et_replay tool with trace-path to replay multi-rank distributed traces across processes', 'run the TraceValidator on a PyTorch execution trace JSON file to validate operators and param comms', 'validate that all PyTorch operators in an execution trace have valid names', 'validate that record_param_comms nodes have correct process group attributes for a given schema version', 'count the total number of ops, communication ops, and triton ops in an execution trace', 'validate that triton kernel nodes in an execution trace have correct values']
```

Usage

```
{'run_trace_validation': 'run the TraceValidator on a PyTorch execution trace JSON file to validate operators and param comms', 'validate_ops': 'validate that all PyTorch operators in an execution trace have valid names', 'validate_param_comms': 'validate that record_param_comms nodes have correct process group attributes for a given schema version', 'count_ops': 'count the total number of ops, communication ops, and triton ops in an execution trace', 'validate_triton_kernels': 'validate that triton kernel nodes in an execution trace have correct values'}
```

