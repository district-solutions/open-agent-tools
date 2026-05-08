# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/cli.py

Prompts

```
['start a Ray cluster with optional Slurm workers and Grafana monitoring enabled', 'stop the running Ray cluster and release all allocated resources', 'check the status of the Ray cluster including head node and Serve applications', 'deploy applications like vLLM serving or LLM proxy to the Ray cluster', 'run batch LLM inference on input JSONL or Hugging Face datasets using a deployed app', 'start a FastAPI server on port 6289 to manage Matrix clusters and jobs via HTTP endpoints', 'submit a new job with task definitions to the Matrix JobManager via the POST /jobs endpoint', 'submit a checkpoint evaluation job that runs benchmarks on a model checkpoint across multiple seeds', 'start a new Ray cluster with optional Slurm or local worker configuration via the POST /start-cluster endpoint', 'get the status and benchmark statistics for a checkpoint evaluation job by its job ID']
```

Usage

```
{'start_ray_cluster': 'start a Ray cluster with optional Slurm workers and Grafana monitoring enabled', 'stop_ray_cluster': 'stop the running Ray cluster and release all allocated resources', 'check_cluster_status': 'check the status of the Ray cluster including head node and Serve applications', 'deploy_applications': 'deploy applications like vLLM serving or LLM proxy to the Ray cluster', 'run_llm_inference': 'run batch LLM inference on input JSONL or Hugging Face datasets using a deployed app'}
```

## File: facebookresearch_matrix/matrix/matrix_server.py

Prompts

```
['start a Ray cluster with optional Slurm workers and Grafana monitoring enabled', 'stop the running Ray cluster and release all allocated resources', 'check the status of the Ray cluster including head node and Serve applications', 'deploy applications like vLLM serving or LLM proxy to the Ray cluster', 'run batch LLM inference on input JSONL or Hugging Face datasets using a deployed app', 'start a FastAPI server on port 6289 to manage Matrix clusters and jobs via HTTP endpoints', 'submit a new job with task definitions to the Matrix JobManager via the POST /jobs endpoint', 'submit a checkpoint evaluation job that runs benchmarks on a model checkpoint across multiple seeds', 'start a new Ray cluster with optional Slurm or local worker configuration via the POST /start-cluster endpoint', 'get the status and benchmark statistics for a checkpoint evaluation job by its job ID']
```

Usage

```
{'start_matrix_server': 'start a FastAPI server on port 6289 to manage Matrix clusters and jobs via HTTP endpoints', 'submit_job': 'submit a new job with task definitions to the Matrix JobManager via the POST /jobs endpoint', 'evaluate_checkpoint': 'submit a checkpoint evaluation job that runs benchmarks on a model checkpoint across multiple seeds', 'start_cluster': 'start a new Ray cluster with optional Slurm or local worker configuration via the POST /start-cluster endpoint', 'get_checkpoint_eval_metrics': 'get the status and benchmark statistics for a checkpoint evaluation job by its job ID'}
```

