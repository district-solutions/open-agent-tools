# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/eigen/debug/gdb/printers.py

Prompts

```
['register eigen pretty-printers with gdb so Matrix, SparseMatrix, Array, and Quaternion types display nicely in the debugger', 'look up and return the appropriate pretty-printer for a given gdb value based on its typename', 'create a pretty-printer for Eigen Matrix or Array types that extracts template params, dimensions, and data pointers', 'create a pretty-printer for Eigen SparseMatrix types that iterates over compressed sparse row or column storage', 'create a pretty-printer for Eigen Quaternion types that exposes x, y, z, w components as named children']
```

Usage

```
{'register_eigen_printers': 'register eigen pretty-printers with gdb so Matrix, SparseMatrix, Array, and Quaternion types display nicely in the debugger', 'lookup_function': 'look up and return the appropriate pretty-printer for a given gdb value based on its typename', 'EigenMatrixPrinter': 'create a pretty-printer for Eigen Matrix or Array types that extracts template params, dimensions, and data pointers', 'EigenSparseMatrixPrinter': 'create a pretty-printer for Eigen SparseMatrix types that iterates over compressed sparse row or column storage', 'EigenQuaternionPrinter': 'create a pretty-printer for Eigen Quaternion types that exposes x, y, z, w components as named children'}
```

