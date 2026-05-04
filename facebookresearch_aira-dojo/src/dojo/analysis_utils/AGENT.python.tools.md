# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/analysis_utils/journal_to_tree.py

Prompts

```
['parse a JSONL journal log file into a structured JSON dictionary with optional time cutoff', 'read a journal JSONL file and save the parsed entries as a JSON file to disk', 'generate an HTML tree visualization from a Journal instance and save it to a file', 'generate an HTML tree visualization from JSON data by reconstructing a Journal instance', 'concurrently process multiple experiment folders and generate tree visualizations for each', 'analyze a Slurm meta-experiment directory and return a DataFrame with job states, elapsed times, and failure logs', 'collect all meta-experiments into a single DataFrame by processing journal logs, gathering data, and joining Slurm info', 'format an experiments DataFrame into competition reports with scores, medals, percentiles, and rank for each method and seed', 'filter a DataFrame to ensure every competition-method-seed group has at least one valid node and overwrite invalid groups with sentinel scores', 'parse a report DataFrame into a dictionary of per-method numpy matrices pivoted by competition and seed for a given metric', 'generate a markdown error analysis report from SLURM experiment log directories using LLM-powered crash summarization', 'extract the last approximate tokens from a file by byte offset and compress whitespace', 'check if a log text snippet likely indicates a crashed job using keyword heuristics', 'gather SLURM error log data for a list of job IDs and detect likely crashed jobs', 'map SLURM job IDs to their corresponding experiment log directory paths', 'generate tree reports and aggregate statistics for all experiments in a meta experiment directory concurrently', 'calculate statistical metrics like node counts, execution times, and depth from a Journal tree structure', 'generate a structured technical markdown report from a research journal using an LLM client', 'plot boxplots, histograms, and bar charts of numerical metrics across multiple experiment runs using seaborn', 'write detailed markdown reports and statistics files for a single experiment based on its journal']
```

Usage

```
{'parse_journal_jsonl_to_json': 'parse a JSONL journal log file into a structured JSON dictionary with optional time cutoff', 'save_journal_log_as_json': 'read a journal JSONL file and save the parsed entries as a JSON file to disk', 'generate_tree_from_journal': 'generate an HTML tree visualization from a Journal instance and save it to a file', 'generate_tree_from_json': 'generate an HTML tree visualization from JSON data by reconstructing a Journal instance', 'visualize_all_experiment_trees': 'concurrently process multiple experiment folders and generate tree visualizations for each'}
```

## File: facebookresearch_aira-dojo/src/dojo/analysis_utils/meta_data_wrangling.py

Prompts

```
['parse a JSONL journal log file into a structured JSON dictionary with optional time cutoff', 'read a journal JSONL file and save the parsed entries as a JSON file to disk', 'generate an HTML tree visualization from a Journal instance and save it to a file', 'generate an HTML tree visualization from JSON data by reconstructing a Journal instance', 'concurrently process multiple experiment folders and generate tree visualizations for each', 'analyze a Slurm meta-experiment directory and return a DataFrame with job states, elapsed times, and failure logs', 'collect all meta-experiments into a single DataFrame by processing journal logs, gathering data, and joining Slurm info', 'format an experiments DataFrame into competition reports with scores, medals, percentiles, and rank for each method and seed', 'filter a DataFrame to ensure every competition-method-seed group has at least one valid node and overwrite invalid groups with sentinel scores', 'parse a report DataFrame into a dictionary of per-method numpy matrices pivoted by competition and seed for a given metric', 'generate a markdown error analysis report from SLURM experiment log directories using LLM-powered crash summarization', 'extract the last approximate tokens from a file by byte offset and compress whitespace', 'check if a log text snippet likely indicates a crashed job using keyword heuristics', 'gather SLURM error log data for a list of job IDs and detect likely crashed jobs', 'map SLURM job IDs to their corresponding experiment log directory paths', 'generate tree reports and aggregate statistics for all experiments in a meta experiment directory concurrently', 'calculate statistical metrics like node counts, execution times, and depth from a Journal tree structure', 'generate a structured technical markdown report from a research journal using an LLM client', 'plot boxplots, histograms, and bar charts of numerical metrics across multiple experiment runs using seaborn', 'write detailed markdown reports and statistics files for a single experiment based on its journal']
```

Usage

```
{'analyze_slurm_meta_exp': 'analyze a Slurm meta-experiment directory and return a DataFrame with job states, elapsed times, and failure logs', 'collect_all_meta_experiments_in_one_df': 'collect all meta-experiments into a single DataFrame by processing journal logs, gathering data, and joining Slurm info', 'format_experiment_data': 'format an experiments DataFrame into competition reports with scores, medals, percentiles, and rank for each method and seed', 'filter_dataframe_based_on_data_validity': 'filter a DataFrame to ensure every competition-method-seed group has at least one valid node and overwrite invalid groups with sentinel scores', 'parse_into_aggregate_dict': 'parse a report DataFrame into a dictionary of per-method numpy matrices pivoted by competition and seed for a given metric'}
```

