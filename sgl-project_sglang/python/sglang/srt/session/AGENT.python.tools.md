# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/session/session_controller.py

Prompts

```
['open a new session with a given session id, capacity, streaming flag, and timeout', 'close an existing session by session id, releasing its KV cache and multimodal features', 'create a session request that appends to or replaces previous session context', 'reap timed-out sessions and finish deferred closes for completed requests', 'adjust multimodal input offsets by the prefix length when prepending session context', 'create a StreamingSession cache wrapper around a BasePrefixCache to enable KV state persistence across streaming turns', 'save KV pool state from a finishing request into a SessionSlot for later restoration', 'restore KV pool state from a SessionSlot into an incoming streaming request', 'release and free all KV tokens held by a streaming session slot', 'match prefix tokens from a streaming session slot instead of the radix tree cache']
```

Usage

```
{'open_session': 'open a new session with a given session id, capacity, streaming flag, and timeout', 'close_session': 'close an existing session by session id, releasing its KV cache and multimodal features', 'create_session_request': 'create a session request that appends to or replaces previous session context', 'reap_timed_out_sessions': 'reap timed-out sessions and finish deferred closes for completed requests', 'adjust_multimodal_offsets': 'adjust multimodal input offsets by the prefix length when prepending session context'}
```

## File: sgl-project_sglang/python/sglang/srt/session/streaming_session.py

Prompts

```
['open a new session with a given session id, capacity, streaming flag, and timeout', 'close an existing session by session id, releasing its KV cache and multimodal features', 'create a session request that appends to or replaces previous session context', 'reap timed-out sessions and finish deferred closes for completed requests', 'adjust multimodal input offsets by the prefix length when prepending session context', 'create a StreamingSession cache wrapper around a BasePrefixCache to enable KV state persistence across streaming turns', 'save KV pool state from a finishing request into a SessionSlot for later restoration', 'restore KV pool state from a SessionSlot into an incoming streaming request', 'release and free all KV tokens held by a streaming session slot', 'match prefix tokens from a streaming session slot instead of the radix tree cache']
```

Usage

```
{'create_streaming_session_cache': 'create a StreamingSession cache wrapper around a BasePrefixCache to enable KV state persistence across streaming turns', 'save_session_kv_state': 'save KV pool state from a finishing request into a SessionSlot for later restoration', 'restore_session_kv_state': 'restore KV pool state from a SessionSlot into an incoming streaming request', 'release_session_kv': 'release and free all KV tokens held by a streaming session slot', 'match_streaming_prefix': 'match prefix tokens from a streaming session slot instead of the radix tree cache'}
```

