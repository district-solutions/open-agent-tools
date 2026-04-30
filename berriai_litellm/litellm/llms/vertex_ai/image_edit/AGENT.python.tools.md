# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/image_edit/cost_calculator.py

Prompts

```
['calculate the cost of a Vertex AI image edit response given a model name and ImageResponse object', 'get the per-image cost metadata for a Vertex AI model using litellm.get_model_info', 'validate that an image response is of type ImageResponse before calculating cost', 'count the number of images returned in a Vertex AI image edit response', 'compute total cost by multiplying per-image price with the number of returned images', 'test the VertexAIGeminiImageEditConfig validate_environment method to verify Vertex AI credentials and headers', 'build the get_complete_url method to construct the Vertex AI Gemini generateContent API endpoint URL', 'transform an image edit request into the Vertex AI Gemini format with inline base64 image data and generation config', 'transform a Vertex AI Gemini HTTP response into a structured ImageResponse containing base64-encoded image data', 'map OpenAI image edit parameters like size to Vertex AI Gemini parameters such as aspectRatio', 'create a VertexAIImagenImageEditConfig instance to configure Imagen image edit on Vertex AI', 'validate and configure Vertex AI credentials, project, location, and access token headers']
```

Usage

```
{'calculate_vertex_ai_image_edit_cost': 'calculate the cost of a Vertex AI image edit response given a model name and ImageResponse object', 'get_vertex_ai_model_cost_info': 'get the per-image cost metadata for a Vertex AI model using litellm.get_model_info', 'validate_image_response_type': 'validate that an image response is of type ImageResponse before calculating cost', 'count_returned_images_in_response': 'count the number of images returned in a Vertex AI image edit response', 'compute_total_edit_cost_from_per_image_price': 'compute total cost by multiplying per-image price with the number of returned images'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/image_edit/vertex_gemini_transformation.py

Prompts

```
['calculate the cost of a Vertex AI image edit response given a model name and ImageResponse object', 'get the per-image cost metadata for a Vertex AI model using litellm.get_model_info', 'validate that an image response is of type ImageResponse before calculating cost', 'count the number of images returned in a Vertex AI image edit response', 'compute total cost by multiplying per-image price with the number of returned images', 'test the VertexAIGeminiImageEditConfig validate_environment method to verify Vertex AI credentials and headers', 'build the get_complete_url method to construct the Vertex AI Gemini generateContent API endpoint URL', 'transform an image edit request into the Vertex AI Gemini format with inline base64 image data and generation config', 'transform a Vertex AI Gemini HTTP response into a structured ImageResponse containing base64-encoded image data', 'map OpenAI image edit parameters like size to Vertex AI Gemini parameters such as aspectRatio', 'create a VertexAIImagenImageEditConfig instance to configure Imagen image edit on Vertex AI', 'validate and configure Vertex AI credentials, project, location, and access token headers']
```

Usage

```
{'test_validate_environment': 'test the VertexAIGeminiImageEditConfig validate_environment method to verify Vertex AI credentials and headers', 'build_get_complete_url': 'build the get_complete_url method to construct the Vertex AI Gemini generateContent API endpoint URL', 'transform_image_edit_request': 'transform an image edit request into the Vertex AI Gemini format with inline base64 image data and generation config', 'transform_image_edit_response': 'transform a Vertex AI Gemini HTTP response into a structured ImageResponse containing base64-encoded image data', 'map_openai_params': 'map OpenAI image edit parameters like size to Vertex AI Gemini parameters such as aspectRatio'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/image_edit/vertex_imagen_transformation.py

Prompts

```
['calculate the cost of a Vertex AI image edit response given a model name and ImageResponse object', 'get the per-image cost metadata for a Vertex AI model using litellm.get_model_info', 'validate that an image response is of type ImageResponse before calculating cost', 'count the number of images returned in a Vertex AI image edit response', 'compute total cost by multiplying per-image price with the number of returned images', 'test the VertexAIGeminiImageEditConfig validate_environment method to verify Vertex AI credentials and headers', 'build the get_complete_url method to construct the Vertex AI Gemini generateContent API endpoint URL', 'transform an image edit request into the Vertex AI Gemini format with inline base64 image data and generation config', 'transform a Vertex AI Gemini HTTP response into a structured ImageResponse containing base64-encoded image data', 'map OpenAI image edit parameters like size to Vertex AI Gemini parameters such as aspectRatio', 'create a VertexAIImagenImageEditConfig instance to configure Imagen image edit on Vertex AI', 'validate and configure Vertex AI credentials, project, location, and access token headers']
```

Usage

```
{'create_vertex_ai_imagen_image_edit_config': 'create a VertexAIImagenImageEditConfig instance to configure Imagen image edit on Vertex AI', 'transform_image_edit_request': 'transform an OpenAI-style image edit request into Vertex AI Imagen API format with prompt and reference images', 'transform_image_edit_response': 'transform a Vertex AI Imagen API response into OpenAI-compatible ImageResponse format', 'map_openai_params': 'map OpenAI image edit parameters like n, size, and mask to Vertex AI Imagen parameters', 'validate_vertex_ai_environment': 'validate and configure Vertex AI credentials, project, location, and access token headers'}
```

