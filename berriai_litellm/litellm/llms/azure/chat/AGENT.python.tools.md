# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/azure/chat/gpt_5_transformation.py

Prompts

```
['test the AzureOpenAIGPT5Config.is_model_gpt_5_model method to check if a model string refers to a gpt-5 variant', 'test the AzureOpenAIGPT5Config._supports_reasoning_effort_level method to validate reasoning effort levels for gpt-5 models', 'test the AzureOpenAIGPT5Config.get_supported_openai_params method to retrieve supported parameters for Azure OpenAI GPT-5 models', 'test the AzureOpenAIGPT5Config.map_openai_params method to map and validate OpenAI parameters for Azure GPT-5 reasoning effort', 'test the AzureOpenAIGPT5Config.transform_request method to strip gpt5_series prefix and transform the request for Azure GPT-5 models', 'transform chat request messages for Azure OpenAI by converting message format and merging optional params', 'map OpenAI chat params to Azure-compatible params with API version checks for tool_choice and response_format', 'get the list of supported OpenAI parameters for Azure OpenAI chat completions', 'get the AzureOpenAI error class for a given error message, status code, and response headers', 'get the Azure OpenAI configuration object with supported parameters like temperature, max_tokens, and stop sequences', 'create an Azure OpenAI o1/o3 model chat completion handler instance', 'test the AzureOpenAIO1ChatCompletion completion method with model and messages', 'review the get_azure_openai_client method used to obtain the Azure OpenAI client', 'summarize the Azure OpenAI o1/o3 family model chat completion handler', 'refactor the BaseAzureLLM base class usage in the o-series handler', 'build an Azure OpenAI O-Series config that translates model parameters for o1 and o3 families', 'test the AzureOpenAIO1Config.get_supported_openai_params method to filter unsupported params', 'review the AzureOpenAIO1Config.should_fake_stream method for streaming emulation logic', 'summarize the AzureOpenAIO1Config.is_o_series_model method for detecting o1, o3, and o4 models', 'refactor the AzureOpenAIO1Config.transform_request method to handle o_series prefix stripping']
```

Usage

```
{'test_AzureOpenAIGPT5Config_is_model_gpt_5_model': 'test the AzureOpenAIGPT5Config.is_model_gpt_5_model method to check if a model string refers to a gpt-5 variant', 'test_AzureOpenAIGPT5Config__supports_reasoning_effort_level': 'test the AzureOpenAIGPT5Config._supports_reasoning_effort_level method to validate reasoning effort levels for gpt-5 models', 'test_AzureOpenAIGPT5Config_get_supported_openai_params': 'test the AzureOpenAIGPT5Config.get_supported_openai_params method to retrieve supported parameters for Azure OpenAI GPT-5 models', 'test_AzureOpenAIGPT5Config_map_openai_params': 'test the AzureOpenAIGPT5Config.map_openai_params method to map and validate OpenAI parameters for Azure GPT-5 reasoning effort', 'test_AzureOpenAIGPT5Config_transform_request': 'test the AzureOpenAIGPT5Config.transform_request method to strip gpt5_series prefix and transform the request for Azure GPT-5 models'}
```

## File: berriai_litellm/litellm/llms/azure/chat/gpt_transformation.py

Prompts

```
['test the AzureOpenAIGPT5Config.is_model_gpt_5_model method to check if a model string refers to a gpt-5 variant', 'test the AzureOpenAIGPT5Config._supports_reasoning_effort_level method to validate reasoning effort levels for gpt-5 models', 'test the AzureOpenAIGPT5Config.get_supported_openai_params method to retrieve supported parameters for Azure OpenAI GPT-5 models', 'test the AzureOpenAIGPT5Config.map_openai_params method to map and validate OpenAI parameters for Azure GPT-5 reasoning effort', 'test the AzureOpenAIGPT5Config.transform_request method to strip gpt5_series prefix and transform the request for Azure GPT-5 models', 'transform chat request messages for Azure OpenAI by converting message format and merging optional params', 'map OpenAI chat params to Azure-compatible params with API version checks for tool_choice and response_format', 'get the list of supported OpenAI parameters for Azure OpenAI chat completions', 'get the AzureOpenAI error class for a given error message, status code, and response headers', 'get the Azure OpenAI configuration object with supported parameters like temperature, max_tokens, and stop sequences', 'create an Azure OpenAI o1/o3 model chat completion handler instance', 'test the AzureOpenAIO1ChatCompletion completion method with model and messages', 'review the get_azure_openai_client method used to obtain the Azure OpenAI client', 'summarize the Azure OpenAI o1/o3 family model chat completion handler', 'refactor the BaseAzureLLM base class usage in the o-series handler', 'build an Azure OpenAI O-Series config that translates model parameters for o1 and o3 families', 'test the AzureOpenAIO1Config.get_supported_openai_params method to filter unsupported params', 'review the AzureOpenAIO1Config.should_fake_stream method for streaming emulation logic', 'summarize the AzureOpenAIO1Config.is_o_series_model method for detecting o1, o3, and o4 models', 'refactor the AzureOpenAIO1Config.transform_request method to handle o_series prefix stripping']
```

Usage

```
{'transform_request': 'transform chat request messages for Azure OpenAI by converting message format and merging optional params', 'map_openai_params': 'map OpenAI chat params to Azure-compatible params with API version checks for tool_choice and response_format', 'get_supported_openai_params': 'get the list of supported OpenAI parameters for Azure OpenAI chat completions', 'get_error_class': 'get the AzureOpenAI error class for a given error message, status code, and response headers', 'get_config': 'get the Azure OpenAI configuration object with supported parameters like temperature, max_tokens, and stop sequences'}
```

