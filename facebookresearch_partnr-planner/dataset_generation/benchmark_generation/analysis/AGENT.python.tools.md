# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/dataset_generation/benchmark_generation/analysis/run_dataset_analysis.py

Prompts

```
['run the dataset analysis script to generate plots for propositions, predicates, objects, and task types from a .json.gz dataset', 'analyze a PARTNER dataset and metadata to produce distribution plots for objects, furniture, rooms, and predicates', 'load a gzip-compressed JSON dataset file and return it as a Python dictionary', 'load object and receptacle class metadata from CSV annotation files into a hash-to-category mapping', 'create a bar chart from a key-value dictionary and save it as a PNG image file', 'run the script with --dataset-path and --save-dir to generate UpSet plot figures for a dataset', 'generate UpSet top and side bar chart figures from a gzipped JSON dataset file', 'load episodes from a dataset and compute task type combination percentages for UpSet analysis', 'generate a vertical bar chart showing episode percentage for each task type combination', 'generate a horizontal bar chart showing total episode percentage per individual task type']
```

Usage

```
{'run_dataset_analysis': 'run the dataset analysis script to generate plots for propositions, predicates, objects, and task types from a .json.gz dataset', 'analyze_dataset': 'analyze a PARTNER dataset and metadata to produce distribution plots for objects, furniture, rooms, and predicates', 'load_dataset': 'load a gzip-compressed JSON dataset file and return it as a Python dictionary', 'load_metadata': 'load object and receptacle class metadata from CSV annotation files into a hash-to-category mapping', 'plot_bar': 'create a bar chart from a key-value dictionary and save it as a PNG image file'}
```

## File: facebookresearch_partnr-planner/dataset_generation/benchmark_generation/analysis/task_type_upset_plot.py

Prompts

```
['run the dataset analysis script to generate plots for propositions, predicates, objects, and task types from a .json.gz dataset', 'analyze a PARTNER dataset and metadata to produce distribution plots for objects, furniture, rooms, and predicates', 'load a gzip-compressed JSON dataset file and return it as a Python dictionary', 'load object and receptacle class metadata from CSV annotation files into a hash-to-category mapping', 'create a bar chart from a key-value dictionary and save it as a PNG image file', 'run the script with --dataset-path and --save-dir to generate UpSet plot figures for a dataset', 'generate UpSet top and side bar chart figures from a gzipped JSON dataset file', 'load episodes from a dataset and compute task type combination percentages for UpSet analysis', 'generate a vertical bar chart showing episode percentage for each task type combination', 'generate a horizontal bar chart showing total episode percentage per individual task type']
```

Usage

```
{'run_upset_plot_cli': 'run the script with --dataset-path and --save-dir to generate UpSet plot figures for a dataset', 'generate_upset_figs': 'generate UpSet top and side bar chart figures from a gzipped JSON dataset file', 'load_upset_data': 'load episodes from a dataset and compute task type combination percentages for UpSet analysis', 'generate_upset_top': 'generate a vertical bar chart showing episode percentage for each task type combination', 'generate_upset_side': 'generate a horizontal bar chart showing total episode percentage per individual task type'}
```

