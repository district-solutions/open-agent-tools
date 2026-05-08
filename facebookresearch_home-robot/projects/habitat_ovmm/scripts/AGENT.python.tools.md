# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/habitat_ovmm/scripts/gen_configs.py

Prompts

```
['run the script to generate all baseline config variants from a base YAML config file', 'run the script with a custom base config path and save folder for generated configs', 'build YAML config variants combining heuristic and RL navigation, manipulation, and perception modes', 'create agent skill configs that toggle navigation, gaze, pick, and place skills for each variant', 'generate config variants that enable or disable visualization and oracle pick skills', 'run the summarize_metrics script with --folder_name and --exp_name args to compute episode metric summaries', 'read a single episode_results.json file and return the metrics as a pandas DataFrame', 'collect episode metrics from multiple JSON files in subfolders and concatenate them into one DataFrame', 'compute summary statistics across experiments and save results to a CSV file in the results folder', 'review the get_summary function that aggregates episode metrics and generates a sorted summary DataFrame']
```

Usage

```
{'run_gen_all_configs': 'run the script to generate all baseline config variants from a base YAML config file', 'run_gen_configs_with_args': 'run the script with a custom base config path and save folder for generated configs', 'build_config_variants': 'build YAML config variants combining heuristic and RL navigation, manipulation, and perception modes', 'create_agent_config': 'create agent skill configs that toggle navigation, gaze, pick, and place skills for each variant', 'generate_viz_configs': 'generate config variants that enable or disable visualization and oracle pick skills'}
```

## File: facebookresearch_home-robot/projects/habitat_ovmm/scripts/summarize_metrics.py

Prompts

```
['run the script to generate all baseline config variants from a base YAML config file', 'run the script with a custom base config path and save folder for generated configs', 'build YAML config variants combining heuristic and RL navigation, manipulation, and perception modes', 'create agent skill configs that toggle navigation, gaze, pick, and place skills for each variant', 'generate config variants that enable or disable visualization and oracle pick skills', 'run the summarize_metrics script with --folder_name and --exp_name args to compute episode metric summaries', 'read a single episode_results.json file and return the metrics as a pandas DataFrame', 'collect episode metrics from multiple JSON files in subfolders and concatenate them into one DataFrame', 'compute summary statistics across experiments and save results to a CSV file in the results folder', 'review the get_summary function that aggregates episode metrics and generates a sorted summary DataFrame']
```

Usage

```
{'run_summarize_metrics_cli': 'run the summarize_metrics script with --folder_name and --exp_name args to compute episode metric summaries', 'read_single_json_to_dataframe': 'read a single episode_results.json file and return the metrics as a pandas DataFrame', 'get_metrics_from_jsons': 'collect episode metrics from multiple JSON files in subfolders and concatenate them into one DataFrame', 'get_summary_stats': 'compute summary statistics across experiments and save results to a CSV file in the results folder', 'review_get_summary': 'review the get_summary function that aggregates episode metrics and generates a sorted summary DataFrame'}
```

