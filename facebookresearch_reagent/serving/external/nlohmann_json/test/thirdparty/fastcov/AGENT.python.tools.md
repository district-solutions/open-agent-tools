# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/nlohmann_json/test/thirdparty/fastcov/fastcov.py

Prompts

```
['run fastcov with --lcov flag to generate an lcov info file from gcda coverage data', 'run fastcov to generate a distilled JSON coverage report from gcda files in the build directory', 'run fastcov with --zerocounters flag to recursively delete all gcda files and reset coverage counters', 'run fastcov with --branch-coverage flag to include branch counts in the coverage report output', 'run fastcov with --exclude and --include flags to filter source files in the coverage report']
```

Usage

```
{'generate_lcov_coverage_report': 'run fastcov with --lcov flag to generate an lcov info file from gcda coverage data', 'generate_fastcov_json_report': 'run fastcov to generate a distilled JSON coverage report from gcda files in the build directory', 'zero_coverage_counters': 'run fastcov with --zerocounters flag to recursively delete all gcda files and reset coverage counters', 'generate_branch_coverage_report': 'run fastcov with --branch-coverage flag to include branch counts in the coverage report output', 'filter_coverage_by_source_files': 'run fastcov with --exclude and --include flags to filter source files in the coverage report'}
```

