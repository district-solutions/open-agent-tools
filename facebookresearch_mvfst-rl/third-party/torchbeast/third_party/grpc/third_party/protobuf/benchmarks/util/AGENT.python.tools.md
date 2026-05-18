# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/benchmarks/util/big_query_utils.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create a partitioned BigQuery table with a 30-day expiration policy and DAY partition type', 'insert a list of row dictionaries into a BigQuery table using the insertAll API', 'execute a synchronous SQL query against BigQuery and return the query job result', 'parse a C++ benchmark JSON file and extract throughput data into the results list', 'parse a Java benchmark JSON file and compute weighted average throughput per measurement', 'parse a Python benchmark JSON file and extract per-behavior throughput results', 'parse a Go benchmark text file and extract per-operation throughput from ns/op values', 'aggregate benchmark results from multiple language files into a single unified results list', 'run the result uploader CLI to upload protobuf benchmark results for cpp, java, python, go, node, and php to BigQuery', 'run the result uploader with a cpp benchmark input file to upload throughput results to BigQuery', 'get CI/CD metadata from environment variables including build number, build url, job name, and git commit', 'upload a list of benchmark result dicts with throughput values to a BigQuery table partitioned by date', 'review the upload_result function that formats benchmark throughput data and inserts rows into BigQuery']
```

Usage

```
{'create_bigquery_service': 'create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create_dataset': 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create_partitioned_table': 'create a partitioned BigQuery table with a 30-day expiration policy and DAY partition type', 'insert_rows': 'insert a list of row dictionaries into a BigQuery table using the insertAll API', 'sync_query_job': 'execute a synchronous SQL query against BigQuery and return the query job result'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/benchmarks/util/result_parser.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create a partitioned BigQuery table with a 30-day expiration policy and DAY partition type', 'insert a list of row dictionaries into a BigQuery table using the insertAll API', 'execute a synchronous SQL query against BigQuery and return the query job result', 'parse a C++ benchmark JSON file and extract throughput data into the results list', 'parse a Java benchmark JSON file and compute weighted average throughput per measurement', 'parse a Python benchmark JSON file and extract per-behavior throughput results', 'parse a Go benchmark text file and extract per-operation throughput from ns/op values', 'aggregate benchmark results from multiple language files into a single unified results list', 'run the result uploader CLI to upload protobuf benchmark results for cpp, java, python, go, node, and php to BigQuery', 'run the result uploader with a cpp benchmark input file to upload throughput results to BigQuery', 'get CI/CD metadata from environment variables including build number, build url, job name, and git commit', 'upload a list of benchmark result dicts with throughput values to a BigQuery table partitioned by date', 'review the upload_result function that formats benchmark throughput data and inserts rows into BigQuery']
```

Usage

```
{'parse_cpp_benchmark_results': 'parse a C++ benchmark JSON file and extract throughput data into the results list', 'parse_java_benchmark_results': 'parse a Java benchmark JSON file and compute weighted average throughput per measurement', 'parse_python_benchmark_results': 'parse a Python benchmark JSON file and extract per-behavior throughput results', 'parse_go_benchmark_results': 'parse a Go benchmark text file and extract per-operation throughput from ns/op values', 'get_result_from_file': 'aggregate benchmark results from multiple language files into a single unified results list'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/benchmarks/util/result_uploader.py

Prompts

```
['create a BigQuery service object by authenticating with Google Cloud application default credentials', 'create a new BigQuery dataset in a specified project using the BigQuery service object', 'create a partitioned BigQuery table with a 30-day expiration policy and DAY partition type', 'insert a list of row dictionaries into a BigQuery table using the insertAll API', 'execute a synchronous SQL query against BigQuery and return the query job result', 'parse a C++ benchmark JSON file and extract throughput data into the results list', 'parse a Java benchmark JSON file and compute weighted average throughput per measurement', 'parse a Python benchmark JSON file and extract per-behavior throughput results', 'parse a Go benchmark text file and extract per-operation throughput from ns/op values', 'aggregate benchmark results from multiple language files into a single unified results list', 'run the result uploader CLI to upload protobuf benchmark results for cpp, java, python, go, node, and php to BigQuery', 'run the result uploader with a cpp benchmark input file to upload throughput results to BigQuery', 'get CI/CD metadata from environment variables including build number, build url, job name, and git commit', 'upload a list of benchmark result dicts with throughput values to a BigQuery table partitioned by date', 'review the upload_result function that formats benchmark throughput data and inserts rows into BigQuery']
```

Usage

```
{'run_benchmark_upload': 'run the result uploader CLI to upload protobuf benchmark results for cpp, java, python, go, node, and php to BigQuery', 'run_upload_with_cpp': 'run the result uploader with a cpp benchmark input file to upload throughput results to BigQuery', 'get_metadata': 'get CI/CD metadata from environment variables including build number, build url, job name, and git commit', 'upload_result': 'upload a list of benchmark result dicts with throughput values to a BigQuery table partitioned by date', 'review_upload_result': 'review the upload_result function that formats benchmark throughput data and inserts rows into BigQuery'}
```

