# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/k2/app/common.py

Prompts

```
['get the HuggingFace model config for a given model ID and config section name', 'build an OfflineAsr instance by downloading model files from a HuggingFace repo using its config', 'transcribe a single audio tensor batch using an existing OfflineAsr model', 'create an OfflineAsr instance with a neural model file, BPE or token file, and decoding method', 'decode a list of audio wave tensors into transcribed text strings using an OfflineAsr model', 'run an RNN-T model with greedy search to decode audio features into token IDs', 'run an RNN-T model with modified beam search to decode audio features into token IDs', 'run a sherpa RNN-T conformer model encoder on batched padded feature tensors', 'review the run_model_and_do_greedy_search function for RNN-T decoding with greedy search', 'review the run_model_and_do_modified_beam_search function for RNN-T decoding with beam search', 'run the starlette app that serves HuggingFace model inference via POST requests', 'build a cached pipeline instance using the TASK and MODEL_ID environment variables', 'create a dictionary mapping task names like automatic-speech-recognition to their pipeline classes', 'configure gzip compression and optional CORS middleware for the starlette application', 'review the async startup event that initializes logging and preloads the pipeline']
```

Usage

```
{'get_hfconfig': 'get the HuggingFace model config for a given model ID and config section name', 'model_from_hfconfig': 'build an OfflineAsr instance by downloading model files from a HuggingFace repo using its config', 'transcribe_batch_from_tensor': 'transcribe a single audio tensor batch using an existing OfflineAsr model', 'OfflineAsr_init': 'create an OfflineAsr instance with a neural model file, BPE or token file, and decoding method', 'OfflineAsr_decode_waves': 'decode a list of audio wave tensors into transcribed text strings using an OfflineAsr model'}
```

## File: huggingface_api-inference-community/docker_images/k2/app/decode.py

Prompts

```
['get the HuggingFace model config for a given model ID and config section name', 'build an OfflineAsr instance by downloading model files from a HuggingFace repo using its config', 'transcribe a single audio tensor batch using an existing OfflineAsr model', 'create an OfflineAsr instance with a neural model file, BPE or token file, and decoding method', 'decode a list of audio wave tensors into transcribed text strings using an OfflineAsr model', 'run an RNN-T model with greedy search to decode audio features into token IDs', 'run an RNN-T model with modified beam search to decode audio features into token IDs', 'run a sherpa RNN-T conformer model encoder on batched padded feature tensors', 'review the run_model_and_do_greedy_search function for RNN-T decoding with greedy search', 'review the run_model_and_do_modified_beam_search function for RNN-T decoding with beam search', 'run the starlette app that serves HuggingFace model inference via POST requests', 'build a cached pipeline instance using the TASK and MODEL_ID environment variables', 'create a dictionary mapping task names like automatic-speech-recognition to their pipeline classes', 'configure gzip compression and optional CORS middleware for the starlette application', 'review the async startup event that initializes logging and preloads the pipeline']
```

Usage

```
{'run_greedy_search_decode': 'run an RNN-T model with greedy search to decode audio features into token IDs', 'run_modified_beam_search_decode': 'run an RNN-T model with modified beam search to decode audio features into token IDs', 'run_model_inference': 'run a sherpa RNN-T conformer model encoder on batched padded feature tensors', 'review_greedy_search_function': 'review the run_model_and_do_greedy_search function for RNN-T decoding with greedy search', 'review_beam_search_function': 'review the run_model_and_do_modified_beam_search function for RNN-T decoding with beam search'}
```

## File: huggingface_api-inference-community/docker_images/k2/app/main.py

Prompts

```
['get the HuggingFace model config for a given model ID and config section name', 'build an OfflineAsr instance by downloading model files from a HuggingFace repo using its config', 'transcribe a single audio tensor batch using an existing OfflineAsr model', 'create an OfflineAsr instance with a neural model file, BPE or token file, and decoding method', 'decode a list of audio wave tensors into transcribed text strings using an OfflineAsr model', 'run an RNN-T model with greedy search to decode audio features into token IDs', 'run an RNN-T model with modified beam search to decode audio features into token IDs', 'run a sherpa RNN-T conformer model encoder on batched padded feature tensors', 'review the run_model_and_do_greedy_search function for RNN-T decoding with greedy search', 'review the run_model_and_do_modified_beam_search function for RNN-T decoding with beam search', 'run the starlette app that serves HuggingFace model inference via POST requests', 'build a cached pipeline instance using the TASK and MODEL_ID environment variables', 'create a dictionary mapping task names like automatic-speech-recognition to their pipeline classes', 'configure gzip compression and optional CORS middleware for the starlette application', 'review the async startup event that initializes logging and preloads the pipeline']
```

Usage

```
{'run_starlette_inference_app': 'run the starlette app that serves HuggingFace model inference via POST requests', 'build_pipeline_from_env': 'build a cached pipeline instance using the TASK and MODEL_ID environment variables', 'create_allowed_tasks_registry': 'create a dictionary mapping task names like automatic-speech-recognition to their pipeline classes', 'configure_gzip_cors_middleware': 'configure gzip compression and optional CORS middleware for the starlette application', 'review_startup_event': 'review the async startup event that initializes logging and preloads the pipeline'}
```

