# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/job/eval_utils.py

Prompts

```
['extract benchmark success, failure, and metric statistics from a dictionary of evaluation results using a regex pattern', 'generate environment variables and a shell command string for running a checkpoint evaluation script with benchmark and seed config', 'review the extract_benchmark_data function to understand how it parses benchmark_seed keys and calculates metric averages and stderr', 'review the run_eval_script function to understand how it constructs evaluation commands with benchmark config and optional sampling params', 'refactor the run_eval_script function to support additional benchmark types or custom command-line argument configurations', 'submit a job definition with task definitions to the Ray JobManager actor for execution', 'get the current status and progress details of a previously submitted job by job ID', 'get the results for all tasks within a completed or failed job by job ID', 'list all job IDs currently known by the JobManager actor', 'delete a specific job by its job ID from the JobManager actor', 'gracefully shut down the JobManager monitor thread and cancel remaining running tasks', 'generate a unique job ID using UUID for the Matrix job manager', 'generate a unique task ID within a job using the job ID and index', 'deploy applications for Matrix jobs using the app API deploy action', 'check the deployment status of a Matrix application using the app API', 'undeploy a Matrix application using the app API remove action']
```

Usage

```
{'extract_benchmark_data': 'extract benchmark success, failure, and metric statistics from a dictionary of evaluation results using a regex pattern', 'run_eval_script': 'generate environment variables and a shell command string for running a checkpoint evaluation script with benchmark and seed config', 'review_extract_benchmark_data': 'review the extract_benchmark_data function to understand how it parses benchmark_seed keys and calculates metric averages and stderr', 'review_run_eval_script': 'review the run_eval_script function to understand how it constructs evaluation commands with benchmark config and optional sampling params', 'refactor_run_eval_script': 'refactor the run_eval_script function to support additional benchmark types or custom command-line argument configurations'}
```

## File: facebookresearch_matrix/matrix/job/job_api.py

Prompts

```
['extract benchmark success, failure, and metric statistics from a dictionary of evaluation results using a regex pattern', 'generate environment variables and a shell command string for running a checkpoint evaluation script with benchmark and seed config', 'review the extract_benchmark_data function to understand how it parses benchmark_seed keys and calculates metric averages and stderr', 'review the run_eval_script function to understand how it constructs evaluation commands with benchmark config and optional sampling params', 'refactor the run_eval_script function to support additional benchmark types or custom command-line argument configurations', 'submit a job definition with task definitions to the Ray JobManager actor for execution', 'get the current status and progress details of a previously submitted job by job ID', 'get the results for all tasks within a completed or failed job by job ID', 'list all job IDs currently known by the JobManager actor', 'delete a specific job by its job ID from the JobManager actor', 'gracefully shut down the JobManager monitor thread and cancel remaining running tasks', 'generate a unique job ID using UUID for the Matrix job manager', 'generate a unique task ID within a job using the job ID and index', 'deploy applications for Matrix jobs using the app API deploy action', 'check the deployment status of a Matrix application using the app API', 'undeploy a Matrix application using the app API remove action']
```

Usage

```
{'submit_job': 'submit a job definition with task definitions to the Ray JobManager actor for execution', 'get_job_status': 'get the current status and progress details of a previously submitted job by job ID', 'get_job_results': 'get the results for all tasks within a completed or failed job by job ID', 'list_jobs': 'list all job IDs currently known by the JobManager actor', 'delete_job': 'delete a specific job by its job ID from the JobManager actor'}
```

## File: facebookresearch_matrix/matrix/job/job_manager.py

Prompts

```
['extract benchmark success, failure, and metric statistics from a dictionary of evaluation results using a regex pattern', 'generate environment variables and a shell command string for running a checkpoint evaluation script with benchmark and seed config', 'review the extract_benchmark_data function to understand how it parses benchmark_seed keys and calculates metric averages and stderr', 'review the run_eval_script function to understand how it constructs evaluation commands with benchmark config and optional sampling params', 'refactor the run_eval_script function to support additional benchmark types or custom command-line argument configurations', 'submit a job definition with task definitions to the Ray JobManager actor for execution', 'get the current status and progress details of a previously submitted job by job ID', 'get the results for all tasks within a completed or failed job by job ID', 'list all job IDs currently known by the JobManager actor', 'delete a specific job by its job ID from the JobManager actor', 'gracefully shut down the JobManager monitor thread and cancel remaining running tasks', 'generate a unique job ID using UUID for the Matrix job manager', 'generate a unique task ID within a job using the job ID and index', 'deploy applications for Matrix jobs using the app API deploy action', 'check the deployment status of a Matrix application using the app API', 'undeploy a Matrix application using the app API remove action']
```

Usage

```
{'submit_job': 'submit a new job with task definitions and concurrency limit to the JobManager actor', 'get_job_status': 'get the status and progress of a job including task counts and active tasks', 'get_job_results': 'get the results for all tasks within a completed or running job', 'delete_job': 'delete a job by ID and cancel any running Ray tasks associated with it', 'stop_job_manager': 'gracefully shut down the JobManager monitor thread and cancel remaining running tasks'}
```

## File: facebookresearch_matrix/matrix/job/job_utils.py

Prompts

```
['extract benchmark success, failure, and metric statistics from a dictionary of evaluation results using a regex pattern', 'generate environment variables and a shell command string for running a checkpoint evaluation script with benchmark and seed config', 'review the extract_benchmark_data function to understand how it parses benchmark_seed keys and calculates metric averages and stderr', 'review the run_eval_script function to understand how it constructs evaluation commands with benchmark config and optional sampling params', 'refactor the run_eval_script function to support additional benchmark types or custom command-line argument configurations', 'submit a job definition with task definitions to the Ray JobManager actor for execution', 'get the current status and progress details of a previously submitted job by job ID', 'get the results for all tasks within a completed or failed job by job ID', 'list all job IDs currently known by the JobManager actor', 'delete a specific job by its job ID from the JobManager actor', 'gracefully shut down the JobManager monitor thread and cancel remaining running tasks', 'generate a unique job ID using UUID for the Matrix job manager', 'generate a unique task ID within a job using the job ID and index', 'deploy applications for Matrix jobs using the app API deploy action', 'check the deployment status of a Matrix application using the app API', 'undeploy a Matrix application using the app API remove action']
```

Usage

```
{'generate_job_id': 'generate a unique job ID using UUID for the Matrix job manager', 'generate_task_id': 'generate a unique task ID within a job using the job ID and index', 'deploy_helper': 'deploy applications for Matrix jobs using the app API deploy action', 'check_status_helper': 'check the deployment status of a Matrix application using the app API', 'undeploy_helper': 'undeploy a Matrix application using the app API remove action'}
```

