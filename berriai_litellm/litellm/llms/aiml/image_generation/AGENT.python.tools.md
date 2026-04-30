# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/aiml/image_generation/cost_calculator.py

Prompts

```
['calculate the cost of AI/ML flux image generation given a model name and image response', "get model pricing info for an AIML provider using litellm's get_model_info function", 'validate that an image response is of type ImageResponse before calculating cost', 'count the number of generated images from an ImageResponse data list', 'compute total cost by multiplying cost per image by the number of generated images', 'test the AimlImageGenerationConfig.get_supported_openai_params method to return supported OpenAI image generation params', 'build a function that maps OpenAI image generation params to AI/ML API params like num_images and image_size', 'run the get_complete_url method to construct the full API endpoint URL for image generation requests', 'test the validate_environment method to set Authorization and Content-Type headers with the AI/ML API key', 'summarize the transform_image_generation_response method that handles multiple API response formats for image data']
```

Usage

```
{'calculate_cost': 'calculate the cost of AI/ML flux image generation given a model name and image response', 'get_model_info': "get model pricing info for an AIML provider using litellm's get_model_info function", 'validate_image_response': 'validate that an image response is of type ImageResponse before calculating cost', 'count_generated_images': 'count the number of generated images from an ImageResponse data list', 'compute_total_cost': 'compute total cost by multiplying cost per image by the number of generated images'}
```

## File: berriai_litellm/litellm/llms/aiml/image_generation/transformation.py

Prompts

```
['calculate the cost of AI/ML flux image generation given a model name and image response', "get model pricing info for an AIML provider using litellm's get_model_info function", 'validate that an image response is of type ImageResponse before calculating cost', 'count the number of generated images from an ImageResponse data list', 'compute total cost by multiplying cost per image by the number of generated images', 'test the AimlImageGenerationConfig.get_supported_openai_params method to return supported OpenAI image generation params', 'build a function that maps OpenAI image generation params to AI/ML API params like num_images and image_size', 'run the get_complete_url method to construct the full API endpoint URL for image generation requests', 'test the validate_environment method to set Authorization and Content-Type headers with the AI/ML API key', 'summarize the transform_image_generation_response method that handles multiple API response formats for image data']
```

Usage

```
{'test_get_supported_openai_params': 'test the AimlImageGenerationConfig.get_supported_openai_params method to return supported OpenAI image generation params', 'build_map_openai_params': 'build a function that maps OpenAI image generation params to AI/ML API params like num_images and image_size', 'run_get_complete_url': 'run the get_complete_url method to construct the full API endpoint URL for image generation requests', 'test_validate_environment': 'test the validate_environment method to set Authorization and Content-Type headers with the AI/ML API key', 'summarize_transform_image_generation_response': 'summarize the transform_image_generation_response method that handles multiple API response formats for image data'}
```

