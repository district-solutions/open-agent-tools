# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/core/jobs_registry/registry.py

Prompts

```
['create a JobsRegistry instance to store and manage scheduled jobs in an ordered dictionary', 'register a StopesJob into the JobsRegistry so it can be tracked and queried later', 'kill a running or pending job by its ID using the async kill_job method', 'segment all jobs in the registry by their current status like COMPLETED or FAILED', 'get a formatted log string of all registry jobs grouped by their status', 'create an ArrayJobInfo instance with a parent job ID and array index for tracking array jobs', 'review the StopesJob abstract kill_job method that terminates a running job and waits for completion', 'review the StopesJob abstract get_status method that returns a RegistryStatuses enum value for the job', 'review the StopesJob get_job_info_log method that returns a formatted one-line string of job metadata', 'create a NonIdentifiableJobType exception with a job ID and custom message when job type cannot be determined', 'create a SubmititJob instance wrapping a submitit.Job with registry index and StopesModule', 'get the current registry status of a SubmititJob by converting its SLURM state', 'kill a running SubmititJob asynchronously and wait until the job is fully terminated', 'convert a raw SLURM job status string into a RegistryStatuses enum value', 'map submitit SLURM job states to high-level registry statuses using the state dictionary']
```

Usage

```
{'create_JobsRegistry': 'create a JobsRegistry instance to store and manage scheduled jobs in an ordered dictionary', 'register_job': 'register a StopesJob into the JobsRegistry so it can be tracked and queried later', 'kill_job': 'kill a running or pending job by its ID using the async kill_job method', 'segment_registry_by_status': 'segment all jobs in the registry by their current status like COMPLETED or FAILED', 'get_log_for_registry_jobs_ordered_by_status': 'get a formatted log string of all registry jobs grouped by their status'}
```

## File: facebookresearch_stopes/stopes/core/jobs_registry/stopes_job.py

Prompts

```
['create a JobsRegistry instance to store and manage scheduled jobs in an ordered dictionary', 'register a StopesJob into the JobsRegistry so it can be tracked and queried later', 'kill a running or pending job by its ID using the async kill_job method', 'segment all jobs in the registry by their current status like COMPLETED or FAILED', 'get a formatted log string of all registry jobs grouped by their status', 'create an ArrayJobInfo instance with a parent job ID and array index for tracking array jobs', 'review the StopesJob abstract kill_job method that terminates a running job and waits for completion', 'review the StopesJob abstract get_status method that returns a RegistryStatuses enum value for the job', 'review the StopesJob get_job_info_log method that returns a formatted one-line string of job metadata', 'create a NonIdentifiableJobType exception with a job ID and custom message when job type cannot be determined', 'create a SubmititJob instance wrapping a submitit.Job with registry index and StopesModule', 'get the current registry status of a SubmititJob by converting its SLURM state', 'kill a running SubmititJob asynchronously and wait until the job is fully terminated', 'convert a raw SLURM job status string into a RegistryStatuses enum value', 'map submitit SLURM job states to high-level registry statuses using the state dictionary']
```

Usage

```
{'create_ArrayJobInfo': 'create an ArrayJobInfo instance with a parent job ID and array index for tracking array jobs', 'review_StopesJob_kill_job': 'review the StopesJob abstract kill_job method that terminates a running job and waits for completion', 'review_StopesJob_get_status': 'review the StopesJob abstract get_status method that returns a RegistryStatuses enum value for the job', 'review_StopesJob_get_job_info_log': 'review the StopesJob get_job_info_log method that returns a formatted one-line string of job metadata', 'create_NonIdentifiableJobType': 'create a NonIdentifiableJobType exception with a job ID and custom message when job type cannot be determined'}
```

## File: facebookresearch_stopes/stopes/core/jobs_registry/submitit_slurm_job.py

Prompts

```
['create a JobsRegistry instance to store and manage scheduled jobs in an ordered dictionary', 'register a StopesJob into the JobsRegistry so it can be tracked and queried later', 'kill a running or pending job by its ID using the async kill_job method', 'segment all jobs in the registry by their current status like COMPLETED or FAILED', 'get a formatted log string of all registry jobs grouped by their status', 'create an ArrayJobInfo instance with a parent job ID and array index for tracking array jobs', 'review the StopesJob abstract kill_job method that terminates a running job and waits for completion', 'review the StopesJob abstract get_status method that returns a RegistryStatuses enum value for the job', 'review the StopesJob get_job_info_log method that returns a formatted one-line string of job metadata', 'create a NonIdentifiableJobType exception with a job ID and custom message when job type cannot be determined', 'create a SubmititJob instance wrapping a submitit.Job with registry index and StopesModule', 'get the current registry status of a SubmititJob by converting its SLURM state', 'kill a running SubmititJob asynchronously and wait until the job is fully terminated', 'convert a raw SLURM job status string into a RegistryStatuses enum value', 'map submitit SLURM job states to high-level registry statuses using the state dictionary']
```

Usage

```
{'create_SubmititJob': 'create a SubmititJob instance wrapping a submitit.Job with registry index and StopesModule', 'get_status_SubmititJob': 'get the current registry status of a SubmititJob by converting its SLURM state', 'kill_job_SubmititJob': 'kill a running SubmititJob asynchronously and wait until the job is fully terminated', 'convert_slurm_status': 'convert a raw SLURM job status string into a RegistryStatuses enum value', 'map_submitit_states': 'map submitit SLURM job states to high-level registry statuses using the state dictionary'}
```

