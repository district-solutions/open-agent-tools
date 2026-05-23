# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/abseil-cpp/preprocessed_builds.yaml.gen.py

Prompts

```
['run generate_builds to produce a YAML list of all abseil cc_library rules with headers, sources, and deps', 'parse a Bazel XML rule element into a Rule namedtuple with normalized paths and dependencies', 'parse an absl_cc_library CMake rule string into a Rule namedtuple with name, srcs, hdrs, and deps', 'match Bazel rules to CMake rules by comparing source and header file overlap to build a pair map', 'walk a directory tree to find all BUILD.bazel files and collect cc_library rules via bazel query']
```

Usage

```
{'generate_builds_abseil': 'run generate_builds to produce a YAML list of all abseil cc_library rules with headers, sources, and deps', 'parse_bazel_rule_from_xml': 'parse a Bazel XML rule element into a Rule namedtuple with normalized paths and dependencies', 'parse_cmake_rule_from_text': 'parse an absl_cc_library CMake rule string into a Rule namedtuple with name, srcs, hdrs, and deps', 'pairing_bazel_and_cmake_rules': 'match Bazel rules to CMake rules by comparing source and header file overlap to build a pair map', 'collect_bazel_rules_recursive': 'walk a directory tree to find all BUILD.bazel files and collect cc_library rules via bazel query'}
```

