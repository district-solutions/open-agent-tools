# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/litellm_core_utils/llm_cost_calc/tool_call_cost_tracking.py

Prompts

```
['calculate the cost of built-in tools like web search, file search, and code interpreter from a model response', 'get the cost of a web search call based on search context size and model pricing', 'get the cost of a file search call using storage-based or per-call pricing', 'get the cost of computer use based on input and output token counts', 'get the cost of code interpreter sessions based on session count and provider pricing', 'test the TranscriptionUsageObjectTransformation.is_transcription_usage_object method to check if an object is a transcription usage type', 'transform a TranscriptionUsageTokensObject into a standard Usage object with prompt and completion token fields', 'build a transformation pipeline that converts transcription usage objects into standard Usage objects for cost calculation', 'review the TranscriptionUsageObjectTransformation.is_transcription_usage_object method for correct type checking logic', 'summarize how the transform_transcription_usage_object method maps transcription token details to Usage fields', 'calculate cost for a single usage component given model info, cost key, and usage value', 'calculate cache writing cost with support for 5m and 1h ephemeral cache token durations', 'calculate prompt and completion cost in USD for a model given usage and optional service tier', 'get billable input tokens by subtracting cached tokens from total prompt tokens', 'route image generation cost calculation to the correct provider-specific calculator']
```

Usage

```
{'calculate_built_in_tool_costs': 'calculate the cost of built-in tools like web search, file search, and code interpreter from a model response', 'get_cost_for_web_search': 'get the cost of a web search call based on search context size and model pricing', 'get_cost_for_file_search': 'get the cost of a file search call using storage-based or per-call pricing', 'get_cost_for_computer_use': 'get the cost of computer use based on input and output token counts', 'get_cost_for_code_interpreter': 'get the cost of code interpreter sessions based on session count and provider pricing'}
```

## File: berriai_litellm/litellm/litellm_core_utils/llm_cost_calc/usage_object_transformation.py

Prompts

```
['calculate the cost of built-in tools like web search, file search, and code interpreter from a model response', 'get the cost of a web search call based on search context size and model pricing', 'get the cost of a file search call using storage-based or per-call pricing', 'get the cost of computer use based on input and output token counts', 'get the cost of code interpreter sessions based on session count and provider pricing', 'test the TranscriptionUsageObjectTransformation.is_transcription_usage_object method to check if an object is a transcription usage type', 'transform a TranscriptionUsageTokensObject into a standard Usage object with prompt and completion token fields', 'build a transformation pipeline that converts transcription usage objects into standard Usage objects for cost calculation', 'review the TranscriptionUsageObjectTransformation.is_transcription_usage_object method for correct type checking logic', 'summarize how the transform_transcription_usage_object method maps transcription token details to Usage fields', 'calculate cost for a single usage component given model info, cost key, and usage value', 'calculate cache writing cost with support for 5m and 1h ephemeral cache token durations', 'calculate prompt and completion cost in USD for a model given usage and optional service tier', 'get billable input tokens by subtracting cached tokens from total prompt tokens', 'route image generation cost calculation to the correct provider-specific calculator']
```

Usage

```
{'test_is_transcription_usage_object': 'test the TranscriptionUsageObjectTransformation.is_transcription_usage_object method to check if an object is a transcription usage type', 'transform_transcription_usage_object': 'transform a TranscriptionUsageTokensObject into a standard Usage object with prompt and completion token fields', 'build_transform_transcription_usage': 'build a transformation pipeline that converts transcription usage objects into standard Usage objects for cost calculation', 'review_is_transcription_usage_object': 'review the TranscriptionUsageObjectTransformation.is_transcription_usage_object method for correct type checking logic', 'summarize_transform_transcription_usage_object': 'summarize how the transform_transcription_usage_object method maps transcription token details to Usage fields'}
```

## File: berriai_litellm/litellm/litellm_core_utils/llm_cost_calc/utils.py

Prompts

```
['calculate the cost of built-in tools like web search, file search, and code interpreter from a model response', 'get the cost of a web search call based on search context size and model pricing', 'get the cost of a file search call using storage-based or per-call pricing', 'get the cost of computer use based on input and output token counts', 'get the cost of code interpreter sessions based on session count and provider pricing', 'test the TranscriptionUsageObjectTransformation.is_transcription_usage_object method to check if an object is a transcription usage type', 'transform a TranscriptionUsageTokensObject into a standard Usage object with prompt and completion token fields', 'build a transformation pipeline that converts transcription usage objects into standard Usage objects for cost calculation', 'review the TranscriptionUsageObjectTransformation.is_transcription_usage_object method for correct type checking logic', 'summarize how the transform_transcription_usage_object method maps transcription token details to Usage fields', 'calculate cost for a single usage component given model info, cost key, and usage value', 'calculate cache writing cost with support for 5m and 1h ephemeral cache token durations', 'calculate prompt and completion cost in USD for a model given usage and optional service tier', 'get billable input tokens by subtracting cached tokens from total prompt tokens', 'route image generation cost calculation to the correct provider-specific calculator']
```

Usage

```
{'calculate_cost_component': 'calculate cost for a single usage component given model info, cost key, and usage value', 'calculate_cache_writing_cost': 'calculate cache writing cost with support for 5m and 1h ephemeral cache token durations', 'generic_cost_per_token': 'calculate prompt and completion cost in USD for a model given usage and optional service tier', 'get_billable_input_tokens': 'get billable input tokens by subtracting cached tokens from total prompt tokens', 'route_image_generation_cost_calculator': 'route image generation cost calculation to the correct provider-specific calculator'}
```

