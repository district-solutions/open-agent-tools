# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/utils/fs_utils.py

Prompts

```
['expand a relative or tilde path into an absolute path using expand_path', 'check if a filename matches any glob pattern in a list using fname_matches_any', 'copy a directory tree to a target path while ignoring specific files using cp_dir', 'create a unique temporary folder with a given name prefix using create_unique_temp_folder', 'review the fs_utils module for path expansion, file matching, directory copy, and temp folder utilities', 'extract key-value metric pairs from a single line of text and cast values to specified types', 'extract the best metrics line from multi-line text based on a selection metric with optional threshold constraints', 'extract metrics from the last valid line of multi-line text with key-value pairs', 'review the extract_single_line_metrics function to understand its regex pattern and type casting behavior', 'refactor the extract_best_line_metrics function to support additional selection criteria or threshold logic', 'submit a SLURM job using submitit with specified nodes, GPUs, CPUs, and timeout', 'observe a submitit job status and execute a callback when the job finishes', 'wait for all observed submitit jobs and their callbacks to complete', 'cancel all pending observed submitit jobs in the JobObserver pool', 'simulate a submitit job locally by running a command as a subprocess', "convert a type name string like 'float' or 'int' to its corresponding Python type object", 'filter a dictionary to keep only JSON-serializable key-value pairs and drop the rest', 'refactor the basic_type_name_to_type function to support additional type mappings', 'review the get_serializable_dict_subset function and its JSON serialization filtering logic', 'summarize the str_utils module and its type conversion and serialization utility functions']
```

Usage

```
{'expand_path': 'expand a relative or tilde path into an absolute path using expand_path', 'fname_matches_any': 'check if a filename matches any glob pattern in a list using fname_matches_any', 'cp_dir': 'copy a directory tree to a target path while ignoring specific files using cp_dir', 'create_unique_temp_folder': 'create a unique temporary folder with a given name prefix using create_unique_temp_folder', 'review_fs_utils': 'review the fs_utils module for path expansion, file matching, directory copy, and temp folder utilities'}
```

## File: facebookresearch_llm-speedrunner/utils/metrics_utils.py

Prompts

```
['expand a relative or tilde path into an absolute path using expand_path', 'check if a filename matches any glob pattern in a list using fname_matches_any', 'copy a directory tree to a target path while ignoring specific files using cp_dir', 'create a unique temporary folder with a given name prefix using create_unique_temp_folder', 'review the fs_utils module for path expansion, file matching, directory copy, and temp folder utilities', 'extract key-value metric pairs from a single line of text and cast values to specified types', 'extract the best metrics line from multi-line text based on a selection metric with optional threshold constraints', 'extract metrics from the last valid line of multi-line text with key-value pairs', 'review the extract_single_line_metrics function to understand its regex pattern and type casting behavior', 'refactor the extract_best_line_metrics function to support additional selection criteria or threshold logic', 'submit a SLURM job using submitit with specified nodes, GPUs, CPUs, and timeout', 'observe a submitit job status and execute a callback when the job finishes', 'wait for all observed submitit jobs and their callbacks to complete', 'cancel all pending observed submitit jobs in the JobObserver pool', 'simulate a submitit job locally by running a command as a subprocess', "convert a type name string like 'float' or 'int' to its corresponding Python type object", 'filter a dictionary to keep only JSON-serializable key-value pairs and drop the rest', 'refactor the basic_type_name_to_type function to support additional type mappings', 'review the get_serializable_dict_subset function and its JSON serialization filtering logic', 'summarize the str_utils module and its type conversion and serialization utility functions']
```

Usage

```
{'extract_single_line_metrics': 'extract key-value metric pairs from a single line of text and cast values to specified types', 'extract_best_line_metrics': 'extract the best metrics line from multi-line text based on a selection metric with optional threshold constraints', 'extract_last_line_metrics': 'extract metrics from the last valid line of multi-line text with key-value pairs', 'review_extract_single_line_metrics': 'review the extract_single_line_metrics function to understand its regex pattern and type casting behavior', 'refactor_extract_best_line_metrics': 'refactor the extract_best_line_metrics function to support additional selection criteria or threshold logic'}
```

