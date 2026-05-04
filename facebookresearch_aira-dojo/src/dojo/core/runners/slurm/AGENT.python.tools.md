# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/core/runners/slurm/slurm_utils.py

Prompts

```
['submit a SLURM job using submitit with a command, job name, and resource parameters', 'retrieve stdout and stderr logs from a submitted SLURM job as lists of strings', 'observe a submitit job status and execute a callback when the job finishes', 'wait asynchronously for all observed SLURM jobs and their callbacks to complete', 'create a dataclass aggregating job ID, metadata, status, stdout, and stderr for a finished job']
```

Usage

```
{'submit_job': 'submit a SLURM job using submitit with a command, job name, and resource parameters', 'get_logs': 'retrieve stdout and stderr logs from a submitted SLURM job as lists of strings', 'JobObserver_observe': 'observe a submitit job status and execute a callback when the job finishes', 'JobObserver_wait': 'wait asynchronously for all observed SLURM jobs and their callbacks to complete', 'JobResult': 'create a dataclass aggregating job ID, metadata, status, stdout, and stderr for a finished job'}
```

