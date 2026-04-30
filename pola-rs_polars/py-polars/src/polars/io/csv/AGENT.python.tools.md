# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/io/csv/batched_reader.py

Prompts

```
['create a BatchedCsvReader to read a CSV file in configurable batches with custom separator and date parsing', 'read n batches of DataFrames from a BatchedCsvReader using next_batches with a specified chunk count', 'select specific columns from a CSV file during batched reading by passing a column sequence to BatchedCsvReader', 'handle empty CSV files by controlling the raise_if_empty flag in BatchedCsvReader initialization', 'parse a CSV file with schema overrides and null value mappings in BatchedCsvReader for typed data ingestion', 'read a CSV file into a Polars DataFrame with custom separator and date parsing', 'lazily scan a CSV file or multiple files via glob patterns for query optimization', 'read a CSV file with schema_overrides to enforce specific column dtypes during inference', 'read a large CSV file in batches using BatchedCsvReader for memory-efficient processing', "read a CSV file using PyArrow's native CSV parser for faster date parsing"]
```

Usage

```
{'create_batched_csv_reader': 'create a BatchedCsvReader to read a CSV file in configurable batches with custom separator and date parsing', 'read_csv_batches': 'read n batches of DataFrames from a BatchedCsvReader using next_batches with a specified chunk count', 'select_csv_columns': 'select specific columns from a CSV file during batched reading by passing a column sequence to BatchedCsvReader', 'handle_empty_csv': 'handle empty CSV files by controlling the raise_if_empty flag in BatchedCsvReader initialization', 'parse_csv_with_schema': 'parse a CSV file with schema overrides and null value mappings in BatchedCsvReader for typed data ingestion'}
```

## File: pola-rs_polars/py-polars/src/polars/io/csv/functions.py

Prompts

```
['create a BatchedCsvReader to read a CSV file in configurable batches with custom separator and date parsing', 'read n batches of DataFrames from a BatchedCsvReader using next_batches with a specified chunk count', 'select specific columns from a CSV file during batched reading by passing a column sequence to BatchedCsvReader', 'handle empty CSV files by controlling the raise_if_empty flag in BatchedCsvReader initialization', 'parse a CSV file with schema overrides and null value mappings in BatchedCsvReader for typed data ingestion', 'read a CSV file into a Polars DataFrame with custom separator and date parsing', 'lazily scan a CSV file or multiple files via glob patterns for query optimization', 'read a CSV file with schema_overrides to enforce specific column dtypes during inference', 'read a large CSV file in batches using BatchedCsvReader for memory-efficient processing', "read a CSV file using PyArrow's native CSV parser for faster date parsing"]
```

Usage

```
{'read_csv_file': 'read a CSV file into a Polars DataFrame with custom separator and date parsing', 'scan_csv_lazy': 'lazily scan a CSV file or multiple files via glob patterns for query optimization', 'read_csv_with_schema_override': 'read a CSV file with schema_overrides to enforce specific column dtypes during inference', 'read_csv_batched_large_file': 'read a large CSV file in batches using BatchedCsvReader for memory-efficient processing', 'read_csv_pyarrow': "read a CSV file using PyArrow's native CSV parser for faster date parsing"}
```

