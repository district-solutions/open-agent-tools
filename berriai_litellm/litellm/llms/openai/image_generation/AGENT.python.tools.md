# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/image_generation/cost_calculator.py

Prompts

```
['calculate cost for OpenAI gpt-image-1 and gpt-image-1-mini models from an ImageResponse', 'calculate cost for gpt-image models with a custom LLM provider name', 'calculate cost for gpt-image models returning zero when usage data is missing', 'transform response API usage to chat completion usage format for cost calculation', 'calculate cost using generic token-based pricing for image generation models', 'review the DallE2ImageGenerationConfig class and its image generation configuration methods', 'test the get_supported_openai_params method returns the list of supported OpenAI image generation parameters', 'test the map_openai_params method maps non-default params with validation and drop_params behavior', 'test the transform_image_generation_response method transforms a raw httpx.Response into an ImageResponse object', 'review the map_openai_params method for parameter validation and unsupported parameter handling', 'review the DallE3ImageGenerationConfig class and its image generation configuration methods', 'build a DallE3ImageGenerationConfig instance to configure OpenAI dall-e-3 image generation with supported parameters', 'create a GPTImageGenerationConfig instance to configure OpenAI gpt-image-1 image generation', 'get the list of supported OpenAI parameters for gpt-image-1 image generation model', 'map non-default OpenAI params to optional params with validation and drop_params support', 'transform a raw httpx image generation response into a structured ImageResponse object', 'test the GPTImageGenerationConfig class and its parameter mapping and response transformation methods']
```

Usage

```
{'calculate_cost_gpt_image': 'calculate cost for OpenAI gpt-image-1 and gpt-image-1-mini models from an ImageResponse', 'calculate_cost_with_provider': 'calculate cost for gpt-image models with a custom LLM provider name', 'calculate_cost_no_usage': 'calculate cost for gpt-image models returning zero when usage data is missing', 'transform_response_api_usage': 'transform response API usage to chat completion usage format for cost calculation', 'calculate_cost_generic_token': 'calculate cost using generic token-based pricing for image generation models'}
```

## File: berriai_litellm/litellm/llms/openai/image_generation/dall_e_2_transformation.py

Prompts

```
['calculate cost for OpenAI gpt-image-1 and gpt-image-1-mini models from an ImageResponse', 'calculate cost for gpt-image models with a custom LLM provider name', 'calculate cost for gpt-image models returning zero when usage data is missing', 'transform response API usage to chat completion usage format for cost calculation', 'calculate cost using generic token-based pricing for image generation models', 'review the DallE2ImageGenerationConfig class and its image generation configuration methods', 'test the get_supported_openai_params method returns the list of supported OpenAI image generation parameters', 'test the map_openai_params method maps non-default params with validation and drop_params behavior', 'test the transform_image_generation_response method transforms a raw httpx.Response into an ImageResponse object', 'review the map_openai_params method for parameter validation and unsupported parameter handling', 'review the DallE3ImageGenerationConfig class and its image generation configuration methods', 'build a DallE3ImageGenerationConfig instance to configure OpenAI dall-e-3 image generation with supported parameters', 'create a GPTImageGenerationConfig instance to configure OpenAI gpt-image-1 image generation', 'get the list of supported OpenAI parameters for gpt-image-1 image generation model', 'map non-default OpenAI params to optional params with validation and drop_params support', 'transform a raw httpx image generation response into a structured ImageResponse object', 'test the GPTImageGenerationConfig class and its parameter mapping and response transformation methods']
```

Usage

```
{'review_DallE2ImageGenerationConfig': 'review the DallE2ImageGenerationConfig class and its image generation configuration methods', 'test_get_supported_openai_params': 'test the get_supported_openai_params method returns the list of supported OpenAI image generation parameters', 'test_map_openai_params': 'test the map_openai_params method maps non-default params with validation and drop_params behavior', 'test_transform_image_generation_response': 'test the transform_image_generation_response method transforms a raw httpx.Response into an ImageResponse object', 'review_map_openai_params': 'review the map_openai_params method for parameter validation and unsupported parameter handling'}
```