## File: facebookresearch_aira-dojo/src/dojo/analysis_utils/meta_error_summary.py

Prompts

```
['parse a JSONL journal log file into a structured JSON dictionary with optional time cutoff', 'read a journal JSONL file and save the parsed entries as a JSON file to disk', 'generate an HTML tree visualization from a Journal instance and save it to a file', 'generate an HTML tree visualization from JSON data by reconstructing a Journal instance', 'concurrently process multiple experiment folders and generate tree visualizations for each', 'analyze a Slurm meta-experiment directory and return a DataFrame with job states, elapsed times, and failure logs', 'collect all meta-experiments into a single DataFrame by processing journal logs, gathering data, and joining Slurm info', 'format an experiments DataFrame into competition reports with scores, medals, percentiles, and rank for each method and seed', 'filter a DataFrame to ensure every competition-method-seed group has at least one valid node and overwrite invalid groups with sentinel scores', 'parse a report DataFrame into a dictionary of per-method numpy matrices pivoted by competition and seed for a given metric', 'generate a markdown error analysis report from SLURM experiment log directories using LLM-powered crash summarization', 'extract the last approximate tokens from a file by byte offset and compress whitespace', 'check if a log text snippet likely indicates a crashed job using keyword heuristics', 'gather SLURM error log data for a list of job IDs and detect likely crashed jobs', 'map SLURM job IDs to their corresponding experiment log directory paths', 'generate tree reports and aggregate statistics for all experiments in a meta experiment directory concurrently', 'calculate statistical metrics like node counts, execution times, and depth from a Journal tree structure', 'generate a structured technical markdown report from a research journal using an LLM client', 'plot boxplots, histograms, and bar charts of numerical metrics across multiple experiment runs using seaborn', 'write detailed markdown reports and statistics files for a single experiment based on its journal']
```

Usage

```
{'generate_error_reports': 'generate a markdown error analysis report from SLURM experiment log directories using LLM-powered crash summarization', 'get_last_approx_tokens': 'extract the last approximate tokens from a file by byte offset and compress whitespace', 'likely_crashed': 'check if a log text snippet likely indicates a crashed job using keyword heuristics', 'gather_submitit_data': 'gather SLURM error log data for a list of job IDs and detect likely crashed jobs', 'slurm_id_to_log': 'map SLURM job IDs to their corresponding experiment log directory paths'}
```

## File: facebookresearch_aira-dojo/src/dojo/analysis_utils/meta_tree_analysis.py

Prompts

```
['parse a JSONL journal log file into a structured JSON dictionary with optional time cutoff', 'read a journal JSONL file and save the parsed entries as a JSON file to disk', 'generate an HTML tree visualization from a Journal instance and save it to a file', 'generate an HTML tree visualization from JSON data by reconstructing a Journal instance', 'concurrently process multiple experiment folders and generate tree visualizations for each', 'analyze a Slurm meta-experiment directory and return a DataFrame with job states, elapsed times, and failure logs', 'collect all meta-experiments into a single DataFrame by processing journal logs, gathering data, and joining Slurm info', 'format an experiments DataFrame into competition reports with scores, medals, percentiles, and rank for each method and seed', 'filter a DataFrame to ensure every competition-method-seed group has at least one valid node and overwrite invalid groups with sentinel scores', 'parse a report DataFrame into a dictionary of per-method numpy matrices pivoted by competition and seed for a given metric', 'generate a markdown error analysis report from SLURM experiment log directories using LLM-powered crash summarization', 'extract the last approximate tokens from a file by byte offset and compress whitespace', 'check if a log text snippet likely indicates a crashed job using keyword heuristics', 'gather SLURM error log data for a list of job IDs and detect likely crashed jobs', 'map SLURM job IDs to their corresponding experiment log directory paths', 'generate tree reports and aggregate statistics for all experiments in a meta experiment directory concurrently', 'calculate statistical metrics like node counts, execution times, and depth from a Journal tree structure', 'generate a structured technical markdown report from a research journal using an LLM client', 'plot boxplots, histograms, and bar charts of numerical metrics across multiple experiment runs using seaborn', 'write detailed markdown reports and statistics files for a single experiment based on its journal']
```

Usage

```
{'generate_tree_reports_and_stats': 'generate tree reports and aggregate statistics for all experiments in a meta experiment directory concurrently', 'calculate_tree_statistics': 'calculate statistical metrics like node counts, execution times, and depth from a Journal tree structure', 'generate_journal_report': 'generate a structured technical markdown report from a research journal using an LLM client', 'plot_aggregate_stats': 'plot boxplots, histograms, and bar charts of numerical metrics across multiple experiment runs using seaborn', 'write_tree_reports': 'write detailed markdown reports and statistics files for a single experiment based on its journal'}
```

