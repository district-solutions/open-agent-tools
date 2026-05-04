# Agent Python Tools

- repo: facebookresearch/ariadatatools
- repo_uri: https://github.com/facebookresearch/aria_data_tools

## File: facebookresearch_ariadatatools/src/third_party/eigen/debug/gdb/printers.py

Prompts

```
['register eigen pretty-printers with gdb so matrix and quaternion types display nicely during debugging sessions', 'look up and return the appropriate pretty-printer class for a given gdb value by matching its type name', 'build the registry mapping eigen type regex patterns to their corresponding pretty-printer constructor lambdas', 'cast an eigen block or vectorblock expression to a plain eigen matrix type for uniform pretty-printing', 'create a gdb pretty-printer for eigen dense matrix or array types supporting both fixed and dynamic sizes']
```

Usage

```
{'register_eigen_printers': 'register eigen pretty-printers with gdb so matrix and quaternion types display nicely during debugging sessions', 'lookup_function': 'look up and return the appropriate pretty-printer class for a given gdb value by matching its type name', 'build_eigen_dictionary': 'build the registry mapping eigen type regex patterns to their corresponding pretty-printer constructor lambdas', 'cast_eigen_block_to_matrix': 'cast an eigen block or vectorblock expression to a plain eigen matrix type for uniform pretty-printing', 'EigenMatrixPrinter': 'create a gdb pretty-printer for eigen dense matrix or array types supporting both fixed and dynamic sizes'}
```

