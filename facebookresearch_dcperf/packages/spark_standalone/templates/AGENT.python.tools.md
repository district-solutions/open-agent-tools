# Agent Python Tools

- repo: facebookresearch/dcperf
- repo_uri: https://github.com/facebookresearch/dcperf

## File: facebookresearch_dcperf/packages/spark_standalone/templates/fetch_dataset.py

Prompts

```
['run the fetch_dataset script to download files from a manifold dataset to a target path', 'run the fetch_file function to download a single file from the manifold dataset to a destination', 'run the create_dir function to create a directory at the specified destination path', 'run the run_cmd function to execute a shell command with optional dry-run mode', 'run the CLI with --dst-path and --file-list args to fetch a dataset from a JSON manifest', 'run the spark standalone benchmark with dataset download, database install, and test execution', 'setup remote SSDs via NVMe-over-TCP for spark standalone benchmark environment', 'download the synthetic dataset from manifold and create a symlink in the dataset directory', 'install the spark metastore database from the synthetic dataset with configurable warehouse and shuffle dirs', 'start a perf recording profiler thread that triggers when stage 2.0 is detected in the sparkbench log']
```

Usage

```
{'run_fetch_dataset': 'run the fetch_dataset script to download files from a manifold dataset to a target path', 'run_fetch_file': 'run the fetch_file function to download a single file from the manifold dataset to a destination', 'run_create_dir': 'run the create_dir function to create a directory at the specified destination path', 'run_run_cmd': 'run the run_cmd function to execute a shell command with optional dry-run mode', 'run_fetch_dataset_cli': 'run the CLI with --dst-path and --file-list args to fetch a dataset from a JSON manifest'}
```

## File: facebookresearch_dcperf/packages/spark_standalone/templates/runner.py

Prompts

```
['run the fetch_dataset script to download files from a manifold dataset to a target path', 'run the fetch_file function to download a single file from the manifold dataset to a destination', 'run the create_dir function to create a directory at the specified destination path', 'run the run_cmd function to execute a shell command with optional dry-run mode', 'run the CLI with --dst-path and --file-list args to fetch a dataset from a JSON manifest', 'run the spark standalone benchmark with dataset download, database install, and test execution', 'setup remote SSDs via NVMe-over-TCP for spark standalone benchmark environment', 'download the synthetic dataset from manifold and create a symlink in the dataset directory', 'install the spark metastore database from the synthetic dataset with configurable warehouse and shuffle dirs', 'start a perf recording profiler thread that triggers when stage 2.0 is detected in the sparkbench log']
```

Usage

```
{'run_spark_benchmark': 'run the spark standalone benchmark with dataset download, database install, and test execution', 'setup_remote_ssds': 'setup remote SSDs via NVMe-over-TCP for spark standalone benchmark environment', 'download_dataset': 'download the synthetic dataset from manifold and create a symlink in the dataset directory', 'install_database': 'install the spark metastore database from the synthetic dataset with configurable warehouse and shuffle dirs', 'profile_spark_server': 'start a perf recording profiler thread that triggers when stage 2.0 is detected in the sparkbench log'}
```

