# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/sap/chat/handler.py

Prompts

```
['test the sync SAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx streaming response', 'test the async AsyncSAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx async streaming response', 'test the _StreamParser class that normalizes orchestration streaming events into OpenAI-like chunks', 'test the GenAIHubOrchestrationError exception class that carries status_code and message from the LLM provider', 'test the GenAIHubOrchestration LLM handler class that adds stream parameters to request bodies', 'build an OrchestrationRequest with modules for prompt templating, filtering, and grounding', 'create a FunctionTool with name, description, and JSON schema parameters for SAP Orchestration Service', 'create a SAPUserMessage with text and image content for multimodal chat conversations', 'create a MaskingModuleConfig with anonymization providers for PII data masking', 'create a FilteringModuleConfig with input and output content safety filters', 'build an OpenAI chat completion request to SAP GenAI Hub Orchestration v2/completion format', 'transform a raw SAP GenAI Hub HTTP response into a LiteLLM ModelResponse object', 'get the SAP GenAI Hub orchestration deployment URL for a given model', 'convert a list of OpenAI-style chat messages to SAP GenAI Hub template format', 'extract tools, response format, and stream configuration from optional parameters']
```

Usage

```
{'test_SAPStreamIterator': 'test the sync SAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx streaming response', 'test_AsyncSAPStreamIterator': 'test the async AsyncSAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx async streaming response', 'test_StreamParser': 'test the _StreamParser class that normalizes orchestration streaming events into OpenAI-like chunks', 'test_GenAIHubOrchestrationError': 'test the GenAIHubOrchestrationError exception class that carries status_code and message from the LLM provider', 'test_GenAIHubOrchestration': 'test the GenAIHubOrchestration LLM handler class that adds stream parameters to request bodies'}
```

## File: berriai_litellm/litellm/llms/sap/chat/models.py

Prompts

```
['test the sync SAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx streaming response', 'test the async AsyncSAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx async streaming response', 'test the _StreamParser class that normalizes orchestration streaming events into OpenAI-like chunks', 'test the GenAIHubOrchestrationError exception class that carries status_code and message from the LLM provider', 'test the GenAIHubOrchestration LLM handler class that adds stream parameters to request bodies', 'build an OrchestrationRequest with modules for prompt templating, filtering, and grounding', 'create a FunctionTool with name, description, and JSON schema parameters for SAP Orchestration Service', 'create a SAPUserMessage with text and image content for multimodal chat conversations', 'create a MaskingModuleConfig with anonymization providers for PII data masking', 'create a FilteringModuleConfig with input and output content safety filters', 'build an OpenAI chat completion request to SAP GenAI Hub Orchestration v2/completion format', 'transform a raw SAP GenAI Hub HTTP response into a LiteLLM ModelResponse object', 'get the SAP GenAI Hub orchestration deployment URL for a given model', 'convert a list of OpenAI-style chat messages to SAP GenAI Hub template format', 'extract tools, response format, and stream configuration from optional parameters']
```

Usage

```
{'build_OrchestrationRequest': 'build an OrchestrationRequest with modules for prompt templating, filtering, and grounding', 'create_FunctionTool': 'create a FunctionTool with name, description, and JSON schema parameters for SAP Orchestration Service', 'create_SAPUserMessage': 'create a SAPUserMessage with text and image content for multimodal chat conversations', 'create_MaskingModuleConfig': 'create a MaskingModuleConfig with anonymization providers for PII data masking', 'create_FilteringModuleConfig': 'create a FilteringModuleConfig with input and output content safety filters'}
```

## File: berriai_litellm/litellm/llms/sap/chat/transformation.py

Prompts

```
['test the sync SAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx streaming response', 'test the async AsyncSAPStreamIterator that yields OpenAIChatCompletionChunk from an httpx async streaming response', 'test the _StreamParser class that normalizes orchestration streaming events into OpenAI-like chunks', 'test the GenAIHubOrchestrationError exception class that carries status_code and message from the LLM provider', 'test the GenAIHubOrchestration LLM handler class that adds stream parameters to request bodies', 'build an OrchestrationRequest with modules for prompt templating, filtering, and grounding', 'create a FunctionTool with name, description, and JSON schema parameters for SAP Orchestration Service', 'create a SAPUserMessage with text and image content for multimodal chat conversations', 'create a MaskingModuleConfig with anonymization providers for PII data masking', 'create a FilteringModuleConfig with input and output content safety filters', 'build an OpenAI chat completion request to SAP GenAI Hub Orchestration v2/completion format', 'transform a raw SAP GenAI Hub HTTP response into a LiteLLM ModelResponse object', 'get the SAP GenAI Hub orchestration deployment URL for a given model', 'convert a list of OpenAI-style chat messages to SAP GenAI Hub template format', 'extract tools, response format, and stream configuration from optional parameters']
```

Usage

```
{'build_sap_orchestration_request': 'build an OpenAI chat completion request to SAP GenAI Hub Orchestration v2/completion format', 'transform_sap_response': 'transform a raw SAP GenAI Hub HTTP response into a LiteLLM ModelResponse object', 'get_sap_orchestration_url': 'get the SAP GenAI Hub orchestration deployment URL for a given model', 'convert_messages_to_sap_template': 'convert a list of OpenAI-style chat messages to SAP GenAI Hub template format', 'extract_tools_and_stream_config': 'extract tools, response format, and stream configuration from optional parameters'}
```

