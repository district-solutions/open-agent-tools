# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/api_inference_community/hub.py

Prompts

```
['get Hugging Face Hub model info with offline cache support for a given repo and revision', 'resolve the local cache snapshot path for a specific repo revision by following refs', 'rebuild partial model info from cached README and sibling files when offline', 'walk a local repo directory and build a list of sibling file dicts with relative paths and sizes', 'load cached model info from a JSON file or rebuild it from local cache files', 'build a python module that normalizes speaker diarization tensor outputs into sorted speaker segments with timestamps', 'create a function that parses a torch tensor of speaker labels into start and end time segments per speaker', 'refactor speaker_diarization_normalize to support additional tensor formats or output schemas', 'review speaker_diarization_normalize for correctness when handling edge cases like empty tensors or mismatched classnames', 'test speaker_diarization_normalize with a sample torch tensor, sampling rate, and list of speaker class names', 'check if an HTTP client has disconnected by inspecting active TCP connections with psutil', 'handle an incoming inference request by validating the task, normalizing the payload, and calling the pipeline', 'invoke a pipeline with inputs and parameters, capture warnings, and return the appropriate response', 'compute inference metrics like audio length, image count, or character count based on the task type', 'recursively count the total number of characters in string, list, tuple, or dict inputs', 'normalize a raw payload for audio, image, text, or tensor inference tasks by task type', 'validate generation parameters like temperature and top_k against a specific pipeline task', 'validate inputs against a specific Hugging Face pipeline task like question answering or text generation', 'read audio bytes into a numpy float32 array using ffmpeg with a given sampling rate', 'decode a base64-encoded PyTorch tensor from a JSON payload with shape and dtype parameters']
```

Usage

```
{'hub_model_info': 'get Hugging Face Hub model info with offline cache support for a given repo and revision', 'cached_revision_path': 'resolve the local cache snapshot path for a specific repo revision by following refs', 'build_offline_model_info': 'rebuild partial model info from cached README and sibling files when offline', 'build_offline_siblings': 'walk a local repo directory and build a list of sibling file dicts with relative paths and sizes', 'cached_model_info': 'load cached model info from a JSON file or rebuild it from local cache files'}
```

## File: huggingface_api-inference-community/api_inference_community/normalizers.py

Prompts

```
['get Hugging Face Hub model info with offline cache support for a given repo and revision', 'resolve the local cache snapshot path for a specific repo revision by following refs', 'rebuild partial model info from cached README and sibling files when offline', 'walk a local repo directory and build a list of sibling file dicts with relative paths and sizes', 'load cached model info from a JSON file or rebuild it from local cache files', 'build a python module that normalizes speaker diarization tensor outputs into sorted speaker segments with timestamps', 'create a function that parses a torch tensor of speaker labels into start and end time segments per speaker', 'refactor speaker_diarization_normalize to support additional tensor formats or output schemas', 'review speaker_diarization_normalize for correctness when handling edge cases like empty tensors or mismatched classnames', 'test speaker_diarization_normalize with a sample torch tensor, sampling rate, and list of speaker class names', 'check if an HTTP client has disconnected by inspecting active TCP connections with psutil', 'handle an incoming inference request by validating the task, normalizing the payload, and calling the pipeline', 'invoke a pipeline with inputs and parameters, capture warnings, and return the appropriate response', 'compute inference metrics like audio length, image count, or character count based on the task type', 'recursively count the total number of characters in string, list, tuple, or dict inputs', 'normalize a raw payload for audio, image, text, or tensor inference tasks by task type', 'validate generation parameters like temperature and top_k against a specific pipeline task', 'validate inputs against a specific Hugging Face pipeline task like question answering or text generation', 'read audio bytes into a numpy float32 array using ffmpeg with a given sampling rate', 'decode a base64-encoded PyTorch tensor from a JSON payload with shape and dtype parameters']
```

Usage

```
{'build_speaker_diarization_normalizer': 'build a python module that normalizes speaker diarization tensor outputs into sorted speaker segments with timestamps', 'create_speaker_segment_parser': 'create a function that parses a torch tensor of speaker labels into start and end time segments per speaker', 'refactor_speaker_diarization_normalize': 'refactor speaker_diarization_normalize to support additional tensor formats or output schemas', 'review_speaker_diarization_normalize': 'review speaker_diarization_normalize for correctness when handling edge cases like empty tensors or mismatched classnames', 'test_speaker_diarization_normalize': 'test speaker_diarization_normalize with a sample torch tensor, sampling rate, and list of speaker class names'}
```

