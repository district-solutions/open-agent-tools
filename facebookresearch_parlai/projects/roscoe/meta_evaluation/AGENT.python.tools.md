# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/roscoe/meta_evaluation/correlations.py

Prompts

```
['create an Analyzer instance with a reference column name for Somers D correlation analysis', 'run Somers D correlation between a reference column and a hypothesis column on a DataFrame', 'run get_statistics to compute Somers D correlation and p-values for all columns against a reference', 'review the Analyzer class correlation_stat method that computes Somers D on a DataFrame subset', 'summarize the Analyzer get_statistics method that returns correlation statistics and p-values as DataFrames', 'run correlation analysis on annotated data evaluations for a specific dataset like drop or gsm8k', 'run correlation analysis across all datasets drop gsm8k esnli cosmos and semeval at once', 'compute Somers D correlation and p-value tables between ROSCOE scores and human annotation labels', 'parse and aggregate human annotation rows and model scores into a values dictionary for correlation analysis', 'generate correlation tables and granular summaries for a single dataset with optional baseline scores', 'run correlation analysis on synthetic data evaluations for a named dataset like aqua', 'run correlation analysis on sentinel scores by passing the sentinel-scores flag', 'create a function that reads a whitespace-delimited CSV file and returns a pandas DataFrame', 'create a function that annotates a scores DataFrame with perturbation marks from a JSONL file', 'run the full correlation pipeline to compute statistics and save results to CSV files', 'write a granular summary LaTeX table for a single dataset with bold top-2 values and significance markers', 'write a cross-dataset summary LaTeX table with granular annotations and model section headers', 'write a final combined summary LaTeX table across all datasets with formatted top-2 values', 'find the top 2 values in each DataFrame column and return LaTeX bold and underline replacement mappings', 'generate a LaTeX section title string for a given ROSCOE section and embedding model name']
```

Usage

```
{'create_Analyzer': 'create an Analyzer instance with a reference column name for Somers D correlation analysis', 'run_correlation_stat': 'run Somers D correlation between a reference column and a hypothesis column on a DataFrame', 'run_get_statistics': 'run get_statistics to compute Somers D correlation and p-values for all columns against a reference', 'review_Analyzer_correlation_stat': 'review the Analyzer class correlation_stat method that computes Somers D on a DataFrame subset', 'summarize_Analyzer_get_statistics': 'summarize the Analyzer get_statistics method that returns correlation statistics and p-values as DataFrames'}
```

## File: facebookresearch_parlai/projects/roscoe/meta_evaluation/roscoe_correlations.py

Prompts

```
['create an Analyzer instance with a reference column name for Somers D correlation analysis', 'run Somers D correlation between a reference column and a hypothesis column on a DataFrame', 'run get_statistics to compute Somers D correlation and p-values for all columns against a reference', 'review the Analyzer class correlation_stat method that computes Somers D on a DataFrame subset', 'summarize the Analyzer get_statistics method that returns correlation statistics and p-values as DataFrames', 'run correlation analysis on annotated data evaluations for a specific dataset like drop or gsm8k', 'run correlation analysis across all datasets drop gsm8k esnli cosmos and semeval at once', 'compute Somers D correlation and p-value tables between ROSCOE scores and human annotation labels', 'parse and aggregate human annotation rows and model scores into a values dictionary for correlation analysis', 'generate correlation tables and granular summaries for a single dataset with optional baseline scores', 'run correlation analysis on synthetic data evaluations for a named dataset like aqua', 'run correlation analysis on sentinel scores by passing the sentinel-scores flag', 'create a function that reads a whitespace-delimited CSV file and returns a pandas DataFrame', 'create a function that annotates a scores DataFrame with perturbation marks from a JSONL file', 'run the full correlation pipeline to compute statistics and save results to CSV files', 'write a granular summary LaTeX table for a single dataset with bold top-2 values and significance markers', 'write a cross-dataset summary LaTeX table with granular annotations and model section headers', 'write a final combined summary LaTeX table across all datasets with formatted top-2 values', 'find the top 2 values in each DataFrame column and return LaTeX bold and underline replacement mappings', 'generate a LaTeX section title string for a given ROSCOE section and embedding model name']
```

Usage

```
{'run_correlation_analysis': 'run correlation analysis on annotated data evaluations for a specific dataset like drop or gsm8k', 'run_correlation_all_datasets': 'run correlation analysis across all datasets drop gsm8k esnli cosmos and semeval at once', 'make_correlations_table': 'compute Somers D correlation and p-value tables between ROSCOE scores and human annotation labels', 'process_values': 'parse and aggregate human annotation rows and model scores into a values dictionary for correlation analysis', 'generate_scores_and_correls_for_dataset': 'generate correlation tables and granular summaries for a single dataset with optional baseline scores'}
```

