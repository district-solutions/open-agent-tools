# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/protobuf/benchmarks/compare.py

Prompts

```
['run a benchmark comparing the current directory against a baseline git commit for size and speed', 'create a temporary git worktree at a given commit and clean it up after use', 'execute a shell command and raise an error if it fails', 'build and run CPU benchmarks then output results in benchstat format', 'strip debug symbols and compare binary sizes between old and new builds using bloaty', 'run the script to generate a C++ benchmark source file for protobuf message serialization', 'run the script with an include path and message name to generate C++ code referencing protobuf messages', 'build a C++ benchmark file that parses and serializes multiple protobuf message types using this generator', 'refactor the RefMessage function to support additional protobuf serialization methods beyond ParseFromArray and SerializePartialToArray', 'summarize the script that generates C++ benchmark code for protobuf binary serialization and deserialization', 'run the script to generate synthetic proto benchmark files in a given output directory', 'create proto files containing 100 or 500 empty message definitions for benchmarking', 'create proto files with 100 or 200 weighted-random fields using real-world frequency distribution', 'refactor the choices function to support custom field type weights or additional protobuf types', 'summarize the field frequency distribution data showing which protobuf field types are most common', 'run the script with an include header and message basename to generate a C benchmark program', 'build a C benchmark that parses and serializes upb protobuf messages using an arena', 'run the script with a numeric suffix on the message name to generate code for multiple message types', 'review the RefMessage function that prints C code to parse and serialize a single upb message type', 'refactor the script to accept arguments via argparse instead of raw sys.argv access']
```

Usage

```
{'run_benchmark_compare': 'run a benchmark comparing the current directory against a baseline git commit for size and speed', 'run_GitWorktree': 'create a temporary git worktree at a given commit and clean it up after use', 'run_Run': 'execute a shell command and raise an error if it fails', 'run_Benchmark': 'build and run CPU benchmarks then output results in benchstat format', 'run_bloaty_compare': 'strip debug symbols and compare binary sizes between old and new builds using bloaty'}
```

## File: google-deepmind_actionengine/third_party/protobuf/benchmarks/gen_protobuf_binary_cc.py

Prompts

```
['run a benchmark comparing the current directory against a baseline git commit for size and speed', 'create a temporary git worktree at a given commit and clean it up after use', 'execute a shell command and raise an error if it fails', 'build and run CPU benchmarks then output results in benchstat format', 'strip debug symbols and compare binary sizes between old and new builds using bloaty', 'run the script to generate a C++ benchmark source file for protobuf message serialization', 'run the script with an include path and message name to generate C++ code referencing protobuf messages', 'build a C++ benchmark file that parses and serializes multiple protobuf message types using this generator', 'refactor the RefMessage function to support additional protobuf serialization methods beyond ParseFromArray and SerializePartialToArray', 'summarize the script that generates C++ benchmark code for protobuf binary serialization and deserialization', 'run the script to generate synthetic proto benchmark files in a given output directory', 'create proto files containing 100 or 500 empty message definitions for benchmarking', 'create proto files with 100 or 200 weighted-random fields using real-world frequency distribution', 'refactor the choices function to support custom field type weights or additional protobuf types', 'summarize the field frequency distribution data showing which protobuf field types are most common', 'run the script with an include header and message basename to generate a C benchmark program', 'build a C benchmark that parses and serializes upb protobuf messages using an arena', 'run the script with a numeric suffix on the message name to generate code for multiple message types', 'review the RefMessage function that prints C code to parse and serialize a single upb message type', 'refactor the script to accept arguments via argparse instead of raw sys.argv access']
```

Usage

```
{'run_gen_protobuf_binary_cc': 'run the script to generate a C++ benchmark source file for protobuf message serialization', 'run_RefMessage': 'run the script with an include path and message name to generate C++ code referencing protobuf messages', 'build_protobuf_benchmark_cpp': 'build a C++ benchmark file that parses and serializes multiple protobuf message types using this generator', 'refactor_RefMessage': 'refactor the RefMessage function to support additional protobuf serialization methods beyond ParseFromArray and SerializePartialToArray', 'summarize_gen_protobuf_binary_cc': 'summarize the script that generates C++ benchmark code for protobuf binary serialization and deserialization'}
```

