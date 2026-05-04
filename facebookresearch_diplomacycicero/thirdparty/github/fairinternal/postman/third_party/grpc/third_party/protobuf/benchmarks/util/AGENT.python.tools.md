# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/benchmarks/util/big_query_utils.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create a new BigQuery table with a given schema and description in a dataset', 'create a partitioned BigQuery table with day-level partitioning and a 30-day expiration policy', 'insert a list of rows into a BigQuery table using the insertAll API method', 'parse C++ benchmark JSON results and extract throughput per benchmark entry', 'parse Java JMH benchmark JSON results and compute weighted average throughput', 'parse Python benchmark JSON results and extract per-behavior throughput data', 'parse Go text benchmark output and extract per-operation throughput metrics', 'get aggregated benchmark results from multiple language result files at once', 'run the CLI to upload protobuf benchmark results from multiple language files to BigQuery', 'run get_metadata to collect CI build number, job name, and git commit from environment variables', 'run upload_result to insert a list of benchmark throughput results into a BigQuery table', 'review get_metadata to understand how CI environment variables are collected into a metadata dictionary', 'review upload_result to see how benchmark results are formatted and inserted into BigQuery with labels']
```

Usage

```
{'create_bigquery_service': 'create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create_bigquery_dataset': 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create_bigquery_table': 'create a new BigQuery table with a given schema and description in a dataset', 'create_partitioned_bigquery_table': 'create a partitioned BigQuery table with day-level partitioning and a 30-day expiration policy', 'insert_rows_bigquery': 'insert a list of rows into a BigQuery table using the insertAll API method'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/benchmarks/util/result_parser.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create a new BigQuery table with a given schema and description in a dataset', 'create a partitioned BigQuery table with day-level partitioning and a 30-day expiration policy', 'insert a list of rows into a BigQuery table using the insertAll API method', 'parse C++ benchmark JSON results and extract throughput per benchmark entry', 'parse Java JMH benchmark JSON results and compute weighted average throughput', 'parse Python benchmark JSON results and extract per-behavior throughput data', 'parse Go text benchmark output and extract per-operation throughput metrics', 'get aggregated benchmark results from multiple language result files at once', 'run the CLI to upload protobuf benchmark results from multiple language files to BigQuery', 'run get_metadata to collect CI build number, job name, and git commit from environment variables', 'run upload_result to insert a list of benchmark throughput results into a BigQuery table', 'review get_metadata to understand how CI environment variables are collected into a metadata dictionary', 'review upload_result to see how benchmark results are formatted and inserted into BigQuery with labels']
```

Usage

```
{'parse_cpp_benchmark_results': 'parse C++ benchmark JSON results and extract throughput per benchmark entry', 'parse_java_benchmark_results': 'parse Java JMH benchmark JSON results and compute weighted average throughput', 'parse_python_benchmark_results': 'parse Python benchmark JSON results and extract per-behavior throughput data', 'parse_go_benchmark_results': 'parse Go text benchmark output and extract per-operation throughput metrics', 'get_result_from_file': 'get aggregated benchmark results from multiple language result files at once'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/benchmarks/util/result_uploader.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create a new BigQuery table with a given schema and description in a dataset', 'create a partitioned BigQuery table with day-level partitioning and a 30-day expiration policy', 'insert a list of rows into a BigQuery table using the insertAll API method', 'parse C++ benchmark JSON results and extract throughput per benchmark entry', 'parse Java JMH benchmark JSON results and compute weighted average throughput', 'parse Python benchmark JSON results and extract per-behavior throughput data', 'parse Go text benchmark output and extract per-operation throughput metrics', 'get aggregated benchmark results from multiple language result files at once', 'run the CLI to upload protobuf benchmark results from multiple language files to BigQuery', 'run get_metadata to collect CI build number, job name, and git commit from environment variables', 'run upload_result to insert a list of benchmark throughput results into a BigQuery table', 'review get_metadata to understand how CI environment variables are collected into a metadata dictionary', 'review upload_result to see how benchmark results are formatted and inserted into BigQuery with labels']
```

Usage

```
{'run_upload_benchmark_results': 'run the CLI to upload protobuf benchmark results from multiple language files to BigQuery', 'run_get_metadata': 'run get_metadata to collect CI build number, job name, and git commit from environment variables', 'run_upload_result': 'run upload_result to insert a list of benchmark throughput results into a BigQuery table', 'review_get_metadata': 'review get_metadata to understand how CI environment variables are collected into a metadata dictionary', 'review_upload_result': 'review upload_result to see how benchmark results are formatted and inserted into BigQuery with labels'}
```

