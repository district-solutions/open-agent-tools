# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/scripts/test_pick_runtime_dtype.py

Prompts

```
['test pick_runtime_dtype for MPS low-precision dtype forcing and VOXCPM_MPS_DTYPE override behavior', 'test get_dtype parses every valid dtype override string correctly', "test that 'half' is removed from _VALID_DTYPE_OVERRIDES and _LOW_PRECISION_DTYPES", 'test pick_runtime_dtype passes through bfloat16 and float32 unchanged on CUDA and CPU', 'test pick_runtime_dtype forces float32 for low-precision dtypes on MPS backend', 'synthesize speech from text using a finetuned VoxCPM checkpoint directory', 'clone a voice using reference audio and transcript for voice cloning inference', 'configure diffusion inference timesteps and CFG scale for audio generation quality', 'run the VoxCPM finetune inference CLI with text, checkpoint, and output arguments', 'save generated audio numpy array to a WAV file using soundfile', 'test the VoxCPM LoRA inference script by synthesizing audio from text with a LoRA checkpoint', 'test voice cloning by providing reference audio and prompt text with LoRA inference', 'test disabling and re-enabling LoRA weights during VoxCPM audio synthesis', 'test unloading and hot-reloading LoRA weights on a running VoxCPM model', 'test VoxCPM LoRA inference with custom CFG scale, diffusion timesteps, and max generation length', 'run the VoxCPM model finetuning with pretrained weights, training manifest, and validation manifest', 'validate the VoxCPM model on a validation dataset and generate sample audio for TensorBoard logging', 'generate sample audio from the VoxCPM model using validation text prompts and log mel spectrograms to TensorBoard', 'save model optimizer scheduler and training state checkpoint with LoRA or full finetune strategies', 'load the latest checkpoint including model weights optimizer state scheduler and resume step number']
```

Usage

```
{'test_pick_runtime_dtype': 'test pick_runtime_dtype for MPS low-precision dtype forcing and VOXCPM_MPS_DTYPE override behavior', 'test_get_dtype': 'test get_dtype parses every valid dtype override string correctly', 'test_override_sanity': "test that 'half' is removed from _VALID_DTYPE_OVERRIDES and _LOW_PRECISION_DTYPES", 'test_pick_runtime_dtype_cuda_cpu': 'test pick_runtime_dtype passes through bfloat16 and float32 unchanged on CUDA and CPU', 'test_pick_runtime_dtype_mps_fp32': 'test pick_runtime_dtype forces float32 for low-precision dtypes on MPS backend'}
```

## File: OpenBMB_VoxCPM/scripts/test_voxcpm_ft_infer.py

Prompts

```
['test pick_runtime_dtype for MPS low-precision dtype forcing and VOXCPM_MPS_DTYPE override behavior', 'test get_dtype parses every valid dtype override string correctly', "test that 'half' is removed from _VALID_DTYPE_OVERRIDES and _LOW_PRECISION_DTYPES", 'test pick_runtime_dtype passes through bfloat16 and float32 unchanged on CUDA and CPU', 'test pick_runtime_dtype forces float32 for low-precision dtypes on MPS backend', 'synthesize speech from text using a finetuned VoxCPM checkpoint directory', 'clone a voice using reference audio and transcript for voice cloning inference', 'configure diffusion inference timesteps and CFG scale for audio generation quality', 'run the VoxCPM finetune inference CLI with text, checkpoint, and output arguments', 'save generated audio numpy array to a WAV file using soundfile', 'test the VoxCPM LoRA inference script by synthesizing audio from text with a LoRA checkpoint', 'test voice cloning by providing reference audio and prompt text with LoRA inference', 'test disabling and re-enabling LoRA weights during VoxCPM audio synthesis', 'test unloading and hot-reloading LoRA weights on a running VoxCPM model', 'test VoxCPM LoRA inference with custom CFG scale, diffusion timesteps, and max generation length', 'run the VoxCPM model finetuning with pretrained weights, training manifest, and validation manifest', 'validate the VoxCPM model on a validation dataset and generate sample audio for TensorBoard logging', 'generate sample audio from the VoxCPM model using validation text prompts and log mel spectrograms to TensorBoard', 'save model optimizer scheduler and training state checkpoint with LoRA or full finetune strategies', 'load the latest checkpoint including model weights optimizer state scheduler and resume step number']
```

Usage

```
{'synthesize_speech_from_text': 'synthesize speech from text using a finetuned VoxCPM checkpoint directory', 'clone_voice_with_reference_audio': 'clone a voice using reference audio and transcript for voice cloning inference', 'configure_diffusion_inference_steps': 'configure diffusion inference timesteps and CFG scale for audio generation quality', 'run_cli_inference_test': 'run the VoxCPM finetune inference CLI with text, checkpoint, and output arguments', 'save_generated_audio_to_wav': 'save generated audio numpy array to a WAV file using soundfile'}
```

