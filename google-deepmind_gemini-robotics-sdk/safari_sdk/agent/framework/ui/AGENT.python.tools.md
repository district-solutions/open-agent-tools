# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/ui/default_ui.py

Prompts

```
['create a TranscriptBuffer with a flush callback and timeout to buffer transcript fragments', 'append text fragments to a TranscriptBuffer that auto flushes after a timeout period', 'flush a TranscriptBuffer to immediately send all buffered text to the callback', 'clear a TranscriptBuffer without flushing to discard all buffered text fragments', 'handle an event_bus Event by printing it to the terminal with color-coded formatting', 'handle a MODEL_TURN event to buffer and display model text in the robotics UI chatbox', 'handle a TOOL_CALL event to display the instruction from function call arguments in the UI', 'handle a TOOL_RESULT event to display success or failure status in the robotics UI', 'handle a TOOL_CALL_CANCELLATION event to display a cancellation message in the robotics UI', 'send a formatted message string to the robotics UI chatbox via the framework client', 'parse a user input message into an event bus event with special prefix handling', 'create a TerminalUI instance that subscribes to model turn and tool call events on the event bus', 'connect the terminal UI to the event bus and start the text input listener loop', 'disconnect the terminal UI from the event bus and cancel all pending async tasks', 'run an async loop that reads user text input and publishes parsed events to the event bus']
```

Usage

```
{'create_TranscriptBuffer': 'create a TranscriptBuffer with a flush callback and timeout to buffer transcript fragments', 'append_TranscriptBuffer': 'append text fragments to a TranscriptBuffer that auto flushes after a timeout period', 'flush_TranscriptBuffer': 'flush a TranscriptBuffer to immediately send all buffered text to the callback', 'clear_TranscriptBuffer': 'clear a TranscriptBuffer without flushing to discard all buffered text fragments', 'handle_event': 'handle an event_bus Event by printing it to the terminal with color-coded formatting'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/ui/operator_text_ui.py

Prompts

```
['create a TranscriptBuffer with a flush callback and timeout to buffer transcript fragments', 'append text fragments to a TranscriptBuffer that auto flushes after a timeout period', 'flush a TranscriptBuffer to immediately send all buffered text to the callback', 'clear a TranscriptBuffer without flushing to discard all buffered text fragments', 'handle an event_bus Event by printing it to the terminal with color-coded formatting', 'handle a MODEL_TURN event to buffer and display model text in the robotics UI chatbox', 'handle a TOOL_CALL event to display the instruction from function call arguments in the UI', 'handle a TOOL_RESULT event to display success or failure status in the robotics UI', 'handle a TOOL_CALL_CANCELLATION event to display a cancellation message in the robotics UI', 'send a formatted message string to the robotics UI chatbox via the framework client', 'parse a user input message into an event bus event with special prefix handling', 'create a TerminalUI instance that subscribes to model turn and tool call events on the event bus', 'connect the terminal UI to the event bus and start the text input listener loop', 'disconnect the terminal UI from the event bus and cancel all pending async tasks', 'run an async loop that reads user text input and publishes parsed events to the event bus']
```

Usage

```
{'handle_event_model_turn': 'handle a MODEL_TURN event to buffer and display model text in the robotics UI chatbox', 'handle_event_tool_call': 'handle a TOOL_CALL event to display the instruction from function call arguments in the UI', 'handle_event_tool_result': 'handle a TOOL_RESULT event to display success or failure status in the robotics UI', 'handle_event_tool_cancellation': 'handle a TOOL_CALL_CANCELLATION event to display a cancellation message in the robotics UI', 'send_to_robotics_ui': 'send a formatted message string to the robotics UI chatbox via the framework client'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/ui/terminal_ui.py

Prompts

```
['create a TranscriptBuffer with a flush callback and timeout to buffer transcript fragments', 'append text fragments to a TranscriptBuffer that auto flushes after a timeout period', 'flush a TranscriptBuffer to immediately send all buffered text to the callback', 'clear a TranscriptBuffer without flushing to discard all buffered text fragments', 'handle an event_bus Event by printing it to the terminal with color-coded formatting', 'handle a MODEL_TURN event to buffer and display model text in the robotics UI chatbox', 'handle a TOOL_CALL event to display the instruction from function call arguments in the UI', 'handle a TOOL_RESULT event to display success or failure status in the robotics UI', 'handle a TOOL_CALL_CANCELLATION event to display a cancellation message in the robotics UI', 'send a formatted message string to the robotics UI chatbox via the framework client', 'parse a user input message into an event bus event with special prefix handling', 'create a TerminalUI instance that subscribes to model turn and tool call events on the event bus', 'connect the terminal UI to the event bus and start the text input listener loop', 'disconnect the terminal UI from the event bus and cancel all pending async tasks', 'run an async loop that reads user text input and publishes parsed events to the event bus']
```

Usage

```
{'parse_user_input_to_event': 'parse a user input message into an event bus event with special prefix handling', 'TerminalUI_init': 'create a TerminalUI instance that subscribes to model turn and tool call events on the event bus', 'TerminalUI_connect': 'connect the terminal UI to the event bus and start the text input listener loop', 'TerminalUI_disconnect': 'disconnect the terminal UI from the event bus and cancel all pending async tasks', 'TerminalUI_text_input_loop': 'run an async loop that reads user text input and publishes parsed events to the event bus'}
```