## File: facebookresearch_llm-speedrunner/utils/slurm_utils.py

Prompts

```
['expand a relative or tilde path into an absolute path using expand_path', 'check if a filename matches any glob pattern in a list using fname_matches_any', 'copy a directory tree to a target path while ignoring specific files using cp_dir', 'create a unique temporary folder with a given name prefix using create_unique_temp_folder', 'review the fs_utils module for path expansion, file matching, directory copy, and temp folder utilities', 'extract key-value metric pairs from a single line of text and cast values to specified types', 'extract the best metrics line from multi-line text based on a selection metric with optional threshold constraints', 'extract metrics from the last valid line of multi-line text with key-value pairs', 'review the extract_single_line_metrics function to understand its regex pattern and type casting behavior', 'refactor the extract_best_line_metrics function to support additional selection criteria or threshold logic', 'submit a SLURM job using submitit with specified nodes, GPUs, CPUs, and timeout', 'observe a submitit job status and execute a callback when the job finishes', 'wait for all observed submitit jobs and their callbacks to complete', 'cancel all pending observed submitit jobs in the JobObserver pool', 'simulate a submitit job locally by running a command as a subprocess', "convert a type name string like 'float' or 'int' to its corresponding Python type object", 'filter a dictionary to keep only JSON-serializable key-value pairs and drop the rest', 'refactor the basic_type_name_to_type function to support additional type mappings', 'review the get_serializable_dict_subset function and its JSON serialization filtering logic', 'summarize the str_utils module and its type conversion and serialization utility functions']
```

Usage

```
{'submit_slurm_job': 'submit a SLURM job using submitit with specified nodes, GPUs, CPUs, and timeout', 'observe_submitit_job': 'observe a submitit job status and execute a callback when the job finishes', 'wait_for_observed_jobs': 'wait for all observed submitit jobs and their callbacks to complete', 'cancel_observed_jobs': 'cancel all pending observed submitit jobs in the JobObserver pool', 'simulate_local_submitit_job': 'simulate a submitit job locally by running a command as a subprocess'}
```

## File: facebookresearch_llm-speedrunner/utils/str_utils.py

Prompts

```
['expand a relative or tilde path into an absolute path using expand_path', 'check if a filename matches any glob pattern in a list using fname_matches_any', 'copy a directory tree to a target path while ignoring specific files using cp_dir', 'create a unique temporary folder with a given name prefix using create_unique_temp_folder', 'review the fs_utils module for path expansion, file matching, directory copy, and temp folder utilities', 'extract key-value metric pairs from a single line of text and cast values to specified types', 'extract the best metrics line from multi-line text based on a selection metric with optional threshold constraints', 'extract metrics from the last valid line of multi-line text with key-value pairs', 'review the extract_single_line_metrics function to understand its regex pattern and type casting behavior', 'refactor the extract_best_line_metrics function to support additional selection criteria or threshold logic', 'submit a SLURM job using submitit with specified nodes, GPUs, CPUs, and timeout', 'observe a submitit job status and execute a callback when the job finishes', 'wait for all observed submitit jobs and their callbacks to complete', 'cancel all pending observed submitit jobs in the JobObserver pool', 'simulate a submitit job locally by running a command as a subprocess', "convert a type name string like 'float' or 'int' to its corresponding Python type object", 'filter a dictionary to keep only JSON-serializable key-value pairs and drop the rest', 'refactor the basic_type_name_to_type function to support additional type mappings', 'review the get_serializable_dict_subset function and its JSON serialization filtering logic', 'summarize the str_utils module and its type conversion and serialization utility functions']
```

Usage

```
{'convert_type_name_to_type': "convert a type name string like 'float' or 'int' to its corresponding Python type object", 'filter_serializable_dict': 'filter a dictionary to keep only JSON-serializable key-value pairs and drop the rest', 'refactor_basic_type_name_to_type': 'refactor the basic_type_name_to_type function to support additional type mappings', 'review_get_serializable_dict_subset': 'review the get_serializable_dict_subset function and its JSON serialization filtering logic', 'summarize_str_utils': 'summarize the str_utils module and its type conversion and serialization utility functions'}
```

