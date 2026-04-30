# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/gemini/cost_calculator.py

Prompts

```
['calculate the cost of a web search request for Vertex AI Gemini using usage and model_info objects', 'test cost_per_web_search_request returns $0.035 when usage has PromptTokensDetailsWrapper', 'refactor cost_per_web_search_request to extract the web search detection logic into a helper function', 'review cost_per_web_search_request for Vertex AI Gemini web search cost calculation', 'summarize cost_per_web_search_request that charges $35 per 1000 web search prompts for Vertex AI Gemini', 'transform OpenAI format messages into a Gemini Vertex AI request body with generation config, tools, and safety settings', 'convert a list of OpenAI-format messages to Gemini ContentType format handling tool calls, images, and multi-part content', 'process an image, audio, or video URL into a Gemini PartType with proper mime type and GCS URI support', 'extract system messages from OpenAI messages and convert them to Gemini SystemInstructions format', 'extract the highest media resolution detail level from OpenAI-format messages for Gemini 2.x global config', 'create a Vertex AI Gemini completion call using the VertexLLM completion method with streaming enabled', 'build Vertex AI Gemini API configuration by mapping OpenAI params to Vertex AI format with temperature and tool settings', 'test the ModelResponseIterator class for parsing streaming chunks from Vertex AI Gemini API responses', 'refactor the VertexGeminiConfig._map_function to transform OpenAI-style tools to Vertex AI format for function calling', 'summarize the VertexGeminiConfig.transform_response method that converts Google GenerateContent responses to OpenAI model response format']
```

Usage

```
{'calculate_cost_per_web_search_request': 'calculate the cost of a web search request for Vertex AI Gemini using usage and model_info objects', 'test_cost_per_web_search_request': 'test cost_per_web_search_request returns $0.035 when usage has PromptTokensDetailsWrapper', 'refactor_cost_per_web_search_request': 'refactor cost_per_web_search_request to extract the web search detection logic into a helper function', 'review_cost_per_web_search_request': 'review cost_per_web_search_request for Vertex AI Gemini web search cost calculation', 'summarize_cost_per_web_search_request': 'summarize cost_per_web_search_request that charges $35 per 1000 web search prompts for Vertex AI Gemini'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/gemini/transformation.py

Prompts

```
['calculate the cost of a web search request for Vertex AI Gemini using usage and model_info objects', 'test cost_per_web_search_request returns $0.035 when usage has PromptTokensDetailsWrapper', 'refactor cost_per_web_search_request to extract the web search detection logic into a helper function', 'review cost_per_web_search_request for Vertex AI Gemini web search cost calculation', 'summarize cost_per_web_search_request that charges $35 per 1000 web search prompts for Vertex AI Gemini', 'transform OpenAI format messages into a Gemini Vertex AI request body with generation config, tools, and safety settings', 'convert a list of OpenAI-format messages to Gemini ContentType format handling tool calls, images, and multi-part content', 'process an image, audio, or video URL into a Gemini PartType with proper mime type and GCS URI support', 'extract system messages from OpenAI messages and convert them to Gemini SystemInstructions format', 'extract the highest media resolution detail level from OpenAI-format messages for Gemini 2.x global config', 'create a Vertex AI Gemini completion call using the VertexLLM completion method with streaming enabled', 'build Vertex AI Gemini API configuration by mapping OpenAI params to Vertex AI format with temperature and tool settings', 'test the ModelResponseIterator class for parsing streaming chunks from Vertex AI Gemini API responses', 'refactor the VertexGeminiConfig._map_function to transform OpenAI-style tools to Vertex AI format for function calling', 'summarize the VertexGeminiConfig.transform_response method that converts Google GenerateContent responses to OpenAI model response format']
```

Usage

```
{'transform_request_body': 'transform OpenAI format messages into a Gemini Vertex AI request body with generation config, tools, and safety settings', 'convert_messages_with_history': 'convert a list of OpenAI-format messages to Gemini ContentType format handling tool calls, images, and multi-part content', 'process_gemini_media': 'process an image, audio, or video URL into a Gemini PartType with proper mime type and GCS URI support', 'transform_system_message': 'extract system messages from OpenAI messages and convert them to Gemini SystemInstructions format', 'extract_max_media_resolution': 'extract the highest media resolution detail level from OpenAI-format messages for Gemini 2.x global config'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/gemini/vertex_and_google_ai_studio_gemini.py

Prompts

```
['calculate the cost of a web search request for Vertex AI Gemini using usage and model_info objects', 'test cost_per_web_search_request returns $0.035 when usage has PromptTokensDetailsWrapper', 'refactor cost_per_web_search_request to extract the web search detection logic into a helper function', 'review cost_per_web_search_request for Vertex AI Gemini web search cost calculation', 'summarize cost_per_web_search_request that charges $35 per 1000 web search prompts for Vertex AI Gemini', 'transform OpenAI format messages into a Gemini Vertex AI request body with generation config, tools, and safety settings', 'convert a list of OpenAI-format messages to Gemini ContentType format handling tool calls, images, and multi-part content', 'process an image, audio, or video URL into a Gemini PartType with proper mime type and GCS URI support', 'extract system messages from OpenAI messages and convert them to Gemini SystemInstructions format', 'extract the highest media resolution detail level from OpenAI-format messages for Gemini 2.x global config', 'create a Vertex AI Gemini completion call using the VertexLLM completion method with streaming enabled', 'build Vertex AI Gemini API configuration by mapping OpenAI params to Vertex AI format with temperature and tool settings', 'test the ModelResponseIterator class for parsing streaming chunks from Vertex AI Gemini API responses', 'refactor the VertexGeminiConfig._map_function to transform OpenAI-style tools to Vertex AI format for function calling', 'summarize the VertexGeminiConfig.transform_response method that converts Google GenerateContent responses to OpenAI model response format']
```

Usage

```
{'create_vertex_gemini_completion': 'create a Vertex AI Gemini completion call using the VertexLLM completion method with streaming enabled', 'build_vertex_gemini_config': 'build Vertex AI Gemini API configuration by mapping OpenAI params to Vertex AI format with temperature and tool settings', 'test_model_response_iterator': 'test the ModelResponseIterator class for parsing streaming chunks from Vertex AI Gemini API responses', 'refactor_vertex_gemini_tools': 'refactor the VertexGeminiConfig._map_function to transform OpenAI-style tools to Vertex AI format for function calling', 'summarize_transform_response': 'summarize the VertexGeminiConfig.transform_response method that converts Google GenerateContent responses to OpenAI model response format'}
```

