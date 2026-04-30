# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/images/main.py

Prompts

```
['create an image from a text prompt using the image_generation function with a model like dall-e-2', 'create a variation of an input image using the image_variation function with a dall-e-2 model', 'edit an existing image with a text prompt using the image_edit function with an optional mask', 'run an async image generation call using aimage_generation with a text prompt and model', 'run an async image edit call using aimage_edit on an image with a prompt and optional mask', 'create optional parameters for the image edit API by filtering unsupported params and mapping provider-specific values', 'build a filtered dict of image edit optional request params containing only valid keys with non-None values', 'test image content type detection from BytesIO, bytes, or file-like objects returning the correct MIME type string', 'refactor the optional params handler to silently drop unsupported parameters when drop_params is enabled', 'review the image content type detection that reads magic bytes and maps them to standard MIME types']
```

Usage

```
{'create_image_generation': 'create an image from a text prompt using the image_generation function with a model like dall-e-2', 'create_image_variation': 'create a variation of an input image using the image_variation function with a dall-e-2 model', 'create_image_edit': 'edit an existing image with a text prompt using the image_edit function with an optional mask', 'run_async_image_generation': 'run an async image generation call using aimage_generation with a text prompt and model', 'run_async_image_edit': 'run an async image edit call using aimage_edit on an image with a prompt and optional mask'}
```

## File: berriai_litellm/litellm/images/utils.py

Prompts

```
['create an image from a text prompt using the image_generation function with a model like dall-e-2', 'create a variation of an input image using the image_variation function with a dall-e-2 model', 'edit an existing image with a text prompt using the image_edit function with an optional mask', 'run an async image generation call using aimage_generation with a text prompt and model', 'run an async image edit call using aimage_edit on an image with a prompt and optional mask', 'create optional parameters for the image edit API by filtering unsupported params and mapping provider-specific values', 'build a filtered dict of image edit optional request params containing only valid keys with non-None values', 'test image content type detection from BytesIO, bytes, or file-like objects returning the correct MIME type string', 'refactor the optional params handler to silently drop unsupported parameters when drop_params is enabled', 'review the image content type detection that reads magic bytes and maps them to standard MIME types']
```

Usage

```
{'create_get_optional_params_image_edit': 'create optional parameters for the image edit API by filtering unsupported params and mapping provider-specific values', 'build_get_requested_image_edit_optional_param': 'build a filtered dict of image edit optional request params containing only valid keys with non-None values', 'test_get_image_content_type': 'test image content type detection from BytesIO, bytes, or file-like objects returning the correct MIME type string', 'refactor_get_optional_params_image_edit': 'refactor the optional params handler to silently drop unsupported parameters when drop_params is enabled', 'review_get_image_content_type': 'review the image content type detection that reads magic bytes and maps them to standard MIME types'}
```

