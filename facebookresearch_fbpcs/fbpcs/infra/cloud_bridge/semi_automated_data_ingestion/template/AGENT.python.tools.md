# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/infra/cloud_bridge/semi_automated_data_ingestion/template/lambda_trigger.py

Prompts

```
['run the lambda_handler function to trigger an AWS Glue job from an S3 upload event', 'start an AWS Glue job run with s3_read_path and s3_write_path arguments via boto3', 'extract the S3 bucket name and object key from an S3 event record', 'review the lambda_handler function to understand S3 event validation and Glue job triggering logic', 'refactor the lambda_handler to accept the Glue job name as a configurable parameter instead of a hardcoded variable']
```

Usage

```
{'run_lambda_handler': 'run the lambda_handler function to trigger an AWS Glue job from an S3 upload event', 'start_glue_job_run': 'start an AWS Glue job run with s3_read_path and s3_write_path arguments via boto3', 'extract_s3_info': 'extract the S3 bucket name and object key from an S3 event record', 'review_lambda_handler': 'review the lambda_handler function to understand S3 event validation and Glue job triggering logic', 'refactor_glue_job_name': 'refactor the lambda_handler to accept the Glue job name as a configurable parameter instead of a hardcoded variable'}
```

