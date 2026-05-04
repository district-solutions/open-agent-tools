# Agent Python Tools

- repo: facebookresearch/dcperf
- repo_uri: https://github.com/facebookresearch/dcperf

## File: facebookresearch_dcperf/perfutils/generate_amd_perf_report.py

Prompts

```
['generate an AMD performance report as a formatted table from a perf CSV file for zen3/zen4/zen5/zen5es architectures', 'generate an AMD performance report as CSV output from a perf CSV file with aggregated statistics', 'generate derived time-series data as CSV from an AMD perf CSV file using the --series option', 'read an AMD perf CSV file with columns for timestamp, socket, counter_value, event_name, and counter_runtime into a pandas DataFrame', 'get the number of memory channels and DDR frequency by running dmidecode and parsing the output', 'run the ARM perf report CLI tool on a perf CSV file to generate a performance metrics summary table', 'run the ARM perf report CLI tool on a perf CSV file and output aggregated metrics as CSV format', 'run the ARM perf report CLI tool on a perf CSV file and write derived time-series data to a file', 'create a new metric derivation function decorated with skip_if_missing that computes a derived metric from grouped perf data', 'review the ARM perf metric derivation functions such as ipc, mips, flops, branch_mpki, and topdown metrics for correctness']
```

Usage

```
{'generate_amd_perf_report_table': 'generate an AMD performance report as a formatted table from a perf CSV file for zen3/zen4/zen5/zen5es architectures', 'generate_amd_perf_report_csv': 'generate an AMD performance report as CSV output from a perf CSV file with aggregated statistics', 'generate_amd_perf_report_timeseries': 'generate derived time-series data as CSV from an AMD perf CSV file using the --series option', 'read_amd_perf_csv': 'read an AMD perf CSV file with columns for timestamp, socket, counter_value, event_name, and counter_runtime into a pandas DataFrame', 'get_memory_info': 'get the number of memory channels and DDR frequency by running dmidecode and parsing the output'}
```

## File: facebookresearch_dcperf/perfutils/generate_arm_perf_report.py

Prompts

```
['generate an AMD performance report as a formatted table from a perf CSV file for zen3/zen4/zen5/zen5es architectures', 'generate an AMD performance report as CSV output from a perf CSV file with aggregated statistics', 'generate derived time-series data as CSV from an AMD perf CSV file using the --series option', 'read an AMD perf CSV file with columns for timestamp, socket, counter_value, event_name, and counter_runtime into a pandas DataFrame', 'get the number of memory channels and DDR frequency by running dmidecode and parsing the output', 'run the ARM perf report CLI tool on a perf CSV file to generate a performance metrics summary table', 'run the ARM perf report CLI tool on a perf CSV file and output aggregated metrics as CSV format', 'run the ARM perf report CLI tool on a perf CSV file and write derived time-series data to a file', 'create a new metric derivation function decorated with skip_if_missing that computes a derived metric from grouped perf data', 'review the ARM perf metric derivation functions such as ipc, mips, flops, branch_mpki, and topdown metrics for correctness']
```

Usage

```
{'run_arm_perf_report': 'run the ARM perf report CLI tool on a perf CSV file to generate a performance metrics summary table', 'run_arm_perf_report_csv': 'run the ARM perf report CLI tool on a perf CSV file and output aggregated metrics as CSV format', 'run_arm_perf_report_series': 'run the ARM perf report CLI tool on a perf CSV file and write derived time-series data to a file', 'create_metric_derivation': 'create a new metric derivation function decorated with skip_if_missing that computes a derived metric from grouped perf data', 'review_metric_functions': 'review the ARM perf metric derivation functions such as ipc, mips, flops, branch_mpki, and topdown metrics for correctness'}
```

