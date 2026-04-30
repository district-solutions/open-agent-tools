# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/image_generation/cost_calculator.py

Prompts

```
['calculate the cost for Vertex AI image generation responses using model name and image response data', 'get model info for a Vertex AI image generation model including pricing details', 'calculate image response cost from usage metrics for Vertex AI providers', 'count the number of generated images in an image response for cost calculation', 'compute total cost by multiplying cost per image by the number of generated images', 'build a Vertex AI image generation call using prompt, project, location, and credentials to return base64-encoded images', 'create an ImageResponse object from a Vertex AI JSON response containing predictions with bytesBase64Encoded fields', 'transform snake_case optional parameters to camelCase format with default sampleCount of 1 for Vertex AI API', 'test whether a JSON response contains predictions with bytesBase64Encoded to confirm it is an image generation response', 'run an async image generation request to Vertex AI using prompt, project, location, credentials, and optional parameters', 'transform a prompt into Gemini generateContent API request body with imageConfig and candidateCount', 'transform a Gemini generateContent response into litellm ImageResponse format with inline base64 image data', 'map OpenAI image generation parameters like n, size, aspectRatio to Gemini format for Vertex AI', 'build the Vertex AI generateContent API URL with project, location, and model name', 'validate Vertex AI environment by resolving credentials, project, and location and setting auth headers', 'create a VertexAIImagenImageGenerationConfig instance for Imagen image generation on Vertex AI', 'map OpenAI image generation parameters to Vertex AI Imagen format with sampleCount and aspectRatio', 'build the complete Vertex AI Imagen predict API URL from project, location, and model name']
```

Usage

