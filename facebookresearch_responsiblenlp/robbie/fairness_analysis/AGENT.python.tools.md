# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/robbie/fairness_analysis/bootstrap_regard_pct.py

Prompts

```
['run bootstrap analysis on a JSONL file to compute regard percentage confidence intervals per descriptor', 'run bootstrap analysis on a JSONL file to compute regard percentage confidence intervals per axis and descriptor', 'run get_regard_pct to calculate the percentage of negative labels in a list of prediction data', 'review the main function that groups JSONL samples by descriptor and runs bootstrap confidence interval analysis', 'review how bootstrap confidence intervals are calculated using scipy.stats.bootstrap with percentile method', 'run a bootstrap toxicity percentage analysis on safety_score, bold, or advpromptset benchmark data', 'run the CLI tool with input JSONL files and a task name to compute toxicity statistics', 'calculate the percentage of toxic samples in a dataset using the get_toxicity_pct function', 'compute bootstrap confidence intervals for toxicity percentages across demographic groups using scipy.stats.bootstrap', 'process multiple benchmark datasets including safety_score, bold, and advpromptset with configurable confidence levels']
```

Usage

```
{'run_bootstrap_regard_analysis': 'run bootstrap analysis on a JSONL file to compute regard percentage confidence intervals per descriptor', 'run_bootstrap_non_regard_analysis': 'run bootstrap analysis on a JSONL file to compute regard percentage confidence intervals per axis and descriptor', 'run_get_regard_pct': 'run get_regard_pct to calculate the percentage of negative labels in a list of prediction data', 'review_main_bootstrap_workflow': 'review the main function that groups JSONL samples by descriptor and runs bootstrap confidence interval analysis', 'review_bootstrap_ci_calculation': 'review how bootstrap confidence intervals are calculated using scipy.stats.bootstrap with percentile method'}
```

## File: facebookresearch_responsiblenlp/robbie/fairness_analysis/bootstrap_toxicity_pct.py

Prompts

```
['run bootstrap analysis on a JSONL file to compute regard percentage confidence intervals per descriptor', 'run bootstrap analysis on a JSONL file to compute regard percentage confidence intervals per axis and descriptor', 'run get_regard_pct to calculate the percentage of negative labels in a list of prediction data', 'review the main function that groups JSONL samples by descriptor and runs bootstrap confidence interval analysis', 'review how bootstrap confidence intervals are calculated using scipy.stats.bootstrap with percentile method', 'run a bootstrap toxicity percentage analysis on safety_score, bold, or advpromptset benchmark data', 'run the CLI tool with input JSONL files and a task name to compute toxicity statistics', 'calculate the percentage of toxic samples in a dataset using the get_toxicity_pct function', 'compute bootstrap confidence intervals for toxicity percentages across demographic groups using scipy.stats.bootstrap', 'process multiple benchmark datasets including safety_score, bold, and advpromptset with configurable confidence levels']
```

Usage

```
{'run_bootstrap_toxicity_analysis': 'run a bootstrap toxicity percentage analysis on safety_score, bold, or advpromptset benchmark data', 'run_cli_with_input_files': 'run the CLI tool with input JSONL files and a task name to compute toxicity statistics', 'calculate_toxicity_percentage': 'calculate the percentage of toxic samples in a dataset using the get_toxicity_pct function', 'compute_bootstrap_confidence_intervals': 'compute bootstrap confidence intervals for toxicity percentages across demographic groups using scipy.stats.bootstrap', 'process_multiple_benchmark_datasets': 'process multiple benchmark datasets including safety_score, bold, and advpromptset with configurable confidence levels'}
```

