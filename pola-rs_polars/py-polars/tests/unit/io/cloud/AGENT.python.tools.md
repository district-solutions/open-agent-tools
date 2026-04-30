# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/io/cloud/test_aws.py

Prompts

```
['test reading a CSV file from S3 using pl.read_csv with storage_options endpoint_url', 'test reading an IPC file from S3 using pl.read_ipc with storage_options endpoint_url', 'test scanning an IPC file from S3 using pl.scan_ipc with storage_options endpoint_url', 'test scanning a parquet file from S3 using pl.scan_parquet with storage_options endpoint_url', 'test lazy count aggregation on S3 parquet files using pl.scan_parquet with glob pattern and pl.len()', 'test the pl.Catalog class raises ValueError when given an http:// URL with require_https enabled', 'create a pl.Catalog instance using a valid https:// URL', 'create a pl.Catalog instance using an http:// URL with require_https set to False', 'test that pl.Catalog rejects http:// URLs by raising ValueError when require_https is True', 'review the pl.Catalog class and its https URL requirement validation behavior', 'test scanning a nonexistent S3 cloud path returns a LazyFrame without raising errors immediately', 'test that credential provider callbacks are called the expected number of times on collection failure', 'test the _is_aws_cloud utility correctly identifies AWS S3 cloud URLs and rejects non-AWS paths', 'test polars scan_parquet scan_csv scan_ndjson and scan_ipc functions with credential_provider=None on S3 paths', 'test that collecting a LazyFrame from a nonexistent S3 path raises an IOError', 'test credential provider auto initialization with scan_parquet, read_parquet, scan_csv, scan_ndjson, read_ndjson, and scan_ipc io functions', 'test credential provider auto initialization serialization with pickle for AWS, GCP, and Azure providers', 'test credential provider builder cache behavior with POLARS_CREDENTIAL_PROVIDER_BUILDER_CACHE_SIZE configuration', 'test credential provider credentials caching with POLARS_DISABLE_PYTHON_CREDENTIAL_CACHING configuration', 'test AWS credential provider expiry handling with credential_process profiles and session tokens']
```

Usage

```
{'test_read_s3_csv': 'test reading a CSV file from S3 using pl.read_csv with storage_options endpoint_url', 'test_read_s3_ipc': 'test reading an IPC file from S3 using pl.read_ipc with storage_options endpoint_url', 'test_scan_s3_ipc': 'test scanning an IPC file from S3 using pl.scan_ipc with storage_options endpoint_url', 'test_scan_s3_parquet': 'test scanning a parquet file from S3 using pl.scan_parquet with storage_options endpoint_url', 'test_lazy_count_s3': 'test lazy count aggregation on S3 parquet files using pl.scan_parquet with glob pattern and pl.len()'}
```

## File: pola-rs_polars/py-polars/tests/unit/io/cloud/test_catalog.py

Prompts

```
['test reading a CSV file from S3 using pl.read_csv with storage_options endpoint_url', 'test reading an IPC file from S3 using pl.read_ipc with storage_options endpoint_url', 'test scanning an IPC file from S3 using pl.scan_ipc with storage_options endpoint_url', 'test scanning a parquet file from S3 using pl.scan_parquet with storage_options endpoint_url', 'test lazy count aggregation on S3 parquet files using pl.scan_parquet with glob pattern and pl.len()', 'test the pl.Catalog class raises ValueError when given an http:// URL with require_https enabled', 'create a pl.Catalog instance using a valid https:// URL', 'create a pl.Catalog instance using an http:// URL with require_https set to False', 'test that pl.Catalog rejects http:// URLs by raising ValueError when require_https is True', 'review the pl.Catalog class and its https URL requirement validation behavior', 'test scanning a nonexistent S3 cloud path returns a LazyFrame without raising errors immediately', 'test that credential provider callbacks are called the expected number of times on collection failure', 'test the _is_aws_cloud utility correctly identifies AWS S3 cloud URLs and rejects non-AWS paths', 'test polars scan_parquet scan_csv scan_ndjson and scan_ipc functions with credential_provider=None on S3 paths', 'test that collecting a LazyFrame from a nonexistent S3 path raises an IOError', 'test credential provider auto initialization with scan_parquet, read_parquet, scan_csv, scan_ndjson, read_ndjson, and scan_ipc io functions', 'test credential provider auto initialization serialization with pickle for AWS, GCP, and Azure providers', 'test credential provider builder cache behavior with POLARS_CREDENTIAL_PROVIDER_BUILDER_CACHE_SIZE configuration', 'test credential provider credentials caching with POLARS_DISABLE_PYTHON_CREDENTIAL_CACHING configuration', 'test AWS credential provider expiry handling with credential_process profiles and session tokens']
```

Usage

```
{'test_Catalog_require_https': 'test the pl.Catalog class raises ValueError when given an http:// URL with require_https enabled', 'create_Catalog_https': 'create a pl.Catalog instance using a valid https:// URL', 'create_Catalog_http_disabled': 'create a pl.Catalog instance using an http:// URL with require_https set to False', 'test_Catalog_http_rejected': 'test that pl.Catalog rejects http:// URLs by raising ValueError when require_https is True', 'review_Catalog_https_requirement': 'review the pl.Catalog class and its https URL requirement validation behavior'}
```

## File: pola-rs_polars/py-polars/tests/unit/io/cloud/test_cloud.py

