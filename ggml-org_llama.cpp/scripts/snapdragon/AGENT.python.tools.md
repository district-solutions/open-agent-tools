# Agent Python Tools

- repo: ggml-org/llama.cpp
- repo_uri: https://github.com/ggml-org/llama.cpp

## File: ggml-org_llama.cpp/scripts/snapdragon/ggml-hexagon-profile.py

Prompts

```
['parse a hexagon op profile log file and extract operation metrics like usec, cycles, and pmu values', 'generate a formatted markdown report of top N grouped operations sorted by max usec or cycles', 'summarize hexagon Snapdragon profile data grouped by op name, dims, and dtypes with statistics', 'sort hexagon profile operations by PMU counter values using a specified PMU index', 'run the ggml-hexagon-profile CLI tool to post-process and display op profile info from a log file']
```

Usage

```
{'parse_log_profile': 'parse a hexagon op profile log file and extract operation metrics like usec, cycles, and pmu values', 'generate_profile_report': 'generate a formatted markdown report of top N grouped operations sorted by max usec or cycles', 'summarize_hexagon_profile': 'summarize hexagon Snapdragon profile data grouped by op name, dims, and dtypes with statistics', 'sort_profile_by_pmu': 'sort hexagon profile operations by PMU counter values using a specified PMU index', 'run_profile_report_cli': 'run the ggml-hexagon-profile CLI tool to post-process and display op profile info from a log file'}
```

