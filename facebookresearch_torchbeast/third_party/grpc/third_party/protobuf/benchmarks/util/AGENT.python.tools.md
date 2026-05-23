# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/benchmarks/util/big_query_utils.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud Platform application default credentials', 'create a new BigQuery dataset in a specified project with the given dataset ID', 'create a partitioned BigQuery table with day-level time partitioning and a 30 day expiration policy', 'insert multiple rows into a BigQuery table using the insertAll API with retry logic', 'execute a synchronous SQL query against BigQuery and return the query job result', 'parse a C++ benchmark JSON file and extract throughput per benchmark entry', 'parse a Java benchmark JSON file and compute weighted average throughput', 'parse a Go benchmark text output file and extract per-operation throughput', 'parse a Python benchmark JSON file and extract throughput for each behavior', 'aggregate benchmark results from multiple language files into a unified list', 'run the result uploader CLI to parse benchmark files and upload results to BigQuery', 'get CI/CD metadata from environment variables including build number, URL, job name, and git commit', 'upload a list of benchmark throughput results to a BigQuery table partitioned by date', 'parse benchmark result files for C++, Java, Python, Go, Node.js, and PHP languages', 'review the upload_result function to understand how benchmark results are formatted and inserted into BigQuery']
```

Usage

```
{'create_big_query_service': 'create a BigQuery service object by authenticating with Google Cloud Platform application default credentials', 'create_dataset': 'create a new BigQuery dataset in a specified project with the given dataset ID', 'create_partitioned_table': 'create a partitioned BigQuery table with day-level time partitioning and a 30 day expiration policy', 'insert_rows': 'insert multiple rows into a BigQuery table using the insertAll API with retry logic', 'sync_query_job': 'execute a synchronous SQL query against BigQuery and return the query job result'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/benchmarks/util/result_parser.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud Platform application default credentials', 'create a new BigQuery dataset in a specified project with the given dataset ID', 'create a partitioned BigQuery table with day-level time partitioning and a 30 day expiration policy', 'insert multiple rows into a BigQuery table using the insertAll API with retry logic', 'execute a synchronous SQL query against BigQuery and return the query job result', 'parse a C++ benchmark JSON file and extract throughput per benchmark entry', 'parse a Java benchmark JSON file and compute weighted average throughput', 'parse a Go benchmark text output file and extract per-operation throughput', 'parse a Python benchmark JSON file and extract throughput for each behavior', 'aggregate benchmark results from multiple language files into a unified list', 'run the result uploader CLI to parse benchmark files and upload results to BigQuery', 'get CI/CD metadata from environment variables including build number, URL, job name, and git commit', 'upload a list of benchmark throughput results to a BigQuery table partitioned by date', 'parse benchmark result files for C++, Java, Python, Go, Node.js, and PHP languages', 'review the upload_result function to understand how benchmark results are formatted and inserted into BigQuery']
```

Usage

```
{'parse_cpp_benchmark_result': 'parse a C++ benchmark JSON file and extract throughput per benchmark entry', 'parse_java_benchmark_result': 'parse a Java benchmark JSON file and compute weighted average throughput', 'parse_go_benchmark_result': 'parse a Go benchmark text output file and extract per-operation throughput', 'parse_python_benchmark_result': 'parse a Python benchmark JSON file and extract throughput for each behavior', 'get_result_from_file': 'aggregate benchmark results from multiple language files into a unified list'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/benchmarks/util/result_uploader.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud Platform application default credentials', 'create a new BigQuery dataset in a specified project with the given dataset ID', 'create a partitioned BigQuery table with day-level time partitioning and a 30 day expiration policy', 'insert multiple rows into a BigQuery table using the insertAll API with retry logic', 'execute a synchronous SQL query against BigQuery and return the query job result', 'parse a C++ benchmark JSON file and extract throughput per benchmark entry', 'parse a Java benchmark JSON file and compute weighted average throughput', 'parse a Go benchmark text output file and extract per-operation throughput', 'parse a Python benchmark JSON file and extract throughput for each behavior', 'aggregate benchmark results from multiple language files into a unified list', 'run the result uploader CLI to parse benchmark files and upload results to BigQuery', 'get CI/CD metadata from environment variables including build number, URL, job name, and git commit', 'upload a list of benchmark throughput results to a BigQuery table partitioned by date', 'parse benchmark result files for C++, Java, Python, Go, Node.js, and PHP languages', 'review the upload_result function to understand how benchmark results are formatted and inserted into BigQuery']
```

Usage

```
{'run_result_uploader_cli': 'run the result uploader CLI to parse benchmark files and upload results to BigQuery', 'get_metadata': 'get CI/CD metadata from environment variables including build number, URL, job name, and git commit', 'upload_result': 'upload a list of benchmark throughput results to a BigQuery table partitioned by date', 'parse_benchmark_files': 'parse benchmark result files for C++, Java, Python, Go, Node.js, and PHP languages', 'review_upload_result': 'review the upload_result function to understand how benchmark results are formatted and inserted into BigQuery'}
```

