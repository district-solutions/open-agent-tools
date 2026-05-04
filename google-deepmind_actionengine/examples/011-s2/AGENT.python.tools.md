# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/examples/011-s2/client.py

Prompts

```
['create an ActionRegistry and register an echo action schema with input and output ports', 'create an async Redis client using environment variables for host and port configuration', 'create a Redis-backed ChunkStore for a given node ID with no TTL expiration', 'send a message through an echo action via Redis and yield the output responses', 'run the async echo client that sends ten messages through the action engine pipeline', 'run an actionengine worker that listens on a redis queue and echoes input messages to output', 'build a redis chunk store with a given node id and no TTL for actionengine data persistence', 'listen on a redis queue and execute actions from incoming wire messages using an action registry', 'configure actionengine global settings to enable automatic deserialization and preserve read chunks']
```

Usage

```
{'create_action_registry': 'create an ActionRegistry and register an echo action schema with input and output ports', 'create_aioredis_client': 'create an async Redis client using environment variables for host and port configuration', 'create_redis_chunk_store': 'create a Redis-backed ChunkStore for a given node ID with no TTL expiration', 'call_echo_action': 'send a message through an echo action via Redis and yield the output responses', 'run_echo_client': 'run the async echo client that sends ten messages through the action engine pipeline'}
```

## File: google-deepmind_actionengine/examples/011-s2/worker.py

Prompts

```
['create an ActionRegistry and register an echo action schema with input and output ports', 'create an async Redis client using environment variables for host and port configuration', 'create a Redis-backed ChunkStore for a given node ID with no TTL expiration', 'send a message through an echo action via Redis and yield the output responses', 'run the async echo client that sends ten messages through the action engine pipeline', 'run an actionengine worker that listens on a redis queue and echoes input messages to output', 'build a redis chunk store with a given node id and no TTL for actionengine data persistence', 'listen on a redis queue and execute actions from incoming wire messages using an action registry', 'configure actionengine global settings to enable automatic deserialization and preserve read chunks']
```

Usage

```
{'run_echo_worker': 'run an actionengine worker that listens on a redis queue and echoes input messages to output', 'create_action_registry': 'create an action registry that registers an echo action with its schema and handler function', 'build_redis_chunk_store': 'build a redis chunk store with a given node id and no TTL for actionengine data persistence', 'listen_execute_actions': 'listen on a redis queue and execute actions from incoming wire messages using an action registry', 'configure_global_settings': 'configure actionengine global settings to enable automatic deserialization and preserve read chunks'}
```

