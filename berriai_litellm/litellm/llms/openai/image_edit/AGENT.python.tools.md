# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/image_edit/dalle2_transformation.py

Prompts

```
['create a DallE2ImageEditConfig instance for transforming image edit requests', 'build a transformed DALL-E-2 image edit request with a single image and prompt', 'test that DallE2ImageEditConfig rejects requests with more than one image', 'build a DALL-E-2 image edit request with an optional mask parameter', 'review that DallE2ImageEditConfig uses singular "image" field instead of "image[]"', 'transform image edit request to OpenAI API format with multipart/form-data support for multiple images and masks', 'validate environment and inject OpenAI Bearer token authorization header from api_key or OPENAI_API_KEY secret', 'get the complete OpenAI images edits endpoint URL from api_base or environment variables with trailing slash removal', 'get the list of supported OpenAI image edit params including image, prompt, mask, model, n, quality, size, and timeout', 'map OpenAI image edit optional request params to a dictionary with no transformation since inputs follow OpenAI spec']
```

Usage

```
{'create_dalle2_image_edit_config': 'create a DallE2ImageEditConfig instance for transforming image edit requests', 'build_dalle2_transform_request': 'build a transformed DALL-E-2 image edit request with a single image and prompt', 'test_dalle2_single_image_validation': 'test that DallE2ImageEditConfig rejects requests with more than one image', 'build_dalle2_mask_handling': 'build a DALL-E-2 image edit request with an optional mask parameter', 'review_dalle2_field_name': 'review that DallE2ImageEditConfig uses singular "image" field instead of "image[]"'}
```

## File: berriai_litellm/litellm/llms/openai/image_edit/transformation.py

Prompts

```
['create a DallE2ImageEditConfig instance for transforming image edit requests', 'build a transformed DALL-E-2 image edit request with a single image and prompt', 'test that DallE2ImageEditConfig rejects requests with more than one image', 'build a DALL-E-2 image edit request with an optional mask parameter', 'review that DallE2ImageEditConfig uses singular "image" field instead of "image[]"', 'transform image edit request to OpenAI API format with multipart/form-data support for multiple images and masks', 'validate environment and inject OpenAI Bearer token authorization header from api_key or OPENAI_API_KEY secret', 'get the complete OpenAI images edits endpoint URL from api_base or environment variables with trailing slash removal', 'get the list of supported OpenAI image edit params including image, prompt, mask, model, n, quality, size, and timeout', 'map OpenAI image edit optional request params to a dictionary with no transformation since inputs follow OpenAI spec']
```

Usage

```
{'transform_image_edit_request': 'transform image edit request to OpenAI API format with multipart/form-data support for multiple images and masks', 'validate_environment': 'validate environment and inject OpenAI Bearer token authorization header from api_key or OPENAI_API_KEY secret', 'get_complete_url': 'get the complete OpenAI images edits endpoint URL from api_base or environment variables with trailing slash removal', 'get_supported_openai_params': 'get the list of supported OpenAI image edit params including image, prompt, mask, model, n, quality, size, and timeout', 'map_openai_params': 'map OpenAI image edit optional request params to a dictionary with no transformation since inputs follow OpenAI spec'}
```

