# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/performance/massage_qps_stats.py

Prompts

```
['extract core stats counters from gRPC QPS scenario results into flat BigQuery-compatible fields', 'extract histogram data from gRPC core stats and compute 50th, 95th, and 99th percentile values', 'extract HTTP/2 operation counters like send message, recv message, and settings writes from core stats', 'extract syscall counters including poll, wait, epoll_ctl, read, and write from gRPC core stats', 'extract HPACK compression counters for indexed, literal, and Huffman-encoded headers from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from gRPC core stats metrics dictionary', 'extract histogram buckets and boundaries from gRPC core stats metrics by name', 'compute the threshold value for a given cumulative count across histogram buckets', 'create a Histogram namedtuple with buckets and boundaries for gRPC performance stats', 'create a ping pong benchmark scenario with custom rpc type, client type, and server type', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'generate a geometric progression of integers from a start value to a stop value', 'build a payload config dict with bytebuf or simple params for request and response sizes', 'iterate over benchmark scenarios for a language class like CXXLanguage or JavaLanguage']
```

Usage

```
{'massage_qps_stats_counters': 'extract core stats counters from gRPC QPS scenario results into flat BigQuery-compatible fields', 'massage_qps_stats_histograms': 'extract histogram data from gRPC core stats and compute 50th, 95th, and 99th percentile values', 'massage_qps_stats_http2_ops': 'extract HTTP/2 operation counters like send message, recv message, and settings writes from core stats', 'massage_qps_stats_syscalls': 'extract syscall counters including poll, wait, epoll_ctl, read, and write from gRPC core stats', 'massage_qps_stats_hpack': 'extract HPACK compression counters for indexed, literal, and Huffman-encoded headers from core stats'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/performance/massage_qps_stats_helpers.py

Prompts

```
['extract core stats counters from gRPC QPS scenario results into flat BigQuery-compatible fields', 'extract histogram data from gRPC core stats and compute 50th, 95th, and 99th percentile values', 'extract HTTP/2 operation counters like send message, recv message, and settings writes from core stats', 'extract syscall counters including poll, wait, epoll_ctl, read, and write from gRPC core stats', 'extract HPACK compression counters for indexed, literal, and Huffman-encoded headers from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from gRPC core stats metrics dictionary', 'extract histogram buckets and boundaries from gRPC core stats metrics by name', 'compute the threshold value for a given cumulative count across histogram buckets', 'create a Histogram namedtuple with buckets and boundaries for gRPC performance stats', 'create a ping pong benchmark scenario with custom rpc type, client type, and server type', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'generate a geometric progression of integers from a start value to a stop value', 'build a payload config dict with bytebuf or simple params for request and response sizes', 'iterate over benchmark scenarios for a language class like CXXLanguage or JavaLanguage']
```

Usage

```
{'calculate_percentile_from_histogram': 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract_counter_from_stats': 'extract a named counter value from gRPC core stats metrics dictionary', 'extract_histogram_from_stats': 'extract histogram buckets and boundaries from gRPC core stats metrics by name', 'compute_threshold_for_count_below': 'compute the threshold value for a given cumulative count across histogram buckets', 'create_histogram_namedtuple': 'create a Histogram namedtuple with buckets and boundaries for gRPC performance stats'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/performance/scenario_config.py

Prompts

```
['extract core stats counters from gRPC QPS scenario results into flat BigQuery-compatible fields', 'extract histogram data from gRPC core stats and compute 50th, 95th, and 99th percentile values', 'extract HTTP/2 operation counters like send message, recv message, and settings writes from core stats', 'extract syscall counters including poll, wait, epoll_ctl, read, and write from gRPC core stats', 'extract HPACK compression counters for indexed, literal, and Huffman-encoded headers from core stats', 'calculate a percentile value from histogram buckets and boundaries using the percentile function', 'extract a named counter value from gRPC core stats metrics dictionary', 'extract histogram buckets and boundaries from gRPC core stats metrics by name', 'compute the threshold value for a given cumulative count across histogram buckets', 'create a Histogram namedtuple with buckets and boundaries for gRPC performance stats', 'create a ping pong benchmark scenario with custom rpc type, client type, and server type', 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'generate a geometric progression of integers from a start value to a stop value', 'build a payload config dict with bytebuf or simple params for request and response sizes', 'iterate over benchmark scenarios for a language class like CXXLanguage or JavaLanguage']
```

Usage

```
{'create_ping_pong_scenario': 'create a ping pong benchmark scenario with custom rpc type, client type, and server type', 'remove_nonproto_fields': 'remove non-protobuf fields like CATEGORIES and CLIENT_LANGUAGE from a scenario config dict', 'generate_geometric_progression': 'generate a geometric progression of integers from a start value to a stop value', 'build_payload_config': 'build a payload config dict with bytebuf or simple params for request and response sizes', 'iterate_language_scenarios': 'iterate over benchmark scenarios for a language class like CXXLanguage or JavaLanguage'}
```

