# Agent Python Tools

- repo: facebookresearch/replica-dataset
- repo_uri: https://github.com/facebookresearch/replica-dataset

## File: facebookresearch_replica-dataset/3rdparty/eigen/debug/gdb/printers.py

Prompts

```
['register eigen pretty-printers with gdb so matrix and quaternion types display readably during debugging sessions', 'look up and return the appropriate pretty-printer for a given gdb value by matching its type name', 'build the regex-to-printer dictionary mapping eigen type patterns to their corresponding pretty-printer classes', 'create a pretty-printer for eigen dense matrices or arrays that extracts dimensions, storage layout, and element data', 'create a pretty-printer for eigen sparse matrices that iterates over compressed storage and returns non-zero entries']
```

Usage

```
{'register_eigen_printers': 'register eigen pretty-printers with gdb so matrix and quaternion types display readably during debugging sessions', 'lookup_function': 'look up and return the appropriate pretty-printer for a given gdb value by matching its type name', 'build_eigen_dictionary': 'build the regex-to-printer dictionary mapping eigen type patterns to their corresponding pretty-printer classes', 'EigenMatrixPrinter': 'create a pretty-printer for eigen dense matrices or arrays that extracts dimensions, storage layout, and element data', 'EigenSparseMatrixPrinter': 'create a pretty-printer for eigen sparse matrices that iterates over compressed storage and returns non-zero entries'}
```

