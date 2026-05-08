# Agent Python Tools

- repo: facebookresearch/looptool
- repo_uri: https://github.com/facebookresearch/loop_tool

## File: facebookresearch_looptool/extern/wasm-micro-runtime/ci/coding_guidelines_check.py

Prompts

```
['run the coding guidelines check CLI tool against a commit range to validate C/C++ code style and naming conventions', 'run clang-format diff check on a commit range to find C/C++ files with formatting violations', 'check a file path for invalid naming segments containing hyphens instead of underscores', 'check a directory path for invalid naming segments containing underscores instead of hyphens', 'process an entire PR by checking commit naming conventions and clang-format compliance across all commits']
```

Usage

```
{'run_coding_guidelines_check': 'run the coding guidelines check CLI tool against a commit range to validate C/C++ code style and naming conventions', 'run_clang_format_diff': 'run clang-format diff check on a commit range to find C/C++ files with formatting violations', 'check_file_name': 'check a file path for invalid naming segments containing hyphens instead of underscores', 'check_dir_name': 'check a directory path for invalid naming segments containing underscores instead of hyphens', 'process_entire_pr': 'process an entire PR by checking commit naming conventions and clang-format compliance across all commits'}
```

