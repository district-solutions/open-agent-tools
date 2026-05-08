# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/hitl/dashboard_app/backend/dashboard_aws_helper.py

Prompts

```
['list all HITL job batch IDs from the S3 bucket by scanning timestamp-based prefixes', 'download and retrieve the traceback CSV log for a given HITL batch ID from S3', 'retrieve the JSON run info record for a given HITL batch ID from S3', 'list all interaction session names for a given HITL batch ID from the S3 bucket', 'download the best model checkpoint for a given HITL batch ID from S3 and load it', 'load a PyTorch model from a file path using torch.load', 'get all keys from a loaded model dictionary', 'retrieve and JSON-serialize a specific value from the model dictionary by key', 'serialize the entire model dictionary into a JSON string for socket transport', 'review the dashboard model utilities for loading and serializing PyTorch model data', 'run the flask socketio server for the HITL dashboard backend app', 'get a list of past job batch IDs stored on AWS via the socketio endpoint', 'get run metadata and HIT job statistics for a given batch ID', 'get a list of interaction session names for a given batch ID', 'get a specific model value or the complete model dict by batch ID and key']
```

Usage

```
{'get_job_list': 'list all HITL job batch IDs from the S3 bucket by scanning timestamp-based prefixes', 'get_traceback_by_id': 'download and retrieve the traceback CSV log for a given HITL batch ID from S3', 'get_run_info_by_id': 'retrieve the JSON run info record for a given HITL batch ID from S3', 'get_interaction_sessions_by_id': 'list all interaction session names for a given HITL batch ID from the S3 bucket', 'get_model_by_id': 'download the best model checkpoint for a given HITL batch ID from S3 and load it'}
```

## File: facebookresearch_fairo/droidlet/tools/hitl/dashboard_app/backend/dashboard_model_utils.py

Prompts

```
['list all HITL job batch IDs from the S3 bucket by scanning timestamp-based prefixes', 'download and retrieve the traceback CSV log for a given HITL batch ID from S3', 'retrieve the JSON run info record for a given HITL batch ID from S3', 'list all interaction session names for a given HITL batch ID from the S3 bucket', 'download the best model checkpoint for a given HITL batch ID from S3 and load it', 'load a PyTorch model from a file path using torch.load', 'get all keys from a loaded model dictionary', 'retrieve and JSON-serialize a specific value from the model dictionary by key', 'serialize the entire model dictionary into a JSON string for socket transport', 'review the dashboard model utilities for loading and serializing PyTorch model data', 'run the flask socketio server for the HITL dashboard backend app', 'get a list of past job batch IDs stored on AWS via the socketio endpoint', 'get run metadata and HIT job statistics for a given batch ID', 'get a list of interaction session names for a given batch ID', 'get a specific model value or the complete model dict by batch ID and key']
```

Usage

```
{'load_model_from_file': 'load a PyTorch model from a file path using torch.load', 'get_model_keys': 'get all keys from a loaded model dictionary', 'get_value_by_key': 'retrieve and JSON-serialize a specific value from the model dictionary by key', 'get_complete_model_json': 'serialize the entire model dictionary into a JSON string for socket transport', 'review_model_utils': 'review the dashboard model utilities for loading and serializing PyTorch model data'}
```

## File: facebookresearch_fairo/droidlet/tools/hitl/dashboard_app/backend/dashboard_server.py

Prompts

```
['list all HITL job batch IDs from the S3 bucket by scanning timestamp-based prefixes', 'download and retrieve the traceback CSV log for a given HITL batch ID from S3', 'retrieve the JSON run info record for a given HITL batch ID from S3', 'list all interaction session names for a given HITL batch ID from the S3 bucket', 'download the best model checkpoint for a given HITL batch ID from S3 and load it', 'load a PyTorch model from a file path using torch.load', 'get all keys from a loaded model dictionary', 'retrieve and JSON-serialize a specific value from the model dictionary by key', 'serialize the entire model dictionary into a JSON string for socket transport', 'review the dashboard model utilities for loading and serializing PyTorch model data', 'run the flask socketio server for the HITL dashboard backend app', 'get a list of past job batch IDs stored on AWS via the socketio endpoint', 'get run metadata and HIT job statistics for a given batch ID', 'get a list of interaction session names for a given batch ID', 'get a specific model value or the complete model dict by batch ID and key']
```

Usage

```
{'run_flask_socketio_dashboard_server': 'run the flask socketio server for the HITL dashboard backend app', 'get_jobs_from_aws': 'get a list of past job batch IDs stored on AWS via the socketio endpoint', 'get_run_info_by_batch_id': 'get run metadata and HIT job statistics for a given batch ID', 'get_interaction_sessions_by_batch_id': 'get a list of interaction session names for a given batch ID', 'get_model_value_by_batch_id_and_key': 'get a specific model value or the complete model dict by batch ID and key'}
```

