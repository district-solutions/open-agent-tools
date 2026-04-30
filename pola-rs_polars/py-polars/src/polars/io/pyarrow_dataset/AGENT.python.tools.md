# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/io/pyarrow_dataset/anonymous_scan.py

Prompts

```
['create a LazyFrame from a PyArrow dataset with optional predicate pushdown and batch size', 'build a DataFrame by scanning a PyArrow dataset with projected columns and optional row limit', 'test predicate pushdown behavior when allow_pyarrow_filter is enabled for PyArrow dataset scans', 'review the _scan_pyarrow_dataset_impl function that materializes Arrow tables from projected columns', 'summarize how batch_size and user_batch_size parameters control record batch sizes in PyArrow dataset scans', 'scan a pyarrow dataset and return a polars LazyFrame for lazy evaluation', 'scan a partitioned cloud dataset stored in s3 using pyarrow dataset with ipc format', 'scan a pyarrow dataset and push down predicates to pyarrow for filtered column selection', 'scan a pyarrow dataset with a custom batch size to control record batch row counts', 'scan a partitioned pyarrow dataset ensuring partition columns are passed to polars']
```

Usage

```
{'create_scan_pyarrow_dataset': 'create a LazyFrame from a PyArrow dataset with optional predicate pushdown and batch size', 'build_scan_pyarrow_dataset_impl': 'build a DataFrame by scanning a PyArrow dataset with projected columns and optional row limit', 'test_allow_pyarrow_filter': 'test predicate pushdown behavior when allow_pyarrow_filter is enabled for PyArrow dataset scans', 'review_scan_pyarrow_dataset_impl': 'review the _scan_pyarrow_dataset_impl function that materializes Arrow tables from projected columns', 'summarize_batch_size_handling': 'summarize how batch_size and user_batch_size parameters control record batch sizes in PyArrow dataset scans'}
```

## File: pola-rs_polars/py-polars/src/polars/io/pyarrow_dataset/functions.py

Prompts

```
['create a LazyFrame from a PyArrow dataset with optional predicate pushdown and batch size', 'build a DataFrame by scanning a PyArrow dataset with projected columns and optional row limit', 'test predicate pushdown behavior when allow_pyarrow_filter is enabled for PyArrow dataset scans', 'review the _scan_pyarrow_dataset_impl function that materializes Arrow tables from projected columns', 'summarize how batch_size and user_batch_size parameters control record batch sizes in PyArrow dataset scans', 'scan a pyarrow dataset and return a polars LazyFrame for lazy evaluation', 'scan a partitioned cloud dataset stored in s3 using pyarrow dataset with ipc format', 'scan a pyarrow dataset and push down predicates to pyarrow for filtered column selection', 'scan a pyarrow dataset with a custom batch size to control record batch row counts', 'scan a partitioned pyarrow dataset ensuring partition columns are passed to polars']
```

Usage

```
{'scan_pyarrow_dataset': 'scan a pyarrow dataset and return a polars LazyFrame for lazy evaluation', 'scan_pyarrow_dataset_cloud': 'scan a partitioned cloud dataset stored in s3 using pyarrow dataset with ipc format', 'scan_pyarrow_dataset_filter': 'scan a pyarrow dataset and push down predicates to pyarrow for filtered column selection', 'scan_pyarrow_dataset_batch': 'scan a pyarrow dataset with a custom batch size to control record batch row counts', 'scan_pyarrow_dataset_partitioned': 'scan a partitioned pyarrow dataset ensuring partition columns are passed to polars'}
```

