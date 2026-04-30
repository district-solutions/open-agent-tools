# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/benchmark.py

Prompts

```
['run the F5-TTS benchmark CLI to measure RTF on a dataset split with a specified batch size', 'build a VocosTensorRT class that decodes mel spectrograms to waveform using a TensorRT engine', 'test the load_vocoder function to initialize Vocos or VocosTensorRT vocoder from local or huggingface', 'review the data_collator function that preprocesses audio-text batches into padded mel and text sequences', 'summarize the init_distributed function that sets up NCCL process group for multi-GPU inference', 'run the F5-TTS gRPC client to send audio inference requests to a Triton server', 'test the send function that loads audio and sends inference requests to Triton', 'test the load_manifests function that parses manifest files with audio paths and text', 'test the write_triton_stats function that parses and writes Triton inference statistics', 'test the split_data function that divides a list into k approximately equal chunks', 'run the HTTP client CLI to send a TTS inference request to a Triton server and save output audio', 'create a function that builds a JSON request payload with waveform, lengths, and text inputs for Triton inference', 'create a function that loads a WAV file and resamples it to 24000 Hz using scipy', 'create a function that parses CLI arguments for server URL, reference audio, reference text, target text, model name, and output path', 'test the HTTP inference client by sending a reference audio and target text to a Triton F5-TTS model server']
```

Usage

```
{'run_benchmark_cli': 'run the F5-TTS benchmark CLI to measure RTF on a dataset split with a specified batch size', 'build_vocos_tensorrt_engine': 'build a VocosTensorRT class that decodes mel spectrograms to waveform using a TensorRT engine', 'test_load_vocoder': 'test the load_vocoder function to initialize Vocos or VocosTensorRT vocoder from local or huggingface', 'review_data_collator': 'review the data_collator function that preprocesses audio-text batches into padded mel and text sequences', 'summarize_init_distributed': 'summarize the init_distributed function that sets up NCCL process group for multi-GPU inference'}
```

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/client_grpc.py

Prompts

```
['run the F5-TTS benchmark CLI to measure RTF on a dataset split with a specified batch size', 'build a VocosTensorRT class that decodes mel spectrograms to waveform using a TensorRT engine', 'test the load_vocoder function to initialize Vocos or VocosTensorRT vocoder from local or huggingface', 'review the data_collator function that preprocesses audio-text batches into padded mel and text sequences', 'summarize the init_distributed function that sets up NCCL process group for multi-GPU inference', 'run the F5-TTS gRPC client to send audio inference requests to a Triton server', 'test the send function that loads audio and sends inference requests to Triton', 'test the load_manifests function that parses manifest files with audio paths and text', 'test the write_triton_stats function that parses and writes Triton inference statistics', 'test the split_data function that divides a list into k approximately equal chunks', 'run the HTTP client CLI to send a TTS inference request to a Triton server and save output audio', 'create a function that builds a JSON request payload with waveform, lengths, and text inputs for Triton inference', 'create a function that loads a WAV file and resamples it to 24000 Hz using scipy', 'create a function that parses CLI arguments for server URL, reference audio, reference text, target text, model name, and output path', 'test the HTTP inference client by sending a reference audio and target text to a Triton F5-TTS model server']
```

Usage

```
{'run_client_grpc': 'run the F5-TTS gRPC client to send audio inference requests to a Triton server', 'test_send': 'test the send function that loads audio and sends inference requests to Triton', 'test_load_manifests': 'test the load_manifests function that parses manifest files with audio paths and text', 'test_write_triton_stats': 'test the write_triton_stats function that parses and writes Triton inference statistics', 'test_split_data': 'test the split_data function that divides a list into k approximately equal chunks'}
```

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/client_http.py

Prompts

```
['run the F5-TTS benchmark CLI to measure RTF on a dataset split with a specified batch size', 'build a VocosTensorRT class that decodes mel spectrograms to waveform using a TensorRT engine', 'test the load_vocoder function to initialize Vocos or VocosTensorRT vocoder from local or huggingface', 'review the data_collator function that preprocesses audio-text batches into padded mel and text sequences', 'summarize the init_distributed function that sets up NCCL process group for multi-GPU inference', 'run the F5-TTS gRPC client to send audio inference requests to a Triton server', 'test the send function that loads audio and sends inference requests to Triton', 'test the load_manifests function that parses manifest files with audio paths and text', 'test the write_triton_stats function that parses and writes Triton inference statistics', 'test the split_data function that divides a list into k approximately equal chunks', 'run the HTTP client CLI to send a TTS inference request to a Triton server and save output audio', 'create a function that builds a JSON request payload with waveform, lengths, and text inputs for Triton inference', 'create a function that loads a WAV file and resamples it to 24000 Hz using scipy', 'create a function that parses CLI arguments for server URL, reference audio, reference text, target text, model name, and output path', 'test the HTTP inference client by sending a reference audio and target text to a Triton F5-TTS model server']
```

Usage

```
{'run_client_http_cli': 'run the HTTP client CLI to send a TTS inference request to a Triton server and save output audio', 'create_function_prepare_request': 'create a function that builds a JSON request payload with waveform, lengths, and text inputs for Triton inference', 'create_function_load_audio': 'create a function that loads a WAV file and resamples it to 24000 Hz using scipy', 'create_function_get_args': 'create a function that parses CLI arguments for server URL, reference audio, reference text, target text, model name, and output path', 'test_client_http_inference': 'test the HTTP inference client by sending a reference audio and target text to a Triton F5-TTS model server'}
```

