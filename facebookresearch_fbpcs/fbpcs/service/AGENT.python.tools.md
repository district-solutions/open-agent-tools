# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/service/workflow.py

Prompts

```
['implement a concrete subclass of WorkflowService that starts and tracks workflow execution', 'call start_workflow on a WorkflowService subclass to begin a workflow with a config and run ID', 'call get_workflow_status on a WorkflowService subclass to retrieve the current WorkflowStatus enum value', 'use the WorkflowStatus enum to check if a workflow is COMPLETED, FAILED, STARTED, CREATED, or UNKNOWN', 'review the WorkflowService abstract base class and its start_workflow and get_workflow_status abstract methods', 'create a python module to start an Airflow DAG workflow using AWS MWAA with a given run ID', 'create a python module to get the status of a running Airflow DAG workflow via MWAA', 'create a python module to trigger an Airflow CLI command against an MWAA environment using a CLI token', 'create a python module to parse and decode base64 encoded stdout and stderr from an MWAA CLI response', 'create a python module to parse and decode base64 encoded JSON stdout from an MWAA CLI response', 'create an SfnWorkflowService instance with AWS credentials and a region to manage Step Functions workflows', 'start a Step Functions workflow execution using a state machine ARN and optional run configuration', 'review the SfnReturnStatus enum that defines FAILED, RUNNING, SUCCEEDED, TIMED_OUT, and ABORTED states', 'refactor the SfnWorkflowService to support additional AWS Step Functions operations or credential providers']
```

Usage

```
{'implement_workflow_service': 'implement a concrete subclass of WorkflowService that starts and tracks workflow execution', 'start_workflow': 'call start_workflow on a WorkflowService subclass to begin a workflow with a config and run ID', 'get_workflow_status': 'call get_workflow_status on a WorkflowService subclass to retrieve the current WorkflowStatus enum value', 'use_workflow_status_enum': 'use the WorkflowStatus enum to check if a workflow is COMPLETED, FAILED, STARTED, CREATED, or UNKNOWN', 'review_workflow_service_abc': 'review the WorkflowService abstract base class and its start_workflow and get_workflow_status abstract methods'}
```

## File: facebookresearch_fbpcs/fbpcs/service/workflow_mwaa.py

Prompts

```
['implement a concrete subclass of WorkflowService that starts and tracks workflow execution', 'call start_workflow on a WorkflowService subclass to begin a workflow with a config and run ID', 'call get_workflow_status on a WorkflowService subclass to retrieve the current WorkflowStatus enum value', 'use the WorkflowStatus enum to check if a workflow is COMPLETED, FAILED, STARTED, CREATED, or UNKNOWN', 'review the WorkflowService abstract base class and its start_workflow and get_workflow_status abstract methods', 'create a python module to start an Airflow DAG workflow using AWS MWAA with a given run ID', 'create a python module to get the status of a running Airflow DAG workflow via MWAA', 'create a python module to trigger an Airflow CLI command against an MWAA environment using a CLI token', 'create a python module to parse and decode base64 encoded stdout and stderr from an MWAA CLI response', 'create a python module to parse and decode base64 encoded JSON stdout from an MWAA CLI response', 'create an SfnWorkflowService instance with AWS credentials and a region to manage Step Functions workflows', 'start a Step Functions workflow execution using a state machine ARN and optional run configuration', 'review the SfnReturnStatus enum that defines FAILED, RUNNING, SUCCEEDED, TIMED_OUT, and ABORTED states', 'refactor the SfnWorkflowService to support additional AWS Step Functions operations or credential providers']
```

Usage

```
{'start_workflow_mwaa': 'create a python module to start an Airflow DAG workflow using AWS MWAA with a given run ID', 'get_workflow_status_mwaa': 'create a python module to get the status of a running Airflow DAG workflow via MWAA', 'trigger_airflow_cli_mwaa': 'create a python module to trigger an Airflow CLI command against an MWAA environment using a CLI token', 'parse_response_plain_result_mwaa': 'create a python module to parse and decode base64 encoded stdout and stderr from an MWAA CLI response', 'parse_response_json_result_mwaa': 'create a python module to parse and decode base64 encoded JSON stdout from an MWAA CLI response'}
```

## File: facebookresearch_fbpcs/fbpcs/service/workflow_sfn.py

Prompts

```
['implement a concrete subclass of WorkflowService that starts and tracks workflow execution', 'call start_workflow on a WorkflowService subclass to begin a workflow with a config and run ID', 'call get_workflow_status on a WorkflowService subclass to retrieve the current WorkflowStatus enum value', 'use the WorkflowStatus enum to check if a workflow is COMPLETED, FAILED, STARTED, CREATED, or UNKNOWN', 'review the WorkflowService abstract base class and its start_workflow and get_workflow_status abstract methods', 'create a python module to start an Airflow DAG workflow using AWS MWAA with a given run ID', 'create a python module to get the status of a running Airflow DAG workflow via MWAA', 'create a python module to trigger an Airflow CLI command against an MWAA environment using a CLI token', 'create a python module to parse and decode base64 encoded stdout and stderr from an MWAA CLI response', 'create a python module to parse and decode base64 encoded JSON stdout from an MWAA CLI response', 'create an SfnWorkflowService instance with AWS credentials and a region to manage Step Functions workflows', 'start a Step Functions workflow execution using a state machine ARN and optional run configuration', 'review the SfnReturnStatus enum that defines FAILED, RUNNING, SUCCEEDED, TIMED_OUT, and ABORTED states', 'refactor the SfnWorkflowService to support additional AWS Step Functions operations or credential providers']
```

Usage

```
{'create_sfn_workflow_service': 'create an SfnWorkflowService instance with AWS credentials and a region to manage Step Functions workflows', 'start_workflow_execution': 'start a Step Functions workflow execution using a state machine ARN and optional run configuration', 'get_workflow_status': 'get the current status of a running Step Functions workflow execution by its execution ARN', 'review_sfn_return_status_enum': 'review the SfnReturnStatus enum that defines FAILED, RUNNING, SUCCEEDED, TIMED_OUT, and ABORTED states', 'refactor_sfn_workflow_service': 'refactor the SfnWorkflowService to support additional AWS Step Functions operations or credential providers'}
```

