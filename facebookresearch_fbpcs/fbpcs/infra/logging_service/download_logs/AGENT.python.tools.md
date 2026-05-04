# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/infra/logging_service/download_logs/download_logs.py

Prompts

```
['build a python module to download container logs from AWS CloudWatch and upload them as a compressed archive to an S3 bucket', 'build a python module to concurrently download logs for multiple container ARNs using a configurable thread pool', "build a python module to fetch a single container's CloudWatch logs and write them to a local file", 'build a python module to parse an ECS container ARN and extract the service name, container name, and container ID', 'build a python module to copy compressed log files from a temporary directory to a local destination for debugging', 'run the CLI to download container logs from CloudWatch and upload archived logs to S3', 'extract container ID and instance ID mappings from a private computation CLI log file', 'parse an S3 bucket name from a full S3 URL or plain bucket name string', 'export container info CSV lines to a temporary file for inclusion in the log archive', 'run the CLI with the get_deployment_logs flag to fetch and add deployment logs to the archive']
```

Usage

```
{'upload_logs_to_s3_from_cloudwatch': 'build a python module to download container logs from AWS CloudWatch and upload them as a compressed archive to an S3 bucket', 'run_threaded_download': 'build a python module to concurrently download logs for multiple container ARNs using a configurable thread pool', 'store_container_logs_locally': "build a python module to fetch a single container's CloudWatch logs and write them to a local file", 'parse_container_arn': 'build a python module to parse an ECS container ARN and extract the service name, container name, and container ID', 'copy_logs_for_debug': 'build a python module to copy compressed log files from a temporary directory to a local destination for debugging'}
```

## File: facebookresearch_fbpcs/fbpcs/infra/logging_service/download_logs/download_logs_cli.py

Prompts

```
['build a python module to download container logs from AWS CloudWatch and upload them as a compressed archive to an S3 bucket', 'build a python module to concurrently download logs for multiple container ARNs using a configurable thread pool', "build a python module to fetch a single container's CloudWatch logs and write them to a local file", 'build a python module to parse an ECS container ARN and extract the service name, container name, and container ID', 'build a python module to copy compressed log files from a temporary directory to a local destination for debugging', 'run the CLI to download container logs from CloudWatch and upload archived logs to S3', 'extract container ID and instance ID mappings from a private computation CLI log file', 'parse an S3 bucket name from a full S3 URL or plain bucket name string', 'export container info CSV lines to a temporary file for inclusion in the log archive', 'run the CLI with the get_deployment_logs flag to fetch and add deployment logs to the archive']
```

Usage

```
{'run_download_logs_cli': 'run the CLI to download container logs from CloudWatch and upload archived logs to S3', 'extract_container_infos': 'extract container ID and instance ID mappings from a private computation CLI log file', 'get_s3_bucket_name': 'parse an S3 bucket name from a full S3 URL or plain bucket name string', 'export_container_info': 'export container info CSV lines to a temporary file for inclusion in the log archive', 'run_download_logs_with_deployment_logs': 'run the CLI with the get_deployment_logs flag to fetch and add deployment logs to the archive'}
```

