# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/examples/007-python-generative-media/client.py

Prompts

```
['run the actionengine client to generate images from text prompts via WebRTC stream', 'create an action registry that registers echo and text_to_image action schemas', 'configure global actionengine settings for auto-deserialization and ordered reader chunks', 'create a WebRTC stream connection to the actionengine demo server for action dispatching', 'consume the generated image output from a text_to_image action and save to file', 'build a FastAPI app that serves an Action Engine HTTP API with echo, generate content, and session management endpoints', 'create a new chat session and send a message to get a generated response with session token', 'stream a chat response as server-sent events with thoughts and output fragments from a session', 'follow a session to receive real-time updates on new messages and thoughts via server-sent events', 'resolve a session token to get the session ID and next message and thought sequence numbers', 'run the action engine memory client with a session token and fact node id via CLI', 'call the infer_updated_facts action over a WebRTC stream and stream back updated facts', 'dispatch a session from a WebRTC stream connected to the action engine server', 'run the redis client example that writes and reads text chunks using actionengine', 'write a text chunk to a redis key at a given offset using the action engine', 'read text chunks from a redis key by offset and count using the action engine', 'configure the action engine global settings for auto-deserialize ordered reads and chunk removal', 'run the Action Engine WebRTC server with configurable host and signalling server settings', 'register echo, gemini, memory, text-to-image, OCR, and SAM actions into the ActionRegistry', 'set up WebRTC TURN server credentials for the signalling server connection', 'set API key and timed peer token headers on the WebRTC server for authentication']
```

Usage

```
{'run_text_to_image_client': 'run the actionengine client to generate images from text prompts via WebRTC stream', 'create_action_registry': 'create an action registry that registers echo and text_to_image action schemas', 'setup_action_engine_settings': 'configure global actionengine settings for auto-deserialization and ordered reader chunks', 'make_webrtc_stream': 'create a WebRTC stream connection to the actionengine demo server for action dispatching', 'consume_generated_image': 'consume the generated image output from a text_to_image action and save to file'}
```

## File: google-deepmind_actionengine/examples/007-python-generative-media/httpapi.py

Prompts

```
['run the actionengine client to generate images from text prompts via WebRTC stream', 'create an action registry that registers echo and text_to_image action schemas', 'configure global actionengine settings for auto-deserialization and ordered reader chunks', 'create a WebRTC stream connection to the actionengine demo server for action dispatching', 'consume the generated image output from a text_to_image action and save to file', 'build a FastAPI app that serves an Action Engine HTTP API with echo, generate content, and session management endpoints', 'create a new chat session and send a message to get a generated response with session token', 'stream a chat response as server-sent events with thoughts and output fragments from a session', 'follow a session to receive real-time updates on new messages and thoughts via server-sent events', 'resolve a session token to get the session ID and next message and thought sequence numbers', 'run the action engine memory client with a session token and fact node id via CLI', 'call the infer_updated_facts action over a WebRTC stream and stream back updated facts', 'dispatch a session from a WebRTC stream connected to the action engine server', 'run the redis client example that writes and reads text chunks using actionengine', 'write a text chunk to a redis key at a given offset using the action engine', 'read text chunks from a redis key by offset and count using the action engine', 'configure the action engine global settings for auto-deserialize ordered reads and chunk removal', 'run the Action Engine WebRTC server with configurable host and signalling server settings', 'register echo, gemini, memory, text-to-image, OCR, and SAM actions into the ActionRegistry', 'set up WebRTC TURN server credentials for the signalling server connection', 'set API key and timed peer token headers on the WebRTC server for authentication']
```

Usage

```
{'build_fastapi_action_engine_http_api': 'build a FastAPI app that serves an Action Engine HTTP API with echo, generate content, and session management endpoints', 'create_session_and_send_message': 'create a new chat session and send a message to get a generated response with session token', 'stream_chat_response_with_sse': 'stream a chat response as server-sent events with thoughts and output fragments from a session', 'follow_session_updates_via_sse': 'follow a session to receive real-time updates on new messages and thoughts via server-sent events', 'resolve_session_token_to_info': 'resolve a session token to get the session ID and next message and thought sequence numbers'}
```

## File: google-deepmind_actionengine/examples/007-python-generative-media/memory_client.py

Prompts

```
['run the actionengine client to generate images from text prompts via WebRTC stream', 'create an action registry that registers echo and text_to_image action schemas', 'configure global actionengine settings for auto-deserialization and ordered reader chunks', 'create a WebRTC stream connection to the actionengine demo server for action dispatching', 'consume the generated image output from a text_to_image action and save to file', 'build a FastAPI app that serves an Action Engine HTTP API with echo, generate content, and session management endpoints', 'create a new chat session and send a message to get a generated response with session token', 'stream a chat response as server-sent events with thoughts and output fragments from a session', 'follow a session to receive real-time updates on new messages and thoughts via server-sent events', 'resolve a session token to get the session ID and next message and thought sequence numbers', 'run the action engine memory client with a session token and fact node id via CLI', 'call the infer_updated_facts action over a WebRTC stream and stream back updated facts', 'dispatch a session from a WebRTC stream connected to the action engine server', 'run the redis client example that writes and reads text chunks using actionengine', 'write a text chunk to a redis key at a given offset using the action engine', 'read text chunks from a redis key by offset and count using the action engine', 'configure the action engine global settings for auto-deserialize ordered reads and chunk removal', 'run the Action Engine WebRTC server with configurable host and signalling server settings', 'register echo, gemini, memory, text-to-image, OCR, and SAM actions into the ActionRegistry', 'set up WebRTC TURN server credentials for the signalling server connection', 'set API key and timed peer token headers on the WebRTC server for authentication']
```

