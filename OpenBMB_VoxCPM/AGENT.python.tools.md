# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/app.py

Prompts

```
['run the VoxCPM2 speech generation Gradio demo server on a configurable port', 'create a Gradio interface for VoxCPM2 voice design, cloning, and speech generation', 'generate TTS audio from text with optional voice cloning and control instructions', 'transcribe reference audio to text using the SenseVoiceSmall ASR model', 'load the VoxCPM2 model from HuggingFace or a local path on demand', 'run a Gradio demo server for VoxCPM text-to-speech synthesis on localhost:7860', 'create a Gradio UI interface for VoxCPM text-to-speech with prompt audio, text input, and audio output', 'build a VoxCPMDemo instance that initializes ASR and TTS models for voice synthesis', 'generate TTS audio from text with optional prompt audio for voice cloning using VoxCPM', 'recognize speech-to-text from a prompt WAV file using the SenseVoiceSmall ASR model', 'run VoxCPM LoRA training with pretrained model path, train manifest, and LoRA hyperparameters', 'run VoxCPM inference to generate audio from text with optional voice cloning and LoRA checkpoint', 'scan the lora directory for LoRA checkpoint directories containing lora_weights.safetensors', 'load a VoxCPM model with optional LoRA weights for inference or hot-swapping', 'recognize speech from an audio file using the SenseVoiceSmall ASR model']
```

Usage

```
{'run_demo': 'run the VoxCPM2 speech generation Gradio demo server on a configurable port', 'create_demo_interface': 'create a Gradio interface for VoxCPM2 voice design, cloning, and speech generation', 'generate_tts_audio': 'generate TTS audio from text with optional voice cloning and control instructions', 'prompt_wav_recognition': 'transcribe reference audio to text using the SenseVoiceSmall ASR model', 'get_or_load_voxcpm': 'load the VoxCPM2 model from HuggingFace or a local path on demand'}
```

## File: OpenBMB_VoxCPM/app_old.py

Prompts

```
['run the VoxCPM2 speech generation Gradio demo server on a configurable port', 'create a Gradio interface for VoxCPM2 voice design, cloning, and speech generation', 'generate TTS audio from text with optional voice cloning and control instructions', 'transcribe reference audio to text using the SenseVoiceSmall ASR model', 'load the VoxCPM2 model from HuggingFace or a local path on demand', 'run a Gradio demo server for VoxCPM text-to-speech synthesis on localhost:7860', 'create a Gradio UI interface for VoxCPM text-to-speech with prompt audio, text input, and audio output', 'build a VoxCPMDemo instance that initializes ASR and TTS models for voice synthesis', 'generate TTS audio from text with optional prompt audio for voice cloning using VoxCPM', 'recognize speech-to-text from a prompt WAV file using the SenseVoiceSmall ASR model', 'run VoxCPM LoRA training with pretrained model path, train manifest, and LoRA hyperparameters', 'run VoxCPM inference to generate audio from text with optional voice cloning and LoRA checkpoint', 'scan the lora directory for LoRA checkpoint directories containing lora_weights.safetensors', 'load a VoxCPM model with optional LoRA weights for inference or hot-swapping', 'recognize speech from an audio file using the SenseVoiceSmall ASR model']
```

Usage

```
{'run_demo_gradio_tts_server': 'run a Gradio demo server for VoxCPM text-to-speech synthesis on localhost:7860', 'create_gradio_tts_interface': 'create a Gradio UI interface for VoxCPM text-to-speech with prompt audio, text input, and audio output', 'build_voxcpm_demo_instance': 'build a VoxCPMDemo instance that initializes ASR and TTS models for voice synthesis', 'generate_tts_audio_voxcpm': 'generate TTS audio from text with optional prompt audio for voice cloning using VoxCPM', 'recognize_prompt_wav_text': 'recognize speech-to-text from a prompt WAV file using the SenseVoiceSmall ASR model'}
```

## File: OpenBMB_VoxCPM/lora_ft_webui.py

Prompts

```
['run the VoxCPM2 speech generation Gradio demo server on a configurable port', 'create a Gradio interface for VoxCPM2 voice design, cloning, and speech generation', 'generate TTS audio from text with optional voice cloning and control instructions', 'transcribe reference audio to text using the SenseVoiceSmall ASR model', 'load the VoxCPM2 model from HuggingFace or a local path on demand', 'run a Gradio demo server for VoxCPM text-to-speech synthesis on localhost:7860', 'create a Gradio UI interface for VoxCPM text-to-speech with prompt audio, text input, and audio output', 'build a VoxCPMDemo instance that initializes ASR and TTS models for voice synthesis', 'generate TTS audio from text with optional prompt audio for voice cloning using VoxCPM', 'recognize speech-to-text from a prompt WAV file using the SenseVoiceSmall ASR model', 'run VoxCPM LoRA training with pretrained model path, train manifest, and LoRA hyperparameters', 'run VoxCPM inference to generate audio from text with optional voice cloning and LoRA checkpoint', 'scan the lora directory for LoRA checkpoint directories containing lora_weights.safetensors', 'load a VoxCPM model with optional LoRA weights for inference or hot-swapping', 'recognize speech from an audio file using the SenseVoiceSmall ASR model']
```

Usage

```
{'run_training': 'run VoxCPM LoRA training with pretrained model path, train manifest, and LoRA hyperparameters', 'run_inference': 'run VoxCPM inference to generate audio from text with optional voice cloning and LoRA checkpoint', 'scan_lora_checkpoints': 'scan the lora directory for LoRA checkpoint directories containing lora_weights.safetensors', 'load_model': 'load a VoxCPM model with optional LoRA weights for inference or hot-swapping', 'recognize_audio': 'recognize speech from an audio file using the SenseVoiceSmall ASR model'}
```

