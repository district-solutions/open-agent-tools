# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/benchmarks/compare.py

Prompts

```
['run a benchmark comparing the current working directory against a given git baseline commit', 'run a temporary git worktree at a specific commit for isolated benchmarking', 'run a benchmark that builds and tests the project with configurable CPU and fasttable options', 'run a shell command using subprocess check_call with shell mode enabled', 'run benchstat to compare benchmark results between old and new builds', 'generate a C++ benchmark source file that parses and serializes protobuf messages', 'run the RefMessage function to print a C++ block for a given protobuf message name', 'build a C++ benchmark file that references multiple protobuf message types by passing a numeric suffix', 'review the regex pattern that splits a trailing digit count from the protobuf message base name', 'summarize the Python script that generates C++ protobuf parse and serialize benchmark code', 'run the script to generate synthetic proto files for benchmarking in a given directory', 'generate proto files with 100 or 500 empty message definitions for benchmarking', 'generate proto files with 100 or 200 randomly weighted fields in a message', 'review the choices function that returns weighted random field type and label tuples', 'refactor the field_freqs list to add or modify protobuf field type distribution weights', 'generate a C benchmark source file that parses and serializes upb protobuf messages', 'run the script with an include header path and message base name to output C code', 'refactor the RefMessage function to support additional upb message operations beyond parse and serialize', 'review the RefMessage function that prints C code for parsing and serializing a named upb message', 'summarize the script that generates C benchmark code for upb message parsing and serialization']
```

Usage

