# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/socket/main.py

Prompts

```
['build a Socket.IO ASGI server with Redis pub/sub support for real-time chat and collaborative document editing', 'create an event emitter function that broadcasts chat events to a specific user and updates the database with message content', 'create an event caller function that sends a request to a specific session and returns the response', 'emit a Socket.IO event to multiple users by their user IDs using user-prefixed rooms', 'join a collaborative Yjs document room for a note with access control validation and sync document state', 'run periodic cleanup of the usage pool to remove timed-out model connections and free resources', 'get the list of model IDs currently tracked in the usage pool', 'build a Redis distributed lock using RedisLock to safely acquire, renew, and release locks across processes', 'create a Redis-backed dictionary using RedisDict that supports dict-like operations with JSON serialization', 'test the YdocManager class for managing CRDT document updates and user tracking in Redis', 'review the YdocManager append_to_updates and get_updates methods for storing and retrieving document delta updates', 'refactor the YdocManager add_user, remove_user, and remove_user_from_all_documents methods for concurrent user session tracking']
```

Usage

```
{'build_websocket_server': 'build a Socket.IO ASGI server with Redis pub/sub support for real-time chat and collaborative document editing', 'create_event_emitter': 'create an event emitter function that broadcasts chat events to a specific user and updates the database with message content', 'create_event_caller': 'create an event caller function that sends a request to a specific session and returns the response', 'emit_to_users': 'emit a Socket.IO event to multiple users by their user IDs using user-prefixed rooms', 'join_note_document': 'join a collaborative Yjs document room for a note with access control validation and sync document state', 'periodic_usage_pool_cleanup': 'run periodic cleanup of the usage pool to remove timed-out model connections and free resources', 'get_models_in_use': 'get the list of model IDs currently tracked in the usage pool'}
```

## File: open-webui_open-webui/backend/open_webui/socket/utils.py

Prompts

```
['build a Socket.IO ASGI server with Redis pub/sub support for real-time chat and collaborative document editing', 'create an event emitter function that broadcasts chat events to a specific user and updates the database with message content', 'create an event caller function that sends a request to a specific session and returns the response', 'emit a Socket.IO event to multiple users by their user IDs using user-prefixed rooms', 'join a collaborative Yjs document room for a note with access control validation and sync document state', 'run periodic cleanup of the usage pool to remove timed-out model connections and free resources', 'get the list of model IDs currently tracked in the usage pool', 'build a Redis distributed lock using RedisLock to safely acquire, renew, and release locks across processes', 'create a Redis-backed dictionary using RedisDict that supports dict-like operations with JSON serialization', 'test the YdocManager class for managing CRDT document updates and user tracking in Redis', 'review the YdocManager append_to_updates and get_updates methods for storing and retrieving document delta updates', 'refactor the YdocManager add_user, remove_user, and remove_user_from_all_documents methods for concurrent user session tracking']
```

Usage

```
{'build_redis_lock': 'build a Redis distributed lock using RedisLock to safely acquire, renew, and release locks across processes', 'create_redis_dict': 'create a Redis-backed dictionary using RedisDict that supports dict-like operations with JSON serialization', 'test_ydoc_manager': 'test the YdocManager class for managing CRDT document updates and user tracking in Redis', 'review_ydoc_update_flow': 'review the YdocManager append_to_updates and get_updates methods for storing and retrieving document delta updates', 'refactor_ydoc_user_management': 'refactor the YdocManager add_user, remove_user, and remove_user_from_all_documents methods for concurrent user session tracking'}
```

