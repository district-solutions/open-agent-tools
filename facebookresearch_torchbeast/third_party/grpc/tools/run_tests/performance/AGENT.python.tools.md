# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/performance/massage_qps_stats.py

Prompts

```
['extract core counter stats from gRPC QPS scenario results into flat key-value pairs', 'extract core histogram stats with bucket boundaries and percentiles from gRPC QPS scenario results', 'extract HTTP/2 operation counters like op batches, pings sent, and writes begun from core stats', 'extract HPACK encoding counters for indexed, literal, and Huffman header compression from core stats', 'extract TCP read and write size histograms with 50th, 95th, and 99th percentile values from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from core stats metrics dictionary using the counter function', 'extract histogram buckets and boundaries from core stats metrics using the histogram function', 'compute the threshold value for a given count below using histogram buckets and boundaries', 'create a Histogram namedtuple with buckets and boundaries fields for storing histogram data', 'create a gRPC performance benchmark ping pong scenario with custom rpc_type, client_type, and server_type', 'generate C++ gRPC performance benchmark scenarios using the CXXLanguage class scenarios method', 'generate Python gRPC performance benchmark scenarios using the PythonLanguage class scenarios method', 'generate Java gRPC performance benchmark scenarios using the JavaLanguage class scenarios method', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'get JSON scenarios for a given language filtered by name regex and category', 'get all JSON scenarios for a language without filtering by category', 'get JSON scenarios matching a specific name pattern using regex', 'dump a list of JSON scenarios to individual files with a custom prefix', 'dump JSON scenarios to files using the default scenario_dump_ prefix']
```

Usage