## File: facebookresearch_parlai/projects/roscoe/meta_evaluation/roscoe_synthetic_correlations.py

Prompts

```
['create an Analyzer instance with a reference column name for Somers D correlation analysis', 'run Somers D correlation between a reference column and a hypothesis column on a DataFrame', 'run get_statistics to compute Somers D correlation and p-values for all columns against a reference', 'review the Analyzer class correlation_stat method that computes Somers D on a DataFrame subset', 'summarize the Analyzer get_statistics method that returns correlation statistics and p-values as DataFrames', 'run correlation analysis on annotated data evaluations for a specific dataset like drop or gsm8k', 'run correlation analysis across all datasets drop gsm8k esnli cosmos and semeval at once', 'compute Somers D correlation and p-value tables between ROSCOE scores and human annotation labels', 'parse and aggregate human annotation rows and model scores into a values dictionary for correlation analysis', 'generate correlation tables and granular summaries for a single dataset with optional baseline scores', 'run correlation analysis on synthetic data evaluations for a named dataset like aqua', 'run correlation analysis on sentinel scores by passing the sentinel-scores flag', 'create a function that reads a whitespace-delimited CSV file and returns a pandas DataFrame', 'create a function that annotates a scores DataFrame with perturbation marks from a JSONL file', 'run the full correlation pipeline to compute statistics and save results to CSV files', 'write a granular summary LaTeX table for a single dataset with bold top-2 values and significance markers', 'write a cross-dataset summary LaTeX table with granular annotations and model section headers', 'write a final combined summary LaTeX table across all datasets with formatted top-2 values', 'find the top 2 values in each DataFrame column and return LaTeX bold and underline replacement mappings', 'generate a LaTeX section title string for a given ROSCOE section and embedding model name']
```

Usage

```
{'run_synthetic_correlations': 'run correlation analysis on synthetic data evaluations for a named dataset like aqua', 'run_sentinel_correlations': 'run correlation analysis on sentinel scores by passing the sentinel-scores flag', 'fetch_to_df': 'create a function that reads a whitespace-delimited CSV file and returns a pandas DataFrame', 'fetch_parturbation_mark': 'create a function that annotates a scores DataFrame with perturbation marks from a JSONL file', 'get_correlations': 'run the full correlation pipeline to compute statistics and save results to CSV files'}
```

## File: facebookresearch_parlai/projects/roscoe/meta_evaluation/table_file_writing.py

Prompts

```
['create an Analyzer instance with a reference column name for Somers D correlation analysis', 'run Somers D correlation between a reference column and a hypothesis column on a DataFrame', 'run get_statistics to compute Somers D correlation and p-values for all columns against a reference', 'review the Analyzer class correlation_stat method that computes Somers D on a DataFrame subset', 'summarize the Analyzer get_statistics method that returns correlation statistics and p-values as DataFrames', 'run correlation analysis on annotated data evaluations for a specific dataset like drop or gsm8k', 'run correlation analysis across all datasets drop gsm8k esnli cosmos and semeval at once', 'compute Somers D correlation and p-value tables between ROSCOE scores and human annotation labels', 'parse and aggregate human annotation rows and model scores into a values dictionary for correlation analysis', 'generate correlation tables and granular summaries for a single dataset with optional baseline scores', 'run correlation analysis on synthetic data evaluations for a named dataset like aqua', 'run correlation analysis on sentinel scores by passing the sentinel-scores flag', 'create a function that reads a whitespace-delimited CSV file and returns a pandas DataFrame', 'create a function that annotates a scores DataFrame with perturbation marks from a JSONL file', 'run the full correlation pipeline to compute statistics and save results to CSV files', 'write a granular summary LaTeX table for a single dataset with bold top-2 values and significance markers', 'write a cross-dataset summary LaTeX table with granular annotations and model section headers', 'write a final combined summary LaTeX table across all datasets with formatted top-2 values', 'find the top 2 values in each DataFrame column and return LaTeX bold and underline replacement mappings', 'generate a LaTeX section title string for a given ROSCOE section and embedding model name']
```

Usage

```
{'write_granular_summary_tex': 'write a granular summary LaTeX table for a single dataset with bold top-2 values and significance markers', 'write_every_dataset_summary_table_tex': 'write a cross-dataset summary LaTeX table with granular annotations and model section headers', 'write_every_dataset_final_summary_table_tex': 'write a final combined summary LaTeX table across all datasets with formatted top-2 values', 'top_2_format_replacements': 'find the top 2 values in each DataFrame column and return LaTeX bold and underline replacement mappings', 'model_section_title_tex': 'generate a LaTeX section title string for a given ROSCOE section and embedding model name'}
```

