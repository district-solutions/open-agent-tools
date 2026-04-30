# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/webhook/tests/routes/test_webhook.py

Prompts

```
['test the parse_payload function with various webhook event payloads to validate JSON schema', 'test the process_payload function to verify delete_dataset and update_dataset are called correctly', 'test parse_payload raises an exception when given an unrecognized webhook event type', 'test process_payload skips processing when the webhook scope is discussion.comment', 'test process_payload handles move events by using the movedTo field as the new dataset name']
```

Usage

```
{'test_parse_payload': 'test the parse_payload function with various webhook event payloads to validate JSON schema', 'test_process_payload': 'test the process_payload function to verify delete_dataset and update_dataset are called correctly', 'test_parse_payload_invalid_event': 'test parse_payload raises an exception when given an unrecognized webhook event type', 'test_process_payload_discussion_scope': 'test process_payload skips processing when the webhook scope is discussion.comment', 'test_process_payload_move_event': 'test process_payload handles move events by using the movedTo field as the new dataset name'}
```

