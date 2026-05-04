# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/event_bus/audio_event_handler.py

Prompts

```
['create an AudioHandler instance with an EventBus to manage microphone recording and speaker playback', 'start the arecord subprocess and recording loop to capture 16kHz mono PCM audio from the microphone', 'start the aplay subprocess and playback loop to play 24kHz mono PCM audio to the speaker', 'connect the AudioHandler to start both recording and playback streams based on enabled flags', 'disconnect the AudioHandler to stop recording and playback subprocesses and cancel async tasks', 'create an EventBus instance with an AgentFrameworkConfig to manage async event publishing and dispatching', 'subscribe a handler function to one or more EventType values on the EventBus', 'publish an Event to the EventBus queue for async dispatch to registered handlers', 'start the EventBus event queue loop and initialize session logging with a generated agent session ID', 'shutdown the EventBus by cancelling the main task and all pending handler tasks with a timeout']
```

Usage

```
{'create_audio_handler': 'create an AudioHandler instance with an EventBus to manage microphone recording and speaker playback', 'start_recording': 'start the arecord subprocess and recording loop to capture 16kHz mono PCM audio from the microphone', 'start_playback': 'start the aplay subprocess and playback loop to play 24kHz mono PCM audio to the speaker', 'connect_audio': 'connect the AudioHandler to start both recording and playback streams based on enabled flags', 'disconnect_audio': 'disconnect the AudioHandler to stop recording and playback subprocesses and cancel async tasks'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/event_bus/event_bus.py

Prompts

```
['create an AudioHandler instance with an EventBus to manage microphone recording and speaker playback', 'start the arecord subprocess and recording loop to capture 16kHz mono PCM audio from the microphone', 'start the aplay subprocess and playback loop to play 24kHz mono PCM audio to the speaker', 'connect the AudioHandler to start both recording and playback streams based on enabled flags', 'disconnect the AudioHandler to stop recording and playback subprocesses and cancel async tasks', 'create an EventBus instance with an AgentFrameworkConfig to manage async event publishing and dispatching', 'subscribe a handler function to one or more EventType values on the EventBus', 'publish an Event to the EventBus queue for async dispatch to registered handlers', 'start the EventBus event queue loop and initialize session logging with a generated agent session ID', 'shutdown the EventBus by cancelling the main task and all pending handler tasks with a timeout']
```

Usage

```
{'create_event_bus': 'create an EventBus instance with an AgentFrameworkConfig to manage async event publishing and dispatching', 'subscribe_event_handlers': 'subscribe a handler function to one or more EventType values on the EventBus', 'publish_event': 'publish an Event to the EventBus queue for async dispatch to registered handlers', 'start_event_bus': 'start the EventBus event queue loop and initialize session logging with a generated agent session ID', 'shutdown_event_bus': 'shutdown the EventBus by cancelling the main task and all pending handler tasks with a timeout'}
```