## File: OpenBMB_VoxCPM/scripts/test_voxcpm_lora_infer.py

Prompts

```
['test pick_runtime_dtype for MPS low-precision dtype forcing and VOXCPM_MPS_DTYPE override behavior', 'test get_dtype parses every valid dtype override string correctly', "test that 'half' is removed from _VALID_DTYPE_OVERRIDES and _LOW_PRECISION_DTYPES", 'test pick_runtime_dtype passes through bfloat16 and float32 unchanged on CUDA and CPU', 'test pick_runtime_dtype forces float32 for low-precision dtypes on MPS backend', 'synthesize speech from text using a finetuned VoxCPM checkpoint directory', 'clone a voice using reference audio and transcript for voice cloning inference', 'configure diffusion inference timesteps and CFG scale for audio generation quality', 'run the VoxCPM finetune inference CLI with text, checkpoint, and output arguments', 'save generated audio numpy array to a WAV file using soundfile', 'test the VoxCPM LoRA inference script by synthesizing audio from text with a LoRA checkpoint', 'test voice cloning by providing reference audio and prompt text with LoRA inference', 'test disabling and re-enabling LoRA weights during VoxCPM audio synthesis', 'test unloading and hot-reloading LoRA weights on a running VoxCPM model', 'test VoxCPM LoRA inference with custom CFG scale, diffusion timesteps, and max generation length', 'run the VoxCPM model finetuning with pretrained weights, training manifest, and validation manifest', 'validate the VoxCPM model on a validation dataset and generate sample audio for TensorBoard logging', 'generate sample audio from the VoxCPM model using validation text prompts and log mel spectrograms to TensorBoard', 'save model optimizer scheduler and training state checkpoint with LoRA or full finetune strategies', 'load the latest checkpoint including model weights optimizer state scheduler and resume step number']
```

Usage

```
{'test_voxcpm_lora_inference': 'test the VoxCPM LoRA inference script by synthesizing audio from text with a LoRA checkpoint', 'test_voice_cloning_with_lora': 'test voice cloning by providing reference audio and prompt text with LoRA inference', 'test_lora_disable_enable': 'test disabling and re-enabling LoRA weights during VoxCPM audio synthesis', 'test_lora_unload_reload': 'test unloading and hot-reloading LoRA weights on a running VoxCPM model', 'test_cfg_timestep_parameters': 'test VoxCPM LoRA inference with custom CFG scale, diffusion timesteps, and max generation length'}
```

## File: OpenBMB_VoxCPM/scripts/train_voxcpm_finetune.py

Prompts

```
['test pick_runtime_dtype for MPS low-precision dtype forcing and VOXCPM_MPS_DTYPE override behavior', 'test get_dtype parses every valid dtype override string correctly', "test that 'half' is removed from _VALID_DTYPE_OVERRIDES and _LOW_PRECISION_DTYPES", 'test pick_runtime_dtype passes through bfloat16 and float32 unchanged on CUDA and CPU', 'test pick_runtime_dtype forces float32 for low-precision dtypes on MPS backend', 'synthesize speech from text using a finetuned VoxCPM checkpoint directory', 'clone a voice using reference audio and transcript for voice cloning inference', 'configure diffusion inference timesteps and CFG scale for audio generation quality', 'run the VoxCPM finetune inference CLI with text, checkpoint, and output arguments', 'save generated audio numpy array to a WAV file using soundfile', 'test the VoxCPM LoRA inference script by synthesizing audio from text with a LoRA checkpoint', 'test voice cloning by providing reference audio and prompt text with LoRA inference', 'test disabling and re-enabling LoRA weights during VoxCPM audio synthesis', 'test unloading and hot-reloading LoRA weights on a running VoxCPM model', 'test VoxCPM LoRA inference with custom CFG scale, diffusion timesteps, and max generation length', 'run the VoxCPM model finetuning with pretrained weights, training manifest, and validation manifest', 'validate the VoxCPM model on a validation dataset and generate sample audio for TensorBoard logging', 'generate sample audio from the VoxCPM model using validation text prompts and log mel spectrograms to TensorBoard', 'save model optimizer scheduler and training state checkpoint with LoRA or full finetune strategies', 'load the latest checkpoint including model weights optimizer state scheduler and resume step number']
```

Usage

```
{'train_run_finetune': 'run the VoxCPM model finetuning with pretrained weights, training manifest, and validation manifest', 'validate_model': 'validate the VoxCPM model on a validation dataset and generate sample audio for TensorBoard logging', 'generate_sample_audio': 'generate sample audio from the VoxCPM model using validation text prompts and log mel spectrograms to TensorBoard', 'save_checkpoint': 'save model optimizer scheduler and training state checkpoint with LoRA or full finetune strategies', 'load_checkpoint': 'load the latest checkpoint including model weights optimizer state scheduler and resume step number'}
```

