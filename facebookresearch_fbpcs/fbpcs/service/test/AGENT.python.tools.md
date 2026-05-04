# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/service/test/test_workflow_mwaa.py

Prompts

```
['create a python module to start an AWS MWAA Airflow DAG run with a given environment name and DAG ID', 'create a python module to start an MWAA workflow with custom configuration parameters passed to the DAG run', 'create a python module to get the current status of an MWAA workflow run by environment name and DAG ID', 'test the MwaaWorkflowService start_workflow method to handle existing run IDs and invalid DAG IDs gracefully', 'test the MwaaWorkflowService get_workflow_status method to return FAILED, STARTED, COMPLETED, CREATED, or UNKNOWN based on task states', 'test the SfnWorkflowService start_workflow method to start an AWS Step Functions execution with or without config', 'test the SfnWorkflowService get_workflow_status method to check execution status and return WorkflowStatus enum', 'test the SfnWorkflowService error handling when start_execution returns an errorMessage instead of executionArn', 'review the SfnWorkflowService class that wraps boto3 stepfunctions client for starting and monitoring workflow executions', 'summarize the WorkflowStatus enum with values UNKNOWN, CREATED, STARTED, COMPLETED, and FAILED']
```

Usage

```
{'start_workflow_mwaa': 'create a python module to start an AWS MWAA Airflow DAG run with a given environment name and DAG ID', 'start_workflow_with_conf': 'create a python module to start an MWAA workflow with custom configuration parameters passed to the DAG run', 'get_workflow_status_mwaa': 'create a python module to get the current status of an MWAA workflow run by environment name and DAG ID', 'test_start_workflow_error_handling': 'test the MwaaWorkflowService start_workflow method to handle existing run IDs and invalid DAG IDs gracefully', 'test_get_workflow_status_all_cases': 'test the MwaaWorkflowService get_workflow_status method to return FAILED, STARTED, COMPLETED, CREATED, or UNKNOWN based on task states'}
```

## File: facebookresearch_fbpcs/fbpcs/service/test/test_workflow_sfn.py

Prompts

```
['create a python module to start an AWS MWAA Airflow DAG run with a given environment name and DAG ID', 'create a python module to start an MWAA workflow with custom configuration parameters passed to the DAG run', 'create a python module to get the current status of an MWAA workflow run by environment name and DAG ID', 'test the MwaaWorkflowService start_workflow method to handle existing run IDs and invalid DAG IDs gracefully', 'test the MwaaWorkflowService get_workflow_status method to return FAILED, STARTED, COMPLETED, CREATED, or UNKNOWN based on task states', 'test the SfnWorkflowService start_workflow method to start an AWS Step Functions execution with or without config', 'test the SfnWorkflowService get_workflow_status method to check execution status and return WorkflowStatus enum', 'test the SfnWorkflowService error handling when start_execution returns an errorMessage instead of executionArn', 'review the SfnWorkflowService class that wraps boto3 stepfunctions client for starting and monitoring workflow executions', 'summarize the WorkflowStatus enum with values UNKNOWN, CREATED, STARTED, COMPLETED, and FAILED']
```

Usage

```
{'test_SfnWorkflowService_start_workflow': 'test the SfnWorkflowService start_workflow method to start an AWS Step Functions execution with or without config', 'test_SfnWorkflowService_get_workflow_status': 'test the SfnWorkflowService get_workflow_status method to check execution status and return WorkflowStatus enum', 'test_SfnWorkflowService_error_handling': 'test the SfnWorkflowService error handling when start_execution returns an errorMessage instead of executionArn', 'review_SfnWorkflowService': 'review the SfnWorkflowService class that wraps boto3 stepfunctions client for starting and monitoring workflow executions', 'summarize_WorkflowStatus': 'summarize the WorkflowStatus enum with values UNKNOWN, CREATED, STARTED, COMPLETED, and FAILED'}
```