Usage

```
{'run_memory_client': 'run the action engine memory client with a session token and fact node id via CLI', 'create_action_registry': 'create an action registry that registers the infer_updated_facts action schema', 'setup_action_engine_settings': 'configure action engine global settings for automatic deserialization and ordered reading', 'call_infer_updated_facts': 'call the infer_updated_facts action over a WebRTC stream and stream back updated facts', 'dispatch_session_from_webrtc': 'dispatch a session from a WebRTC stream connected to the action engine server'}
```

## File: google-deepmind_actionengine/examples/007-python-generative-media/redis_client.py

Prompts

```
['run the actionengine client to generate images from text prompts via WebRTC stream', 'create an action registry that registers echo and text_to_image action schemas', 'configure global actionengine settings for auto-deserialization and ordered reader chunks', 'create a WebRTC stream connection to the actionengine demo server for action dispatching', 'consume the generated image output from a text_to_image action and save to file', 'build a FastAPI app that serves an Action Engine HTTP API with echo, generate content, and session management endpoints', 'create a new chat session and send a message to get a generated response with session token', 'stream a chat response as server-sent events with thoughts and output fragments from a session', 'follow a session to receive real-time updates on new messages and thoughts via server-sent events', 'resolve a session token to get the session ID and next message and thought sequence numbers', 'run the action engine memory client with a session token and fact node id via CLI', 'call the infer_updated_facts action over a WebRTC stream and stream back updated facts', 'dispatch a session from a WebRTC stream connected to the action engine server', 'run the redis client example that writes and reads text chunks using actionengine', 'write a text chunk to a redis key at a given offset using the action engine', 'read text chunks from a redis key by offset and count using the action engine', 'configure the action engine global settings for auto-deserialize ordered reads and chunk removal', 'run the Action Engine WebRTC server with configurable host and signalling server settings', 'register echo, gemini, memory, text-to-image, OCR, and SAM actions into the ActionRegistry', 'set up WebRTC TURN server credentials for the signalling server connection', 'set API key and timed peer token headers on the WebRTC server for authentication']
```

Usage

```
{'run_redis_client': 'run the redis client example that writes and reads text chunks using actionengine', 'create_action_registry': 'create an action registry that registers read_store and write_store redis actions', 'write_text_chunk': 'write a text chunk to a redis key at a given offset using the action engine', 'read_text_chunks': 'read text chunks from a redis key by offset and count using the action engine', 'setup_action_engine': 'configure the action engine global settings for auto-deserialize ordered reads and chunk removal'}
```

## File: google-deepmind_actionengine/examples/007-python-generative-media/server.py

Prompts

```
['run the actionengine client to generate images from text prompts via WebRTC stream', 'create an action registry that registers echo and text_to_image action schemas', 'configure global actionengine settings for auto-deserialization and ordered reader chunks', 'create a WebRTC stream connection to the actionengine demo server for action dispatching', 'consume the generated image output from a text_to_image action and save to file', 'build a FastAPI app that serves an Action Engine HTTP API with echo, generate content, and session management endpoints', 'create a new chat session and send a message to get a generated response with session token', 'stream a chat response as server-sent events with thoughts and output fragments from a session', 'follow a session to receive real-time updates on new messages and thoughts via server-sent events', 'resolve a session token to get the session ID and next message and thought sequence numbers', 'run the action engine memory client with a session token and fact node id via CLI', 'call the infer_updated_facts action over a WebRTC stream and stream back updated facts', 'dispatch a session from a WebRTC stream connected to the action engine server', 'run the redis client example that writes and reads text chunks using actionengine', 'write a text chunk to a redis key at a given offset using the action engine', 'read text chunks from a redis key by offset and count using the action engine', 'configure the action engine global settings for auto-deserialize ordered reads and chunk removal', 'run the Action Engine WebRTC server with configurable host and signalling server settings', 'register echo, gemini, memory, text-to-image, OCR, and SAM actions into the ActionRegistry', 'set up WebRTC TURN server credentials for the signalling server connection', 'set API key and timed peer token headers on the WebRTC server for authentication']
```

Usage

```
{'run_webrtc_server': 'run the Action Engine WebRTC server with configurable host and signalling server settings', 'register_actions': 'register echo, gemini, memory, text-to-image, OCR, and SAM actions into the ActionRegistry', 'setup_action_engine': 'configure global Action Engine settings for automatic deserialization and read chunk handling', 'configure_turn_servers': 'set up WebRTC TURN server credentials for the signalling server connection', 'set_signalling_headers': 'set API key and timed peer token headers on the WebRTC server for authentication'}
```

