# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/et_replay/comm/commsTraceParser.py

Prompts

```
['parse a Chakra host execution trace file into a PARAM replay-compatible comms operation list', 'convert an ExecutionTrace object comms metadata into the common trace format for PARAM replay', 'extract process group rank mappings and descriptions from process group init nodes in an execution trace', 'parse record_param_comms nodes from an execution trace into commsArgs objects with rank and message details', 'create a commsArgs init node with process group id, ranks, description, and world size', 'parse a comma-separated or range string of ranks into a list of integers', 'read distributed training environment variables and return world size, local size, global rank, and local rank', 'map creative collective operation name aliases to their internal canonical names', 'initialize quantization communication handlers for a given collective with specified bitwidth', 'allocate input and output tensors for a specified collective communication operation', 'create a paramTimer dataclass instance to track elapsed time in nanoseconds', 'use paramProfile as a context manager to profile a code block with a description', 'reset a paramTimer instance to zero or a new elapsed time value', 'get the elapsed time in microseconds from a paramTimer using getTimeUS', 'profile a code block with paramProfile linked to a paramTimer for cumulative timing', 'analyze PyTorch profiler traces from a directory and generate a bandwidth and performance report', "preprocess a single rank's profiler trace and save extracted bandwidth data to disk", 'summarize preprocessed profiler trace data from all ranks and generate an analysis report', 'calculate algebraic and bus bandwidth for NCCL collective communication events in a trace', 'calculate shared bandwidth per rank from NCCL kernel events in a profiler trace']
```

Usage

```
{'parse_trace_for_param_replay': 'parse a Chakra host execution trace file into a PARAM replay-compatible comms operation list', 'parse_execution_trace_comms_metadata': 'convert an ExecutionTrace object comms metadata into the common trace format for PARAM replay', 'parse_process_group_info': 'extract process group rank mappings and descriptions from process group init nodes in an execution trace', 'parse_comms_operation_nodes': 'parse record_param_comms nodes from an execution trace into commsArgs objects with rank and message details', 'create_process_group_init_node': 'create a commsArgs init node with process group id, ranks, description, and world size'}
```

## File: facebookresearch_param/et_replay/comm/comms_utils.py

Prompts

```
['parse a Chakra host execution trace file into a PARAM replay-compatible comms operation list', 'convert an ExecutionTrace object comms metadata into the common trace format for PARAM replay', 'extract process group rank mappings and descriptions from process group init nodes in an execution trace', 'parse record_param_comms nodes from an execution trace into commsArgs objects with rank and message details', 'create a commsArgs init node with process group id, ranks, description, and world size', 'parse a comma-separated or range string of ranks into a list of integers', 'read distributed training environment variables and return world size, local size, global rank, and local rank', 'map creative collective operation name aliases to their internal canonical names', 'initialize quantization communication handlers for a given collective with specified bitwidth', 'allocate input and output tensors for a specified collective communication operation', 'create a paramTimer dataclass instance to track elapsed time in nanoseconds', 'use paramProfile as a context manager to profile a code block with a description', 'reset a paramTimer instance to zero or a new elapsed time value', 'get the elapsed time in microseconds from a paramTimer using getTimeUS', 'profile a code block with paramProfile linked to a paramTimer for cumulative timing', 'analyze PyTorch profiler traces from a directory and generate a bandwidth and performance report', "preprocess a single rank's profiler trace and save extracted bandwidth data to disk", 'summarize preprocessed profiler trace data from all ranks and generate an analysis report', 'calculate algebraic and bus bandwidth for NCCL collective communication events in a trace', 'calculate shared bandwidth per rank from NCCL kernel events in a profiler trace']
```

Usage

```
{'parse_rank_list': 'parse a comma-separated or range string of ranks into a list of integers', 'read_comms_env_vars': 'read distributed training environment variables and return world size, local size, global rank, and local rank', 'param_to_comm_name': 'map creative collective operation name aliases to their internal canonical names', 'init_quant_comm_ctx': 'initialize quantization communication handlers for a given collective with specified bitwidth', 'prep_comm': 'allocate input and output tensors for a specified collective communication operation'}
```

