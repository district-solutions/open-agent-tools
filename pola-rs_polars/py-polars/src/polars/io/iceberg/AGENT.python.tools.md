# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/io/iceberg/_dataset.py

Prompts

```
['build a polars LazyFrame scan from a PyIceberg table with optional snapshot ID, projection, and filter columns', 'create an IcebergCatalogConfig from a PyIceberg catalog instance or load the default catalog', 'build an IcebergTableWrap that lazily fetches a PyIceberg Table from a catalog descriptor or static metadata path', 'convert Iceberg storage configuration keys to object-store compatible storage options for S3, Azure, and GCS', 'test the IcebergScanResolver that resolves an Iceberg table scan to either native parquet or pyiceberg fallback', 'create an IcebergSinkState instance to configure an Iceberg table sink with append or overwrite mode', 'attach an Iceberg sink to a polars LazyFrame for partitioned parquet writing', 'commit data file paths to an Iceberg table via a transaction with add_files', 'get the output base path for an Iceberg sink partitioned parquet output directory', 'resolve an Iceberg sink by attaching parquet partitioned output with storage options', 'build a pyiceberg filter expression from a pyarrow predicate string using AST conversion', 'create an iceberg statistics loader that loads min, max, and null count from data file metadata', 'build an identity-transformed partition values builder for iceberg table schema fields', 'scan a pyarrow dataset from an iceberg table with projected columns, filter, and row limit', 'load iceberg column statistics from binary byte values into polars series with proper dtype casting', 'scan an Apache Iceberg table from a local filesystem path and return a LazyFrame', 'scan an Iceberg table from S3 with storage options for authentication and region', 'scan an Iceberg table from Azure blob storage with account name and key options', 'scan an Iceberg table from Google Cloud Storage with project ID and OAuth token', 'scan an Iceberg table at a specific snapshot ID for point-in-time queries']
```

Usage

```
{'build_iceberg_scan_lazyframe': 'build a polars LazyFrame scan from a PyIceberg table with optional snapshot ID, projection, and filter columns', 'create_iceberg_catalog_config': 'create an IcebergCatalogConfig from a PyIceberg catalog instance or load the default catalog', 'build_iceberg_table_wrap': 'build an IcebergTableWrap that lazily fetches a PyIceberg Table from a catalog descriptor or static metadata path', 'convert_iceberg_storage_options': 'convert Iceberg storage configuration keys to object-store compatible storage options for S3, Azure, and GCS', 'test_iceberg_scan_resolver': 'test the IcebergScanResolver that resolves an Iceberg table scan to either native parquet or pyiceberg fallback'}
```

## File: pola-rs_polars/py-polars/src/polars/io/iceberg/_sink.py

Prompts

```
['build a polars LazyFrame scan from a PyIceberg table with optional snapshot ID, projection, and filter columns', 'create an IcebergCatalogConfig from a PyIceberg catalog instance or load the default catalog', 'build an IcebergTableWrap that lazily fetches a PyIceberg Table from a catalog descriptor or static metadata path', 'convert Iceberg storage configuration keys to object-store compatible storage options for S3, Azure, and GCS', 'test the IcebergScanResolver that resolves an Iceberg table scan to either native parquet or pyiceberg fallback', 'create an IcebergSinkState instance to configure an Iceberg table sink with append or overwrite mode', 'attach an Iceberg sink to a polars LazyFrame for partitioned parquet writing', 'commit data file paths to an Iceberg table via a transaction with add_files', 'get the output base path for an Iceberg sink partitioned parquet output directory', 'resolve an Iceberg sink by attaching parquet partitioned output with storage options', 'build a pyiceberg filter expression from a pyarrow predicate string using AST conversion', 'create an iceberg statistics loader that loads min, max, and null count from data file metadata', 'build an identity-transformed partition values builder for iceberg table schema fields', 'scan a pyarrow dataset from an iceberg table with projected columns, filter, and row limit', 'load iceberg column statistics from binary byte values into polars series with proper dtype casting', 'scan an Apache Iceberg table from a local filesystem path and return a LazyFrame', 'scan an Iceberg table from S3 with storage options for authentication and region', 'scan an Iceberg table from Azure blob storage with account name and key options', 'scan an Iceberg table from Google Cloud Storage with project ID and OAuth token', 'scan an Iceberg table at a specific snapshot ID for point-in-time queries']
```

Usage

```
{'create_iceberg_sink_state': 'create an IcebergSinkState instance to configure an Iceberg table sink with append or overwrite mode', 'attach_iceberg_sink_to_lazyframe': 'attach an Iceberg sink to a polars LazyFrame for partitioned parquet writing', 'commit_iceberg_sink_data_files': 'commit data file paths to an Iceberg table via a transaction with add_files', 'get_iceberg_sink_output_base_path': 'get the output base path for an Iceberg sink partitioned parquet output directory', 'resolve_iceberg_sink_with_parquet': 'resolve an Iceberg sink by attaching parquet partitioned output with storage options'}
```

