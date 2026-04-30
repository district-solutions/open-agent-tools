# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/response_polling/polling_handler.py

Prompts

```
['create a polling response state in Redis cache with status queued and the given request data', 'update a polling response state in Redis cache with new status, output, usage, or error fields', 'get the current polling response state from Redis cache by polling ID', 'cancel a polling request by updating its status to cancelled in Redis cache', 'delete a polling response entry from Redis cache by polling ID', 'determine if polling via cache should be used for a background request based on provider and config']
```

Usage

```
{'create_initial_state': 'create a polling response state in Redis cache with status queued and the given request data', 'update_polling_state': 'update a polling response state in Redis cache with new status, output, usage, or error fields', 'get_polling_state': 'get the current polling response state from Redis cache by polling ID', 'cancel_polling_request': 'cancel a polling request by updating its status to cancelled in Redis cache', 'delete_polling_state': 'delete a polling response entry from Redis cache by polling ID', 'should_use_polling_for_request': 'determine if polling via cache should be used for a background request based on provider and config'}
```

