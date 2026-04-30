# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/cli.py

Prompts

```
['design speech with VoxCPM2 voice design command using text and optional control instruction', 'clone a voice using reference audio and generate speech from provided text', 'batch-generate speech files from a text input file with one text per line', 'load a VoxCPM model from local path or Hugging Face Hub with optional LoRA weights', 'detect the VoxCPM model architecture from a local config or Hugging Face model id', 'create a VoxCPM TTS pipeline instance from a Hugging Face Hub model id with optional denoiser and LoRA support', 'create a VoxCPM TTS pipeline instance from a local model directory with configurable device and optimization', 'generate a numpy waveform array from input text using the VoxCPM TTS pipeline', 'generate streaming audio chunks from input text using the VoxCPM TTS pipeline', 'load LoRA fine-tuning weights into a VoxCPM model for voice cloning or custom synthesis', 'create a ZipEnhancer instance with a custom ModelScope model path for audio denoising', 'run ZipEnhancer enhance to denoise an input audio file and save to an output path', 'run ZipEnhancer enhance with auto-generated temporary output file and loudness normalization enabled', 'refactor ZipEnhancer._normalize_loudness to use adjustable target loudness level instead of fixed -20 dB', 'review ZipEnhancer.enhance and its temporary file cleanup behavior on processing failure']
```

Usage

```
{'design_voxcpm2_voice': 'design speech with VoxCPM2 voice design command using text and optional control instruction', 'clone_voice_with_reference': 'clone a voice using reference audio and generate speech from provided text', 'batch_generate_speech': 'batch-generate speech files from a text input file with one text per line', 'load_voxcpm_model': 'load a VoxCPM model from local path or Hugging Face Hub with optional LoRA weights', 'detect_model_architecture': 'detect the VoxCPM model architecture from a local config or Hugging Face model id'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/core.py

Prompts

```
['design speech with VoxCPM2 voice design command using text and optional control instruction', 'clone a voice using reference audio and generate speech from provided text', 'batch-generate speech files from a text input file with one text per line', 'load a VoxCPM model from local path or Hugging Face Hub with optional LoRA weights', 'detect the VoxCPM model architecture from a local config or Hugging Face model id', 'create a VoxCPM TTS pipeline instance from a Hugging Face Hub model id with optional denoiser and LoRA support', 'create a VoxCPM TTS pipeline instance from a local model directory with configurable device and optimization', 'generate a numpy waveform array from input text using the VoxCPM TTS pipeline', 'generate streaming audio chunks from input text using the VoxCPM TTS pipeline', 'load LoRA fine-tuning weights into a VoxCPM model for voice cloning or custom synthesis', 'create a ZipEnhancer instance with a custom ModelScope model path for audio denoising', 'run ZipEnhancer enhance to denoise an input audio file and save to an output path', 'run ZipEnhancer enhance with auto-generated temporary output file and loudness normalization enabled', 'refactor ZipEnhancer._normalize_loudness to use adjustable target loudness level instead of fixed -20 dB', 'review ZipEnhancer.enhance and its temporary file cleanup behavior on processing failure']
```

Usage

```
{'create_VoxCPM_from_pretrained': 'create a VoxCPM TTS pipeline instance from a Hugging Face Hub model id with optional denoiser and LoRA support', 'create_VoxCPM_from_local': 'create a VoxCPM TTS pipeline instance from a local model directory with configurable device and optimization', 'generate_speech_text': 'generate a numpy waveform array from input text using the VoxCPM TTS pipeline', 'generate_streaming_speech': 'generate streaming audio chunks from input text using the VoxCPM TTS pipeline', 'load_VoxCPM_lora_weights': 'load LoRA fine-tuning weights into a VoxCPM model for voice cloning or custom synthesis'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/zipenhancer.py

Prompts

```
['design speech with VoxCPM2 voice design command using text and optional control instruction', 'clone a voice using reference audio and generate speech from provided text', 'batch-generate speech files from a text input file with one text per line', 'load a VoxCPM model from local path or Hugging Face Hub with optional LoRA weights', 'detect the VoxCPM model architecture from a local config or Hugging Face model id', 'create a VoxCPM TTS pipeline instance from a Hugging Face Hub model id with optional denoiser and LoRA support', 'create a VoxCPM TTS pipeline instance from a local model directory with configurable device and optimization', 'generate a numpy waveform array from input text using the VoxCPM TTS pipeline', 'generate streaming audio chunks from input text using the VoxCPM TTS pipeline', 'load LoRA fine-tuning weights into a VoxCPM model for voice cloning or custom synthesis', 'create a ZipEnhancer instance with a custom ModelScope model path for audio denoising', 'run ZipEnhancer enhance to denoise an input audio file and save to an output path', 'run ZipEnhancer enhance with auto-generated temporary output file and loudness normalization enabled', 'refactor ZipEnhancer._normalize_loudness to use adjustable target loudness level instead of fixed -20 dB', 'review ZipEnhancer.enhance and its temporary file cleanup behavior on processing failure']
```

Usage

```
{'create_zipenhancer_instance': 'create a ZipEnhancer instance with a custom ModelScope model path for audio denoising', 'run_zipenhancer_enhance': 'run ZipEnhancer enhance to denoise an input audio file and save to an output path', 'run_zipenhancer_enhance_temp': 'run ZipEnhancer enhance with auto-generated temporary output file and loudness normalization enabled', 'refactor_zipenhancer_normalize_loudness': 'refactor ZipEnhancer._normalize_loudness to use adjustable target loudness level instead of fixed -20 dB', 'review_zipenhancer_enhance': 'review ZipEnhancer.enhance and its temporary file cleanup behavior on processing failure'}
```

