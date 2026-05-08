# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/build_helpers/build_helpers.py

Prompts

```
['run the ANTLRCommand to generate Python3 parsers from OverrideLexer and OverrideParser grammar files', 'run the CleanCommand to remove generated files, pycache, egg-info, and build directories', 'find the __version__ string in a Python file using regex pattern matching', 'find files and directories matching include patterns while excluding specified paths from a root', 'test the matches function to check if a string matches any of the provided regex patterns', 'test the find function with include_files, include_dirs, excludes, and scan_exclude regex patterns', 'test the matches function with regex patterns and path queries including backslash normalization', 'review the test_find parametrized test cases covering file and directory filtering scenarios', 'review the test_matches parametrized test cases covering cross-platform path separator matching', 'refactor the test_find function to add new include or exclude pattern test cases']
```

Usage

```
{'run_antlr_parsers': 'run the ANTLRCommand to generate Python3 parsers from OverrideLexer and OverrideParser grammar files', 'run_clean_command': 'run the CleanCommand to remove generated files, pycache, egg-info, and build directories', 'find_version_string': 'find the __version__ string in a Python file using regex pattern matching', 'find_files_with_patterns': 'find files and directories matching include patterns while excluding specified paths from a root', 'test_matches_function': 'test the matches function to check if a string matches any of the provided regex patterns'}
```

## File: facebookresearch_hydra/build_helpers/test_helpers.py

Prompts

```
['run the ANTLRCommand to generate Python3 parsers from OverrideLexer and OverrideParser grammar files', 'run the CleanCommand to remove generated files, pycache, egg-info, and build directories', 'find the __version__ string in a Python file using regex pattern matching', 'find files and directories matching include patterns while excluding specified paths from a root', 'test the matches function to check if a string matches any of the provided regex patterns', 'test the find function with include_files, include_dirs, excludes, and scan_exclude regex patterns', 'test the matches function with regex patterns and path queries including backslash normalization', 'review the test_find parametrized test cases covering file and directory filtering scenarios', 'review the test_matches parametrized test cases covering cross-platform path separator matching', 'refactor the test_find function to add new include or exclude pattern test cases']
```

Usage

```
{'test_find': 'test the find function with include_files, include_dirs, excludes, and scan_exclude regex patterns', 'test_matches': 'test the matches function with regex patterns and path queries including backslash normalization', 'review_test_find': 'review the test_find parametrized test cases covering file and directory filtering scenarios', 'review_test_matches': 'review the test_matches parametrized test cases covering cross-platform path separator matching', 'refactor_test_find': 'refactor the test_find function to add new include or exclude pattern test cases'}
```

