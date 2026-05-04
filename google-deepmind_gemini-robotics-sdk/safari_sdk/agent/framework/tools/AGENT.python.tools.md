# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/tools/genai_client.py

Prompts

```
['generate content using the GeminiClientWrapper async generate_content method with model and config', 'create a LocalFileLogger instance to write timestamped messages to log files in /tmp/genai_client_logs', 'check the GeminiClientHealth enum to track NORMAL, quota exceeded, overloaded, or other error states', 'configure a GeminiClientWrapper with an event bus, genai client, model name, and generation config', 'publish TOOL_CLIENT_HEALTH events to the event bus when Gemini client errors like 429 or 503 occur', 'create an ImageBuffer instance with camera endpoint names and an AgentFrameworkConfig', 'handle a MODEL_IMAGE_INPUT event to store image data in the buffer', 'get the latest images map as a dictionary of camera stream names to event deques', 'get the timestamp of the most recent image event across all camera streams', 'reset the latest images map to clear all stored image events', 'create a SubtaskSuccessDetectorV4 instance with an event bus, config, and API key', 'run detect_success on a subtask string to check if the robot completed it', 'build a multimodal prompt with start and latest camera images for success detection', 'query the Gemini model via _query_success_signal to evaluate task completion from camera views', 'set the timeout in seconds on an AbstractSuccessDetectionTool to limit how long success detection runs']
```

Usage

```
{'generate_content_gemini': 'generate content using the GeminiClientWrapper async generate_content method with model and config', 'create_local_file_logger': 'create a LocalFileLogger instance to write timestamped messages to log files in /tmp/genai_client_logs', 'check_gemini_client_health': 'check the GeminiClientHealth enum to track NORMAL, quota exceeded, overloaded, or other error states', 'configure_gemini_client_wrapper': 'configure a GeminiClientWrapper with an event bus, genai client, model name, and generation config', 'publish_health_events': 'publish TOOL_CLIENT_HEALTH events to the event bus when Gemini client errors like 429 or 503 occur'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/tools/image_buffer.py

Prompts

```
['generate content using the GeminiClientWrapper async generate_content method with model and config', 'create a LocalFileLogger instance to write timestamped messages to log files in /tmp/genai_client_logs', 'check the GeminiClientHealth enum to track NORMAL, quota exceeded, overloaded, or other error states', 'configure a GeminiClientWrapper with an event bus, genai client, model name, and generation config', 'publish TOOL_CLIENT_HEALTH events to the event bus when Gemini client errors like 429 or 503 occur', 'create an ImageBuffer instance with camera endpoint names and an AgentFrameworkConfig', 'handle a MODEL_IMAGE_INPUT event to store image data in the buffer', 'get the latest images map as a dictionary of camera stream names to event deques', 'get the timestamp of the most recent image event across all camera streams', 'reset the latest images map to clear all stored image events', 'create a SubtaskSuccessDetectorV4 instance with an event bus, config, and API key', 'run detect_success on a subtask string to check if the robot completed it', 'build a multimodal prompt with start and latest camera images for success detection', 'query the Gemini model via _query_success_signal to evaluate task completion from camera views', 'set the timeout in seconds on an AbstractSuccessDetectionTool to limit how long success detection runs']
```

Usage

```
{'create_image_buffer': 'create an ImageBuffer instance with camera endpoint names and an AgentFrameworkConfig', 'handle_model_image_input_event': 'handle a MODEL_IMAGE_INPUT event to store image data in the buffer', 'get_latest_images_map': 'get the latest images map as a dictionary of camera stream names to event deques', 'get_latest_image_timestamp': 'get the timestamp of the most recent image event across all camera streams', 'reset_latest_images_map': 'reset the latest images map to clear all stored image events'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/tools/success_detection.py

Prompts

```
['generate content using the GeminiClientWrapper async generate_content method with model and config', 'create a LocalFileLogger instance to write timestamped messages to log files in /tmp/genai_client_logs', 'check the GeminiClientHealth enum to track NORMAL, quota exceeded, overloaded, or other error states', 'configure a GeminiClientWrapper with an event bus, genai client, model name, and generation config', 'publish TOOL_CLIENT_HEALTH events to the event bus when Gemini client errors like 429 or 503 occur', 'create an ImageBuffer instance with camera endpoint names and an AgentFrameworkConfig', 'handle a MODEL_IMAGE_INPUT event to store image data in the buffer', 'get the latest images map as a dictionary of camera stream names to event deques', 'get the timestamp of the most recent image event across all camera streams', 'reset the latest images map to clear all stored image events', 'create a SubtaskSuccessDetectorV4 instance with an event bus, config, and API key', 'run detect_success on a subtask string to check if the robot completed it', 'build a multimodal prompt with start and latest camera images for success detection', 'query the Gemini model via _query_success_signal to evaluate task completion from camera views', 'set the timeout in seconds on an AbstractSuccessDetectionTool to limit how long success detection runs']
```

Usage

```
{'create_SubtaskSuccessDetectorV4': 'create a SubtaskSuccessDetectorV4 instance with an event bus, config, and API key', 'run_detect_success': 'run detect_success on a subtask string to check if the robot completed it', 'build_prompt_for_success_detection': 'build a multimodal prompt with start and latest camera images for success detection', 'query_success_signal': 'query the Gemini model via _query_success_signal to evaluate task completion from camera views', 'set_timeout_seconds': 'set the timeout in seconds on an AbstractSuccessDetectionTool to limit how long success detection runs'}
```

