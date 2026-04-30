# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/ocr/common_utils.py

Prompts

```
['get the Vertex AI OCR configuration for a model name like deepseek-ocr or mistral-ocr', 'test get_vertex_ai_ocr_config with deepseek model name returns VertexAIDeepSeekOCRConfig', 'test get_vertex_ai_ocr_config with non-deepseek model name returns VertexAIOCRConfig', 'review get_vertex_ai_ocr_config routing logic for model name dispatch', 'summarize get_vertex_ai_ocr_config function that routes model names to OCR configs', 'build a VertexAIDeepSeekOCRConfig instance to configure Vertex AI DeepSeek OCR transformations', 'validate Vertex AI environment and return Bearer token authorization headers for OCR requests', 'build the complete Vertex AI DeepSeek OCR endpoint URL from project, location, and model parameters', 'transform an OCR document request into chat completion format for Vertex AI DeepSeek API', 'transform a Vertex AI chat completion response into standard OCRResponse with pages and usage info', 'create a VertexAIOCRConfig instance for Vertex AI Mistral OCR transformation', 'build authentication headers for Vertex AI OCR using validate_environment method', 'build the complete Vertex AI OCR endpoint URL with project and location parameters', 'transform an OCR request by converting document URLs to base64 data URIs synchronously', 'transform an OCR request by converting image or document URLs to base64 data URIs asynchronously']
```

Usage

```
{'get_vertex_ai_ocr_config': 'get the Vertex AI OCR configuration for a model name like deepseek-ocr or mistral-ocr', 'test_get_vertex_ai_ocr_config': 'test get_vertex_ai_ocr_config with deepseek model name returns VertexAIDeepSeekOCRConfig', 'test_get_vertex_ai_ocr_config_default': 'test get_vertex_ai_ocr_config with non-deepseek model name returns VertexAIOCRConfig', 'review_get_vertex_ai_ocr_config': 'review get_vertex_ai_ocr_config routing logic for model name dispatch', 'summarize_get_vertex_ai_ocr_config': 'summarize get_vertex_ai_ocr_config function that routes model names to OCR configs'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/ocr/deepseek_transformation.py

Prompts

```
['get the Vertex AI OCR configuration for a model name like deepseek-ocr or mistral-ocr', 'test get_vertex_ai_ocr_config with deepseek model name returns VertexAIDeepSeekOCRConfig', 'test get_vertex_ai_ocr_config with non-deepseek model name returns VertexAIOCRConfig', 'review get_vertex_ai_ocr_config routing logic for model name dispatch', 'summarize get_vertex_ai_ocr_config function that routes model names to OCR configs', 'build a VertexAIDeepSeekOCRConfig instance to configure Vertex AI DeepSeek OCR transformations', 'validate Vertex AI environment and return Bearer token authorization headers for OCR requests', 'build the complete Vertex AI DeepSeek OCR endpoint URL from project, location, and model parameters', 'transform an OCR document request into chat completion format for Vertex AI DeepSeek API', 'transform a Vertex AI chat completion response into standard OCRResponse with pages and usage info', 'create a VertexAIOCRConfig instance for Vertex AI Mistral OCR transformation', 'build authentication headers for Vertex AI OCR using validate_environment method', 'build the complete Vertex AI OCR endpoint URL with project and location parameters', 'transform an OCR request by converting document URLs to base64 data URIs synchronously', 'transform an OCR request by converting image or document URLs to base64 data URIs asynchronously']
```

Usage

```
{'build_vertex_ai_ocr_config': 'build a VertexAIDeepSeekOCRConfig instance to configure Vertex AI DeepSeek OCR transformations', 'validate_vertex_ai_headers': 'validate Vertex AI environment and return Bearer token authorization headers for OCR requests', 'build_ocr_endpoint_url': 'build the complete Vertex AI DeepSeek OCR endpoint URL from project, location, and model parameters', 'transform_ocr_request_to_chat': 'transform an OCR document request into chat completion format for Vertex AI DeepSeek API', 'transform_ocr_response_from_api': 'transform a Vertex AI chat completion response into standard OCRResponse with pages and usage info'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/ocr/transformation.py

Prompts

```
['get the Vertex AI OCR configuration for a model name like deepseek-ocr or mistral-ocr', 'test get_vertex_ai_ocr_config with deepseek model name returns VertexAIDeepSeekOCRConfig', 'test get_vertex_ai_ocr_config with non-deepseek model name returns VertexAIOCRConfig', 'review get_vertex_ai_ocr_config routing logic for model name dispatch', 'summarize get_vertex_ai_ocr_config function that routes model names to OCR configs', 'build a VertexAIDeepSeekOCRConfig instance to configure Vertex AI DeepSeek OCR transformations', 'validate Vertex AI environment and return Bearer token authorization headers for OCR requests', 'build the complete Vertex AI DeepSeek OCR endpoint URL from project, location, and model parameters', 'transform an OCR document request into chat completion format for Vertex AI DeepSeek API', 'transform a Vertex AI chat completion response into standard OCRResponse with pages and usage info', 'create a VertexAIOCRConfig instance for Vertex AI Mistral OCR transformation', 'build authentication headers for Vertex AI OCR using validate_environment method', 'build the complete Vertex AI OCR endpoint URL with project and location parameters', 'transform an OCR request by converting document URLs to base64 data URIs synchronously', 'transform an OCR request by converting image or document URLs to base64 data URIs asynchronously']
```

Usage

```
{'create_VertexAIOCRConfig': 'create a VertexAIOCRConfig instance for Vertex AI Mistral OCR transformation', 'build_validate_environment': 'build authentication headers for Vertex AI OCR using validate_environment method', 'build_get_complete_url': 'build the complete Vertex AI OCR endpoint URL with project and location parameters', 'transform_ocr_request': 'transform an OCR request by converting document URLs to base64 data URIs synchronously', 'async_transform_ocr_request': 'transform an OCR request by converting image or document URLs to base64 data URIs asynchronously'}
```

