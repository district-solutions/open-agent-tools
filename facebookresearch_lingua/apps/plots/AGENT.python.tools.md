# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/plots/analysis.py

Prompts

```
['load a JSONL file line by line and return a list of parsed JSON objects', 'load metrics from a JSONL file and merge with config.yaml params into a normalized DataFrame', 'parallel load metrics from multiple JSONL files matching a glob pattern and concatenate into one DataFrame', 'run a function across a list of files in parallel using multiprocessing and flatten results', 'run a function across files matching a glob pattern in parallel using multiprocessing', 'run probe_animation.py with probe folder paths to generate animated HTML plots of model layer statistics over training steps', 'create a Plotter instance to animate mean and quantile distributions across transformer layers for a given run', 'build an animated subplot grid showing layer-wise mean and quantile distributions over training timesteps saved as JSHTML', 'render animated attention distribution plots including attn_logits, attn_entropy, and wq/wk/wv outputs across all layers', 'render animated residual distribution plots showing feed_forward and attention output activations and gradients across all layers']
```

Usage

```
{'load_raw_jsonl': 'load a JSONL file line by line and return a list of parsed JSON objects', 'get_metrics': 'load metrics from a JSONL file and merge with config.yaml params into a normalized DataFrame', 'get_merged_df': 'parallel load metrics from multiple JSONL files matching a glob pattern and concatenate into one DataFrame', 'parallel': 'run a function across a list of files in parallel using multiprocessing and flatten results', 'parallel_from_glob': 'run a function across files matching a glob pattern in parallel using multiprocessing'}
```

## File: facebookresearch_lingua/apps/plots/probe_animation.py

Prompts

```
['load a JSONL file line by line and return a list of parsed JSON objects', 'load metrics from a JSONL file and merge with config.yaml params into a normalized DataFrame', 'parallel load metrics from multiple JSONL files matching a glob pattern and concatenate into one DataFrame', 'run a function across a list of files in parallel using multiprocessing and flatten results', 'run a function across files matching a glob pattern in parallel using multiprocessing', 'run probe_animation.py with probe folder paths to generate animated HTML plots of model layer statistics over training steps', 'create a Plotter instance to animate mean and quantile distributions across transformer layers for a given run', 'build an animated subplot grid showing layer-wise mean and quantile distributions over training timesteps saved as JSHTML', 'render animated attention distribution plots including attn_logits, attn_entropy, and wq/wk/wv outputs across all layers', 'render animated residual distribution plots showing feed_forward and attention output activations and gradients across all layers']
```

Usage

```
{'run_probe_animation': 'run probe_animation.py with probe folder paths to generate animated HTML plots of model layer statistics over training steps', 'create_plotter': 'create a Plotter instance to animate mean and quantile distributions across transformer layers for a given run', 'plot_depth_distr_time': 'build an animated subplot grid showing layer-wise mean and quantile distributions over training timesteps saved as JSHTML', 'render_attention_plots': 'render animated attention distribution plots including attn_logits, attn_entropy, and wq/wk/wv outputs across all layers', 'render_residual_plots': 'render animated residual distribution plots showing feed_forward and attention output activations and gradients across all layers'}
```

