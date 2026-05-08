# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/benchmarks/dash_app/app.py

Prompts

```
['run the CrypTen benchmarks Dash app in debug mode with app.run_server', 'update the Crypten runtime bar chart filtered by date and party mode', 'update the Crypten vs Plaintext runtime gap bar chart by date and mode', 'filter model benchmark data by CPU vs GPU or CPU vs Plaintext comparison option', 'route to the index or compare page layout based on the URL pathname', 'load func and model benchmark CSV files from a directory path into pandas DataFrames', 'aggregate benchmark data across multiple subdirectories and dates into combined DataFrames', 'compute the runtime gap ratio between CrypTen and plain text execution times', 'add error bar columns for plotting based on Q1 and Q3 quantile values', 'list all available date subdirectories within a benchmark data directory']
```

Usage

```
{'run_dash_app': 'run the CrypTen benchmarks Dash app in debug mode with app.run_server', 'update_runtime_crypten': 'update the Crypten runtime bar chart filtered by date and party mode', 'update_runtime_crypten_v_plain': 'update the Crypten vs Plaintext runtime gap bar chart by date and mode', 'process_comparison_options': 'filter model benchmark data by CPU vs GPU or CPU vs Plaintext comparison option', 'display_page': 'route to the index or compare page layout based on the URL pathname'}
```

## File: facebookresearch_crypten/benchmarks/dash_app/load_data.py

Prompts

```
['run the CrypTen benchmarks Dash app in debug mode with app.run_server', 'update the Crypten runtime bar chart filtered by date and party mode', 'update the Crypten vs Plaintext runtime gap bar chart by date and mode', 'filter model benchmark data by CPU vs GPU or CPU vs Plaintext comparison option', 'route to the index or compare page layout based on the URL pathname', 'load func and model benchmark CSV files from a directory path into pandas DataFrames', 'aggregate benchmark data across multiple subdirectories and dates into combined DataFrames', 'compute the runtime gap ratio between CrypTen and plain text execution times', 'add error bar columns for plotting based on Q1 and Q3 quantile values', 'list all available date subdirectories within a benchmark data directory']
```

Usage

```
{'load_benchmark_csv': 'load func and model benchmark CSV files from a directory path into pandas DataFrames', 'aggregate_benchmark_data': 'aggregate benchmark data across multiple subdirectories and dates into combined DataFrames', 'compute_runtime_gap': 'compute the runtime gap ratio between CrypTen and plain text execution times', 'add_error_bars': 'add error bar columns for plotting based on Q1 and Q3 quantile values', 'get_available_dates': 'list all available date subdirectories within a benchmark data directory'}
```

