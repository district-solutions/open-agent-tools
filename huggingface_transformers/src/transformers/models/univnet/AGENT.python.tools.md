# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/univnet/configuration_univnet.py

Prompts

```
['create a UnivNetConfig instance with default architecture parameters for Tortoise TTS', 'create a UnivNetConfig with custom resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes', 'initialize a UnivNetModel with random weights from a UnivNetConfig instance', 'validate that resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes have the same length', 'review the UnivNetConfig class and its architecture validation logic', 'summarize the UnivNetConfig class and its configurable model parameters', 'convert a UnivNet checkpoint to HuggingFace Transformers format and save to a local folder', 'run the UnivNet checkpoint conversion CLI with checkpoint path and output folder arguments', 'get a key mapping for kernel predictor weight names between old and new model architectures', 'get a full key mapping for renaming UnivNet state dict keys to HuggingFace model format', 'rename and filter state dict keys by applying a modification mapping and removing unwanted keys', 'create a UnivNetFeatureExtractor instance with custom sampling rate, num_mel_bins, and hop_length parameters', 'build a log-mel spectrogram from a raw mono waveform using STFT with mel filter bank', 'run feature extraction on raw speech audio to produce mel spectrograms with padding and attention masks', 'generate a random Gaussian noise sequence for use as input in UnivNetModel forward passes', 'batch decode padded waveforms from UnivNetModel output by removing padding and trimming to original lengths', 'generate audio waveforms from mel spectrograms using UnivNetModel', 'apply weight norm to all layers of UnivNetModel for faster inference', 'predict convolution kernels and biases from mel spectrograms using UnivNetKernelPredictor', 'perform location-variable convolution on hidden states with dynamic kernels and biases', 'build a location variable convolution residual block with gated activation and skip connections']
```

Usage

```
{'create_univnet_config': 'create a UnivNetConfig instance with default architecture parameters for Tortoise TTS', 'create_univnet_config_custom': 'create a UnivNetConfig with custom resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes', 'init_univnet_model': 'initialize a UnivNetModel with random weights from a UnivNetConfig instance', 'validate_architecture': 'validate that resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes have the same length', 'review_univnet_config': 'review the UnivNetConfig class and its architecture validation logic', 'summarize_univnet_config': 'summarize the UnivNetConfig class and its configurable model parameters'}
```

## File: huggingface_transformers/src/transformers/models/univnet/convert_univnet.py

Prompts

```
['create a UnivNetConfig instance with default architecture parameters for Tortoise TTS', 'create a UnivNetConfig with custom resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes', 'initialize a UnivNetModel with random weights from a UnivNetConfig instance', 'validate that resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes have the same length', 'review the UnivNetConfig class and its architecture validation logic', 'summarize the UnivNetConfig class and its configurable model parameters', 'convert a UnivNet checkpoint to HuggingFace Transformers format and save to a local folder', 'run the UnivNet checkpoint conversion CLI with checkpoint path and output folder arguments', 'get a key mapping for kernel predictor weight names between old and new model architectures', 'get a full key mapping for renaming UnivNet state dict keys to HuggingFace model format', 'rename and filter state dict keys by applying a modification mapping and removing unwanted keys', 'create a UnivNetFeatureExtractor instance with custom sampling rate, num_mel_bins, and hop_length parameters', 'build a log-mel spectrogram from a raw mono waveform using STFT with mel filter bank', 'run feature extraction on raw speech audio to produce mel spectrograms with padding and attention masks', 'generate a random Gaussian noise sequence for use as input in UnivNetModel forward passes', 'batch decode padded waveforms from UnivNetModel output by removing padding and trimming to original lengths', 'generate audio waveforms from mel spectrograms using UnivNetModel', 'apply weight norm to all layers of UnivNetModel for faster inference', 'predict convolution kernels and biases from mel spectrograms using UnivNetKernelPredictor', 'perform location-variable convolution on hidden states with dynamic kernels and biases', 'build a location variable convolution residual block with gated activation and skip connections']
```

Usage

```
{'convert_univnet_checkpoint': 'convert a UnivNet checkpoint to HuggingFace Transformers format and save to a local folder', 'run_convert_univnet_cli': 'run the UnivNet checkpoint conversion CLI with checkpoint path and output folder arguments', 'get_kernel_predictor_key_mapping': 'get a key mapping for kernel predictor weight names between old and new model architectures', 'get_key_mapping': 'get a full key mapping for renaming UnivNet state dict keys to HuggingFace model format', 'rename_state_dict': 'rename and filter state dict keys by applying a modification mapping and removing unwanted keys'}
```

