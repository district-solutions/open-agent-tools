# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/infra/logging_service/download_logs/test/test_download_logs.py

Prompts

```
['run the DownloadLogsCli to extract container IDs from a log file and upload logs to S3', 'test the AwsContainerLogs upload_logs_to_s3_from_cloudwatch method to fetch CloudWatch logs and upload to S3', 'test the AwsContainerLogs _parse_container_arn method to extract service name, container name, and ID from an ARN', 'test the AwsContainerLogs run_threaded_download method to download container logs concurrently using a thread pool', 'test the AwsContainerLogs ensure_folder_exists method to verify an S3 bucket folder contains objects']
```

Usage

```
{'run_download_logs_cli': 'run the DownloadLogsCli to extract container IDs from a log file and upload logs to S3', 'test_upload_logs_to_s3_from_cloudwatch': 'test the AwsContainerLogs upload_logs_to_s3_from_cloudwatch method to fetch CloudWatch logs and upload to S3', 'test_parse_container_arn': 'test the AwsContainerLogs _parse_container_arn method to extract service name, container name, and ID from an ARN', 'test_run_threaded_download': 'test the AwsContainerLogs run_threaded_download method to download container logs concurrently using a thread pool', 'test_ensure_folder_exists': 'test the AwsContainerLogs ensure_folder_exists method to verify an S3 bucket folder contains objects'}
```

