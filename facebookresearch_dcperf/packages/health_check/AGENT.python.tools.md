# Agent Python Tools

- repo: facebookresearch/dcperf
- repo_uri: https://github.com/facebookresearch/dcperf

## File: facebookresearch_dcperf/packages/health_check/collect-cpu-util.py

Prompts

```
['run a subprocess command and measure its CPU utilization across user, sys, idle, and iowait categories', 'read /proc/stat and return a list of current CPU tick counts for all categories', 'calculate CPU utilization percentages for each category given start and end tick values', 'review the get_cpu_ticks function that parses /proc/stat to extract CPU tick data', 'refactor calc_cpu_util to support per-CPU core utilization instead of aggregate totals']
```

Usage

```
{'run_collect_cpu_util': 'run a subprocess command and measure its CPU utilization across user, sys, idle, and iowait categories', 'get_cpu_ticks': 'read /proc/stat and return a list of current CPU tick counts for all categories', 'calc_cpu_util': 'calculate CPU utilization percentages for each category given start and end tick values', 'review_get_cpu_ticks': 'review the get_cpu_ticks function that parses /proc/stat to extract CPU tick data', 'refactor_calc_cpu_util': 'refactor calc_cpu_util to support per-CPU core utilization instead of aggregate totals'}
```

