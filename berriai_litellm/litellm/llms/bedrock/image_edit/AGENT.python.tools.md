# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/bedrock/image_edit/amazon_nova_canvas_image_edit_transformation.py

Prompts

```
['build a Nova Canvas InvokeModel request body for image editing tasks like inpainting or image variation', 'encode an image file, bytes, or base64 string to a base64-encoded string for Nova Canvas', 'check whether a Bedrock model ID supports Nova Canvas image editing via model_cost', 'map OpenAI-style image edit parameters to Nova Canvas-compatible request parameters', 'transform an OpenAI image edit request into a Nova Canvas InvokeModel body with image generation config', 'build a bedrock image edit handler that sends image edit requests to AWS Bedrock stability or nova canvas models', 'create a bedrock image edit config class for stability or amazon nova canvas model variants', 'test the synchronous image edit method that posts to a bedrock runtime endpoint with signed aws headers', 'test the asynchronous image edit method that uses an async httpx client to call the bedrock invoke endpoint', 'refactor the request body builder to transform image edit parameters into the correct bedrock model format', 'test if a model name matches a Bedrock Stability edit model pattern', 'map OpenAI image edit parameters to Bedrock Stability API parameters', 'transform an OpenAI-style image edit request into Bedrock Stability request format', 'transform a Bedrock Stability response into an OpenAI-compatible ImageResponse object', 'validate and set up request headers for Bedrock Stability image edit']
```

Usage

```
{'build_nova_canvas_task_body': 'build a Nova Canvas InvokeModel request body for image editing tasks like inpainting or image variation', 'encode_image_to_base64': 'encode an image file, bytes, or base64 string to a base64-encoded string for Nova Canvas', 'check_nova_canvas_support': 'check whether a Bedrock model ID supports Nova Canvas image editing via model_cost', 'map_openai_image_params': 'map OpenAI-style image edit parameters to Nova Canvas-compatible request parameters', 'transform_image_edit_request': 'transform an OpenAI image edit request into a Nova Canvas InvokeModel body with image generation config'}
```

## File: berriai_litellm/litellm/llms/bedrock/image_edit/handler.py

Prompts

```
['build a Nova Canvas InvokeModel request body for image editing tasks like inpainting or image variation', 'encode an image file, bytes, or base64 string to a base64-encoded string for Nova Canvas', 'check whether a Bedrock model ID supports Nova Canvas image editing via model_cost', 'map OpenAI-style image edit parameters to Nova Canvas-compatible request parameters', 'transform an OpenAI image edit request into a Nova Canvas InvokeModel body with image generation config', 'build a bedrock image edit handler that sends image edit requests to AWS Bedrock stability or nova canvas models', 'create a bedrock image edit config class for stability or amazon nova canvas model variants', 'test the synchronous image edit method that posts to a bedrock runtime endpoint with signed aws headers', 'test the asynchronous image edit method that uses an async httpx client to call the bedrock invoke endpoint', 'refactor the request body builder to transform image edit parameters into the correct bedrock model format', 'test if a model name matches a Bedrock Stability edit model pattern', 'map OpenAI image edit parameters to Bedrock Stability API parameters', 'transform an OpenAI-style image edit request into Bedrock Stability request format', 'transform a Bedrock Stability response into an OpenAI-compatible ImageResponse object', 'validate and set up request headers for Bedrock Stability image edit']
```

Usage

```
{'build_bedrock_image_edit': 'build a bedrock image edit handler that sends image edit requests to AWS Bedrock stability or nova canvas models', 'create_bedrock_config_class': 'create a bedrock image edit config class for stability or amazon nova canvas model variants', 'test_image_edit_sync': 'test the synchronous image edit method that posts to a bedrock runtime endpoint with signed aws headers', 'test_image_edit_async': 'test the asynchronous image edit method that uses an async httpx client to call the bedrock invoke endpoint', 'refactor_request_body': 'refactor the request body builder to transform image edit parameters into the correct bedrock model format'}
```

## File: berriai_litellm/litellm/llms/bedrock/image_edit/stability_transformation.py

Prompts

```
['build a Nova Canvas InvokeModel request body for image editing tasks like inpainting or image variation', 'encode an image file, bytes, or base64 string to a base64-encoded string for Nova Canvas', 'check whether a Bedrock model ID supports Nova Canvas image editing via model_cost', 'map OpenAI-style image edit parameters to Nova Canvas-compatible request parameters', 'transform an OpenAI image edit request into a Nova Canvas InvokeModel body with image generation config', 'build a bedrock image edit handler that sends image edit requests to AWS Bedrock stability or nova canvas models', 'create a bedrock image edit config class for stability or amazon nova canvas model variants', 'test the synchronous image edit method that posts to a bedrock runtime endpoint with signed aws headers', 'test the asynchronous image edit method that uses an async httpx client to call the bedrock invoke endpoint', 'refactor the request body builder to transform image edit parameters into the correct bedrock model format', 'test if a model name matches a Bedrock Stability edit model pattern', 'map OpenAI image edit parameters to Bedrock Stability API parameters', 'transform an OpenAI-style image edit request into Bedrock Stability request format', 'transform a Bedrock Stability response into an OpenAI-compatible ImageResponse object', 'validate and set up request headers for Bedrock Stability image edit']
```

Usage

```
{'test_BedrockStabilityImageEditConfig_is_stability_edit_model': 'test if a model name matches a Bedrock Stability edit model pattern', 'map_BedrockStabilityImageEditConfig_map_openai_params': 'map OpenAI image edit parameters to Bedrock Stability API parameters', 'transform_BedrockStabilityImageEditConfig_transform_image_edit_request': 'transform an OpenAI-style image edit request into Bedrock Stability request format', 'transform_BedrockStabilityImageEditConfig_transform_image_edit_response': 'transform a Bedrock Stability response into an OpenAI-compatible ImageResponse object', 'validate_BedrockStabilityImageEditConfig_validate_environment': 'validate and set up request headers for Bedrock Stability image edit'}
```