```
{'run_benchmark_against_baseline': 'run a benchmark comparing the current working directory against a given git baseline commit', 'run_GitWorktree': 'run a temporary git worktree at a specific commit for isolated benchmarking', 'run_Benchmark': 'run a benchmark that builds and tests the project with configurable CPU and fasttable options', 'run_Run': 'run a shell command using subprocess check_call with shell mode enabled', 'run_benchstat_comparison': 'run benchstat to compare benchmark results between old and new builds'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/benchmarks/gen_protobuf_binary_cc.py

Prompts

```
['run a benchmark comparing the current working directory against a given git baseline commit', 'run a temporary git worktree at a specific commit for isolated benchmarking', 'run a benchmark that builds and tests the project with configurable CPU and fasttable options', 'run a shell command using subprocess check_call with shell mode enabled', 'run benchstat to compare benchmark results between old and new builds', 'generate a C++ benchmark source file that parses and serializes protobuf messages', 'run the RefMessage function to print a C++ block for a given protobuf message name', 'build a C++ benchmark file that references multiple protobuf message types by passing a numeric suffix', 'review the regex pattern that splits a trailing digit count from the protobuf message base name', 'summarize the Python script that generates C++ protobuf parse and serialize benchmark code', 'run the script to generate synthetic proto files for benchmarking in a given directory', 'generate proto files with 100 or 500 empty message definitions for benchmarking', 'generate proto files with 100 or 200 randomly weighted fields in a message', 'review the choices function that returns weighted random field type and label tuples', 'refactor the field_freqs list to add or modify protobuf field type distribution weights', 'generate a C benchmark source file that parses and serializes upb protobuf messages', 'run the script with an include header path and message base name to output C code', 'refactor the RefMessage function to support additional upb message operations beyond parse and serialize', 'review the RefMessage function that prints C code for parsing and serializing a named upb message', 'summarize the script that generates C benchmark code for upb message parsing and serialization']
```

Usage

```
{'generate_protobuf_benchmark_cpp': 'generate a C++ benchmark source file that parses and serializes protobuf messages', 'run_RefMessage': 'run the RefMessage function to print a C++ block for a given protobuf message name', 'build_benchmark_with_multiple_messages': 'build a C++ benchmark file that references multiple protobuf message types by passing a numeric suffix', 'review_regex_message_parsing': 'review the regex pattern that splits a trailing digit count from the protobuf message base name', 'summarize_code_generator': 'summarize the Python script that generates C++ protobuf parse and serialize benchmark code'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/benchmarks/gen_synthetic_protos.py

Prompts

```
['run a benchmark comparing the current working directory against a given git baseline commit', 'run a temporary git worktree at a specific commit for isolated benchmarking', 'run a benchmark that builds and tests the project with configurable CPU and fasttable options', 'run a shell command using subprocess check_call with shell mode enabled', 'run benchstat to compare benchmark results between old and new builds', 'generate a C++ benchmark source file that parses and serializes protobuf messages', 'run the RefMessage function to print a C++ block for a given protobuf message name', 'build a C++ benchmark file that references multiple protobuf message types by passing a numeric suffix', 'review the regex pattern that splits a trailing digit count from the protobuf message base name', 'summarize the Python script that generates C++ protobuf parse and serialize benchmark code', 'run the script to generate synthetic proto files for benchmarking in a given directory', 'generate proto files with 100 or 500 empty message definitions for benchmarking', 'generate proto files with 100 or 200 randomly weighted fields in a message', 'review the choices function that returns weighted random field type and label tuples', 'refactor the field_freqs list to add or modify protobuf field type distribution weights', 'generate a C benchmark source file that parses and serializes upb protobuf messages', 'run the script with an include header path and message base name to output C code', 'refactor the RefMessage function to support additional upb message operations beyond parse and serialize', 'review the RefMessage function that prints C code for parsing and serializing a named upb message', 'summarize the script that generates C benchmark code for upb message parsing and serialization']
```

Usage

```
{'run_gen_synthetic_protos': 'run the script to generate synthetic proto files for benchmarking in a given directory', 'generate_proto_messages': 'generate proto files with 100 or 500 empty message definitions for benchmarking', 'generate_proto_fields': 'generate proto files with 100 or 200 randomly weighted fields in a message', 'review_choices_function': 'review the choices function that returns weighted random field type and label tuples', 'refactor_field_freqs': 'refactor the field_freqs list to add or modify protobuf field type distribution weights'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/benchmarks/gen_upb_binary_c.py

Prompts

```
['run a benchmark comparing the current working directory against a given git baseline commit', 'run a temporary git worktree at a specific commit for isolated benchmarking', 'run a benchmark that builds and tests the project with configurable CPU and fasttable options', 'run a shell command using subprocess check_call with shell mode enabled', 'run benchstat to compare benchmark results between old and new builds', 'generate a C++ benchmark source file that parses and serializes protobuf messages', 'run the RefMessage function to print a C++ block for a given protobuf message name', 'build a C++ benchmark file that references multiple protobuf message types by passing a numeric suffix', 'review the regex pattern that splits a trailing digit count from the protobuf message base name', 'summarize the Python script that generates C++ protobuf parse and serialize benchmark code', 'run the script to generate synthetic proto files for benchmarking in a given directory', 'generate proto files with 100 or 500 empty message definitions for benchmarking', 'generate proto files with 100 or 200 randomly weighted fields in a message', 'review the choices function that returns weighted random field type and label tuples', 'refactor the field_freqs list to add or modify protobuf field type distribution weights', 'generate a C benchmark source file that parses and serializes upb protobuf messages', 'run the script with an include header path and message base name to output C code', 'refactor the RefMessage function to support additional upb message operations beyond parse and serialize', 'review the RefMessage function that prints C code for parsing and serializing a named upb message', 'summarize the script that generates C benchmark code for upb message parsing and serialization']
```

Usage

```
{'generate_upb_benchmark_c': 'generate a C benchmark source file that parses and serializes upb protobuf messages', 'run_gen_upb_binary_c': 'run the script with an include header path and message base name to output C code', 'refactor_RefMessage': 'refactor the RefMessage function to support additional upb message operations beyond parse and serialize', 'review_RefMessage': 'review the RefMessage function that prints C code for parsing and serializing a named upb message', 'summarize_gen_upb_binary_c': 'summarize the script that generates C benchmark code for upb message parsing and serialization'}
```

