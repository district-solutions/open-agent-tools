# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/agents/agent.py

Prompts

```
['create a subclass of Agent that implements _get_all_tools to register custom robotics tools', 'validate that a model name is compatible with the chosen streaming or non-streaming handler type', 'check if a model name indicates a Live API streaming-only model by searching for keyword matches', "connect the agent's handler and embodiment asynchronously to start the robotics agent session", 'create a LiveConnectConfigDict with tools, audio transcription, speech config, and context window compression', 'review the Handler protocol that defines the interface for API handlers with connect, disconnect, and register_event_subscribers methods', 'implement the async connect method on a Handler to establish a connection or activate the handler', 'implement the async disconnect method on a Handler to disconnect or deactivate the handler', 'implement the register_event_subscribers method on a Handler to subscribe to events from the event bus', 'use the Handler protocol to interchangeably work with both streaming GeminiLiveAPIHandler and non-streaming NonStreamingGenAIHandler implementations']
```

Usage

```
{'create_agent_subclass': 'create a subclass of Agent that implements _get_all_tools to register custom robotics tools', 'validate_model_mode_compatibility': 'validate that a model name is compatible with the chosen streaming or non-streaming handler type', 'is_live_model': 'check if a model name indicates a Live API streaming-only model by searching for keyword matches', 'connect_agent': "connect the agent's handler and embodiment asynchronously to start the robotics agent session", 'create_live_api_config': 'create a LiveConnectConfigDict with tools, audio transcription, speech config, and context window compression'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/agents/handler.py

Prompts

```
['create a subclass of Agent that implements _get_all_tools to register custom robotics tools', 'validate that a model name is compatible with the chosen streaming or non-streaming handler type', 'check if a model name indicates a Live API streaming-only model by searching for keyword matches', "connect the agent's handler and embodiment asynchronously to start the robotics agent session", 'create a LiveConnectConfigDict with tools, audio transcription, speech config, and context window compression', 'review the Handler protocol that defines the interface for API handlers with connect, disconnect, and register_event_subscribers methods', 'implement the async connect method on a Handler to establish a connection or activate the handler', 'implement the async disconnect method on a Handler to disconnect or deactivate the handler', 'implement the register_event_subscribers method on a Handler to subscribe to events from the event bus', 'use the Handler protocol to interchangeably work with both streaming GeminiLiveAPIHandler and non-streaming NonStreamingGenAIHandler implementations']
```

Usage

```
{'review_Handler_protocol': 'review the Handler protocol that defines the interface for API handlers with connect, disconnect, and register_event_subscribers methods', 'implement_Handler_connect': 'implement the async connect method on a Handler to establish a connection or activate the handler', 'implement_Handler_disconnect': 'implement the async disconnect method on a Handler to disconnect or deactivate the handler', 'implement_Handler_register_event_subscribers': 'implement the register_event_subscribers method on a Handler to subscribe to events from the event bus', 'use_Handler_protocol': 'use the Handler protocol to interchangeably work with both streaming GeminiLiveAPIHandler and non-streaming NonStreamingGenAIHandler implementations'}
```

