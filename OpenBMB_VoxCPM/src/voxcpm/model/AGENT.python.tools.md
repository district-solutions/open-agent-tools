# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/model/utils.py

Prompts

```
['create a tokenizer wrapper that splits multi-character Chinese tokens into individual characters', 'build a function that converts dtype string names like bfloat16 or float32 to torch dtype objects', 'test the auto_select_device function that selects cuda, mps, or cpu based on availability', 'build a function that resolves the runtime device with auto fallback and explicit validation', 'run a helper that advances a generator and explicitly closes it to avoid deferred cleanup', 'build a VoxCPMModel instance from a local checkpoint directory with optional optimization and LoRA', 'create a VoxCPMModel and generate speech audio from target text with optional prompt audio', 'run VoxCPMModel streaming speech generation yielding audio chunks for real-time playback', 'test VoxCPMModel generation with a pre-built prompt cache for fast multi-turn speech synthesis', 'refactor VoxCPMModel to load LoRA weights from a checkpoint file after torch.compile wrapping', 'create a VoxCPM2Model from local checkpoint directory with optional optimization and LoRA config', 'generate speech audio from target text using VoxCPM2Model with optional reference audio for voice cloning', 'generate streaming audio chunks from text using VoxCPM2Model generate_streaming method', 'build a prompt cache for subsequent audio generation with reference or prompt audio', 'load LoRA weights from safetensors or checkpoint file into VoxCPM2Model']
```

Usage

```
{'create_mask_multichar_chinese_tokens': 'create a tokenizer wrapper that splits multi-character Chinese tokens into individual characters', 'build_get_dtype': 'build a function that converts dtype string names like bfloat16 or float32 to torch dtype objects', 'test_auto_select_device': 'test the auto_select_device function that selects cuda, mps, or cpu based on availability', 'build_resolve_runtime_device': 'build a function that resolves the runtime device with auto fallback and explicit validation', 'run_next_and_close': 'run a helper that advances a generator and explicitly closes it to avoid deferred cleanup'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/model/voxcpm.py

Prompts

```
['create a tokenizer wrapper that splits multi-character Chinese tokens into individual characters', 'build a function that converts dtype string names like bfloat16 or float32 to torch dtype objects', 'test the auto_select_device function that selects cuda, mps, or cpu based on availability', 'build a function that resolves the runtime device with auto fallback and explicit validation', 'run a helper that advances a generator and explicitly closes it to avoid deferred cleanup', 'build a VoxCPMModel instance from a local checkpoint directory with optional optimization and LoRA', 'create a VoxCPMModel and generate speech audio from target text with optional prompt audio', 'run VoxCPMModel streaming speech generation yielding audio chunks for real-time playback', 'test VoxCPMModel generation with a pre-built prompt cache for fast multi-turn speech synthesis', 'refactor VoxCPMModel to load LoRA weights from a checkpoint file after torch.compile wrapping', 'create a VoxCPM2Model from local checkpoint directory with optional optimization and LoRA config', 'generate speech audio from target text using VoxCPM2Model with optional reference audio for voice cloning', 'generate streaming audio chunks from text using VoxCPM2Model generate_streaming method', 'build a prompt cache for subsequent audio generation with reference or prompt audio', 'load LoRA weights from safetensors or checkpoint file into VoxCPM2Model']
```

Usage

```
{'build_voxcpm_model_from_local': 'build a VoxCPMModel instance from a local checkpoint directory with optional optimization and LoRA', 'create_voxcpm_generate_speech': 'create a VoxCPMModel and generate speech audio from target text with optional prompt audio', 'run_voxcpm_generate_streaming': 'run VoxCPMModel streaming speech generation yielding audio chunks for real-time playback', 'test_voxcpm_generate_prompt_cache': 'test VoxCPMModel generation with a pre-built prompt cache for fast multi-turn speech synthesis', 'refactor_voxcpm_load_lora_weights': 'refactor VoxCPMModel to load LoRA weights from a checkpoint file after torch.compile wrapping'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/model/voxcpm2.py

Prompts

```
['create a tokenizer wrapper that splits multi-character Chinese tokens into individual characters', 'build a function that converts dtype string names like bfloat16 or float32 to torch dtype objects', 'test the auto_select_device function that selects cuda, mps, or cpu based on availability', 'build a function that resolves the runtime device with auto fallback and explicit validation', 'run a helper that advances a generator and explicitly closes it to avoid deferred cleanup', 'build a VoxCPMModel instance from a local checkpoint directory with optional optimization and LoRA', 'create a VoxCPMModel and generate speech audio from target text with optional prompt audio', 'run VoxCPMModel streaming speech generation yielding audio chunks for real-time playback', 'test VoxCPMModel generation with a pre-built prompt cache for fast multi-turn speech synthesis', 'refactor VoxCPMModel to load LoRA weights from a checkpoint file after torch.compile wrapping', 'create a VoxCPM2Model from local checkpoint directory with optional optimization and LoRA config', 'generate speech audio from target text using VoxCPM2Model with optional reference audio for voice cloning', 'generate streaming audio chunks from text using VoxCPM2Model generate_streaming method', 'build a prompt cache for subsequent audio generation with reference or prompt audio', 'load LoRA weights from safetensors or checkpoint file into VoxCPM2Model']
```

Usage

```
{'create_voxcpm_model': 'create a VoxCPM2Model from local checkpoint directory with optional optimization and LoRA config', 'generate_speech_text': 'generate speech audio from target text using VoxCPM2Model with optional reference audio for voice cloning', 'generate_streaming_audio': 'generate streaming audio chunks from text using VoxCPM2Model generate_streaming method', 'build_prompt_cache': 'build a prompt cache for subsequent audio generation with reference or prompt audio', 'load_lora_weights': 'load LoRA weights from safetensors or checkpoint file into VoxCPM2Model'}
```