## File: google-deepmind_actionengine/third_party/protobuf/benchmarks/gen_synthetic_protos.py

Prompts

```
['run a benchmark comparing the current directory against a baseline git commit for size and speed', 'create a temporary git worktree at a given commit and clean it up after use', 'execute a shell command and raise an error if it fails', 'build and run CPU benchmarks then output results in benchstat format', 'strip debug symbols and compare binary sizes between old and new builds using bloaty', 'run the script to generate a C++ benchmark source file for protobuf message serialization', 'run the script with an include path and message name to generate C++ code referencing protobuf messages', 'build a C++ benchmark file that parses and serializes multiple protobuf message types using this generator', 'refactor the RefMessage function to support additional protobuf serialization methods beyond ParseFromArray and SerializePartialToArray', 'summarize the script that generates C++ benchmark code for protobuf binary serialization and deserialization', 'run the script to generate synthetic proto benchmark files in a given output directory', 'create proto files containing 100 or 500 empty message definitions for benchmarking', 'create proto files with 100 or 200 weighted-random fields using real-world frequency distribution', 'refactor the choices function to support custom field type weights or additional protobuf types', 'summarize the field frequency distribution data showing which protobuf field types are most common', 'run the script with an include header and message basename to generate a C benchmark program', 'build a C benchmark that parses and serializes upb protobuf messages using an arena', 'run the script with a numeric suffix on the message name to generate code for multiple message types', 'review the RefMessage function that prints C code to parse and serialize a single upb message type', 'refactor the script to accept arguments via argparse instead of raw sys.argv access']
```

Usage

```
{'run_gen_synthetic_protos': 'run the script to generate synthetic proto benchmark files in a given output directory', 'create_proto_messages': 'create proto files containing 100 or 500 empty message definitions for benchmarking', 'create_proto_fields': 'create proto files with 100 or 200 weighted-random fields using real-world frequency distribution', 'refactor_choices_function': 'refactor the choices function to support custom field type weights or additional protobuf types', 'summarize_field_freqs': 'summarize the field frequency distribution data showing which protobuf field types are most common'}
```

## File: google-deepmind_actionengine/third_party/protobuf/benchmarks/gen_upb_binary_c.py

Prompts

```
['run a benchmark comparing the current directory against a baseline git commit for size and speed', 'create a temporary git worktree at a given commit and clean it up after use', 'execute a shell command and raise an error if it fails', 'build and run CPU benchmarks then output results in benchstat format', 'strip debug symbols and compare binary sizes between old and new builds using bloaty', 'run the script to generate a C++ benchmark source file for protobuf message serialization', 'run the script with an include path and message name to generate C++ code referencing protobuf messages', 'build a C++ benchmark file that parses and serializes multiple protobuf message types using this generator', 'refactor the RefMessage function to support additional protobuf serialization methods beyond ParseFromArray and SerializePartialToArray', 'summarize the script that generates C++ benchmark code for protobuf binary serialization and deserialization', 'run the script to generate synthetic proto benchmark files in a given output directory', 'create proto files containing 100 or 500 empty message definitions for benchmarking', 'create proto files with 100 or 200 weighted-random fields using real-world frequency distribution', 'refactor the choices function to support custom field type weights or additional protobuf types', 'summarize the field frequency distribution data showing which protobuf field types are most common', 'run the script with an include header and message basename to generate a C benchmark program', 'build a C benchmark that parses and serializes upb protobuf messages using an arena', 'run the script with a numeric suffix on the message name to generate code for multiple message types', 'review the RefMessage function that prints C code to parse and serialize a single upb message type', 'refactor the script to accept arguments via argparse instead of raw sys.argv access']
```

Usage

```
{'generate_upb_benchmark_c': 'run the script with an include header and message basename to generate a C benchmark program', 'generate_c_parse_serialize': 'build a C benchmark that parses and serializes upb protobuf messages using an arena', 'generate_multi_message_benchmark': 'run the script with a numeric suffix on the message name to generate code for multiple message types', 'review_RefMessage': 'review the RefMessage function that prints C code to parse and serialize a single upb message type', 'refactor_gen_upb_binary_c': 'refactor the script to accept arguments via argparse instead of raw sys.argv access'}
```

