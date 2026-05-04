# Agent Python Tools

- repo: google-deepmind/alphamissense
- repo_uri: https://github.com/google-deepmind/alphamissense

## File: google-deepmind_alphamissense/alphamissense/data/tools/jackhmmer.py

Prompts

```
['run a Jackhmmer search against a protein database using a FASTA input file', 'run Jackhmmer searches for multiple FASTA query files against a protein database', 'run Jackhmmer with streamed database chunks to avoid loading the full database into memory', 'configure Jackhmmer pre-filter thresholds F1, F2, F3 to tune sensitivity versus speed', 'configure Jackhmmer E-value and domain E-value thresholds for sequence inclusion criteria', 'create a context manager that creates and cleans up a temporary directory on exit', 'create a context manager that logs the elapsed time of a code block', 'use tmpdir_manager to create a temporary directory in a specified base directory path', 'use the timing context manager to log how long a data pipeline step takes', 'review the utils module context managers for temporary directory and timing functionality']
```

Usage

```
{'run_jackhmmer_query': 'run a Jackhmmer search against a protein database using a FASTA input file', 'run_jackhmmer_multiple': 'run Jackhmmer searches for multiple FASTA query files against a protein database', 'run_jackhmmer_streamed': 'run Jackhmmer with streamed database chunks to avoid loading the full database into memory', 'configure_jackhmmer_filters': 'configure Jackhmmer pre-filter thresholds F1, F2, F3 to tune sensitivity versus speed', 'configure_jackhmmer_evalue': 'configure Jackhmmer E-value and domain E-value thresholds for sequence inclusion criteria'}
```

## File: google-deepmind_alphamissense/alphamissense/data/tools/utils.py

Prompts

```
['run a Jackhmmer search against a protein database using a FASTA input file', 'run Jackhmmer searches for multiple FASTA query files against a protein database', 'run Jackhmmer with streamed database chunks to avoid loading the full database into memory', 'configure Jackhmmer pre-filter thresholds F1, F2, F3 to tune sensitivity versus speed', 'configure Jackhmmer E-value and domain E-value thresholds for sequence inclusion criteria', 'create a context manager that creates and cleans up a temporary directory on exit', 'create a context manager that logs the elapsed time of a code block', 'use tmpdir_manager to create a temporary directory in a specified base directory path', 'use the timing context manager to log how long a data pipeline step takes', 'review the utils module context managers for temporary directory and timing functionality']
```

Usage

```
{'create_tmpdir_context_manager': 'create a context manager that creates and cleans up a temporary directory on exit', 'create_timed_block': 'create a context manager that logs the elapsed time of a code block', 'use_tmpdir_manager_with_base_dir': 'use tmpdir_manager to create a temporary directory in a specified base directory path', 'use_timing_for_profiling': 'use the timing context manager to log how long a data pipeline step takes', 'review_utils_context_managers': 'review the utils module context managers for temporary directory and timing functionality'}
```

