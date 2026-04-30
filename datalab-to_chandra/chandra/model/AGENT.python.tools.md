# Agent Python Tools

- repo: datalab-to/chandra
- repo_uri: https://github.com/datalab-to/chandra

## File: datalab-to_chandra/chandra/model/hf.py

Prompts

```
['build a HuggingFace image-text-to-text model with bfloat16 precision and auto device mapping', 'run HuggingFace model generation on a batch of image-text inputs with configurable max output tokens', 'test the process_batch_element function that converts BatchInputItem to chat template format with image and text content', 'refactor the generate_hf function to support custom stop tokens and additional generation kwargs', 'review the load_model function that loads a transformers AutoModelForImageTextToText with configurable attention implementation', 'test the scale_to_fit function to resize an image to fit within max and min pixel bounds on a grid', 'refactor the scale_to_fit function to support custom aspect ratio preservation thresholds', 'test the detect_repeat_token function to identify excessive repeating sequences in predicted token output', 'refactor the detect_repeat_token function to support configurable repeat detection windows', 'review the scale_to_fit function for edge cases with empty or invalid images', 'run batch VLLM generation on a list of image-prompt items with retry and parallel execution', 'create a base64 string from a PIL Image for use in multimodal API calls', 'test the BatchInputItem schema for constructing batch input items with image, prompt, and prompt_type', 'review the GenerationResult schema for returning raw output, token count, and error status', 'build a parallel batch generation pipeline using ThreadPoolExecutor with configurable retries and temperature escalation']
```

Usage

```
{'build_hf_model': 'build a HuggingFace image-text-to-text model with bfloat16 precision and auto device mapping', 'run_hf_generate': 'run HuggingFace model generation on a batch of image-text inputs with configurable max output tokens', 'test_process_batch_element': 'test the process_batch_element function that converts BatchInputItem to chat template format with image and text content', 'refactor_generate_hf': 'refactor the generate_hf function to support custom stop tokens and additional generation kwargs', 'review_load_model': 'review the load_model function that loads a transformers AutoModelForImageTextToText with configurable attention implementation'}
```

## File: datalab-to_chandra/chandra/model/util.py

Prompts

```
['build a HuggingFace image-text-to-text model with bfloat16 precision and auto device mapping', 'run HuggingFace model generation on a batch of image-text inputs with configurable max output tokens', 'test the process_batch_element function that converts BatchInputItem to chat template format with image and text content', 'refactor the generate_hf function to support custom stop tokens and additional generation kwargs', 'review the load_model function that loads a transformers AutoModelForImageTextToText with configurable attention implementation', 'test the scale_to_fit function to resize an image to fit within max and min pixel bounds on a grid', 'refactor the scale_to_fit function to support custom aspect ratio preservation thresholds', 'test the detect_repeat_token function to identify excessive repeating sequences in predicted token output', 'refactor the detect_repeat_token function to support configurable repeat detection windows', 'review the scale_to_fit function for edge cases with empty or invalid images', 'run batch VLLM generation on a list of image-prompt items with retry and parallel execution', 'create a base64 string from a PIL Image for use in multimodal API calls', 'test the BatchInputItem schema for constructing batch input items with image, prompt, and prompt_type', 'review the GenerationResult schema for returning raw output, token count, and error status', 'build a parallel batch generation pipeline using ThreadPoolExecutor with configurable retries and temperature escalation']
```

Usage

```
{'test_scale_to_fit': 'test the scale_to_fit function to resize an image to fit within max and min pixel bounds on a grid', 'refactor_scale_to_fit': 'refactor the scale_to_fit function to support custom aspect ratio preservation thresholds', 'test_detect_repeat_token': 'test the detect_repeat_token function to identify excessive repeating sequences in predicted token output', 'refactor_detect_repeat_token': 'refactor the detect_repeat_token function to support configurable repeat detection windows', 'review_scale_to_fit': 'review the scale_to_fit function for edge cases with empty or invalid images'}
```

## File: datalab-to_chandra/chandra/model/vllm.py

Prompts

```
['build a HuggingFace image-text-to-text model with bfloat16 precision and auto device mapping', 'run HuggingFace model generation on a batch of image-text inputs with configurable max output tokens', 'test the process_batch_element function that converts BatchInputItem to chat template format with image and text content', 'refactor the generate_hf function to support custom stop tokens and additional generation kwargs', 'review the load_model function that loads a transformers AutoModelForImageTextToText with configurable attention implementation', 'test the scale_to_fit function to resize an image to fit within max and min pixel bounds on a grid', 'refactor the scale_to_fit function to support custom aspect ratio preservation thresholds', 'test the detect_repeat_token function to identify excessive repeating sequences in predicted token output', 'refactor the detect_repeat_token function to support configurable repeat detection windows', 'review the scale_to_fit function for edge cases with empty or invalid images', 'run batch VLLM generation on a list of image-prompt items with retry and parallel execution', 'create a base64 string from a PIL Image for use in multimodal API calls', 'test the BatchInputItem schema for constructing batch input items with image, prompt, and prompt_type', 'review the GenerationResult schema for returning raw output, token count, and error status', 'build a parallel batch generation pipeline using ThreadPoolExecutor with configurable retries and temperature escalation']
```

Usage

```
{'run_generate_vllm': 'run batch VLLM generation on a list of image-prompt items with retry and parallel execution', 'create_image_to_base64': 'create a base64 string from a PIL Image for use in multimodal API calls', 'test_batch_input_item': 'test the BatchInputItem schema for constructing batch input items with image, prompt, and prompt_type', 'review_generation_result': 'review the GenerationResult schema for returning raw output, token count, and error status', 'build_vllm_parallel_batch': 'build a parallel batch generation pipeline using ThreadPoolExecutor with configurable retries and temperature escalation'}
```