```
{'massage_qps_stats_counters': 'extract core counter stats from gRPC QPS scenario results into flat key-value pairs', 'massage_qps_stats_histograms': 'extract core histogram stats with bucket boundaries and percentiles from gRPC QPS scenario results', 'massage_qps_stats_http2': 'extract HTTP/2 operation counters like op batches, pings sent, and writes begun from core stats', 'massage_qps_stats_hpack': 'extract HPACK encoding counters for indexed, literal, and Huffman header compression from core stats', 'massage_qps_stats_tcp': 'extract TCP read and write size histograms with 50th, 95th, and 99th percentile values from core stats'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/performance/massage_qps_stats_helpers.py

Prompts

```
['extract core counter stats from gRPC QPS scenario results into flat key-value pairs', 'extract core histogram stats with bucket boundaries and percentiles from gRPC QPS scenario results', 'extract HTTP/2 operation counters like op batches, pings sent, and writes begun from core stats', 'extract HPACK encoding counters for indexed, literal, and Huffman header compression from core stats', 'extract TCP read and write size histograms with 50th, 95th, and 99th percentile values from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from core stats metrics dictionary using the counter function', 'extract histogram buckets and boundaries from core stats metrics using the histogram function', 'compute the threshold value for a given count below using histogram buckets and boundaries', 'create a Histogram namedtuple with buckets and boundaries fields for storing histogram data', 'create a gRPC performance benchmark ping pong scenario with custom rpc_type, client_type, and server_type', 'generate C++ gRPC performance benchmark scenarios using the CXXLanguage class scenarios method', 'generate Python gRPC performance benchmark scenarios using the PythonLanguage class scenarios method', 'generate Java gRPC performance benchmark scenarios using the JavaLanguage class scenarios method', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'get JSON scenarios for a given language filtered by name regex and category', 'get all JSON scenarios for a language without filtering by category', 'get JSON scenarios matching a specific name pattern using regex', 'dump a list of JSON scenarios to individual files with a custom prefix', 'dump JSON scenarios to files using the default scenario_dump_ prefix']
```

Usage

```
{'calculate_percentile_from_histogram': 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract_counter_from_stats': 'extract a named counter value from core stats metrics dictionary using the counter function', 'extract_histogram_from_stats': 'extract histogram buckets and boundaries from core stats metrics using the histogram function', 'compute_threshold_for_count_below': 'compute the threshold value for a given count below using histogram buckets and boundaries', 'create_histogram_namedtuple': 'create a Histogram namedtuple with buckets and boundaries fields for storing histogram data'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/performance/scenario_config.py

Prompts

```
['extract core counter stats from gRPC QPS scenario results into flat key-value pairs', 'extract core histogram stats with bucket boundaries and percentiles from gRPC QPS scenario results', 'extract HTTP/2 operation counters like op batches, pings sent, and writes begun from core stats', 'extract HPACK encoding counters for indexed, literal, and Huffman header compression from core stats', 'extract TCP read and write size histograms with 50th, 95th, and 99th percentile values from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from core stats metrics dictionary using the counter function', 'extract histogram buckets and boundaries from core stats metrics using the histogram function', 'compute the threshold value for a given count below using histogram buckets and boundaries', 'create a Histogram namedtuple with buckets and boundaries fields for storing histogram data', 'create a gRPC performance benchmark ping pong scenario with custom rpc_type, client_type, and server_type', 'generate C++ gRPC performance benchmark scenarios using the CXXLanguage class scenarios method', 'generate Python gRPC performance benchmark scenarios using the PythonLanguage class scenarios method', 'generate Java gRPC performance benchmark scenarios using the JavaLanguage class scenarios method', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'get JSON scenarios for a given language filtered by name regex and category', 'get all JSON scenarios for a language without filtering by category', 'get JSON scenarios matching a specific name pattern using regex', 'dump a list of JSON scenarios to individual files with a custom prefix', 'dump JSON scenarios to files using the default scenario_dump_ prefix']
```

Usage

```
{'create_ping_pong_scenario': 'create a gRPC performance benchmark ping pong scenario with custom rpc_type, client_type, and server_type', 'generate_CXXLanguage_scenarios': 'generate C++ gRPC performance benchmark scenarios using the CXXLanguage class scenarios method', 'generate_PythonLanguage_scenarios': 'generate Python gRPC performance benchmark scenarios using the PythonLanguage class scenarios method', 'generate_JavaLanguage_scenarios': 'generate Java gRPC performance benchmark scenarios using the JavaLanguage class scenarios method', 'remove_nonproto_fields': 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/performance/scenario_config_exporter.py

Prompts

```
['extract core counter stats from gRPC QPS scenario results into flat key-value pairs', 'extract core histogram stats with bucket boundaries and percentiles from gRPC QPS scenario results', 'extract HTTP/2 operation counters like op batches, pings sent, and writes begun from core stats', 'extract HPACK encoding counters for indexed, literal, and Huffman header compression from core stats', 'extract TCP read and write size histograms with 50th, 95th, and 99th percentile values from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from core stats metrics dictionary using the counter function', 'extract histogram buckets and boundaries from core stats metrics using the histogram function', 'compute the threshold value for a given count below using histogram buckets and boundaries', 'create a Histogram namedtuple with buckets and boundaries fields for storing histogram data', 'create a gRPC performance benchmark ping pong scenario with custom rpc_type, client_type, and server_type', 'generate C++ gRPC performance benchmark scenarios using the CXXLanguage class scenarios method', 'generate Python gRPC performance benchmark scenarios using the PythonLanguage class scenarios method', 'generate Java gRPC performance benchmark scenarios using the JavaLanguage class scenarios method', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'get JSON scenarios for a given language filtered by name regex and category', 'get all JSON scenarios for a language without filtering by category', 'get JSON scenarios matching a specific name pattern using regex', 'dump a list of JSON scenarios to individual files with a custom prefix', 'dump JSON scenarios to files using the default scenario_dump_ prefix']
```

Usage

```
{'get_json_scenarios_by_language': 'get JSON scenarios for a given language filtered by name regex and category', 'get_json_scenarios_all_categories': 'get all JSON scenarios for a language without filtering by category', 'get_json_scenarios_regex_filter': 'get JSON scenarios matching a specific name pattern using regex', 'dump_to_json_files': 'dump a list of JSON scenarios to individual files with a custom prefix', 'dump_to_json_files_default_prefix': 'dump JSON scenarios to files using the default scenario_dump_ prefix'}
```