## File: berriai_litellm/litellm/llms/azure/chat/o_series_handler.py

Prompts

```
['test the AzureOpenAIGPT5Config.is_model_gpt_5_model method to check if a model string refers to a gpt-5 variant', 'test the AzureOpenAIGPT5Config._supports_reasoning_effort_level method to validate reasoning effort levels for gpt-5 models', 'test the AzureOpenAIGPT5Config.get_supported_openai_params method to retrieve supported parameters for Azure OpenAI GPT-5 models', 'test the AzureOpenAIGPT5Config.map_openai_params method to map and validate OpenAI parameters for Azure GPT-5 reasoning effort', 'test the AzureOpenAIGPT5Config.transform_request method to strip gpt5_series prefix and transform the request for Azure GPT-5 models', 'transform chat request messages for Azure OpenAI by converting message format and merging optional params', 'map OpenAI chat params to Azure-compatible params with API version checks for tool_choice and response_format', 'get the list of supported OpenAI parameters for Azure OpenAI chat completions', 'get the AzureOpenAI error class for a given error message, status code, and response headers', 'get the Azure OpenAI configuration object with supported parameters like temperature, max_tokens, and stop sequences', 'create an Azure OpenAI o1/o3 model chat completion handler instance', 'test the AzureOpenAIO1ChatCompletion completion method with model and messages', 'review the get_azure_openai_client method used to obtain the Azure OpenAI client', 'summarize the Azure OpenAI o1/o3 family model chat completion handler', 'refactor the BaseAzureLLM base class usage in the o-series handler', 'build an Azure OpenAI O-Series config that translates model parameters for o1 and o3 families', 'test the AzureOpenAIO1Config.get_supported_openai_params method to filter unsupported params', 'review the AzureOpenAIO1Config.should_fake_stream method for streaming emulation logic', 'summarize the AzureOpenAIO1Config.is_o_series_model method for detecting o1, o3, and o4 models', 'refactor the AzureOpenAIO1Config.transform_request method to handle o_series prefix stripping']
```

Usage

```
{'create_azure_o1_chat_completion': 'create an Azure OpenAI o1/o3 model chat completion handler instance', 'test_completion_method': 'test the AzureOpenAIO1ChatCompletion completion method with model and messages', 'review_azure_openai_client': 'review the get_azure_openai_client method used to obtain the Azure OpenAI client', 'summarize_o_series_handler': 'summarize the Azure OpenAI o1/o3 family model chat completion handler', 'refactor_base_azure_llm': 'refactor the BaseAzureLLM base class usage in the o-series handler'}
```

## File: berriai_litellm/litellm/llms/azure/chat/o_series_transformation.py

Prompts

```
['test the AzureOpenAIGPT5Config.is_model_gpt_5_model method to check if a model string refers to a gpt-5 variant', 'test the AzureOpenAIGPT5Config._supports_reasoning_effort_level method to validate reasoning effort levels for gpt-5 models', 'test the AzureOpenAIGPT5Config.get_supported_openai_params method to retrieve supported parameters for Azure OpenAI GPT-5 models', 'test the AzureOpenAIGPT5Config.map_openai_params method to map and validate OpenAI parameters for Azure GPT-5 reasoning effort', 'test the AzureOpenAIGPT5Config.transform_request method to strip gpt5_series prefix and transform the request for Azure GPT-5 models', 'transform chat request messages for Azure OpenAI by converting message format and merging optional params', 'map OpenAI chat params to Azure-compatible params with API version checks for tool_choice and response_format', 'get the list of supported OpenAI parameters for Azure OpenAI chat completions', 'get the AzureOpenAI error class for a given error message, status code, and response headers', 'get the Azure OpenAI configuration object with supported parameters like temperature, max_tokens, and stop sequences', 'create an Azure OpenAI o1/o3 model chat completion handler instance', 'test the AzureOpenAIO1ChatCompletion completion method with model and messages', 'review the get_azure_openai_client method used to obtain the Azure OpenAI client', 'summarize the Azure OpenAI o1/o3 family model chat completion handler', 'refactor the BaseAzureLLM base class usage in the o-series handler', 'build an Azure OpenAI O-Series config that translates model parameters for o1 and o3 families', 'test the AzureOpenAIO1Config.get_supported_openai_params method to filter unsupported params', 'review the AzureOpenAIO1Config.should_fake_stream method for streaming emulation logic', 'summarize the AzureOpenAIO1Config.is_o_series_model method for detecting o1, o3, and o4 models', 'refactor the AzureOpenAIO1Config.transform_request method to handle o_series prefix stripping']
```

Usage

```
{'build_azure_o_series_config': 'build an Azure OpenAI O-Series config that translates model parameters for o1 and o3 families', 'test_get_supported_openai_params': 'test the AzureOpenAIO1Config.get_supported_openai_params method to filter unsupported params', 'review_should_fake_stream': 'review the AzureOpenAIO1Config.should_fake_stream method for streaming emulation logic', 'summarize_is_o_series_model': 'summarize the AzureOpenAIO1Config.is_o_series_model method for detecting o1, o3, and o4 models', 'refactor_transform_request': 'refactor the AzureOpenAIO1Config.transform_request method to handle o_series prefix stripping'}
```