## File: huggingface_api-inference-community/api_inference_community/routes.py

Prompts

```
['get Hugging Face Hub model info with offline cache support for a given repo and revision', 'resolve the local cache snapshot path for a specific repo revision by following refs', 'rebuild partial model info from cached README and sibling files when offline', 'walk a local repo directory and build a list of sibling file dicts with relative paths and sizes', 'load cached model info from a JSON file or rebuild it from local cache files', 'build a python module that normalizes speaker diarization tensor outputs into sorted speaker segments with timestamps', 'create a function that parses a torch tensor of speaker labels into start and end time segments per speaker', 'refactor speaker_diarization_normalize to support additional tensor formats or output schemas', 'review speaker_diarization_normalize for correctness when handling edge cases like empty tensors or mismatched classnames', 'test speaker_diarization_normalize with a sample torch tensor, sampling rate, and list of speaker class names', 'check if an HTTP client has disconnected by inspecting active TCP connections with psutil', 'handle an incoming inference request by validating the task, normalizing the payload, and calling the pipeline', 'invoke a pipeline with inputs and parameters, capture warnings, and return the appropriate response', 'compute inference metrics like audio length, image count, or character count based on the task type', 'recursively count the total number of characters in string, list, tuple, or dict inputs', 'normalize a raw payload for audio, image, text, or tensor inference tasks by task type', 'validate generation parameters like temperature and top_k against a specific pipeline task', 'validate inputs against a specific Hugging Face pipeline task like question answering or text generation', 'read audio bytes into a numpy float32 array using ffmpeg with a given sampling rate', 'decode a base64-encoded PyTorch tensor from a JSON payload with shape and dtype parameters']
```

Usage

```
{'check_client_connection': 'check if an HTTP client has disconnected by inspecting active TCP connections with psutil', 'handle_pipeline_request': 'handle an incoming inference request by validating the task, normalizing the payload, and calling the pipeline', 'invoke_pipeline_with_params': 'invoke a pipeline with inputs and parameters, capture warnings, and return the appropriate response', 'compute_inference_metrics': 'compute inference metrics like audio length, image count, or character count based on the task type', 'count_input_characters': 'recursively count the total number of characters in string, list, tuple, or dict inputs'}
```

## File: huggingface_api-inference-community/api_inference_community/validation.py

Prompts

```
['get Hugging Face Hub model info with offline cache support for a given repo and revision', 'resolve the local cache snapshot path for a specific repo revision by following refs', 'rebuild partial model info from cached README and sibling files when offline', 'walk a local repo directory and build a list of sibling file dicts with relative paths and sizes', 'load cached model info from a JSON file or rebuild it from local cache files', 'build a python module that normalizes speaker diarization tensor outputs into sorted speaker segments with timestamps', 'create a function that parses a torch tensor of speaker labels into start and end time segments per speaker', 'refactor speaker_diarization_normalize to support additional tensor formats or output schemas', 'review speaker_diarization_normalize for correctness when handling edge cases like empty tensors or mismatched classnames', 'test speaker_diarization_normalize with a sample torch tensor, sampling rate, and list of speaker class names', 'check if an HTTP client has disconnected by inspecting active TCP connections with psutil', 'handle an incoming inference request by validating the task, normalizing the payload, and calling the pipeline', 'invoke a pipeline with inputs and parameters, capture warnings, and return the appropriate response', 'compute inference metrics like audio length, image count, or character count based on the task type', 'recursively count the total number of characters in string, list, tuple, or dict inputs', 'normalize a raw payload for audio, image, text, or tensor inference tasks by task type', 'validate generation parameters like temperature and top_k against a specific pipeline task', 'validate inputs against a specific Hugging Face pipeline task like question answering or text generation', 'read audio bytes into a numpy float32 array using ffmpeg with a given sampling rate', 'decode a base64-encoded PyTorch tensor from a JSON payload with shape and dtype parameters']
```

Usage

```
{'normalize_payload_audio_image_text_tensor': 'normalize a raw payload for audio, image, text, or tensor inference tasks by task type', 'check_params_validate_generation': 'validate generation parameters like temperature and top_k against a specific pipeline task', 'check_inputs_validate_pipeline': 'validate inputs against a specific Hugging Face pipeline task like question answering or text generation', 'ffmpeg_read_audio_bytes': 'read audio bytes into a numpy float32 array using ffmpeg with a given sampling rate', 'normalize_payload_tensor_decode': 'decode a base64-encoded PyTorch tensor from a JSON payload with shape and dtype parameters'}
```