## File: facebookresearch_param/et_replay/comm/param_profile.py

Prompts

```
['parse a Chakra host execution trace file into a PARAM replay-compatible comms operation list', 'convert an ExecutionTrace object comms metadata into the common trace format for PARAM replay', 'extract process group rank mappings and descriptions from process group init nodes in an execution trace', 'parse record_param_comms nodes from an execution trace into commsArgs objects with rank and message details', 'create a commsArgs init node with process group id, ranks, description, and world size', 'parse a comma-separated or range string of ranks into a list of integers', 'read distributed training environment variables and return world size, local size, global rank, and local rank', 'map creative collective operation name aliases to their internal canonical names', 'initialize quantization communication handlers for a given collective with specified bitwidth', 'allocate input and output tensors for a specified collective communication operation', 'create a paramTimer dataclass instance to track elapsed time in nanoseconds', 'use paramProfile as a context manager to profile a code block with a description', 'reset a paramTimer instance to zero or a new elapsed time value', 'get the elapsed time in microseconds from a paramTimer using getTimeUS', 'profile a code block with paramProfile linked to a paramTimer for cumulative timing', 'analyze PyTorch profiler traces from a directory and generate a bandwidth and performance report', "preprocess a single rank's profiler trace and save extracted bandwidth data to disk", 'summarize preprocessed profiler trace data from all ranks and generate an analysis report', 'calculate algebraic and bus bandwidth for NCCL collective communication events in a trace', 'calculate shared bandwidth per rank from NCCL kernel events in a profiler trace']
```

Usage

```
{'create_paramTimer': 'create a paramTimer dataclass instance to track elapsed time in nanoseconds', 'use_paramProfile_context_manager': 'use paramProfile as a context manager to profile a code block with a description', 'reset_paramTimer': 'reset a paramTimer instance to zero or a new elapsed time value', 'get_time_microseconds': 'get the elapsed time in microseconds from a paramTimer using getTimeUS', 'profile_with_timer': 'profile a code block with paramProfile linked to a paramTimer for cumulative timing'}
```

## File: facebookresearch_param/et_replay/comm/profiler_trace_analysis.py

Prompts

```
['parse a Chakra host execution trace file into a PARAM replay-compatible comms operation list', 'convert an ExecutionTrace object comms metadata into the common trace format for PARAM replay', 'extract process group rank mappings and descriptions from process group init nodes in an execution trace', 'parse record_param_comms nodes from an execution trace into commsArgs objects with rank and message details', 'create a commsArgs init node with process group id, ranks, description, and world size', 'parse a comma-separated or range string of ranks into a list of integers', 'read distributed training environment variables and return world size, local size, global rank, and local rank', 'map creative collective operation name aliases to their internal canonical names', 'initialize quantization communication handlers for a given collective with specified bitwidth', 'allocate input and output tensors for a specified collective communication operation', 'create a paramTimer dataclass instance to track elapsed time in nanoseconds', 'use paramProfile as a context manager to profile a code block with a description', 'reset a paramTimer instance to zero or a new elapsed time value', 'get the elapsed time in microseconds from a paramTimer using getTimeUS', 'profile a code block with paramProfile linked to a paramTimer for cumulative timing', 'analyze PyTorch profiler traces from a directory and generate a bandwidth and performance report', "preprocess a single rank's profiler trace and save extracted bandwidth data to disk", 'summarize preprocessed profiler trace data from all ranks and generate an analysis report', 'calculate algebraic and bus bandwidth for NCCL collective communication events in a trace', 'calculate shared bandwidth per rank from NCCL kernel events in a profiler trace']
```

Usage

```
{'analyze_profiler_trace': 'analyze PyTorch profiler traces from a directory and generate a bandwidth and performance report', 'preprocess_profiler_trace': "preprocess a single rank's profiler trace and save extracted bandwidth data to disk", 'summarize_profiler_trace': 'summarize preprocessed profiler trace data from all ranks and generate an analysis report', 'calculate_bw_': 'calculate algebraic and bus bandwidth for NCCL collective communication events in a trace', 'calculate_sbw': 'calculate shared bandwidth per rank from NCCL kernel events in a profiler trace'}
```

