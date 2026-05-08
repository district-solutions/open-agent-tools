# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/3p-integrations/crusoe/vllm-fp8/plot.py

Prompts

```
['run the plot script to generate TPOT and TTFT vs QPS charts from JSON files in the current directory', 'extract the QPS and model name from a JSON filename using the expected naming pattern', 'read all JSON files in a directory and return TPOT and TTFT metrics grouped by model', 'create an errorbar chart showing median TPOT vs QPS with standard deviation shading for each model', 'create an errorbar chart showing median TTFT vs QPS with standard deviation shading for each model']
```

Usage

```
{'run_plot_main': 'run the plot script to generate TPOT and TTFT vs QPS charts from JSON files in the current directory', 'extract_info_from_filename': 'extract the QPS and model name from a JSON filename using the expected naming pattern', 'read_json_files': 'read all JSON files in a directory and return TPOT and TTFT metrics grouped by model', 'create_chart_tpot': 'create an errorbar chart showing median TPOT vs QPS with standard deviation shading for each model', 'create_chart_ttft': 'create an errorbar chart showing median TTFT vs QPS with standard deviation shading for each model'}
```

