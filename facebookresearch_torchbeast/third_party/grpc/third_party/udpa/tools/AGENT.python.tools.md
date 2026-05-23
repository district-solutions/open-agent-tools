# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/udpa/tools/generate_go_protobuf.py

Prompts

```
['run the script to generate Go protobufs from Bazel go_proto_library rules and copy them to the workspace', 'build all Go protobuf library targets using Bazel in fastbuild mode', 'copy generated Go protobuf files from the Bazel bin directory to a custom output directory', 'query Bazel for all go_proto_library targets in the workspace', 'create the output directory structure for organizing generated Go protobuf files by rule directory']
```

Usage

```
{'run_generate_protobufs': 'run the script to generate Go protobufs from Bazel go_proto_library rules and copy them to the workspace', 'build_go_protobufs_with_bazel': 'build all Go protobuf library targets using Bazel in fastbuild mode', 'copy_generated_go_files': 'copy generated Go protobuf files from the Bazel bin directory to a custom output directory', 'query_go_proto_library_rules': 'query Bazel for all go_proto_library targets in the workspace', 'setup_output_directory': 'create the output directory structure for organizing generated Go protobuf files by rule directory'}
```