## File: berriai_litellm/litellm/llms/openai/image_generation/dall_e_3_transformation.py

Prompts

```
['calculate cost for OpenAI gpt-image-1 and gpt-image-1-mini models from an ImageResponse', 'calculate cost for gpt-image models with a custom LLM provider name', 'calculate cost for gpt-image models returning zero when usage data is missing', 'transform response API usage to chat completion usage format for cost calculation', 'calculate cost using generic token-based pricing for image generation models', 'review the DallE2ImageGenerationConfig class and its image generation configuration methods', 'test the get_supported_openai_params method returns the list of supported OpenAI image generation parameters', 'test the map_openai_params method maps non-default params with validation and drop_params behavior', 'test the transform_image_generation_response method transforms a raw httpx.Response into an ImageResponse object', 'review the map_openai_params method for parameter validation and unsupported parameter handling', 'review the DallE3ImageGenerationConfig class and its image generation configuration methods', 'build a DallE3ImageGenerationConfig instance to configure OpenAI dall-e-3 image generation with supported parameters', 'create a GPTImageGenerationConfig instance to configure OpenAI gpt-image-1 image generation', 'get the list of supported OpenAI parameters for gpt-image-1 image generation model', 'map non-default OpenAI params to optional params with validation and drop_params support', 'transform a raw httpx image generation response into a structured ImageResponse object', 'test the GPTImageGenerationConfig class and its parameter mapping and response transformation methods']
```

Usage

```
{'review_DallE3ImageGenerationConfig': 'review the DallE3ImageGenerationConfig class and its image generation configuration methods', 'test_get_supported_openai_params': 'test the get_supported_openai_params method returns the list of supported OpenAI image generation parameters for dall-e-3', 'test_map_openai_params': 'test the map_openai_params method maps non-default params with validation and drop_params behavior', 'test_transform_image_generation_response': 'test the transform_image_generation_response method transforms a raw httpx.Response into an ImageResponse object', 'build_dalle3_config': 'build a DallE3ImageGenerationConfig instance to configure OpenAI dall-e-3 image generation with supported parameters'}
```

## File: berriai_litellm/litellm/llms/openai/image_generation/gpt_transformation.py

Prompts

```
['calculate cost for OpenAI gpt-image-1 and gpt-image-1-mini models from an ImageResponse', 'calculate cost for gpt-image models with a custom LLM provider name', 'calculate cost for gpt-image models returning zero when usage data is missing', 'transform response API usage to chat completion usage format for cost calculation', 'calculate cost using generic token-based pricing for image generation models', 'review the DallE2ImageGenerationConfig class and its image generation configuration methods', 'test the get_supported_openai_params method returns the list of supported OpenAI image generation parameters', 'test the map_openai_params method maps non-default params with validation and drop_params behavior', 'test the transform_image_generation_response method transforms a raw httpx.Response into an ImageResponse object', 'review the map_openai_params method for parameter validation and unsupported parameter handling', 'review the DallE3ImageGenerationConfig class and its image generation configuration methods', 'build a DallE3ImageGenerationConfig instance to configure OpenAI dall-e-3 image generation with supported parameters', 'create a GPTImageGenerationConfig instance to configure OpenAI gpt-image-1 image generation', 'get the list of supported OpenAI parameters for gpt-image-1 image generation model', 'map non-default OpenAI params to optional params with validation and drop_params support', 'transform a raw httpx image generation response into a structured ImageResponse object', 'test the GPTImageGenerationConfig class and its parameter mapping and response transformation methods']
```

Usage

```
{'create_GPTImageGenerationConfig': 'create a GPTImageGenerationConfig instance to configure OpenAI gpt-image-1 image generation', 'get_supported_openai_params': 'get the list of supported OpenAI parameters for gpt-image-1 image generation model', 'map_openai_params': 'map non-default OpenAI params to optional params with validation and drop_params support', 'transform_image_generation_response': 'transform a raw httpx image generation response into a structured ImageResponse object', 'test_GPTImageGenerationConfig': 'test the GPTImageGenerationConfig class and its parameter mapping and response transformation methods'}
```