## File: huggingface_transformers/src/transformers/models/univnet/feature_extraction_univnet.py

Prompts

```
['create a UnivNetConfig instance with default architecture parameters for Tortoise TTS', 'create a UnivNetConfig with custom resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes', 'initialize a UnivNetModel with random weights from a UnivNetConfig instance', 'validate that resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes have the same length', 'review the UnivNetConfig class and its architecture validation logic', 'summarize the UnivNetConfig class and its configurable model parameters', 'convert a UnivNet checkpoint to HuggingFace Transformers format and save to a local folder', 'run the UnivNet checkpoint conversion CLI with checkpoint path and output folder arguments', 'get a key mapping for kernel predictor weight names between old and new model architectures', 'get a full key mapping for renaming UnivNet state dict keys to HuggingFace model format', 'rename and filter state dict keys by applying a modification mapping and removing unwanted keys', 'create a UnivNetFeatureExtractor instance with custom sampling rate, num_mel_bins, and hop_length parameters', 'build a log-mel spectrogram from a raw mono waveform using STFT with mel filter bank', 'run feature extraction on raw speech audio to produce mel spectrograms with padding and attention masks', 'generate a random Gaussian noise sequence for use as input in UnivNetModel forward passes', 'batch decode padded waveforms from UnivNetModel output by removing padding and trimming to original lengths', 'generate audio waveforms from mel spectrograms using UnivNetModel', 'apply weight norm to all layers of UnivNetModel for faster inference', 'predict convolution kernels and biases from mel spectrograms using UnivNetKernelPredictor', 'perform location-variable convolution on hidden states with dynamic kernels and biases', 'build a location variable convolution residual block with gated activation and skip connections']
```

Usage

```
{'create_univnet_feature_extractor': 'create a UnivNetFeatureExtractor instance with custom sampling rate, num_mel_bins, and hop_length parameters', 'build_mel_spectrogram': 'build a log-mel spectrogram from a raw mono waveform using STFT with mel filter bank', 'run_feature_extraction': 'run feature extraction on raw speech audio to produce mel spectrograms with padding and attention masks', 'generate_noise_sequence': 'generate a random Gaussian noise sequence for use as input in UnivNetModel forward passes', 'batch_decode_waveforms': 'batch decode padded waveforms from UnivNetModel output by removing padding and trimming to original lengths'}
```

## File: huggingface_transformers/src/transformers/models/univnet/modeling_univnet.py

Prompts

```
['create a UnivNetConfig instance with default architecture parameters for Tortoise TTS', 'create a UnivNetConfig with custom resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes', 'initialize a UnivNetModel with random weights from a UnivNetConfig instance', 'validate that resblock_kernel_sizes, resblock_stride_sizes, and resblock_dilation_sizes have the same length', 'review the UnivNetConfig class and its architecture validation logic', 'summarize the UnivNetConfig class and its configurable model parameters', 'convert a UnivNet checkpoint to HuggingFace Transformers format and save to a local folder', 'run the UnivNet checkpoint conversion CLI with checkpoint path and output folder arguments', 'get a key mapping for kernel predictor weight names between old and new model architectures', 'get a full key mapping for renaming UnivNet state dict keys to HuggingFace model format', 'rename and filter state dict keys by applying a modification mapping and removing unwanted keys', 'create a UnivNetFeatureExtractor instance with custom sampling rate, num_mel_bins, and hop_length parameters', 'build a log-mel spectrogram from a raw mono waveform using STFT with mel filter bank', 'run feature extraction on raw speech audio to produce mel spectrograms with padding and attention masks', 'generate a random Gaussian noise sequence for use as input in UnivNetModel forward passes', 'batch decode padded waveforms from UnivNetModel output by removing padding and trimming to original lengths', 'generate audio waveforms from mel spectrograms using UnivNetModel', 'apply weight norm to all layers of UnivNetModel for faster inference', 'predict convolution kernels and biases from mel spectrograms using UnivNetKernelPredictor', 'perform location-variable convolution on hidden states with dynamic kernels and biases', 'build a location variable convolution residual block with gated activation and skip connections']
```

Usage

```
{'generate_audio_waveforms': 'generate audio waveforms from mel spectrograms using UnivNetModel', 'apply_weight_norm_model': 'apply weight norm to all layers of UnivNetModel for faster inference', 'predict_convolution_kernels': 'predict convolution kernels and biases from mel spectrograms using UnivNetKernelPredictor', 'perform_location_variable_convolution': 'perform location-variable convolution on hidden states with dynamic kernels and biases', 'build_lvc_residual_block': 'build a location variable convolution residual block with gated activation and skip connections'}
```

