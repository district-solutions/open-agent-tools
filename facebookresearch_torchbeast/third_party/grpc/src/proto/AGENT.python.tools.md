# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/proto/gen_build_yaml.py

Prompts

```
['run the script to generate YAML build data for all proto files in src/proto', 'run update_deps to parse a proto file and extract its import dependencies recursively', 'summarize how update_deps traverses proto imports to build direct and transitive dependency graphs', 'review update_deps to understand how it separates google external deps from internal proto deps', 'refactor update_deps to use a set instead of a list for the visited parameter to improve lookup performance']
```

Usage

```
{'run_gen_build_yaml': 'run the script to generate YAML build data for all proto files in src/proto', 'run_update_deps': 'run update_deps to parse a proto file and extract its import dependencies recursively', 'summarize_update_deps': 'summarize how update_deps traverses proto imports to build direct and transitive dependency graphs', 'review_update_deps': 'review update_deps to understand how it separates google external deps from internal proto deps', 'refactor_update_deps': 'refactor update_deps to use a set instead of a list for the visited parameter to improve lookup performance'}
```

