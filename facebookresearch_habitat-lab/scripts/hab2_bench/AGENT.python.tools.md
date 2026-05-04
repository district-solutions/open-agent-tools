# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/scripts/hab2_bench/assert_bench.py

Prompts

```
['run the benchmark regression check script to detect SPS performance regressions in habitat-lab', 'check benchmark steps per second by reading FPS from profile files and comparing against minimum thresholds', 'raise a RegressionError when benchmark performance falls below the expected minimum SPS values', 'review the MINIMUM_PERFORMANCE_1_PROCESS and MINIMUM_PERFORMANCE_16_PROCESS maps to understand benchmark thresholds', 'refactor check_benchmark_sps to support additional benchmark settings or multi-process validation', 'run the habitat simulator benchmark measuring FPS across multiple processes and GPUs', 'create a habitat environment with GPU device assignment from config and options', 'benchmark the HabDemoRunner class to measure step timing and FPS performance', 'initialize the HabDemoRunner with CPU affinity, environment, and action sampling setup', 'execute timed environment steps and optionally render video output for profiling', 'run the plot function to generate a horizontal bar chart of FPS benchmark results from profile data files', 'build a horizontal bar chart with error bars from FPS profile data files and save as PDF', 'create a benchmark plot that reads FPS values from text files and computes mean and standard error', 'refactor the plot function to support custom error bar scaling factors or alternative output formats', 'review the plot function that parses FPS from profile text files and generates matplotlib bar charts']
```

Usage

```
{'run_benchmark_regression_check': 'run the benchmark regression check script to detect SPS performance regressions in habitat-lab', 'check_benchmark_sps_function': 'check benchmark steps per second by reading FPS from profile files and comparing against minimum thresholds', 'use_regression_error': 'raise a RegressionError when benchmark performance falls below the expected minimum SPS values', 'review_minimum_performance_maps': 'review the MINIMUM_PERFORMANCE_1_PROCESS and MINIMUM_PERFORMANCE_16_PROCESS maps to understand benchmark thresholds', 'refactor_check_benchmark_sps': 'refactor check_benchmark_sps to support additional benchmark settings or multi-process validation'}
```

## File: facebookresearch_habitat-lab/scripts/hab2_bench/hab2_benchmark.py

Prompts

```
['run the benchmark regression check script to detect SPS performance regressions in habitat-lab', 'check benchmark steps per second by reading FPS from profile files and comparing against minimum thresholds', 'raise a RegressionError when benchmark performance falls below the expected minimum SPS values', 'review the MINIMUM_PERFORMANCE_1_PROCESS and MINIMUM_PERFORMANCE_16_PROCESS maps to understand benchmark thresholds', 'refactor check_benchmark_sps to support additional benchmark settings or multi-process validation', 'run the habitat simulator benchmark measuring FPS across multiple processes and GPUs', 'create a habitat environment with GPU device assignment from config and options', 'benchmark the HabDemoRunner class to measure step timing and FPS performance', 'initialize the HabDemoRunner with CPU affinity, environment, and action sampling setup', 'execute timed environment steps and optionally render video output for profiling', 'run the plot function to generate a horizontal bar chart of FPS benchmark results from profile data files', 'build a horizontal bar chart with error bars from FPS profile data files and save as PDF', 'create a benchmark plot that reads FPS values from text files and computes mean and standard error', 'refactor the plot function to support custom error bar scaling factors or alternative output formats', 'review the plot function that parses FPS from profile text files and generates matplotlib bar charts']
```

Usage

```
{'run_hab2_benchmark': 'run the habitat simulator benchmark measuring FPS across multiple processes and GPUs', 'create_env_habitat': 'create a habitat environment with GPU device assignment from config and options', 'benchmark_HabDemoRunner': 'benchmark the HabDemoRunner class to measure step timing and FPS performance', 'init_common_HabDemoRunner': 'initialize the HabDemoRunner with CPU affinity, environment, and action sampling setup', 'do_time_steps_HabDemoRunner': 'execute timed environment steps and optionally render video output for profiling'}
```

## File: facebookresearch_habitat-lab/scripts/hab2_bench/plot_bench.py

Prompts

```
['run the benchmark regression check script to detect SPS performance regressions in habitat-lab', 'check benchmark steps per second by reading FPS from profile files and comparing against minimum thresholds', 'raise a RegressionError when benchmark performance falls below the expected minimum SPS values', 'review the MINIMUM_PERFORMANCE_1_PROCESS and MINIMUM_PERFORMANCE_16_PROCESS maps to understand benchmark thresholds', 'refactor check_benchmark_sps to support additional benchmark settings or multi-process validation', 'run the habitat simulator benchmark measuring FPS across multiple processes and GPUs', 'create a habitat environment with GPU device assignment from config and options', 'benchmark the HabDemoRunner class to measure step timing and FPS performance', 'initialize the HabDemoRunner with CPU affinity, environment, and action sampling setup', 'execute timed environment steps and optionally render video output for profiling', 'run the plot function to generate a horizontal bar chart of FPS benchmark results from profile data files', 'build a horizontal bar chart with error bars from FPS profile data files and save as PDF', 'create a benchmark plot that reads FPS values from text files and computes mean and standard error', 'refactor the plot function to support custom error bar scaling factors or alternative output formats', 'review the plot function that parses FPS from profile text files and generates matplotlib bar charts']
```

Usage

```
{'run_plot_benchmark': 'run the plot function to generate a horizontal bar chart of FPS benchmark results from profile data files', 'build_bench_chart': 'build a horizontal bar chart with error bars from FPS profile data files and save as PDF', 'create_profile_plot': 'create a benchmark plot that reads FPS values from text files and computes mean and standard error', 'refactor_plot_function': 'refactor the plot function to support custom error bar scaling factors or alternative output formats', 'review_plot_bench': 'review the plot function that parses FPS from profile text files and generates matplotlib bar charts'}
```

