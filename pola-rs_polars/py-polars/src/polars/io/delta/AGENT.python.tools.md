# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/io/delta/_dataset.py

Prompts

```
['create a DeltaDataset instance to interface with a Delta Lake table for scanning and querying', 'build a LazyFrame scan from a DeltaDataset with projection, limit, and filter column options', 'fetch the schema of a Delta Lake table through a DeltaDataset instance', 'extract deletion vectors from a Delta Lake table for filtered parquet file paths', 'fetch deletion vectors from a Delta Lake table as a Polars DataFrame', 'read a Delta lake table from a local filesystem path into a DataFrame', 'read a specific version of a Delta lake table by numerical version number', 'read a Delta lake table from AWS S3 or GCS with storage authentication options', 'read a Delta lake table and select only specified columns into a DataFrame', 'create a lazy scan of a Delta lake table that returns a LazyFrame for deferred execution']
```

Usage

```
{'create_DeltaDataset': 'create a DeltaDataset instance to interface with a Delta Lake table for scanning and querying', 'build_DeltaDataset_scan': 'build a LazyFrame scan from a DeltaDataset with projection, limit, and filter column options', 'fetch_DeltaDataset_schema': 'fetch the schema of a Delta Lake table through a DeltaDataset instance', 'extract_delta_deletion_vectors': 'extract deletion vectors from a Delta Lake table for filtered parquet file paths', 'fetch_delta_deletion_vectors': 'fetch deletion vectors from a Delta Lake table as a Polars DataFrame'}
```

## File: pola-rs_polars/py-polars/src/polars/io/delta/functions.py

Prompts

```
['create a DeltaDataset instance to interface with a Delta Lake table for scanning and querying', 'build a LazyFrame scan from a DeltaDataset with projection, limit, and filter column options', 'fetch the schema of a Delta Lake table through a DeltaDataset instance', 'extract deletion vectors from a Delta Lake table for filtered parquet file paths', 'fetch deletion vectors from a Delta Lake table as a Polars DataFrame', 'read a Delta lake table from a local filesystem path into a DataFrame', 'read a specific version of a Delta lake table by numerical version number', 'read a Delta lake table from AWS S3 or GCS with storage authentication options', 'read a Delta lake table and select only specified columns into a DataFrame', 'create a lazy scan of a Delta lake table that returns a LazyFrame for deferred execution']
```

Usage

```
{'read_delta_local_table': 'read a Delta lake table from a local filesystem path into a DataFrame', 'read_delta_versioned_table': 'read a specific version of a Delta lake table by numerical version number', 'read_delta_cloud_storage': 'read a Delta lake table from AWS S3 or GCS with storage authentication options', 'read_delta_with_columns': 'read a Delta lake table and select only specified columns into a DataFrame', 'scan_delta_lazy': 'create a lazy scan of a Delta lake table that returns a LazyFrame for deferred execution'}
```

