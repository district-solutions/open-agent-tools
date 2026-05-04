# Agent Python Tools

- repo: facebookresearch/dcperf
- repo_uri: https://github.com/facebookresearch/dcperf

## File: facebookresearch_dcperf/packages/spark_standalone/templates/proj_root/scripts/config_spark.py

Prompts

```
['initialize Spark standalone cluster configs with optional aggressive mode and IPv4 preference for a given platform', 'get the hardware info dict including cores, memory, arch, and sockets for a specified platform', 'get the Spark standalone CLI arguments dict for a specified platform including master URL and memory settings', 'get the full Spark standalone configuration dict for a specified platform including executor and JVM options', 'validate that a given platform string is one of the supported platforms before use', 'run a Spark SQL file with configurable CLI args, configs, and optional NUMA node binding', 'generate SQL statements to create Parquet tables from JSON dataset release metadata', 'parse a Spark execution log file to extract per-stage start and end timestamps', 'run benchmark test queries with cache dropping, timing, and per-stage runtime analysis', 'start a Spark standalone cluster with master, workers, and shuffle service with NUMA policies', 'run a shell command with custom environment variables and capture stdout or write to an output file', 'read system configuration including CPU cores, sockets, threads per core, and total memory in GB', 'find the JAVA_HOME path by checking common JDK install locations or resolving via the java command', 'read and validate environment variables PROJ_ROOT, JAVA_HOME, and SPARK_HOME with fallback defaults', 'check if the current OS distribution matches a given distro ID by parsing /etc/os-release']
```

Usage

```
{'init_spark_configs': 'initialize Spark standalone cluster configs with optional aggressive mode and IPv4 preference for a given platform', 'get_hardware_info': 'get the hardware info dict including cores, memory, arch, and sockets for a specified platform', 'get_standalone_cli_args': 'get the Spark standalone CLI arguments dict for a specified platform including master URL and memory settings', 'get_standalone_configs': 'get the full Spark standalone configuration dict for a specified platform including executor and JVM options', 'check_platform': 'validate that a given platform string is one of the supported platforms before use'}
```

## File: facebookresearch_dcperf/packages/spark_standalone/templates/proj_root/scripts/run_perf_common.py

Prompts

```
['initialize Spark standalone cluster configs with optional aggressive mode and IPv4 preference for a given platform', 'get the hardware info dict including cores, memory, arch, and sockets for a specified platform', 'get the Spark standalone CLI arguments dict for a specified platform including master URL and memory settings', 'get the full Spark standalone configuration dict for a specified platform including executor and JVM options', 'validate that a given platform string is one of the supported platforms before use', 'run a Spark SQL file with configurable CLI args, configs, and optional NUMA node binding', 'generate SQL statements to create Parquet tables from JSON dataset release metadata', 'parse a Spark execution log file to extract per-stage start and end timestamps', 'run benchmark test queries with cache dropping, timing, and per-stage runtime analysis', 'start a Spark standalone cluster with master, workers, and shuffle service with NUMA policies', 'run a shell command with custom environment variables and capture stdout or write to an output file', 'read system configuration including CPU cores, sockets, threads per core, and total memory in GB', 'find the JAVA_HOME path by checking common JDK install locations or resolving via the java command', 'read and validate environment variables PROJ_ROOT, JAVA_HOME, and SPARK_HOME with fallback defaults', 'check if the current OS distribution matches a given distro ID by parsing /etc/os-release']
```

Usage

```
{'run_spark_sql': 'run a Spark SQL file with configurable CLI args, configs, and optional NUMA node binding', 'write_sql_create_tables': 'generate SQL statements to create Parquet tables from JSON dataset release metadata', 'parse_per_stage_runtime': 'parse a Spark execution log file to extract per-stage start and end timestamps', 'run_benchmark_tests': 'run benchmark test queries with cache dropping, timing, and per-stage runtime analysis', 'start_spark_cluster': 'start a Spark standalone cluster with master, workers, and shuffle service with NUMA policies'}
```

## File: facebookresearch_dcperf/packages/spark_standalone/templates/proj_root/scripts/utils.py

Prompts

```
['initialize Spark standalone cluster configs with optional aggressive mode and IPv4 preference for a given platform', 'get the hardware info dict including cores, memory, arch, and sockets for a specified platform', 'get the Spark standalone CLI arguments dict for a specified platform including master URL and memory settings', 'get the full Spark standalone configuration dict for a specified platform including executor and JVM options', 'validate that a given platform string is one of the supported platforms before use', 'run a Spark SQL file with configurable CLI args, configs, and optional NUMA node binding', 'generate SQL statements to create Parquet tables from JSON dataset release metadata', 'parse a Spark execution log file to extract per-stage start and end timestamps', 'run benchmark test queries with cache dropping, timing, and per-stage runtime analysis', 'start a Spark standalone cluster with master, workers, and shuffle service with NUMA policies', 'run a shell command with custom environment variables and capture stdout or write to an output file', 'read system configuration including CPU cores, sockets, threads per core, and total memory in GB', 'find the JAVA_HOME path by checking common JDK install locations or resolving via the java command', 'read and validate environment variables PROJ_ROOT, JAVA_HOME, and SPARK_HOME with fallback defaults', 'check if the current OS distribution matches a given distro ID by parsing /etc/os-release']
```

Usage

```
{'run_cmd_with_env': 'run a shell command with custom environment variables and capture stdout or write to an output file', 'read_sys_configs': 'read system configuration including CPU cores, sockets, threads per core, and total memory in GB', 'find_java_home': 'find the JAVA_HOME path by checking common JDK install locations or resolving via the java command', 'read_environ': 'read and validate environment variables PROJ_ROOT, JAVA_HOME, and SPARK_HOME with fallback defaults', 'is_distro_like': 'check if the current OS distribution matches a given distro ID by parsing /etc/os-release'}
```