Prompts

```
['test reading a CSV file from S3 using pl.read_csv with storage_options endpoint_url', 'test reading an IPC file from S3 using pl.read_ipc with storage_options endpoint_url', 'test scanning an IPC file from S3 using pl.scan_ipc with storage_options endpoint_url', 'test scanning a parquet file from S3 using pl.scan_parquet with storage_options endpoint_url', 'test lazy count aggregation on S3 parquet files using pl.scan_parquet with glob pattern and pl.len()', 'test the pl.Catalog class raises ValueError when given an http:// URL with require_https enabled', 'create a pl.Catalog instance using a valid https:// URL', 'create a pl.Catalog instance using an http:// URL with require_https set to False', 'test that pl.Catalog rejects http:// URLs by raising ValueError when require_https is True', 'review the pl.Catalog class and its https URL requirement validation behavior', 'test scanning a nonexistent S3 cloud path returns a LazyFrame without raising errors immediately', 'test that credential provider callbacks are called the expected number of times on collection failure', 'test the _is_aws_cloud utility correctly identifies AWS S3 cloud URLs and rejects non-AWS paths', 'test polars scan_parquet scan_csv scan_ndjson and scan_ipc functions with credential_provider=None on S3 paths', 'test that collecting a LazyFrame from a nonexistent S3 path raises an IOError', 'test credential provider auto initialization with scan_parquet, read_parquet, scan_csv, scan_ndjson, read_ndjson, and scan_ipc io functions', 'test credential provider auto initialization serialization with pickle for AWS, GCP, and Azure providers', 'test credential provider builder cache behavior with POLARS_CREDENTIAL_PROVIDER_BUILDER_CACHE_SIZE configuration', 'test credential provider credentials caching with POLARS_DISABLE_PYTHON_CREDENTIAL_CACHING configuration', 'test AWS credential provider expiry handling with credential_process profiles and session tokens']
```

Usage

```
{'test_scan_nonexistent_cloud_path': 'test scanning a nonexistent S3 cloud path returns a LazyFrame without raising errors immediately', 'test_scan_err_rebuild_store': 'test that credential provider callbacks are called the expected number of times on collection failure', 'test_is_aws_cloud': 'test the _is_aws_cloud utility correctly identifies AWS S3 cloud URLs and rejects non-AWS paths', 'test_scan_cloud_formats': 'test polars scan_parquet scan_csv scan_ndjson and scan_ipc functions with credential_provider=None on S3 paths', 'test_cloud_collection_raises_ioerror': 'test that collecting a LazyFrame from a nonexistent S3 path raises an IOError'}
```

## File: pola-rs_polars/py-polars/tests/unit/io/cloud/test_credential_provider.py

Prompts

```
['test reading a CSV file from S3 using pl.read_csv with storage_options endpoint_url', 'test reading an IPC file from S3 using pl.read_ipc with storage_options endpoint_url', 'test scanning an IPC file from S3 using pl.scan_ipc with storage_options endpoint_url', 'test scanning a parquet file from S3 using pl.scan_parquet with storage_options endpoint_url', 'test lazy count aggregation on S3 parquet files using pl.scan_parquet with glob pattern and pl.len()', 'test the pl.Catalog class raises ValueError when given an http:// URL with require_https enabled', 'create a pl.Catalog instance using a valid https:// URL', 'create a pl.Catalog instance using an http:// URL with require_https set to False', 'test that pl.Catalog rejects http:// URLs by raising ValueError when require_https is True', 'review the pl.Catalog class and its https URL requirement validation behavior', 'test scanning a nonexistent S3 cloud path returns a LazyFrame without raising errors immediately', 'test that credential provider callbacks are called the expected number of times on collection failure', 'test the _is_aws_cloud utility correctly identifies AWS S3 cloud URLs and rejects non-AWS paths', 'test polars scan_parquet scan_csv scan_ndjson and scan_ipc functions with credential_provider=None on S3 paths', 'test that collecting a LazyFrame from a nonexistent S3 path raises an IOError', 'test credential provider auto initialization with scan_parquet, read_parquet, scan_csv, scan_ndjson, read_ndjson, and scan_ipc io functions', 'test credential provider auto initialization serialization with pickle for AWS, GCP, and Azure providers', 'test credential provider builder cache behavior with POLARS_CREDENTIAL_PROVIDER_BUILDER_CACHE_SIZE configuration', 'test credential provider credentials caching with POLARS_DISABLE_PYTHON_CREDENTIAL_CACHING configuration', 'test AWS credential provider expiry handling with credential_process profiles and session tokens']
```

Usage

```
{'test_credential_provider_scan': 'test credential provider auto initialization with scan_parquet, read_parquet, scan_csv, scan_ndjson, read_ndjson, and scan_ipc io functions', 'test_credential_provider_serialization_auto_init': 'test credential provider auto initialization serialization with pickle for AWS, GCP, and Azure providers', 'test_credential_provider_python_builder_cache': 'test credential provider builder cache behavior with POLARS_CREDENTIAL_PROVIDER_BUILDER_CACHE_SIZE configuration', 'test_credential_provider_python_credentials_cache': 'test credential provider credentials caching with POLARS_DISABLE_PYTHON_CREDENTIAL_CACHING configuration', 'test_credential_provider_aws_expiry': 'test AWS credential provider expiry handling with credential_process profiles and session tokens'}
```

