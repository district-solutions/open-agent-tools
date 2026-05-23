# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/plots/analysis.py

Prompts

```
['load metrics from multiple JSONL files matching a glob pattern into a single merged pandas DataFrame', 'load a single JSONL metrics file and its config.yaml into a normalized pandas DataFrame', 'execute a function across a list of files in parallel using multiprocessing with configurable workers', 'read a JSONL file line by line and return a list of parsed JSON objects', 'execute a function in parallel across all files matching a glob pattern with recursive search', 'run probe_animation.py with probe folder paths to generate animated HTML plots of model activations across layers', 'run plot_depth_distr_time to create animated depth distribution plots for transformer layer probe data over training steps', 'run get_mean_quantiles to extract mean and quantile arrays for specified layer names from probe data', "run Plotter class to initialize an animated plotter for a single run's layer data with quantile fill regions", 'run _render_to_file to generate HTML animation files for attention, residual, or linear layer probe distributions']
```

Usage

```
{'get_merged_df': 'load metrics from multiple JSONL files matching a glob pattern into a single merged pandas DataFrame', 'get_metrics': 'load a single JSONL metrics file and its config.yaml into a normalized pandas DataFrame', 'parallel': 'execute a function across a list of files in parallel using multiprocessing with configurable workers', 'load_raw_jsonl': 'read a JSONL file line by line and return a list of parsed JSON objects', 'parallel_from_glob': 'execute a function in parallel across all files matching a glob pattern with recursive search'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/plots/probe_animation.py

Prompts

```
['load metrics from multiple JSONL files matching a glob pattern into a single merged pandas DataFrame', 'load a single JSONL metrics file and its config.yaml into a normalized pandas DataFrame', 'execute a function across a list of files in parallel using multiprocessing with configurable workers', 'read a JSONL file line by line and return a list of parsed JSON objects', 'execute a function in parallel across all files matching a glob pattern with recursive search', 'run probe_animation.py with probe folder paths to generate animated HTML plots of model activations across layers', 'run plot_depth_distr_time to create animated depth distribution plots for transformer layer probe data over training steps', 'run get_mean_quantiles to extract mean and quantile arrays for specified layer names from probe data', "run Plotter class to initialize an animated plotter for a single run's layer data with quantile fill regions", 'run _render_to_file to generate HTML animation files for attention, residual, or linear layer probe distributions']
```

Usage

```
{'run_probe_animation_cli': 'run probe_animation.py with probe folder paths to generate animated HTML plots of model activations across layers', 'run_plot_depth_distr_time': 'run plot_depth_distr_time to create animated depth distribution plots for transformer layer probe data over training steps', 'run_get_mean_quantiles': 'run get_mean_quantiles to extract mean and quantile arrays for specified layer names from probe data', 'run_Plotter_class': "run Plotter class to initialize an animated plotter for a single run's layer data with quantile fill regions", 'run_render_to_file': 'run _render_to_file to generate HTML animation files for attention, residual, or linear layer probe distributions'}
```