## File: pola-rs_polars/py-polars/src/polars/io/iceberg/_utils.py

Prompts

```
['build a polars LazyFrame scan from a PyIceberg table with optional snapshot ID, projection, and filter columns', 'create an IcebergCatalogConfig from a PyIceberg catalog instance or load the default catalog', 'build an IcebergTableWrap that lazily fetches a PyIceberg Table from a catalog descriptor or static metadata path', 'convert Iceberg storage configuration keys to object-store compatible storage options for S3, Azure, and GCS', 'test the IcebergScanResolver that resolves an Iceberg table scan to either native parquet or pyiceberg fallback', 'create an IcebergSinkState instance to configure an Iceberg table sink with append or overwrite mode', 'attach an Iceberg sink to a polars LazyFrame for partitioned parquet writing', 'commit data file paths to an Iceberg table via a transaction with add_files', 'get the output base path for an Iceberg sink partitioned parquet output directory', 'resolve an Iceberg sink by attaching parquet partitioned output with storage options', 'build a pyiceberg filter expression from a pyarrow predicate string using AST conversion', 'create an iceberg statistics loader that loads min, max, and null count from data file metadata', 'build an identity-transformed partition values builder for iceberg table schema fields', 'scan a pyarrow dataset from an iceberg table with projected columns, filter, and row limit', 'load iceberg column statistics from binary byte values into polars series with proper dtype casting', 'scan an Apache Iceberg table from a local filesystem path and return a LazyFrame', 'scan an Iceberg table from S3 with storage options for authentication and region', 'scan an Iceberg table from Azure blob storage with account name and key options', 'scan an Iceberg table from Google Cloud Storage with project ID and OAuth token', 'scan an Iceberg table at a specific snapshot ID for point-in-time queries']
```

Usage

```
{'build_iceberg_predicate_converter': 'build a pyiceberg filter expression from a pyarrow predicate string using AST conversion', 'create_iceberg_statistics_loader': 'create an iceberg statistics loader that loads min, max, and null count from data file metadata', 'build_partition_values_builder': 'build an identity-transformed partition values builder for iceberg table schema fields', 'scan_pyarrow_dataset_from_iceberg': 'scan a pyarrow dataset from an iceberg table with projected columns, filter, and row limit', 'load_iceberg_bytes_statistics': 'load iceberg column statistics from binary byte values into polars series with proper dtype casting'}
```

## File: pola-rs_polars/py-polars/src/polars/io/iceberg/functions.py

Prompts

```
['build a polars LazyFrame scan from a PyIceberg table with optional snapshot ID, projection, and filter columns', 'create an IcebergCatalogConfig from a PyIceberg catalog instance or load the default catalog', 'build an IcebergTableWrap that lazily fetches a PyIceberg Table from a catalog descriptor or static metadata path', 'convert Iceberg storage configuration keys to object-store compatible storage options for S3, Azure, and GCS', 'test the IcebergScanResolver that resolves an Iceberg table scan to either native parquet or pyiceberg fallback', 'create an IcebergSinkState instance to configure an Iceberg table sink with append or overwrite mode', 'attach an Iceberg sink to a polars LazyFrame for partitioned parquet writing', 'commit data file paths to an Iceberg table via a transaction with add_files', 'get the output base path for an Iceberg sink partitioned parquet output directory', 'resolve an Iceberg sink by attaching parquet partitioned output with storage options', 'build a pyiceberg filter expression from a pyarrow predicate string using AST conversion', 'create an iceberg statistics loader that loads min, max, and null count from data file metadata', 'build an identity-transformed partition values builder for iceberg table schema fields', 'scan a pyarrow dataset from an iceberg table with projected columns, filter, and row limit', 'load iceberg column statistics from binary byte values into polars series with proper dtype casting', 'scan an Apache Iceberg table from a local filesystem path and return a LazyFrame', 'scan an Iceberg table from S3 with storage options for authentication and region', 'scan an Iceberg table from Azure blob storage with account name and key options', 'scan an Iceberg table from Google Cloud Storage with project ID and OAuth token', 'scan an Iceberg table at a specific snapshot ID for point-in-time queries']
```

Usage

```
{'scan_iceberg': 'scan an Apache Iceberg table from a local filesystem path and return a LazyFrame', 'scan_iceberg_s3': 'scan an Iceberg table from S3 with storage options for authentication and region', 'scan_iceberg_azure': 'scan an Iceberg table from Azure blob storage with account name and key options', 'scan_iceberg_gcs': 'scan an Iceberg table from Google Cloud Storage with project ID and OAuth token', 'scan_iceberg_snapshot': 'scan an Iceberg table at a specific snapshot ID for point-in-time queries'}
```

