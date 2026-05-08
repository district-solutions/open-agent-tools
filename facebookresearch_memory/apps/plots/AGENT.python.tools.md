# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/plots/analysis.py

Prompts

```
['run a function in parallel across a list of files using multiprocessing Pool', 'run a function in parallel across files matching a glob pattern with recursive search', 'load a JSONL file line by line into a list of JSON objects with error handling', 'load metrics from a JSONL file and merge with config.yaml params into a normalized DataFrame', 'merge metrics DataFrames from multiple JSONL files matching a glob pattern into a single DataFrame', 'run probe_animation.py with probe folder paths to generate animated HTML plots of activation distributions across transformer layers over training steps', 'run plot_depth_distr_time to create an animated subplot grid showing mean and quantile distributions of layer activations across model depth over time', 'run get_mean_quantiles to extract mean values and quantile arrays for specified layer names from a probe data dictionary', "run the Plotter class to initialize an animated matplotlib plot for a single run's layer activation means and quantile fills across timesteps", 'run _render_to_file to render animated HTML plots for a given linear layer template including input, weight, output, and gradient distributions']
```

Usage

```
{'run_parallel_map': 'run a function in parallel across a list of files using multiprocessing Pool', 'run_parallel_from_glob': 'run a function in parallel across files matching a glob pattern with recursive search', 'load_raw_jsonl': 'load a JSONL file line by line into a list of JSON objects with error handling', 'get_metrics': 'load metrics from a JSONL file and merge with config.yaml params into a normalized DataFrame', 'get_merged_df': 'merge metrics DataFrames from multiple JSONL files matching a glob pattern into a single DataFrame'}
```

## File: facebookresearch_memory/apps/plots/probe_animation.py

Prompts

```
['run a function in parallel across a list of files using multiprocessing Pool', 'run a function in parallel across files matching a glob pattern with recursive search', 'load a JSONL file line by line into a list of JSON objects with error handling', 'load metrics from a JSONL file and merge with config.yaml params into a normalized DataFrame', 'merge metrics DataFrames from multiple JSONL files matching a glob pattern into a single DataFrame', 'run probe_animation.py with probe folder paths to generate animated HTML plots of activation distributions across transformer layers over training steps', 'run plot_depth_distr_time to create an animated subplot grid showing mean and quantile distributions of layer activations across model depth over time', 'run get_mean_quantiles to extract mean values and quantile arrays for specified layer names from a probe data dictionary', "run the Plotter class to initialize an animated matplotlib plot for a single run's layer activation means and quantile fills across timesteps", 'run _render_to_file to render animated HTML plots for a given linear layer template including input, weight, output, and gradient distributions']
```

Usage

```
{'run_probe_animation_cli': 'run probe_animation.py with probe folder paths to generate animated HTML plots of activation distributions across transformer layers over training steps', 'run_plot_depth_distr_time': 'run plot_depth_distr_time to create an animated subplot grid showing mean and quantile distributions of layer activations across model depth over time', 'run_get_mean_quantiles': 'run get_mean_quantiles to extract mean values and quantile arrays for specified layer names from a probe data dictionary', 'run_Plotter_class': "run the Plotter class to initialize an animated matplotlib plot for a single run's layer activation means and quantile fills across timesteps", 'run_render_to_file': 'run _render_to_file to render animated HTML plots for a given linear layer template including input, weight, output, and gradient distributions'}
```

