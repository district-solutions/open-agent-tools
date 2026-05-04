# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/embodiments/embodiment.py

Prompts

```
['create a subclass of Embodiment that implements _create_event_streams and _create_tools for a custom robot', 'implement _create_event_streams to return a list of EventStreamDefinition objects with name, stream, and is_image_stream fields', 'implement _create_tools to return a sequence of tool.Tool instances using the provided EventBus', 'call the async connect method on an Embodiment instance to start streaming robot events to the event bus', 'access the camera_stream_names property to retrieve a list of image stream names from an Embodiment', 'create a FastApiEndpoint dataclass instance with a path and optional response class for a FastAPI route', 'validate that a FastApiEndpoint path starts and ends with forward slashes using __post_init__', 'get a dictionary of FastAPI route arguments from a FastApiEndpoint using the args property', 'build a FastAPI route by unpacking FastApiEndpoint args into app.get or app.post decorators', 'review the FastApiEndpoint frozen dataclass and its path validation and args property']
```

Usage

```
{'create_embodiment_subclass': 'create a subclass of Embodiment that implements _create_event_streams and _create_tools for a custom robot', 'implement_event_stream_definitions': 'implement _create_event_streams to return a list of EventStreamDefinition objects with name, stream, and is_image_stream fields', 'implement_tool_creation': 'implement _create_tools to return a sequence of tool.Tool instances using the provided EventBus', 'connect_embodiment': 'call the async connect method on an Embodiment instance to start streaming robot events to the event bus', 'get_camera_stream_names': 'access the camera_stream_names property to retrieve a list of image stream names from an Embodiment'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/embodiments/fast_api_endpoint.py

Prompts

```
['create a subclass of Embodiment that implements _create_event_streams and _create_tools for a custom robot', 'implement _create_event_streams to return a list of EventStreamDefinition objects with name, stream, and is_image_stream fields', 'implement _create_tools to return a sequence of tool.Tool instances using the provided EventBus', 'call the async connect method on an Embodiment instance to start streaming robot events to the event bus', 'access the camera_stream_names property to retrieve a list of image stream names from an Embodiment', 'create a FastApiEndpoint dataclass instance with a path and optional response class for a FastAPI route', 'validate that a FastApiEndpoint path starts and ends with forward slashes using __post_init__', 'get a dictionary of FastAPI route arguments from a FastApiEndpoint using the args property', 'build a FastAPI route by unpacking FastApiEndpoint args into app.get or app.post decorators', 'review the FastApiEndpoint frozen dataclass and its path validation and args property']
```

Usage

```
{'create_fastapi_endpoint': 'create a FastApiEndpoint dataclass instance with a path and optional response class for a FastAPI route', 'validate_endpoint_path': 'validate that a FastApiEndpoint path starts and ends with forward slashes using __post_init__', 'get_endpoint_args': 'get a dictionary of FastAPI route arguments from a FastApiEndpoint using the args property', 'build_fastapi_route': 'build a FastAPI route by unpacking FastApiEndpoint args into app.get or app.post decorators', 'review_fastapi_endpoint_class': 'review the FastApiEndpoint frozen dataclass and its path validation and args property'}
```

