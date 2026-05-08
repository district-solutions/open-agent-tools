# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/hitl/nsp_retrain/annotation_jobs.py

Prompts

```
['run an AnnotationJob to annotate a text command via MTurk and upload results to S3', 'create an AnnotationJob instance with a Recorder, batch ID, command string, and timeout', 'upload the combined annotated command file from a batch to the droidlet-hitl S3 bucket', 'terminate a stuck MTurk annotation subprocess by sending SIGINT then SIGKILL on timeout', 'review the AnnotationJob class that extends DataGenerator for spinning up HITL annotation jobs', 'run an InteractionJob to spin up ECS instances and collect commands from Turkers via Mephisto', 'run an InteractionLogListener to poll S3 for new commands and create annotation jobs', 'process S3 logs from a batch to parse and collate commands into a single list', 'get the batch ID from an InteractionJob instance for tracking dashboard sessions', 'run a TaskRunner with an InteractionJob and InteractionLogListener to collect and annotate commands']
```

Usage

```
{'run_annotation_job': 'run an AnnotationJob to annotate a text command via MTurk and upload results to S3', 'create_annotation_job_instance': 'create an AnnotationJob instance with a Recorder, batch ID, command string, and timeout', 'upload_annotated_data_to_s3': 'upload the combined annotated command file from a batch to the droidlet-hitl S3 bucket', 'terminate_stuck_annotation_job': 'terminate a stuck MTurk annotation subprocess by sending SIGINT then SIGKILL on timeout', 'review_annotation_job_class': 'review the AnnotationJob class that extends DataGenerator for spinning up HITL annotation jobs'}
```

## File: facebookresearch_fairo/droidlet/tools/hitl/nsp_retrain/interaction_jobs.py

Prompts

```
['run an AnnotationJob to annotate a text command via MTurk and upload results to S3', 'create an AnnotationJob instance with a Recorder, batch ID, command string, and timeout', 'upload the combined annotated command file from a batch to the droidlet-hitl S3 bucket', 'terminate a stuck MTurk annotation subprocess by sending SIGINT then SIGKILL on timeout', 'review the AnnotationJob class that extends DataGenerator for spinning up HITL annotation jobs', 'run an InteractionJob to spin up ECS instances and collect commands from Turkers via Mephisto', 'run an InteractionLogListener to poll S3 for new commands and create annotation jobs', 'process S3 logs from a batch to parse and collate commands into a single list', 'get the batch ID from an InteractionJob instance for tracking dashboard sessions', 'run a TaskRunner with an InteractionJob and InteractionLogListener to collect and annotate commands']
```

Usage

```
{'run_interaction_job': 'run an InteractionJob to spin up ECS instances and collect commands from Turkers via Mephisto', 'run_interaction_log_listener': 'run an InteractionLogListener to poll S3 for new commands and create annotation jobs', 'process_s3_logs': 'process S3 logs from a batch to parse and collate commands into a single list', 'get_batch_id': 'get the batch ID from an InteractionJob instance for tracking dashboard sessions', 'run_interaction_pipeline': 'run a TaskRunner with an InteractionJob and InteractionLogListener to collect and annotate commands'}
```

