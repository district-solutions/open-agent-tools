# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/nlohmann_json/test/thirdparty/imapdl/filterbr.py

Prompts

```
['filter an LCOV trace file to keep only branch data for lines containing preprocessor conditionals', 'skip single line and multi-line C style comments from source code lines using a state machine', 'find line numbers containing standalone if conditionals with balanced parentheses in source code', 'parse a source file to yield line numbers of preprocessor conditional statements after stripping comments', 'filter LCOV trace lines by source file and branch data, keeping only relevant branch coverage entries']
```

Usage

```
{'filter_lcov_branch_coverage': 'filter an LCOV trace file to keep only branch data for lines containing preprocessor conditionals', 'skip_c_style_comments': 'skip single line and multi-line C style comments from source code lines using a state machine', 'find_conditional_lines': 'find line numbers containing standalone if conditionals with balanced parentheses in source code', 'parse_conditional_lines_from_file': 'parse a source file to yield line numbers of preprocessor conditional statements after stripping comments', 'filter_lcov_trace_lines': 'filter LCOV trace lines by source file and branch data, keeping only relevant branch coverage entries'}
```

