# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/scripts/conv_stft.py

Prompts

```
['create an STFT module with configurable window length, hop, FFT length, and window type', 'transform audio tensor to STFT domain returning magnitude and phase or real and imaginary components', 'inverse STFT from magnitude and phase tensors to reconstruct original audio waveform', 'check if STFT parameters obey the constants overlap-add (COLA) condition for perfect reconstruction', 'forward audio through STFT transform and inverse to reconstruct the original waveform', 'convert a PyTorch F5-TTS checkpoint to TensorRT-LLM format with tensor parallelism support', 'run the convert_checkpoint CLI to convert F5-TTS model weights for TensorRT-LLM inference', 'split Q attention weights across tensor parallel ranks for distributed inference', 'save TensorRT-LLM config.json and rank-specific safetensors checkpoint files', 'parallelize checkpoint conversion across multiple workers using ThreadPoolExecutor', 'export the Vocos vocoder model to an ONNX file with dynamic batch and input length axes', 'load the Vocos vocoder model from Hugging Face hub or a local path into PyTorch', 'create an ISTFT head module that converts mel spectrograms to real/imaginary STFT components', 'build a VocosVocoder wrapper module that adapts Vocos head for ONNX export with ISTFT support', 'run the CLI script to export a vocoder to ONNX with --vocoder and --output-path arguments']
```

Usage

```
{'create_stft_instance': 'create an STFT module with configurable window length, hop, FFT length, and window type', 'transform_audio_to_stft': 'transform audio tensor to STFT domain returning magnitude and phase or real and imaginary components', 'inverse_stft_to_audio': 'inverse STFT from magnitude and phase tensors to reconstruct original audio waveform', 'check_perfect_reconstruction': 'check if STFT parameters obey the constants overlap-add (COLA) condition for perfect reconstruction', 'forward_audio_roundtrip': 'forward audio through STFT transform and inverse to reconstruct the original waveform'}
```

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/scripts/convert_checkpoint.py

Prompts

```
['create an STFT module with configurable window length, hop, FFT length, and window type', 'transform audio tensor to STFT domain returning magnitude and phase or real and imaginary components', 'inverse STFT from magnitude and phase tensors to reconstruct original audio waveform', 'check if STFT parameters obey the constants overlap-add (COLA) condition for perfect reconstruction', 'forward audio through STFT transform and inverse to reconstruct the original waveform', 'convert a PyTorch F5-TTS checkpoint to TensorRT-LLM format with tensor parallelism support', 'run the convert_checkpoint CLI to convert F5-TTS model weights for TensorRT-LLM inference', 'split Q attention weights across tensor parallel ranks for distributed inference', 'save TensorRT-LLM config.json and rank-specific safetensors checkpoint files', 'parallelize checkpoint conversion across multiple workers using ThreadPoolExecutor', 'export the Vocos vocoder model to an ONNX file with dynamic batch and input length axes', 'load the Vocos vocoder model from Hugging Face hub or a local path into PyTorch', 'create an ISTFT head module that converts mel spectrograms to real/imaginary STFT components', 'build a VocosVocoder wrapper module that adapts Vocos head for ONNX export with ISTFT support', 'run the CLI script to export a vocoder to ONNX with --vocoder and --output-path arguments']
```

Usage

```
{'convert_pytorch_checkpoint_to_trtllm': 'convert a PyTorch F5-TTS checkpoint to TensorRT-LLM format with tensor parallelism support', 'run_checkpoint_conversion_cli': 'run the convert_checkpoint CLI to convert F5-TTS model weights for TensorRT-LLM inference', 'split_q_weights_for_tensor_parallelism': 'split Q attention weights across tensor parallel ranks for distributed inference', 'save_trtllm_config_and_weights': 'save TensorRT-LLM config.json and rank-specific safetensors checkpoint files', 'parallelize_checkpoint_conversion': 'parallelize checkpoint conversion across multiple workers using ThreadPoolExecutor'}
```

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/scripts/export_vocoder_to_onnx.py

Prompts

```
['create an STFT module with configurable window length, hop, FFT length, and window type', 'transform audio tensor to STFT domain returning magnitude and phase or real and imaginary components', 'inverse STFT from magnitude and phase tensors to reconstruct original audio waveform', 'check if STFT parameters obey the constants overlap-add (COLA) condition for perfect reconstruction', 'forward audio through STFT transform and inverse to reconstruct the original waveform', 'convert a PyTorch F5-TTS checkpoint to TensorRT-LLM format with tensor parallelism support', 'run the convert_checkpoint CLI to convert F5-TTS model weights for TensorRT-LLM inference', 'split Q attention weights across tensor parallel ranks for distributed inference', 'save TensorRT-LLM config.json and rank-specific safetensors checkpoint files', 'parallelize checkpoint conversion across multiple workers using ThreadPoolExecutor', 'export the Vocos vocoder model to an ONNX file with dynamic batch and input length axes', 'load the Vocos vocoder model from Hugging Face hub or a local path into PyTorch', 'create an ISTFT head module that converts mel spectrograms to real/imaginary STFT components', 'build a VocosVocoder wrapper module that adapts Vocos head for ONNX export with ISTFT support', 'run the CLI script to export a vocoder to ONNX with --vocoder and --output-path arguments']
```

Usage

```
{'export_vocos_vocoder_to_onnx': 'export the Vocos vocoder model to an ONNX file with dynamic batch and input length axes', 'load_vocoder_from_huggingface': 'load the Vocos vocoder model from Hugging Face hub or a local path into PyTorch', 'create_istft_head_module': 'create an ISTFT head module that converts mel spectrograms to real/imaginary STFT components', 'build_vocos_vocoder_wrapper': 'build a VocosVocoder wrapper module that adapts Vocos head for ONNX export with ISTFT support', 'run_onnx_export_cli': 'run the CLI script to export a vocoder to ONNX with --vocoder and --output-path arguments'}
```

