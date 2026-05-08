# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/hitl/turk_oncall/allocate_oncall_instances.py

Prompts

```
['allocate oncall ECS instances and register CloudFlare subdomains for a MTurk batch experiment', 'launch a single ECS Fargate task instance with a specified world config and batch ID', 'request multiple ECS instances and wait until they are all up and reachable', 'register an ECS task definition for a Docker image with port mappings and logging config', 'stop and free a list of running ECS task instances by their task ARNs', 'run the process_past_logs function to process TAO bug reports for a list of batch IDs', 'run the TaoBugReportJob class to extract tracebacks from agent logs and upload results to S3', 'run the TaoLogListener class to monitor S3 status files and trigger bug report jobs when logs are ready', 'run the oncall_bug_report module with argparse to process TAO job batch IDs via command line', 'review the TaoBugReportJob get_log_traceback method that parses agent.log files and extracts traceback blocks into a DataFrame', 'run an OnCallJob instance to spin up Turk-as-Oncall HITs and collect dashboard session logs', 'create an OnCallJob with a specified number of ECS instances, image tag, and timeout value', 'process S3 interaction logs for a batch and return a map of agent IDs to log directories', 'retrieve Mephisto local DB results for a task and upload summary stats to S3', 'get the unique batch ID generated for an OnCallJob instance']
```

Usage

```
{'allocate_oncall_instances': 'allocate oncall ECS instances and register CloudFlare subdomains for a MTurk batch experiment', 'launch_instance': 'launch a single ECS Fargate task instance with a specified world config and batch ID', 'request_instance': 'request multiple ECS instances and wait until they are all up and reachable', 'register_task_definition': 'register an ECS task definition for a Docker image with port mappings and logging config', 'free_ecs_instances': 'stop and free a list of running ECS task instances by their task ARNs'}
```

## File: facebookresearch_fairo/droidlet/tools/hitl/turk_oncall/oncall_bug_report.py

Prompts

```
['allocate oncall ECS instances and register CloudFlare subdomains for a MTurk batch experiment', 'launch a single ECS Fargate task instance with a specified world config and batch ID', 'request multiple ECS instances and wait until they are all up and reachable', 'register an ECS task definition for a Docker image with port mappings and logging config', 'stop and free a list of running ECS task instances by their task ARNs', 'run the process_past_logs function to process TAO bug reports for a list of batch IDs', 'run the TaoBugReportJob class to extract tracebacks from agent logs and upload results to S3', 'run the TaoLogListener class to monitor S3 status files and trigger bug report jobs when logs are ready', 'run the oncall_bug_report module with argparse to process TAO job batch IDs via command line', 'review the TaoBugReportJob get_log_traceback method that parses agent.log files and extracts traceback blocks into a DataFrame', 'run an OnCallJob instance to spin up Turk-as-Oncall HITs and collect dashboard session logs', 'create an OnCallJob with a specified number of ECS instances, image tag, and timeout value', 'process S3 interaction logs for a batch and return a map of agent IDs to log directories', 'retrieve Mephisto local DB results for a task and upload summary stats to S3', 'get the unique batch ID generated for an OnCallJob instance']
```

Usage

```
{'run_process_past_logs': 'run the process_past_logs function to process TAO bug reports for a list of batch IDs', 'run_TaoBugReportJob': 'run the TaoBugReportJob class to extract tracebacks from agent logs and upload results to S3', 'run_TaoLogListener': 'run the TaoLogListener class to monitor S3 status files and trigger bug report jobs when logs are ready', 'run_cli_oncall_bug_report': 'run the oncall_bug_report module with argparse to process TAO job batch IDs via command line', 'review_TaoBugReportJob_get_log_traceback': 'review the TaoBugReportJob get_log_traceback method that parses agent.log files and extracts traceback blocks into a DataFrame'}
```

## File: facebookresearch_fairo/droidlet/tools/hitl/turk_oncall/oncall_jobs.py

Prompts

```
['allocate oncall ECS instances and register CloudFlare subdomains for a MTurk batch experiment', 'launch a single ECS Fargate task instance with a specified world config and batch ID', 'request multiple ECS instances and wait until they are all up and reachable', 'register an ECS task definition for a Docker image with port mappings and logging config', 'stop and free a list of running ECS task instances by their task ARNs', 'run the process_past_logs function to process TAO bug reports for a list of batch IDs', 'run the TaoBugReportJob class to extract tracebacks from agent logs and upload results to S3', 'run the TaoLogListener class to monitor S3 status files and trigger bug report jobs when logs are ready', 'run the oncall_bug_report module with argparse to process TAO job batch IDs via command line', 'review the TaoBugReportJob get_log_traceback method that parses agent.log files and extracts traceback blocks into a DataFrame', 'run an OnCallJob instance to spin up Turk-as-Oncall HITs and collect dashboard session logs', 'create an OnCallJob with a specified number of ECS instances, image tag, and timeout value', 'process S3 interaction logs for a batch and return a map of agent IDs to log directories', 'retrieve Mephisto local DB results for a task and upload summary stats to S3', 'get the unique batch ID generated for an OnCallJob instance']
```

Usage

```
{'run_OnCallJob': 'run an OnCallJob instance to spin up Turk-as-Oncall HITs and collect dashboard session logs', 'create_OnCallJob': 'create an OnCallJob with a specified number of ECS instances, image tag, and timeout value', 'process_s3_logs': 'process S3 interaction logs for a batch and return a map of agent IDs to log directories', 'get_local_db_results': 'retrieve Mephisto local DB results for a task and upload summary stats to S3', 'get_batch_id': 'get the unique batch ID generated for an OnCallJob instance'}
```