```
{'calculate_vertex_ai_image_cost': 'calculate the cost for Vertex AI image generation responses using model name and image response data', 'get_vertex_ai_model_info': 'get model info for a Vertex AI image generation model including pricing details', 'calculate_image_response_cost_from_usage': 'calculate image response cost from usage metrics for Vertex AI providers', 'count_generated_images': 'count the number of generated images in an image response for cost calculation', 'compute_per_image_cost': 'compute total cost by multiplying cost per image by the number of generated images'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/image_generation/image_generation_handler.py

Prompts

```
['calculate the cost for Vertex AI image generation responses using model name and image response data', 'get model info for a Vertex AI image generation model including pricing details', 'calculate image response cost from usage metrics for Vertex AI providers', 'count the number of generated images in an image response for cost calculation', 'compute total cost by multiplying cost per image by the number of generated images', 'build a Vertex AI image generation call using prompt, project, location, and credentials to return base64-encoded images', 'create an ImageResponse object from a Vertex AI JSON response containing predictions with bytesBase64Encoded fields', 'transform snake_case optional parameters to camelCase format with default sampleCount of 1 for Vertex AI API', 'test whether a JSON response contains predictions with bytesBase64Encoded to confirm it is an image generation response', 'run an async image generation request to Vertex AI using prompt, project, location, credentials, and optional parameters', 'transform a prompt into Gemini generateContent API request body with imageConfig and candidateCount', 'transform a Gemini generateContent response into litellm ImageResponse format with inline base64 image data', 'map OpenAI image generation parameters like n, size, aspectRatio to Gemini format for Vertex AI', 'build the Vertex AI generateContent API URL with project, location, and model name', 'validate Vertex AI environment by resolving credentials, project, and location and setting auth headers', 'create a VertexAIImagenImageGenerationConfig instance for Imagen image generation on Vertex AI', 'map OpenAI image generation parameters to Vertex AI Imagen format with sampleCount and aspectRatio', 'build the complete Vertex AI Imagen predict API URL from project, location, and model name']
```

Usage

```
{'build_vertex_image_generation': 'build a Vertex AI image generation call using prompt, project, location, and credentials to return base64-encoded images', 'create_image_generation_response': 'create an ImageResponse object from a Vertex AI JSON response containing predictions with bytesBase64Encoded fields', 'transform_optional_params': 'transform snake_case optional parameters to camelCase format with default sampleCount of 1 for Vertex AI API', 'test_is_image_generation_response': 'test whether a JSON response contains predictions with bytesBase64Encoded to confirm it is an image generation response', 'run_async_image_generation': 'run an async image generation request to Vertex AI using prompt, project, location, credentials, and optional parameters'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/image_generation/vertex_gemini_transformation.py

Prompts

```
['calculate the cost for Vertex AI image generation responses using model name and image response data', 'get model info for a Vertex AI image generation model including pricing details', 'calculate image response cost from usage metrics for Vertex AI providers', 'count the number of generated images in an image response for cost calculation', 'compute total cost by multiplying cost per image by the number of generated images', 'build a Vertex AI image generation call using prompt, project, location, and credentials to return base64-encoded images', 'create an ImageResponse object from a Vertex AI JSON response containing predictions with bytesBase64Encoded fields', 'transform snake_case optional parameters to camelCase format with default sampleCount of 1 for Vertex AI API', 'test whether a JSON response contains predictions with bytesBase64Encoded to confirm it is an image generation response', 'run an async image generation request to Vertex AI using prompt, project, location, credentials, and optional parameters', 'transform a prompt into Gemini generateContent API request body with imageConfig and candidateCount', 'transform a Gemini generateContent response into litellm ImageResponse format with inline base64 image data', 'map OpenAI image generation parameters like n, size, aspectRatio to Gemini format for Vertex AI', 'build the Vertex AI generateContent API URL with project, location, and model name', 'validate Vertex AI environment by resolving credentials, project, and location and setting auth headers', 'create a VertexAIImagenImageGenerationConfig instance for Imagen image generation on Vertex AI', 'map OpenAI image generation parameters to Vertex AI Imagen format with sampleCount and aspectRatio', 'build the complete Vertex AI Imagen predict API URL from project, location, and model name']
```

Usage

```
{'transform_image_generation_request': 'transform a prompt into Gemini generateContent API request body with imageConfig and candidateCount', 'transform_image_generation_response': 'transform a Gemini generateContent response into litellm ImageResponse format with inline base64 image data', 'map_openai_params': 'map OpenAI image generation parameters like n, size, aspectRatio to Gemini format for Vertex AI', 'get_complete_url': 'build the Vertex AI generateContent API URL with project, location, and model name', 'validate_environment': 'validate Vertex AI environment by resolving credentials, project, and location and setting auth headers'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/image_generation/vertex_imagen_transformation.py

Prompts

```
['calculate the cost for Vertex AI image generation responses using model name and image response data', 'get model info for a Vertex AI image generation model including pricing details', 'calculate image response cost from usage metrics for Vertex AI providers', 'count the number of generated images in an image response for cost calculation', 'compute total cost by multiplying cost per image by the number of generated images', 'build a Vertex AI image generation call using prompt, project, location, and credentials to return base64-encoded images', 'create an ImageResponse object from a Vertex AI JSON response containing predictions with bytesBase64Encoded fields', 'transform snake_case optional parameters to camelCase format with default sampleCount of 1 for Vertex AI API', 'test whether a JSON response contains predictions with bytesBase64Encoded to confirm it is an image generation response', 'run an async image generation request to Vertex AI using prompt, project, location, credentials, and optional parameters', 'transform a prompt into Gemini generateContent API request body with imageConfig and candidateCount', 'transform a Gemini generateContent response into litellm ImageResponse format with inline base64 image data', 'map OpenAI image generation parameters like n, size, aspectRatio to Gemini format for Vertex AI', 'build the Vertex AI generateContent API URL with project, location, and model name', 'validate Vertex AI environment by resolving credentials, project, and location and setting auth headers', 'create a VertexAIImagenImageGenerationConfig instance for Imagen image generation on Vertex AI', 'map OpenAI image generation parameters to Vertex AI Imagen format with sampleCount and aspectRatio', 'build the complete Vertex AI Imagen predict API URL from project, location, and model name']
```

Usage

```
{'create_VertexAIImagenImageGenerationConfig': 'create a VertexAIImagenImageGenerationConfig instance for Imagen image generation on Vertex AI', 'map_openai_params_to_imagen': 'map OpenAI image generation parameters to Vertex AI Imagen format with sampleCount and aspectRatio', 'get_complete_url_for_imagen': 'build the complete Vertex AI Imagen predict API URL from project, location, and model name', 'transform_image_generation_request': 'transform an OpenAI image generation request into Vertex AI Imagen predict request body', 'transform_image_generation_response': 'transform a Vertex AI Imagen response into litellm ImageResponse with base64-encoded images'}
```

